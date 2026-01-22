# digital-pet

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Biancagambino7/digital-pet/blob/main/digital_pet.ipynb)


https://biancagambino7.github.io/digital-pet/ 

<h1>Emoji Pet Game 🐾</h1>

<p>A digital pet game in Python where you take care of your pet, interact with it, and monitor real-world influences like weather, Bitcoin, and NBA results — all in one interactive console-based dashboard!</p>

<h2>🎮 How to Play</h2>

<ol>
  <li><strong>Choose Your Pet Emoji</strong><br>
      Select your pet from <strong>10 different animal emojis</strong>:
      <ul>
        <li>🐶 Dog</li>
        <li>🐱 Cat</li>
        <li>🐰 Rabbit</li>
        <li>🐹 Hamster</li>
        <li>🦊 Fox</li>
        <li>🐻 Bear</li>
        <li>🐼 Panda</li>
        <li>🐸 Frog</li>
        <li>🐵 Monkey</li>
        <li>🐧 Penguin</li>
      </ul>
  </li>
  
  <li><strong>Name Your Pet</strong><br>
      Give your pet a unique name. This will appear throughout the game.</li>
  
  <li><strong>Pick a Favorite Toy</strong><br>
      Choose your pet’s favorite from 5 toy options:
      <ul>
        <li>🧸 Teddy</li>
        <li>⚽ Ball</li>
        <li>🪃 Boomerang</li>
        <li>🧶 Yarn</li>
        <li>🦴 Bone</li>
      </ul>
      When you play, a random toy is chosen — if it matches your pet’s favorite, happiness gets a bonus!</li>
  
  <li><strong>Enter Your ZIP Code</strong><br>
      The game fetches <strong>real-world weather</strong> for your location:
      <ul>
        <li>Sunny → increases happiness and energy</li>
        <li>Rain/Storm → decreases happiness</li>
        <li>Snow → slightly lowers energy</li>
      </ul>
  </li>
  
  <li><strong>Pick Your NBA Team</strong><br>
      Enter a team name (e.g., <em>Boston Celtics</em>) to track their <strong>most recent game</strong>:
      <ul>
        <li>Win → +2 happiness</li>
        <li>Loss → −2 happiness</li>
        <li>No recent game → neutral effect</li>
      </ul>
  </li>
  
  <li><strong>Game Dashboard</strong><br>
      Your pet stats are displayed as <strong>bars</strong>:
      <ul>
        <li><strong>Hunger:</strong> High = starving, Low = full</li>
        <li><strong>Happiness:</strong> High = happy, Low = sad</li>
        <li><strong>Energy:</strong> High = energetic, Low = tired</li>
      </ul>
      Example:
      <pre>
🐶 Fluffy
Hunger     █████░░░░░ 5/10  Moderate
Happiness  ██████░░░ 6/10  Moderate
Energy     ██████░░░ 6/10  Moderate
      </pre>
  </li>
  
  <li><strong>Actions</strong><br>
      Choose from the following actions each turn:
      <ul>
        <li><strong>Feed 🍎</strong> → decreases Hunger</li>
        <li><strong>Play 🎾</strong> → increases Happiness (+bonus if favorite toy), decreases Energy</li>
        <li><strong>Sleep 😴</strong> → increases Energy, slightly increases Hunger</li>
        <li><strong>Medicine 💊</strong> → increases Happiness</li>
        <li><strong>Quit</strong> → exit the game</li>
      </ul>
      Every action gives a clear description of what happened (e.g., “You fed Fluffy, Hunger decreased by 2”).</li>
  
  <li><strong>Real-World Influences</strong><br>
      Your pet’s mood is affected by:
      <ul>
        <li>🌤 <strong>Weather</strong> at your ZIP code</li>
        <li>₿ <strong>Bitcoin market</strong></li>
        <li>🏀 <strong>NBA team results</strong></li>
      </ul>
      The dashboard shows the current <strong>status and effect</strong> of each.</li>
</ol>

<h2>⚡ Features</h2>
<ul>
  <li>Interactive console-based game with <strong>emoji graphics</strong></li>
  <li>Dynamic <strong>stat bars</strong> for Hunger, Happiness, and Energy</li>
  <li><strong>Favorite toy mechanic</strong> for extra happiness bonus</li>
  <li><strong>Real-time influences</strong>:
    <ul>
      <li>Weather (location-based)</li>
      <li>Bitcoin price (Bull/Bear/Stable)</li>
      <li>NBA team result (Win/Loss/No recent game)</li>
    </ul>
  </li>
  <li>Action descriptions for clarity</li>
  <li>No API keys required</li>
</ul>

<h2>📦 Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li><code>requests</code> library (<code>pip install requests</code>)</li>
</ul>

<h2>🚀 How to Run</h2>
<ol>
  <li>Clone the repository:
    <pre>git clone https://github.com/YOUR_USERNAME/emoji-pet.git
cd emoji-pet</pre>
  </li>
  <li>Install dependencies:
    <pre>pip install requests</pre>
  </li>
  <li>Run the game:
    <pre>python emoji_pet.py</pre>
  </li>
  <li>Follow the on-screen prompts to select your pet, name it, pick a toy, enter your ZIP code, and choose an NBA team.</li>
</ol>

<h2>🐾 Tips</h2>
<ul>
  <li>Monitor Hunger: If Hunger gets too high, your pet may become unhappy or “starving”</li>
  <li>Play strategically: Playing with your pet consumes energy, so balance feeding, playing, and sleeping</li>
  <li>Check weather & NBA/Bitcoin effects: They update your pet’s stats automatically each turn</li>
</ul>

<h3> Ready to Play?</h3>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Biancagambino7/digital-pet/blob/main/digital_pet.ipynb)

<h2>License</h2>
<p>This project is MIT Licensed. Feel free to modify and share!</p>
