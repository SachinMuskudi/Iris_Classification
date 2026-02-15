<h1>🌸 Iris Species Classification Web Application</h1>

<p>
A <strong>Flask-based Machine Learning web application</strong> that predicts
<I>Iris flower species</I> using <strong>K-Nearest Neighbors (KNN)</strong> and
<strong>Gaussian Naive Bayes</strong>.  
The application provides real-time predictions along with detailed
<strong>training and testing performance metrics</strong>.
</p>

<p>
🚀 Live Demo:
<a href="https://iris-classification-9ji9.onrender.com" target="_blank">
Iris Classifier on Render
</a>
</p>

<hr>

<h2>📌 Table of Contents</h2>
<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#architecture">Project Architecture</a></li>
  <li><a href="#models">Machine Learning Models</a></li>
  <li><a href="#dataset">Dataset Information</a></li>
  <li><a href="#performance">Model Performance</a></li>
  <li><a href="#structure">Project Structure</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#deployment">Deployment</a></li>
  <li><a href="#future">Future Enhancements</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#contact">Contact</a></li>
</ul>

<hr>

<h2 id="features">✨ Features</h2>
<ul>
  <li>Interactive input form for Iris flower measurements</li>
  <li>Model selection between KNN and Naive Bayes</li>
  <li>Real-time species prediction (Setosa, Versicolor, Virginica)</li>
  <li>Training & testing accuracy, confusion matrix, and classification report</li>
  <li>Modern glass-morphism UI</li>
  <li>Fully responsive (desktop, tablet, mobile)</li>
</ul>

<hr>

<h2 id="architecture">🏗 Project Architecture</h2>

<p><strong>Frontend</strong></p>
<ul>
  <li>HTML, CSS, JavaScript</li>
  <li>Bootstrap 5</li>
  <li>Glass-morphism UI design</li>
</ul>

<p><strong>Backend</strong></p>
<ul>
  <li>Python with <strong>:contentReference[oaicite:0]{index=0}</strong></li>
  <li>Pickle for model loading</li>
  <li>JSON for metrics storage</li>
  <li>Jinja2 templating</li>
</ul>

<hr>

<h2 id="models">🤖 Machine Learning Models</h2>
<ul>
  <li><strong>K-Nearest Neighbors (k = 3)</strong></li>
  <li><strong>Gaussian Naive Bayes</strong></li>
  <li>Implemented using <strong>:contentReference[oaicite:1]{index=1}</strong></li>
</ul>

<hr>

<h2 id="dataset">📊 Dataset Information</h2>

<p>
Dataset source: <strong>UCI Machine Learning Repository</strong>
</p>

<table>
  <tr>
    <th>Feature</th>
    <th>Range (cm)</th>
  </tr>
  <tr><td>Sepal Length</td><td>4.3 – 7.9</td></tr>
  <tr><td>Sepal Width</td><td>2.0 – 4.4</td></tr>
  <tr><td>Petal Length</td><td>1.0 – 6.9</td></tr>
  <tr><td>Petal Width</td><td>0.1 – 2.5</td></tr>
</table>

<hr>

<h2 id="performance">📈 Model Performance</h2>

<p><strong>KNN & Naive Bayes</strong></p>

<ul>
  <li>Training Accuracy: <strong>95%</strong></li>
  <li>Testing Accuracy: <strong>100%</strong></li>
  <li>Perfect classification on test dataset</li>
</ul>

<hr>

<h2 id="structure">📂 Project Structure</h2>

<pre><code>iris-classifier/
├── app.py
├── requirements.txt
├── Procfile
├── templates/
│   └── index.html
├── KNN.pkl
├── NB.pkl
├── train_knn.json
├── test_knn.json
├── train_NB.json
└── test_NB.json
</code></pre>

<hr>

<h2 id="installation">⚙️ Installation</h2>

<pre><code>git clone https://github.com/yourusername/iris-classifier.git
cd iris-classifier
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
</code></pre>

<p>
Open browser: <code>http://127.0.0.1:5000</code>
</p>

<hr>

<h2 id="usage">🧪 Usage</h2>
<ol>
  <li>Enter flower measurements</li>
  <li>Select KNN or Naive Bayes</li>
  <li>Click <strong>Predict</strong></li>
  <li>View prediction and performance metrics</li>
</ol>

<hr>

<h2 id="deployment">☁️ Deployment (Render)</h2>

<pre><code>Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app
</code></pre>

<hr>

<h2 id="future">🚀 Future Enhancements</h2>
<ul>
  <li>Add more ML algorithms (SVM, Random Forest)</li>
  <li>CSV batch prediction</li>
  <li>Visualization charts</li>
  <li>User authentication</li>
  <li>REST API support</li>
</ul>

<hr>

<h2 id="license">📄 License</h2>
<p>
This project is open-source and available for educational and commercial use.
</p>

<hr>

<h2 id="contact">📧 Contact</h2>

<p>
<strong>Sachin Muskudi</strong><br>
📩 <a href="mailto:sachinmuskudim@gmail.com">sachinmuskudim@gmail.com</a><br>
🔗 <a href="https://github.com/yourusername">GitHub Profile</a>
</p>

<p>⭐ If you like this project, please give it a star!</p>
