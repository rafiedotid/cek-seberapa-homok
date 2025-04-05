<!DOCTYPE html>
<html lang="id">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tes Seberapa Homok Kamu?</title>
  <link rel="icon" type="image/x-icon" href="https://cdn-icons-png.flaticon.com/512/3075/3075977.png">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');
    
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #f3f4f6, #e5e7eb);
    }
    
    .rainbow-text {
      background: linear-gradient(to right, #ff0000, #ff7f00, #ffff00, #00ff00, #0000ff, #4b0082, #9400d3);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      animation: rainbow 8s ease infinite;
      background-size: 400% 100%;
    }
    
    @keyframes rainbow {
      0%, 100% { background-position: 0 0; }
      50% { background-position: 100% 0; }
    }
    
    .pride-flag {
      background: linear-gradient(to bottom, 
        #e40303 16.66%, 
        #ff8c00 16.66%, 33.32%, 
        #ffed00 33.32%, 49.98%, 
        #008026 49.98%, 66.64%, 
        #004dff 66.64%, 83.3%, 
        #750787 83.3%);
    }
  </style>
</head>

<body class="min-h-screen flex flex-col">
  <div class="container mx-auto px-4 py-8 flex-grow">
    <div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden p-6">
      <h1 class="text-3xl font-bold text-center mb-6 rainbow-text">Tes Seberapa Homok Kamu?</h1>
      <p class="text-gray-600 text-center mb-6">Masukkan nama kamu dan temukan kebenarannya! 🏳️‍🌈</p>
      
      <form id="gayTestForm" class="mb-6">
        <input type="text" id="nameInput" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-purple-500 mb-4" placeholder="Masukkan nama kamu" required>
        <button type="submit" id="submitButton" class="w-full bg-purple-600 hover:bg-purple-700 text-white font-bold py-3 px-4 rounded-lg transition duration-200">
          Cek Sekarang!
        </button>
      </form>

      <div id="progressContainer" class="hidden mb-6">
        <div class="w-full bg-gray-200 rounded-full h-4">
          <div id="progressBar" class="bg-purple-600 h-4 rounded-full text-xs text-white flex items-center justify-center" style="width: 0%">0%</div>
        </div>
      </div>

      <div id="resultContainer" class="hidden">
        <div id="resultText" class="text-xl font-bold text-center mb-4"></div>
        <div id="resultImage" class="w-48 h-48 mx-auto rounded-full overflow-hidden border-4 border-purple-300 shadow-lg"></div>
        <div id="shareButton" class="mt-6 hidden">
          <button onclick="shareResult()" class="w-full bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-lg transition duration-200">
            <i class="fab fa-whatsapp mr-2"></i> Bagikan Hasil
          </button>
        </div>
      </div>
    </div>
  </div>

  <footer class="py-4 text-center text-gray-500 text-sm">
    <p>Dibuat dengan ❤️ oleh Rafee &copy; 2025 | 
      <a href="https://github.com/rafiedotid" target="_blank" class="hover:text-purple-600">
        <i class="fab fa-github"></i> GitHub
      </a>
    </p>
  </footer>

  <script>
    // Check if already submitted
    const alreadySubmitted = localStorage.getItem('gayTestSubmitted');
    if (alreadySubmitted) {
      document.getElementById('gayTestForm').style.display = 'none';
      document.getElementById('resultContainer').classList.remove('hidden');
      document.getElementById('resultText').textContent = alreadySubmitted;
      document.getElementById('shareButton').classList.remove('hidden');
      
      // Get the stored result percentage
      const storedPercent = localStorage.getItem('gayTestPercent');
      showResultImage(storedPercent);
    }

    function checkGayLevel() {
      const name = document.getElementById("nameInput").value.trim();
      const resultText = document.getElementById("resultText");
      const resultContainer = document.getElementById("resultContainer");
      const progressBar = document.getElementById("progressBar");
      const progressContainer = document.getElementById("progressContainer");
      const submitButton = document.getElementById("submitButton");

      if (!name) {
        alert("Masukkan nama dulu dong!");
        return;
      }

      // Disable form
      submitButton.disabled = true;
      progressContainer.classList.remove('hidden');
      resultContainer.classList.add('hidden');

      // Generate random percentage (weighted towards lower percentages)
      const percent = Math.floor(Math.pow(Math.random(), 1.5) * 101);
      let current = 0;

      const interval = setInterval(() => {
        if (current >= percent) {
          clearInterval(interval);
          submitButton.disabled = false;
          
          let desc = "";
          let emoji = "";

          if (percent < 20) {
            desc = "Masih sangat lurus! 😎";
            emoji = "🚹";
          } else if (percent < 40) {
            desc = "Sedikit penasaran~ 😏";
            emoji = "🌈";
          } else if (percent < 60) {
            desc = "50:50 bisa jadi gay atau tidak 😘";
            emoji = "💖";
          } else if (percent < 80) {
            desc = "Gay sejati! 💅✨";
            emoji = "🏳️‍🌈";
          } else {
            desc = "GAY LEVEL DEWA! 🔥💯";
            emoji = "👑🏳️‍🌈";
          }

          const resultMessage = `${name}, kamu ${percent}% gay! ${emoji}\n${desc}`;
          resultText.textContent = resultMessage;
          resultContainer.classList.remove('hidden');
          showResultImage(percent);
          
          // Store result in localStorage
          localStorage.setItem('gayTestSubmitted', resultMessage);
          localStorage.setItem('gayTestPercent', percent);
          
          // Show share button
          document.getElementById('shareButton').classList.remove('hidden');
        } else {
          current++;
          progressBar.style.width = `${current}%`;
          progressBar.textContent = `${current}%`;
        }
      }, 20);
    }

    function showResultImage(percent) {
      const resultImage = document.getElementById('resultImage');
      resultImage.innerHTML = '';
      
      const img = document.createElement('div');
      img.className = 'w-full h-full flex items-center justify-center text-6xl';
      
      if (percent < 20) {
        img.innerHTML = '🚹';
        img.className += ' bg-blue-100';
      } else if (percent < 40) {
        img.innerHTML = '🌈';
        img.className += ' bg-purple-100';
      } else if (percent < 60) {
        img.innerHTML = '💖';
        img.className += ' bg-pink-100';
      } else if (percent < 80) {
        img.innerHTML = '🏳️‍🌈';
        img.className += ' pride-flag';
      } else {
        img.innerHTML = '👑';
        img.className += ' bg-yellow-100';
      }
      
      resultImage.appendChild(img);
    }

    function shareResult() {
      const resultText = localStorage.getItem('gayTestSubmitted');
      const shareText = `Aku baru saja mengikuti Tes Seberapa Homok Kamu!\n\n${resultText}\n\nCoba tesnya di: ${window.location.href}`;
      
      if (navigator.share) {
        navigator.share({
          title: 'Hasil Tes Homok Saya',
          text: shareText,
          url: window.location.href
        }).catch(err => {
          console.log('Error sharing:', err);
          copyToClipboard(shareText);
        });
      } else {
        // Fallback for devices that don't support Web Share API
        window.open(`https://wa.me/?text=${encodeURIComponent(shareText)}`, '_blank');
      }
    }

    function copyToClipboard(text) {
      const textarea = document.createElement('textarea');
      textarea.value = text;
      document.body.appendChild(textarea);
      textarea.select();
      document.execCommand('copy');
      document.body.removeChild(textarea);
      alert('Hasil telah disalin ke clipboard!');
    }

    document.getElementById('gayTestForm').addEventListener('submit', function(e) {
      e.preventDefault();
      checkGayLevel();
    });
  </script>
</body>

</html>
