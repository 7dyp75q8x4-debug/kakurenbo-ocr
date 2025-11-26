<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8" />
<title>かくれんぼ OCR Finder</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body {
  background: #111;
  color: #fff;
  text-align: center;
  font-family: sans-serif;
}
video {
  width: 90%;
  max-width: 600px;
  margin-top: 10px;
  border: 2px solid #555;
}
canvas {
  display: none;
}
button {
  padding: 10px 20px;
  font-size: 18px;
  margin: 8px;
  border-radius: 8px;
}
#resultBox {
  margin-top: 20px;
  padding: 15px;
  background: #222;
  border-radius: 5px;
  width: 90%;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}
</style>

<!-- Tesseract.js CDN -->
<script src="https://cdn.jsdelivr.net/npm/tesseract.js@4
