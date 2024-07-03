<!DOCTYPE html>
<html>
<head>
    <title>プログラミング修正ゲーム</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div id="game-container">
        <h1>プログラミング修正ゲーム</h1>
        <div id="level-selection">
            <button onclick="startGame('beginner')">初級</button>
            <button onclick="startGame('intermediate')">中級</button>
            <button onclick="startGame('advanced')">上級</button>
        </div>
        <div id="game-area" style="display:none;">
            <div id="code-editor"></div>
            <button id="submit-button">修正を提出</button>
            <div id="feedback"></div>
        </div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/ace/1.4.12/ace.js"></script>
    <script src="app.js"></script>
</body>
</html>
