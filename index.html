<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello Kitty Painter</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        canvas {
            border: 1px solid #000;
            cursor: crosshair;
        }
        .controls {
            margin: 10px;
        }
        button {
            padding: 10px 15px;
            margin: 5px;
            font-size: 16px;
        }
    </style>
</head>
<body>

<h1>Hello Kitty Painter</h1>
<canvas id="canvas" width="500" height="500"></canvas>
<div class="controls">
    <button id="clear">Clear</button>
</div>

<script>
    const canvas = document.getElementById('canvas');
    const ctx = canvas.getContext('2d');
    let painting = false;

    // Draw Hello Kitty Outline
    function drawHelloKitty() {
        ctx.fillStyle = 'white';
        ctx.fillRect(0, 0, canvas.width, canvas.height);
        
        ctx.lineWidth = 5;
        ctx.strokeStyle = 'black';
        
        // Head
        ctx.beginPath();
        ctx.arc(250, 250, 100, 0, Math.PI * 2); // Circle for head
        ctx.stroke();

        // Eyes
        ctx.beginPath();
        ctx.arc(225, 230, 10, 0, Math.PI * 2); // Left eye
        ctx.stroke();
        ctx.beginPath();
        ctx.arc(275, 230, 10, 0, Math.PI * 2); // Right eye
        ctx.stroke();

        // Nose
        ctx.beginPath();
        ctx.moveTo(250, 250);
        ctx.lineTo(240, 260);
        ctx.lineTo(260, 260);
        ctx.closePath();
        ctx.stroke();

        // Mouth
        ctx.beginPath();
        ctx.arc(250, 270, 30, 0, Math.PI); // Smile
        ctx.stroke();
    }

    function startPosition(e) {
        painting = true;
        draw(e);
    }

    function endPosition() {
        painting = false;
        ctx.beginPath(); // Start a new path
    }

    function draw(e) {
        if (!painting) return;
        ctx.lineWidth = 5;
        ctx.lineCap = 'round';
        ctx.strokeStyle = '#FF69B4'; // Pink color for painting

        ctx.lineTo(e.clientX - canvas.offsetLeft, e.clientY - canvas.offsetTop);
        ctx.stroke();
        ctx.beginPath();
        ctx.moveTo(e.clientX - canvas.offsetLeft, e.clientY - canvas.offsetTop);
    }

    canvas.addEventListener('mousedown', startPosition);
    canvas.addEventListener('mouseup', endPosition);
    canvas.addEventListener('mousemove', draw);

    // Clear the canvas
    document.getElementById('clear').addEventListener('click', () => {
        ctx.clearRect(0, 0, canvas.width, canvas.height);
        drawHelloKitty(); // Redraw Hello Kitty outline
    });

    // Initial draw
    drawHelloKitty();
</script>

</body>
</html>
