<h1>🦴 AI Talking Animatronic Skull</h1>

<p>
  A repository for building and experimenting with an AI-driven animatronic skull that combines
  hardware control, speech processing, chatbot integration, and emotion-recognition experiments.
</p>

<hr>

<h2>📌 Project Status</h2>

<p>
  This repository currently looks like a <strong>project workspace / prototype repository</strong>
  rather than a single packaged application.
  It includes hardware sketches, Python scripts, Jupyter notebooks, 3D-printable parts,
  research material, and supporting assets related to the animatronic skull project.
</p>

<hr>

<h2>🚀 Overview</h2>

<p>
  The project brings together several parts of an interactive animatronic skull system:
</p>

<ul>
  <li>Arduino-based servo control for skull movement</li>
  <li>Python-based serial communication with the hardware</li>
  <li>ChatGPT / OpenAI connection experiments</li>
  <li>Speech-to-text command recognition work</li>
  <li>Wav2Vec2 / Transformers-based speech experiments</li>
  <li>Emotion recognition from speech experiments</li>
  <li>3D models and images for the skull assembly</li>
</ul>

<p>
  Instead of one final end-to-end application, the repository documents the different building blocks
  used while developing the system.
</p>

<hr>

<h2>🧩 What’s Inside</h2>

<h3>Arduino Control</h3>
<p>
  The <code>arduino/</code> folder contains Arduino sketches for testing and driving servo movement,
  including direct servo angle control and “speak” style repetitive jaw motion.
</p>

<h3>Python Hardware Interface</h3>
<p>
  The root-level <code>arduino.py</code> script demonstrates Python-to-Arduino serial communication
  for sending servo angles over a serial port.
</p>

<h3>ChatGPT / OpenAI Integration</h3>
<p>
  The <code>chatGPT/</code> folder contains Python scripts that experiment with sending prompts to OpenAI
  and printing generated responses.
</p>

<h3>Speech Recognition</h3>
<p>
  The <code>speache2text/</code> folder contains a trained model file, sample WAV files,
  and a notebook related to speech command recognition.
</p>

<h3>Wav2Vec2 / Transformer Experiments</h3>
<p>
  The <code>wav2vec2Transformers/</code> folder contains notebooks, vocabulary files,
  and additional supporting materials related to speech modeling with Hugging Face tooling.
</p>

<h3>Speech Emotion Recognition</h3>
<p>
  The <code>wave2vec2emotionRecognition/</code> folder contains notebooks and assets
  for emotion recognition from speech embeddings.
</p>

<h3>3D Skull Assets</h3>
<p>
  The <code>skull/</code> folder contains STL files and images for the physical skull build,
  including separate printable parts such as the jaw, face, base, neck, eye mechanism,
  teeth, and other structural components.
</p>

<hr>

<h2>📁 Repository Structure</h2>

<pre><code>AI-Talkig-Animatronic-Skull/
├── EMR models/
├── SER_Transformers_WAV2VEC2/
├── Speech Recognition LSTM Tensorflow/
├── arduino/
│   ├── checkServos/
│   ├── checkServosSpeak/
│   └── servos/
├── chatGPT/
│   ├── api_project.py
│   └── openAIconnect.py
├── papers/
├── skull/
│   ├── STL/
│   └── images/
├── speache2text/
│   ├── SpeechRecogModel.h5
│   ├── speach2textCommands.ipynb
│   └── sample .wav files
├── wav2vec2Transformers/
├── wave2vec2emotionRecognition/
└── arduino.py</code></pre>

<hr>

<h2>🔧 Key Components</h2>

<h3>1. Arduino Servo Testing</h3>
<p>
  The Arduino sketches are used to test servo movement and speaking-style jaw motion.
  One sketch uses a standard servo setup, while another uses a PCA9685-based controller.
</p>

<h3>2. Python Serial Communication</h3>
<p>
  The Python servo-control script connects to Arduino through a serial port and sends angles
  in the 0–180 range.
</p>

<h3>3. OpenAI Chat Experiments</h3>
<p>
  The chatbot scripts show early experiments for prompting OpenAI models and printing answers
  back in the terminal.
</p>

<h3>4. Speech and Emotion Recognition Research</h3>
<p>
  Multiple notebooks in the repository explore speech-to-text recognition, Wav2Vec2 workflows,
  and speech emotion recognition as part of the broader animatronic interaction pipeline.
</p>

<h3>5. Physical Build Assets</h3>
<p>
  The skull build files suggest that the physical project includes a custom 3D-printed shell
  and mechanical parts for jaw and facial motion.
</p>

<hr>

<h2>🖨️ 3D Printable Parts</h2>

<p>
  The STL assets include printable parts such as:
</p>

<ul>
  <li>Full skull</li>
  <li>Left / right skull sections</li>
  <li>Jaw</li>
  <li>Face</li>
  <li>Base</li>
  <li>Neck</li>
  <li>Teeth</li>
  <li>Eyeballs</li>
  <li>Eye mechanism</li>
  <li>Top enclosure</li>
  <li>Mounts and structural parts</li>
</ul>

<hr>

<h2>⚠️ Current Limitations</h2>

<ul>
  <li>This repository does not currently provide a single polished entry point for running the full system.</li>
  <li>There is no unified installation guide or dependency file at the repository root.</li>
  <li>Some folders appear to be experimental, academic, or intermediate development material.</li>
  <li>OpenAI-related scripts should be cleaned and updated before production use.</li>
</ul>

<hr>

<h2>🛠️ Suggested Cleanup Before Production Use</h2>

<ul>
  <li>Remove hardcoded API keys and use environment variables instead</li>
  <li>Add a proper <code>requirements.txt</code> or <code>pyproject.toml</code></li>
  <li>Create a single runnable application entry point</li>
  <li>Document the hardware wiring and bill of materials</li>
  <li>Add photos or videos of the final skull in action</li>
  <li>Separate research notebooks from the final deployable code</li>
</ul>

<hr>

<h2>🎯 Purpose of This Repository</h2>

<p>
  This repository documents the development of an animatronic skull project that sits at the intersection
  of robotics, embedded systems, conversational AI, speech recognition, and affective computing.
  It is best understood as a multi-part development repository containing both implementation assets
  and research experiments.
</p>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <strong>Sagi Yosef Azulay</strong><br>
  GitHub:
  <a href="https://github.com/sagir567">https://github.com/sagir567</a>
</p>
