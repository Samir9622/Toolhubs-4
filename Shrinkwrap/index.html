<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dev Tools Suite</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4850105760470054"
    crossorigin="anonymous"></script>
  <style>
    body.dark {
      background-color: #1a202c;
      color: white;
    }
    .tool-section { display: none; }
    .tool-section.active { display: block; }
  </style>
</head>

<body class="dark">
  <div class="flex min-h-screen">
    <aside class="w-60 bg-gray-900 text-white p-4 space-y-4">
      <button class="w-full text-left" onclick="switchTool('lorem')">Lorem Ipsum Generator</button>
      <button class="w-full text-left" onclick="switchTool('json')">JSON Formatter</button>
      <button class="w-full text-left" onclick="switchTool('time')">Time Checker</button>
      <button class="w-full text-left" onclick="switchTool('markdown')">Markdown Editor</button>
      <button class="w-full text-left" onclick="switchTool('diff')">Diff Checker</button>
      <button class="w-full text-left" onclick="toggleDarkMode()">Toggle Dark Mode</button>
    </aside>

    <main class="flex-1 p-6 space-y-6">
      <div class="tool-section active" id="lorem">
        <h2 class="text-2xl mb-2">Lorem Ipsum Generator</h2>
        <input type="number" id="lorem-count" class="border p-2" placeholder="Paragraphs" value="2">
        <button onclick="generateLorem()" class="bg-blue-500 text-white px-4 py-2">Generate</button>
        <pre id="lorem-output" class="mt-4 p-2 border"></pre>
      </div>

      <div class="tool-section" id="json">
        <h2 class="text-2xl mb-2">JSON Formatter & Validator</h2>
        <textarea id="json-input" rows="6" class="w-full border p-2"></textarea>
        <button onclick="formatJSON()" class="bg-green-500 text-white px-4 py-2 mt-2">Format</button>
        <pre id="json-output" class="mt-4 p-2 border"></pre>
      </div>

      <div class="tool-section" id="time">
        <h2 class="text-2xl mb-2">Time Checker</h2>
        <button onclick="showTime()" class="bg-purple-500 text-white px-4 py-2">Show Time</button>
        <div id="time-output" class="mt-4"></div>
      </div>

      <div class="tool-section" id="markdown">
        <h2 class="text-2xl mb-2">Markdown Editor</h2>
        <textarea id="markdown-input" rows="6" class="w-full border p-2"></textarea>
        <button onclick="renderMarkdown()" class="bg-yellow-500 text-white px-4 py-2 mt-2">Render</button>
        <div id="markdown-output" class="mt-4 border p-2"></div>
      </div>

      <div class="tool-section" id="diff">
        <h2 class="text-2xl mb-2">Text Diff Checker</h2>
        <textarea id="diff-input-1" rows="4" class="w-full border p-2 mb-2" placeholder="Text 1"></textarea>
        <textarea id="diff-input-2" rows="4" class="w-full border p-2 mb-2" placeholder="Text 2"></textarea>
        <button onclick="checkDiff()" class="bg-red-500 text-white px-4 py-2">Check Diff</button>
        <pre id="diff-output" class="mt-4 p-2 border"></pre>
      </div>

      <ins class="adsbygoogle"
        style="display:block"
        data-ad-client="ca-pub-4850105760470054"
        data-ad-slot="2486822494"
        data-ad-format="auto"
        data-full-width-responsive="true"></ins>
      <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
    </main>
  </div>

  <script>
    function switchTool(id) {
      document.querySelectorAll('.tool-section').forEach(el => el.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }

    function toggleDarkMode() {
      document.body.classList.toggle('dark');
    }

    function generateLorem() {
      const count = document.getElementById('lorem-count').value;
      const text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. ";
      document.getElementById('lorem-output').textContent = Array.from({ length: count }, () => text.repeat(5)).join('\n\n');
    }

    function formatJSON() {
      const input = document.getElementById('json-input').value;
      try {
        const formatted = JSON.stringify(JSON.parse(input), null, 2);
        document.getElementById('json-output').textContent = formatted;
      } catch (e) {
        document.getElementById('json-output').textContent = "Invalid JSON: " + e.message;
      }
    }

    function showTime() {
      const now = new Date();
      document.getElementById('time-output').textContent = now.toString();
    }

    function renderMarkdown() {
      const input = document.getElementById('markdown-input').value;
      document.getElementById('markdown-output').innerHTML = marked.parse(input);
    }

    function checkDiff() {
      const text1 = document.getElementById('diff-input-1').value;
      const text2 = document.getElementById('diff-input-2').value;
      let diff = '';
      const lines1 = text1.split('\n');
      const lines2 = text2.split('\n');
      const max = Math.max(lines1.length, lines2.length);
      for (let i = 0; i < max; i++) {
        if (lines1[i] !== lines2[i]) {
          diff += `Line ${i + 1}:\n- ${lines1[i] || ''}\n+ ${lines2[i] || ''}\n\n`;
        }
      }
      document.getElementById('diff-output').textContent = diff || 'No differences found.';
    }
  </script>
</body>

</html>
