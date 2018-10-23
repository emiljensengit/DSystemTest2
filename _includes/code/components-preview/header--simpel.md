--- 
permalink: /preview-components/header--simpel.html
layout: iframed 
title: Header--simpel.html
---
<header class="header header-extended" role="banner">

    <!--1A: Portal header -->
    <div class="portal-header">
        <div class="container portal-header-inner">
            <a href="/frontend-styleguide/" title="Home" aria-label="Home" class="logo"></a>
            <button class="button button-secondary button-menu-open js-menu-open ml-auto"
                aria-haspopup="menu" title="Åben mobil menu">Menu</button>

            <!-- 1B: Portal header: info + actions-->
            <div class="portal-info">
                <p class="user"><b>Lone Hansen</b> · Snedkeren fra Nordvest ApS</p>

                <a href="/frontend-styleguide/getting-started/download/" class="button button-primary"
                    role="button">
                    Download kode og designfiler
                </a>
                <a href="https://github.com/FSGpilot/frontend-styleguide-components" class="button button-secondary"
                    role="button">
                    Se på GitHub
                </a>
            </div>
        </div>
    </div>

    <!--2A: Solutiuon header -->
    <div class="solution-header">
        <div class="container solution-header-inner">
            <div class="solution-heading">
                <a href="/frontend-styleguide/" title="Home" aria-label="Home">Frontend Styleguide</a>
            </div>

            <!--2B: Solution header: Authority name + text-->
            <div class="solution-info">
                <!-- nav-secondary -->
                <h6 class="h6">Erhvervsstyrelsen</h6>
                <p>Support: 78 73 64 12</p>
            </div>
        </div>
    </div>

    <nav role="navigation" class=" nav">
        <!-- collapsible-->
        <button class="button button-secondary button-menu-close js-menu-close" title="Luk mobil menu">
            <svg class="icon-svg "><use xlink:href="#close"></use></svg> Luk
        </button>
        <!-- 3: Main navigation-->
        <div class="navbar navbar-primary">
            <!--3A: Main navigation-->
            <div class="navbar-inner container">
                <ul class="nav-primary">
                    <li>
                        <a href="/frontend-styleguide/components/" class="nav-link" title="Designsystem">
                            <span>Designsystem</span>
                        </a>
                    </li>
                    <li>
                        <a href="/frontend-styleguide/page-templates/" class="nav-link" title="Eksempler">
                            <span>Eksempler</span>
                        </a>
                    </li>
                    <li>
                        <a href="/frontend-styleguide/getting-started/" class="nav-link" title="Kom godt i gang">
                            <span>Kom godt i gang</span>
                        </a>
                    </li>
                    <li>
                        <a href="/frontend-styleguide/faellesoffentlige-krav/" class="nav-link" title="Fællesoffentlige krav">
                            <span>Fællesoffentlige krav</span>
                        </a>
                    </li>
                    <li>
                        <button class="nav-link js-nav-submenu" title="Om design systemet" data-js-target="#dropdown-nav-section-one"
                            aria-expanded="false" aria-controls="#dropdown-nav-section-one"
                            aria-haspopup="true">
                            <span>Om designsystemet</span>
                        </button>
                        <ul id="dropdown-nav-section-one" class="nav-submenu" aria-hidden="true">
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </ul>
                    </li>
                </ul>

                <!-- 3B: Main navigation - secondary menu-->
                <ul class="unstyled-list nav-actions">
                    <li>
                        <button class="button button-tertiary">Tertiary</button>
                    </li>
                    <li>
                        <select class="form-select style-switcher" name="Style switcher" aria-label="Skift mellem temaer">
                            <option value="">- Vælg tema -</option>
                            <option value="styleguide">Tema: Neutralt</option>
                            <option value="virkdk">Tema: Virk.dk</option>
                            <option value="borgerdk">Tema: Borger.dk</option>
                        </select>
                    </li>
                </ul>
            </div>
        </div>
        <!-- 3: Main navigation end-->

        <!-- 4: Secondary navigation-->
        <div class="navbar">
            <div class="navbar-inner container">
                <div class="nav-secondary">
                    <h4 class="nav-secondary-heading">Solution variable</h4>
                    <ul class="unstyled-list nav-actions">
                        <li>
                            <button class="button button-primary">Toggle</button>
                        </li>
                        <li>
                            <button class="button button-primary">Toggle</button>
                        </li>
                        <li>
                            <button class="button button-primary">Toggle</button>
                        </li>
                    </ul>
                </div>

                <ul class="unstyled-list nav-actions">
                    <li>
                        <a href="/frontend-styleguide/components/" class="button button-ghost">Ghost</a>
                    </li>
                    <li>
                        <a href="/frontend-styleguide/page-templates/" class="button button-tertiary">Tertiary</a>
                    </li>
                </ul>
            </div>
        </div>
        <!-- 4: Secondary header end-->

        <!-- 5: Contextual actions-->
        <div class="navbar">
            <div class="navbar-inner navbar-context-actions container">
                <div class="nav-actions">
                    <a href="" class="function-link">Print entire guide

                        <svg class="icon-svg "><use xlink:href="#printer"></use></svg>

                    </a>
                </div>
            </div>
        </div>
        <!-- 5: Contextual actions end-->

        <div class="portal-info-mobile">
            <p class="user"><b>Christian Emil Vestergaard Christiansen</b></p>
            <p>Københavns Urmager Værksted v/Martin Elsig</p>
            <a href="https://github.com/FSGpilot/frontend-styleguide-components" class="button button-secondary button-signout">
                Sign out
            </a>
        </div>

        <div class="solution-info-mobile">
            <p><b>Styrelsen for International Rekruttering og Integration</b></p>
            <p>Support: 12 34 56 78</p>
        </div>

    </nav>
    <!-- collapsible nav end-->
</header>
<div class="overlay"></div>