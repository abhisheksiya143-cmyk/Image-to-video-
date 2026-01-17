<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Image to Video AI Generator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .box {
      background: #020617;
      padding: 20px;
      width: 350px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
    }
    h2 { text-align: center; }
    input, textarea, button {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      border-radius: 8px;
      border: none;
    }
    button {
      background: #2563eb;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover { background: #1d4ed8; }
    video {
      width: 100%;
      margin-top: 15px;
      border-radius: 10px;
    }
    .note {
      font-size: 12px;
      color: #94a3b8;
      margin-top: 8px;
      text-align: center;
    }
  </style>
</head>
<body>

<div class="box">
  <h2>Image ➜ Video AI</h2>

  <input type="file" accept="image/*" id="imageInput">
  
  <textarea placeholder="Describe motion (e.g. walking, cinematic pan, slow motion)"></textarea>

  <button onclick="generateVideo()">Generate Video</button>

  <video id="resultVideo" controls style="display:none;"></video>

  <div class="note">Unlimited AI Demo Interface</div>
</div>

<script>
function generateVideo() {
  alert("Backend AI API connect nahi hai.\nIs jagah AI Image-to-Video API lagegi.");
  
  // Demo video (replace with AI output)
  const video = document.getElementById("resultVideo");
  video.src = "https://www.w3schools.com/html/mov_bbb.mp4";
  video.style.display = "block";
}
</script>

</body>
</html>
