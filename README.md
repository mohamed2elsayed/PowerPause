<h2>🚀 Introducing PowerPause: The Python Automation Tool I Built to Control Media & System Power</h2>

<p>
Tired of media distractions or forgetting to shut down your PC? Meet <strong>PowerPause</strong> – my open-source Python app that automatically pauses media (<em>Spotify, YouTube, VLC, etc.</em>) and schedules system actions (<em>sleep/shutdown/restart</em>).
</p>

<h3>🔧 Tech Stack Deep Dive</h3>

<h4>🖥 Core Libraries:</h4>
<ul>
  <li><code>Python</code></li>
  <li><code>Tkinter</code> (GUI)</li>
  <li><code>psutil</code> (system monitoring)</li>
  <li><code>pyautogui</code> / <code>pygetwindow</code> (media control)</li>
  <li><code>win32gui</code> / <code>win32con</code> (Windows API integration)</li>
  <li><code>Pillow</code> (tray icon/image handling)</li>
  <li><code>pystray</code> (system tray integration)</li>
</ul>

<h3>⚡ Key Features:</h3>
<ul>
  <li>✅ <strong>Universal Media Pause</strong> – Works across 10+ players (Spotify, Chrome, VLC, Firefox)</li>
  <li>✅ <strong>Precision Timers</strong> – Schedule actions down to the second</li>
  <li>✅ <strong>Minimalist UI</strong> – Dark mode with smooth animations</li>
  <li>✅ <strong>Tray Mode</strong> – Runs hidden with quick-access controls</li>
</ul>

<h3>🚦 Challenges & Lessons</h3>
<ul>
  <li>🔹 <strong>Cross-App Compatibility:</strong> Solved using hybrid control (system APIs + direct keystrokes)</li>
  <li>🔹 <strong>Threaded Timers:</strong> Avoided GUI freezes with <code>threading</code></li>
  <li>🔹 <strong>Windows Integration:</strong> Leveraged <code>ctypes</code> and <code>win32con</code> for low-level control</li>
</ul>

<h3>💡 Why I Built This:</h3>
<p>
As a developer, I wanted a lightweight alternative to bloated automation tools. PowerPause is &lt;5MB and uses just 0.1% CPU at idle.
</p>
