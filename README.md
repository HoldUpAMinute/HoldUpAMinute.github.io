<html>
    <head>
        <title> Extra Math Assistance </title>
        <script src="https://cdn.tailwindcss.com"></script>
    </head>

    <body class="bg:gray-500">
        <h1 id="info"></h1>
    </body>

    <script>
        let info = document.getElementById('info')
        const userAgent = navigator.userAgent;

        info.innerText = 'Screen Height : ' + screen.height + '    Screen Width : ' + screen.width;
    </script>
</html>
