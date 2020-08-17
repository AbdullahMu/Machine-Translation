---


---

<h1 id="project-machine-translation">Project: Machine Translation</h1>
<p>Machine translation is a popular topic in research with new papers coming out every year. Over the years of research, different methods were created, like  <a href="https://en.wikipedia.org/wiki/Rule-based_machine_translation">rule-based</a>,  <a href="https://en.wikipedia.org/wiki/Statistical_machine_translation">statistical</a>, and  <a href="https://en.wikipedia.org/wiki/Example-based_machine_translation">example-based</a>  machine translation. With all this effort, it’s still an unsolved problem. However, neural networks have made a large leap forward in machine translation.</p>
<p>In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.</p>
<h1 id="introduction">Introduction</h1>
<p>In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.</p>
<h1 id="setup"><a href="https://github.com/AbdullahMu/Machine-Translation#setup"></a>Setup</h1>
<p>This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.</p>
<h2 id="udacity-workspaces-recommended"><a href="https://github.com/AbdullahMu/Machine-Translation#udacity-workspaces-recommended"></a>Udacity Workspaces (Recommended)</h2>
<p>Udacity Workspaces provide remote connection to GPU-enabled instances right from the classroom. Refer to the classroom lesson for this project to find an overview of navigating &amp; using Jupyter notebook Workspaces.</p>
<h2 id="amazon-web-services-optional"><a href="https://github.com/AbdullahMu/Machine-Translation#amazon-web-services-optional"></a>Amazon Web Services (Optional)</h2>
<p>Please refer to the Udacity instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project.  <a href="https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project">link for AIND students</a></p>
<h2 id="install"><a href="https://github.com/AbdullahMu/Machine-Translation#install"></a>Install</h2>
<ul>
<li>Python 3</li>
<li>NumPy</li>
<li>TensorFlow 1.x</li>
<li>Keras 2.x</li>
</ul>
<h1 id="submission"><a href="https://github.com/AbdullahMu/Machine-Translation#submission"></a>Submission</h1>
<p>When you are ready to submit your project, do the following steps:</p>
<ol>
<li>Ensure you pass all points on the  <a href="https://review.udacity.com/#!/rubrics/1004/view">rubric</a>.</li>
<li>Submit the following in a zip file:</li>
</ol>
<ul>
<li><code>helper.py</code></li>
<li><code>machine_translation.ipynb</code></li>
<li><code>machine_translation.html</code></li>
</ul>
<h2 id="converting-to-html"><a href="https://github.com/AbdullahMu/Machine-Translation#converting-to-html"></a>Converting to HTML</h2>
<p>There are several ways to generate an HTML copy of the notebook:</p>
<ul>
<li>
<p>Running the last cell of the notebook will export an HTML copy</p>
</li>
<li>
<p>Navigating to  <strong>File -&gt; Download as -&gt; HTML (.html)</strong>  within the notebook</p>
</li>
<li>
<p>Using  <code>nbconvert</code>  from the command line</p>
<p>$ pip install nbconvert $ nbconvert machine_translation.ipynb</p>
</li>
</ul>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

