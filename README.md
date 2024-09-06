<h1 align="center">Equi-Witty: News Research Tool for Equity Analysis</h1>

<p align="center">
  <i>An AI-powered chatbot designed to automate financial data extraction for equity research.</i>
</p>

---

<h2>📋 Project Overview</h2>

<p>
Equi-Witty is a collaborative project designed to assist equity research analysts by automating the extraction of financial information from news articles. Leveraging technologies like <strong>Langchain</strong>, <strong>Streamlit</strong>, and <strong>ChatGroq</strong>, the tool retrieves data efficiently, provides accurate insights, and supports informed investment decision-making.
</p>

<h2>🚀 Key Features</h2>

<ul>
  <li>Automated data extraction and query handling using <strong>LLM</strong> technology.</li>
  <li>Scalable and user-friendly interface built with <strong>Streamlit</strong>.</li>
  <li>Integration of a vector database for enhanced information retrieval.</li>
</ul>

<h2>🛠️ Technologies Used</h2>

<ul>
  <li><strong>Langchain</strong>: for building the language model chain.</li>
  <li><strong>Streamlit</strong>: to create an interactive user interface.</li>
  <li><strong>FAISS</strong>: for generating and managing vector databases.</li>
  <li><strong>Python</strong>: programming language for backend logic and data processing.</li>
</ul>

<h2>🔍 How It Works</h2>

<ol>
  <li>Users input URLs of news articles via the Streamlit interface.</li>
  <li>The tool processes the articles, extracts relevant information, and generates embeddings.</li>
  <li>A vector database stores these embeddings for efficient data retrieval.</li>
  <li>The chatbot provides answers and insights based on user queries.</li>
</ol>

<h2>📂 Project Structure</h2>

<pre>
Equi-Witty/
├── data/                 # Sample data files
├── models/               # Model files for embeddings
├── notebooks/            # Jupyter notebooks for exploration
├── src/                  # Source code
│   ├── utils/            # Utility scripts
│   └── main.py           # Main application script
└── README.md             # Project documentation
</pre>

<h2>📦 Installation</h2>

<pre>
<code>
git clone https://github.com/yourusername/Equi-Witty.git
cd Equi-Witty
pip install -r requirements.txt
</code>
</pre>

<h2>💡 Usage</h2>

<p>
Run the application using the command below and follow the prompts on the Streamlit interface:
</p>

<pre>
<code>streamlit run src/main.py</code>
</pre>

<h2>🖼️ Screenshots</h2>

<p>Here are some screenshots of the application in action:</p>

<ul>
  <li><img src="rockybot.jpg" alt="Screenshot 1" width="500"></li>
</ul>

<p>Upload your screenshots in the <code>screenshots/</code> directory and update the paths accordingly.</p>

<h2>🤝 Contributing</h2>

<p>
We welcome contributions! Please read our <a href="CONTRIBUTING.md">contributing guidelines</a> first.
</p>

<h2>📄 License</h2>

<p>
This project is licensed under the <a href="LICENSE">MIT License</a>.
</p>

<h2>👥 Team</h2>

<ul>
  <li>Epsita Rajesh</li>
  <li>Shruti Ranjan</li>
  <li>Ritushree Dey</li>
</ul>

<p align="center">
  <i>Developed under the guidance of Dr. Neha, CHRIST (Deemed to be University)</i>
</p>
