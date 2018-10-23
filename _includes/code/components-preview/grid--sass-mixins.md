--- 
permalink: /preview-components/grid--sass-mixins.html
layout: iframed 
title: Grid--sass-mixins.html
---
<pre>
    <code><span class="cl">// Creates a wrapper for a series of columns</span>
<span class="k">@include</span> <span class="nd">make-row</span><span class="p">();</span>

<span class="cl">// Make the element grid-ready (applying everything but the width)</span>
<span class="k">@include</span> <span class="nd">make-col-ready</span><span class="p">();</span>
<span class="k">@include</span> <span class="nd">make-col</span><span class="p">(</span><span class="nv">$size</span><span class="o">,</span> <span class="nv">$columns</span><span class="o">:</span> <span class="nv">$grid-columns</span><span class="p">);</span>

<span class="cl">// Get fancy by offsetting, or changing the sort order</span>
<span class="k">@include</span> <span class="nd">make-col-offset</span><span class="p">(</span><span class="nv">$size</span><span class="o">,</span> <span class="nv">$columns</span><span class="o">:</span> <span class="nv">$grid-columns</span><span class="p">);</code>
</pre>


<style scoped>
    pre {
        display: block;
        padding: 0;
        margin-top: 0;
        margin-bottom: 0;
        background-color: transparent;
        border: 0;
        font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        font-size: 98%;
        color: #212529;
    }

    code {
        padding: 0;
        background-color: transparent;
        border-radius: 0;
        font-family: inherit;
        font-size: inherit;
        color: inherit;
    }

    .cl {
        color: #999;
    }

    .m {
        color: #f60;
    }

    .k {
        color: #069;
    }

    .nd {
        color: #99f;
    }

    .p {
        color: #212529;
    }

    .o {
        color: #555;
    }

    .nv {
        color: #033;
    }
</style>