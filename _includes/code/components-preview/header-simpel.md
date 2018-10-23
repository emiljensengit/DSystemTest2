--- 
permalink: /preview-components/header-simpel.html
layout: iframed 
title: Header-simpel.html
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
                <p class="user"><b>Lone Hansen</b></p>
                <a href="https://github.com/FSGpilot/frontend-styleguide-components" class="button button-secondary"
                    role="button">
                    Log ud
                </a>
            </div>
        </div>
    </div>

    <!--2A: Solutiuon header -->
    <div class="solution-header">
        <div class="container solution-header-inner">
            <div class="solution-heading">
                <a href="/frontend-styleguide/" title="Home" aria-label="Home">Løsningstitel</a>
            </div>

            <!--2B: Solution header: Authority name + text-->
            <div class="solution-info">
                <!-- nav-secondary -->
                <h6 class="h6">Myndighedsnavn</h6>
                <p>Support: 12 34 56 78</p>
            </div>
        </div>
    </div>

    <nav role="navigation" class=" nav">
        <!-- collapsible-->
        <button class="button button-secondary button-menu-close js-menu-close" title="Luk mobil menu">
            <svg class="icon-svg "><use xlink:href="#close"></use></svg> Luk
        </button>

        <div class="portal-info-mobile">
            <p class="user"><b>Lone Hansen</b></p>
            <a href="https://github.com/FSGpilot/frontend-styleguide-components" class="button button-secondary button-signout">
                Log ud
            </a>
        </div>

        <div class="solution-info-mobile">
            <p><b>Myndighedsnavn</b></p>
            <p>Support: 12 34 56 78</p>
        </div>

    </nav>
    <!-- collapsible nav end-->
</header>
<div class="overlay"></div>