<h1>🦴 AI Talking Animatronic Skull</h1>

<p>
  A multidisciplinary project combining <strong>AI, speech processing, and robotics</strong> to create
  a physical animatronic skull capable of interacting through voice and motion.
</p>

<hr>

<h2>🚀 Overview</h2>

<p>
  This project explores the integration of <strong>conversational AI</strong>, <strong>speech recognition</strong>,
  and <strong>embedded hardware control</strong> into a single interactive system.
</p>

<p>
  The system is designed to:
</p>

<ul>
  <li>Process spoken input</li>
  <li>Generate intelligent responses using AI</li>
  <li>Convert responses into audio output</li>
  <li>Drive physical motion (jaw / facial components) in sync with speech</li>
</ul>

<p>
  The repository represents the development of a full pipeline — from signal processing and machine learning
  to real-world actuation through hardware.
</p>

<hr>

<h2>🧠 Core Capabilities</h2>

<ul>
  <li>AI-driven conversational response generation</li>
  <li>Speech-to-text experimentation (custom models + datasets)</li>
  <li>Text-to-speech integration groundwork</li>
  <li>Servo-based mechanical motion (jaw control)</li>
  <li>Python ↔ Arduino serial communication</li>
  <li>Emotion recognition from speech (Wav2Vec2-based experiments)</li>
  <li>Custom 3D-designed animatronic structure</li>
</ul>

<hr>

<h2>🏗️ System Concept</h2>

<pre><code>User Speech
     ↓
Speech Processing
     ↓
AI Response Generation
     ↓
Audio Output
     ↓
Physical Actuation (Servo-driven jaw)
</code></pre>

<hr>

<h2>🛠️ Tech Stack</h2>

<h3>Software</h3>
<ul>
  <li>Python</li>
  <li>Transformers (Wav2Vec2)</li>
  <li>TensorFlow / Deep Learning models</li>
  <li>Speech processing pipelines</li>
  <li>OpenAI API (chat-based interaction experiments)</li>
</ul>

<h3>Hardware</h3>
<ul>
  <li>Arduino</li>
  <li>Servo motors</li>
  <li>PCA9685 servo controller (in some setups)</li>
  <li>3D-printed mechanical structure</li>
</ul>

<hr>

<h2>📁 Project Structure</h2>

<pre><code>AI-Talkig-Animatronic-Skull/
├── arduino/                         # Servo control sketches
├── chatGPT/                         # AI interaction scripts
├── speache2text/                    # Speech recognition models & notebooks
├── wav2vec2Transformers/            # Transformer-based speech experiments
├── wave2vec2emotionRecognition/     # Emotion recognition experiments
├── skull/                           # 3D models and images
├── papers/                          # Research references
├── arduino.py                       # Python → Arduino communication
└── additional ML / experiment folders
</code></pre>

<hr>

<h2>🔧 Key Components</h2>

<h3>Arduino Servo Control</h3>
<p>
  Multiple Arduino sketches are used to test and control servo-based motion,
  including jaw actuation patterns designed to simulate speech.
</p>

<h3>Python Hardware Interface</h3>
<p>
  A Python script communicates with the Arduino over a serial connection,
  enabling dynamic control of servo angles from software.
</p>

<h3>AI Integration</h3>
<p>
  The project includes early-stage integration with OpenAI models,
  enabling prompt-based response generation for conversational interaction.
</p>

<h3>Speech Processing</h3>
<p>
  Several experimental pipelines are included for:
</p>
<ul>
  <li>Speech-to-text recognition</li>
  <li>Custom dataset training</li>
  <li>Transformer-based audio modeling (Wav2Vec2)</li>
</ul>

<h3>Emotion Recognition</h3>
<p>
  The repository explores affective computing through speech,
  using deep learning models to classify emotional states from audio signals.
</p>

<h3>Physical System</h3>
<p>
  The skull is built using custom 3D-printed parts, including:
</p>
<ul>
  <li>Jaw mechanism</li>
  <li>Face and skull structure</li>
  <li>Eye components</li>
  <li>Base and mounting parts</li>
</ul>

<hr>

<h2>🖨️ 3D Assets</h2>

<p>
  The <code>skull/</code> directory contains STL files and visual references for building the animatronic skull,
  including modular components for assembly and mechanical integration.
</p>

<hr>

<h2>🎯 Project Scope</h2>

<p>
  This project focuses on bridging the gap between <strong>AI systems</strong> and <strong>physical interaction</strong>.
  It serves as a foundation for building expressive robotic characters that combine perception,
  reasoning, and motion.
</p>

<hr>

<h2>🔮 Future Directions</h2>

<ul>
  <li>Real-time full pipeline integration (STT → AI → TTS → motion)</li>
  <li>Improved lip-sync accuracy</li>
  <li>Multi-servo facial expressions</li>
  <li>Vision-based interaction</li>
  <li>Edge / offline AI models</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <strong>Sagi Yosef Azulay</strong><br>
  GitHub:
  <a href="https://github.com/sagir567">https://github.com/sagir567</a>
</p>
