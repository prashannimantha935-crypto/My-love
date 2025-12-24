<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commit: Sincere Apology</title>
    <style>
        body { background-color: #1e1e1e; color: #d4d4d4; font-family: 'Consolas', 'Courier New', monospace; margin: 0; display: flex; height: 100vh; overflow: hidden; }
        .editor { flex: 1; padding: 20px; border-right: 1px solid #333; overflow-y: auto; }
        .preview { flex: 1; display: flex; align-items: center; justify-content: center; background: #000; position: relative; }
        .line-num { color: #858585; margin-right: 15px; }
        .keyword { color: #569cd6; }
        .string { color: #ce9178; }
        .comment { color: #6a9955; font-style: italic; }
        video { width: 90%; border-radius: 10px; box-shadow: 0 0 20px rgba(0,0,0,0.5); }
        .cursor { border-left: 2px solid #fff; animation: blink 1s infinite; }
        @keyframes blink { 50% { border-color: transparent; } }
        @media (max-width: 768px) { body { flex-direction: column-reverse; } .editor, .preview { flex: none; height: 50vh; } }
    </style>
</head>
<body>
    <div class="editor">
        <p><span class="line-num">1</span><span class="comment">// Resolving Conflict...</span></p>
        <p><span class="line-num">2</span><span class="keyword">function</span> <span style="color: #dcdcaa;">apologize</span>() {</p>
        <p><span class="line-num">3</span> &nbsp;&nbsp;<span class="keyword">let</span> status = <span class="string">"I'm deeply sorry"</span>;</p>
        <p><span class="line-num">4</span> &nbsp;&nbsp;<span class="keyword">let</span> message = <span class="string">"I love you more than words can say"</span>;</p>
        <p><span class="line-num">5</span> &nbsp;&nbsp;<span class="keyword">return</span> { status, message };</p>
        <p><span class="line-num">6</span>}</p>
        <p><span class="line-num">7</span><span class="comment">// Processing feelings...</span><span class="cursor"></span></p>
    </div>
    <div class="preview">
        <video autoplay muted loop playsinline>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        </video>
    </div>
</body>
</html>
