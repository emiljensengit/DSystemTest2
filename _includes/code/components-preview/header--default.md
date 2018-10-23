--- 
permalink: /preview-components/header--default.html
layout: iframed 
title: Header--default.html
---
<!DOCTYPE html>
<html lang="en-US" dir="ltr" class="no-js">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script>
        window.frctl = {
            env: 'static'
        };
    </script>
    <script>
        var cl = document.querySelector('html').classList;
        cl.remove('no-js');
        cl.add('has-js');
    </script>
    <link rel="shortcut icon" href="../../themes/mandelbrot/favicon.ico" type="image/ico">

    <link rel="stylesheet" href="../../themes/mandelbrot/css/white.css?cachebust=1.2.0"
        type="text/css">

    <title>Error rendering component header--default | Frontend Styleguide</title>

</head>

<body>

    <div class="Frame Frame--full" id="frame">

        <div class="Error Error--render">
            <h4 class="Error-title">Error rendering component</h4>
            <div class="Error-message Prose">
                <p>(unknown path) Template render error: (unknown path) Error:
                    Could not render component &#39;@nav-solution-header&#39;
                    - component not found.</p>

            </div>

            <code class="Error-stack">
        <pre>Template render error: (unknown path)
  Template render error: (unknown path)
  Error: Could not render component '@nav-solution-header' - component not found.
    at Object.exports.prettifyError (C:\Projects\FaellesoffentligStyleguide\Code\dk-web-design-standards-components\node_modules\nunjucks\src\lib.js:34:15)
    at C:\Projects\FaellesoffentligStyleguide\Code\dk-web-design-standards-components\node_modules\nunjucks\src\environment.js:486:31
    at eval (eval at _compile (C:\Projects\FaellesoffentligStyleguide\Code\dk-web-design-standards-components\node_modules\nunjucks\src\environment.js:565:24), <anonymous>:18:11)
    at entity.render.then.catch.err (C:\Projects\FaellesoffentligStyleguide\Code\dk-web-design-standards-components\node_modules\@frctl\nunjucks\src\extensions\render.js:46:21)
    at <anonymous></pre>
    </code>

        </div>

    </div>

    <script src="../../themes/mandelbrot/js/mandelbrot.js?cachebust=1.2.0"></script>

</body>

</html>