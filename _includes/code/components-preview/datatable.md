--- 
permalink: /preview-components/datatable.html
layout: iframed 
title: Datatable.html
---
<div class="table-container">
    <h4>Table title</h4>
    <section class="menu">
        <div class="selected-rows-menu">
            <button class="menu-selection-button" type="button">
                <span>Delete</span>

                <i class="icon icon-delete "></i>

            </button>
            <button class="menu-selection-button" type="button">
                <span>Refresh</span>

                <i class="icon icon-refresh "></i>

            </button>
            <button class="menu-selection-button" type="button">
                <span>Pause</span>

                <i class="icon icon-pause-circle "></i>

            </button>
            <div class="selected-items-counter">
                <span class="selected-items-counter-value"></span>
                <span> items selected</span>
            </div>
            <button class="cancel">
                <span>Cancel</span>
            </button>
        </div>
        <div class="default-menu">
            <div class="search-svg">

                <i class="icon icon-magnify "></i>

            </div>
            <input type="text" class="search" placeholder="Search compute">
            <button class="menu-button">

                <i class="icon icon-download "></i>

            </button>
            <button class="menu-button">

                <i class="icon icon-pencil "></i>

            </button>
            <div class="overflow-menu">
                <button class="overflow-menu-btn menu-button" margin-top="15px">

                    <i class="icon icon-settings "></i>

                </button>
                <div class="overflow-menu-options position-left settings">
                    <span>Row height:</span>
                    <div class="radiobutton">
                        <input type="radio" name="size" id="compact">
                        <span>Compact</span>
                    </div>
                    <div class="radiobutton">
                        <input type="radio" name="size" id="short">
                        <span>Short</span>
                    </div>
                    <div class="radiobutton">
                        <input type="radio" name="size" id="default" checked="checked">
                        <span>Default</span>
                    </div>
                    <div class="radiobutton">
                        <input type="radio" name="size" id="tall">
                        <span>Tall</span>
                    </div>
                </div>
            </div>
            <button class="primary-button">
                <span>Add new </span>

                <i class="icon icon-plus-circle "></i>

            </button>
        </div>
    </section>
    <table class="dk-table bordered">
        <thead>
            <tr>
                <th></th>
                <th>
                    <button class="table-sort-button">
                        <span>Document title</span>

                        <i class="icon icon-menu-down "></i>

                    </button>
                </th>
                <th>
                    <button class="table-sort-button">
                        <span>Description</span>

                        <i class="icon icon-menu-down "></i>

                    </button>
                </th>
                <th>
                    <button class="table-sort-button">
                        <span>Year</span>

                        <i class="icon icon-menu-down "></i>

                    </button>
                </th>
                <th></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>
                    <input type="checkbox" class="row-selection-checkbox">
                </td>
                <td scope="row">Declaration of Independence</td>
                <td>Statement adopted by the Continental Congress declaring independence
                    from the British Empire.</td>
                <td>1776</td>
                <td>
                    <div class="overflow-menu">
                        <button class="overflow-menu-btn">

                            <i class="icon icon-dots-horizontal "></i>

                        </button>
                        <div class="overflow-menu-options position-left">
                            <button>Option 1</button>
                            <button>Option 2</button>
                            <button>Option 3</button>
                            <button>Option 4 is longer text</button>
                        </div>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <input type="checkbox" class="row-selection-checkbox">
                </td>
                <td>Bill of Rights</td>
                <td>The first ten amendments of the U.S. Constitution guaranteeing
                    rights and freedoms.</td>
                <td>1791</td>
                <td>
                    <div class="overflow-menu">
                        <button class="overflow-menu-btn">

                            <i class="icon icon-dots-horizontal "></i>

                        </button>
                        <div class="overflow-menu-options position-left">
                            <button>Option 5</button>
                            <button>Option 6 is longer text</button>
                            <button>Option 7</button>
                            <button>Option 8</button>
                        </div>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <input type="checkbox" class="row-selection-checkbox">
                </td>
                <td>Declaration of Sentiments</td>
                <td>A document written during the Seneca Falls Convention outlining
                    the rights that American women should be entitled to as
                    citizens.
                </td>
                <td>1848</td>
                <td>
                    <div class="overflow-menu">
                        <button class="overflow-menu-btn">

                            <i class="icon icon-dots-horizontal "></i>

                        </button>
                        <div class="overflow-menu-options position-left">
                            <button>Option 1</button>
                            <button>Option 2</button>
                            <button>Option 3</button>
                            <button>Option 4 is longer text</button>
                        </div>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <input type="checkbox" class="row-selection-checkbox">
                </td>
                <td>Emancipation Proclamation</td>
                <td>An executive order granting freedom to slaves in designated
                    southern states.</td>
                <td>1863</td>
                <td>
                    <div class="overflow-menu">
                        <button class="overflow-menu-btn">

                            <i class="icon icon-dots-horizontal "></i>

                        </button>
                        <div class="overflow-menu-options position-left">
                            <button>Option 1</button>
                            <button>Option 2</button>
                            <button>Option 3</button>
                            <button>Option 4 is longer text</button>
                        </div>
                    </div>
                </td>
            </tr>
        </tbody>
    </table>
</div>