<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1>🤖 Jarvis - Python Voice Assistant</h1>
    <p>A basic voice assistant built using Python that can search Wikipedia, open websites, play music, tell the time, and send emails. Inspired by Iron Man's Jarvis.</p>

   <h2>🚀 Features</h2>
    <ul>
        <li>Voice greeting based on time of day</li>
        <li>Speech recognition using microphone</li>
        <li>Text-to-speech responses</li>
        <li>Search Wikipedia summaries</li>
        <li>Open websites like YouTube, Google, and Stack Overflow</li>
        <li>Play local music files</li>
        <li>Tell the current time</li>
        <li>Send emails using Gmail SMTP</li>
    </ul>

   <h2>🛠 Requirements</h2>
    <pre><code>pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pyaudio</code></pre>

   <h2>🔧 Setup</h2>
    <ol>
        <li>Install Python 3.x</li>
        <li>Install the required libraries using pip</li>
        <li>Make sure your microphone is working</li>
        <li>Replace paths like <code>music_dir</code> and <code>codePath</code> with your own</li>
        <li>Update the <code>sendEmail</code> function with your Gmail credentials</li>
    </ol>

   <h2>⚙️ Usage</h2>
    <pre><code>python jarvis.py</code></pre>
    <p>Then, speak commands like:</p>
    <ul>
        <li><code>Wikipedia Python</code></li>
        <li><code>Open YouTube</code></li>
        <li><code>Play Music</code></li>
        <li><code>What is the time</code></li>
        <li><code>Email to someone</code></li>
    </ul>

   <h2>🔒 Important Notes</h2>
    <ul>
        <li>Less secure app access must be enabled for Gmail SMTP</li>
        <li>Consider using environment variables or encrypted storage for your email credentials</li>
    </ul>

   <h2>📄 License</h2>
    <p>MIT License - free to use and modify.</p>
</body>
</html>
