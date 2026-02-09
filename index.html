<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>TOEFL iBT Independent Writing – Wireframe</title>
<style>
  * { box-sizing: border-box; font-family: Arial, Helvetica, sans-serif; }
  body { margin: 0; background: #cccccc; }

  .toefl-container {
    display: flex;
    height: 100vh;
    max-width: 1200px;
    margin: 0 auto;
    background: #e6e6e6;
    border: 1px solid #888;
  }

  /* LEFT PANEL */
  .left-panel {
    width: 40%;
    padding: 12px;
    background: #e6e6e6;
    border-right: 2px solid #777;
    display: flex;
    flex-direction: column;
  }

  .box {
    background: #f0f0f0;
    border: 2px solid #9a9a9a;
    padding: 12px;
    margin-bottom: 12px;
    flex-shrink: 0;
  }

  .box h2 { margin-top: 0; font-size: 16px; }
  .box p { font-size: 14px; line-height: 1.4; }

  /* RIGHT PANEL */
  .right-panel {
    width: 60%;
    display: flex;
    flex-direction: column;
    background: #ffffff;
  }

  .toolbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 6px 12px;
    background: #d9d9d9;
    border-bottom: 2px solid #777;
  }

  .toolbar-left button,
  .toolbar-right button {
    font-size: 12px;
    padding: 4px 8px;
    margin-right: 4px;
    cursor: pointer;
    border: 1px solid #888;
    background: #f2f2f2;
  }

  .toolbar-left button:last-child { margin-right: 0; }
  .toolbar-right { display: flex; align-items: center; gap: 10px; font-size: 12px; }

  .editor {
    flex: 1;
    border: none;
    padding: 12px;
    font-size: 14px;
    resize: none;
    outline: none;
    line-height: 1.5;
  }

  /* TIMER STYLE */
  #timer {
    font-weight: bold;
    color: #d32f2f;
  }
</style>
</head>
<body>

<div class="toefl-container">

  <!-- LEFT PANEL -->
  <div class="left-panel">
    <div class="box">
      <h2>Directions:</h2>
      <p>
      說明：1. 依提示在「答案卷」上寫一篇英文作文。 2. 文長約120至150個單詞（words）。
      </p>
    </div>

    <div class="box">
      <h2> 英文作文</h2>
      <p>
       如果你可以不用擔心預算，隨心所欲的度過一天，你會怎麼過？請寫一篇短文，第一段說明 你會邀請誰和你一起度過這一天？為什麼？第二段描述你會去哪裡？做些什麼事？為什麼？
      </p>
      <p>時間共計30分鐘</p>
    </div>
  </div>

  <!-- RIGHT PANEL -->
  <div class="right-panel">
    <div class="toolbar">
      <div class="toolbar-left">
        <button onclick="document.execCommand('cut')">Cut</button>
        <button onclick="document.execCommand('paste')">Paste</button>
        <button onclick="document.execCommand('undo')">Undo</button>
      </div>
      <div class="toolbar-right">
        <span>Word Count: <strong id="wordCount">0</strong></span>
        <span>Time Left: <span id="timer">30:00</span></span>
        <button onclick="toggleEditor()">Hide</button>
      </div>
    </div>

    <textarea
      class="editor"
      id="editor"
      aria-label="Essay writing area"
      placeholder="Begin typing your essay here..."
      oninput="updateWordCount()"
    ></textarea>
  </div>

</div>

<script>
  const editor = document.getElementById('editor');
  const wordCountEl = document.getElementById('wordCount');
  const timerEl = document.getElementById('timer');

  // Live word count
  function updateWordCount() {
    const text = editor.value.trim();
    const words = text ? text.split(/\s+/).length : 0;
    wordCountEl.textContent = words;
  }

  // Hide/Show editor
  function toggleEditor() {
    editor.style.display = editor.style.display === 'none' ? 'block' : 'none';
  }

  // Canvas-safe countdown timer (30 minutes)
  let timeLeft = 30 * 60; // 30 minutes in seconds
  function updateTimer() {
    const minutes = Math.floor(timeLeft / 60).toString().padStart(2, '0');
    const seconds = (timeLeft % 60).toString().padStart(2, '0');
    timerEl.textContent = `${minutes}:${seconds}`;
    if(timeLeft > 0) timeLeft--;
  }
  setInterval(updateTimer, 1000);
</script>

</body>
</html>
