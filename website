<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Syntax.lol & STW GUI Scripts</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 40px;
            background-color: #f5f5f5;
        }

        button {
            margin: 10px;
            padding: 15px 25px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 8px;
            background-color: #4CAF50;
            color: white;
        }

        textarea {
            width: 80%;
            height: 200px;
            margin-top: 20px;
            padding: 15px;
            font-size: 14px;
            border-radius: 8px;
            border: 1px solid #ccc;
            resize: none;
        }
    </style>
</head>
<body>

    <h1>Script Loader</h1>

    <button onclick="loadSyntaxScript()">Syntax.lol Script</button>
    <button onclick="loadSTWGui()">STW GUI Script</button>

    <textarea id="scriptBox" readonly placeholder="Your script will appear here..."></textarea>

    <script>
        function loadSyntaxScript() {
            const script = `-- Syntax.lol Script
loadstring(game:HttpGet("https://syntax.lol/script.lua"))()`;
            document.getElementById("scriptBox").value = script;
        }

        function loadSTWGui() {
            const script = `-- STW GUI Script
loadstring(game:HttpGet("https://stwgui.com/script.lua"))()`;
            document.getElementById("scriptBox").value = script;
        }
    </script>

</body>
</html>
