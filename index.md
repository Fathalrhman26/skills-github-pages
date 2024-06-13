---
layout: default
title: Home
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400;700&display=swap');

  body {
    font-family: 'Roboto', sans-serif;
    background: linear-gradient(135deg, #0f0f0f, #353535);
    color: #e0e0e0;
    margin: 0;
    padding: 0;
    line-height: 1.6em;
  }

  .container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 2em;
    text-align: center;
  }

  h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: 4em;
    margin-bottom: 0.5em;
    color: #00e0ff;
  }

  h2 {
    font-family: 'Orbitron', sans-serif;
    color: #00e0ff;
  }

  p {
    font-size: 1.2em;
    margin-bottom: 2em;
  }

  .tech-icons, .social-links {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin: 2em 0;
  }

  .tech-icons img, .social-links a {
    transition: transform 0.3s ease;
  }

  .tech-icons img:hover, .social-links a:hover {
    transform: scale(1.2);
  }

  .social-links a {
    color: #00e0ff;
    text-decoration: none;
    font-size: 1.5em;
    padding: 10px 15px;
    border: 2px solid #00e0ff;
    border-radius: 5px;
  }

  .timeline {
    position: relative;
    max-width: 800px;
    margin: 2em auto;
    padding: 2em 0;
    text-align: left;
  }

  .timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: #00e0ff;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -3px;
  }

  .container-timeline {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    width: 50%;
  }

  .container-timeline.left {
    left: 0;
  }

  .container-timeline.right {
    left: 50%;
  }

  .container-timeline::after {
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right: -17px;
    background-color: #fff;
    border: 4px solid #00e0ff;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
  }

  .container-timeline.right::after {
    left: -16px;
  }

  .content {
    padding: 20px 30px;
    background-color: #1a1a1a;
    position: relative;
    border-radius: 6px;
  }
</style>

<div class="container">
  <h1>Hi 👋, I'm Fathalrhman</h1>
  <p>
    Welcome to my futuristic space on the web! I'm an AI enthusiast and Software Engineer passionate about contributing to open source and developing AI solutions that make a difference. Explore my projects, connect with me, and let's innovate together.
  </p>

  <h2>Tech Stack</h2>
  <div class="tech-icons">
    <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/pytorch/pytorch-original.svg" title="PyTorch" alt="PyTorch" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" title="C++" alt="C++" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="NumPy" alt="NumPy" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" title="Pandas" alt="Pandas" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" alt="Git" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="GitHub" alt="GitHub" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/flask/flask-original.svg" title="Flask" alt="Flask" width="40" height="40"/>
  </div>

  <h2>Experience and Projects</h2>
  <div class="timeline">
    <div class="container-timeline left">
      <div class="content">
        <h3>Machine Learning Engineering Intern</h3>
        <p><strong>Shai for AI</strong> (Remote) <br> June 2021 – March 2022</p>
        <ul>
          <li>Trained and fine-tuned various supervised and unsupervised models using Python, PyTorch, and JavaScript (TensorFlow.js) for predictive analytics and marketing optimization.</li>
          <li>Developed Jupyter/Colab notebooks for training and evaluating models on different datasets.</li>
          <li>Designed and implemented production-ready pipelines, seamlessly integrating trained models into predictive engine-compatible formats.</li>
        </ul>
      </div>
    </div>
    <div class="container-timeline right">
      <div class="content">
        <h3>Machine Learning Instructor</h3>
        <p><strong>IEEE Alneelain University Student Branch</strong> (Khartoum, Sudan) <br> August 2021 – February 2022</p>
        <ul>
          <li>Implemented ML algorithm prototypes to demo data sets, demonstrating expertise in machine learning model development.</li>
          <li>Organized several labs and seminars, providing hands-on experience with machine learning technologies and tools.</li>
          <li>Designed and developed course content on topics including machine learning, Python programming, and statistical analysis.</li>
        </ul>
      </div>
    </div>
  </div>

  <h2>Projects</h2>
  <div class="tech-icons">
    <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>
  </div>
  <p>
    <strong>AI Based Recipe and Meal Planning App:</strong> An app providing personalized meal plans, recipes, and grocery lists based on dietary preferences.
  </p>
  <p>
    <strong>Open Source Contributions:</strong> Actively contributing to various open source projects, enhancing functionality, and fixing bugs.
  </p>

  <h2>Honors and Awards</h2>
  <p>
    <strong>Travel Grant, Neelain University:</strong> Received a travel grant to attend the Deeplearning Indaba Conference in Tunis, Tunisia.
  </p>
  <p>
    <strong>Fully Funded Scholarship, Arab Innovation Academy:</strong> Received a fully funded scholarship to study entrepreneurship and innovation in Doha, Qatar.
  </p>

  <h2>Let's Connect</h2>
  <div class="social-links">
    <a href="https://twitter.com/Fathalrhman26" title="Twitter"><i class="fab fa-twitter"></i> Twitter</a>
    <a href="https://www.linkedin.com/in/fathalrhman26/" title="LinkedIn"><i class="fab fa-linkedin"></i> LinkedIn</a>
    <a href="mailto:fathalrhman@example.com" title="Email"><i class="fas fa-envelope"></i> Email</a>
  </div>
</div>

<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
