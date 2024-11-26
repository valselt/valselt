<h3>
  <div style="display: flex; align-items: center;">
    <span>Built it yourself!</span>
        <a href="https://www.anaconda.com/">
            <img src="https://skillicons.dev/icons?i=anaconda" alt="Anaconda" style="height: 24px; margin-left: 8px;">
        </a>
  </div>
</h3>

<ol>
  <li>Open Anaconda Prompt, then type this :</br><pre><code>conda create --name watsonxai-1 python=3.10</code></pre></li>
  <li>After creating the Conda Environment, activate it by type this</br><pre><code>conda activate watsonxai-1</code></pre></li>
  <li>Download the <a href="https://github.com/ibm-build-lab/VAD-VAR-Workshop/blob/main/content/labs/Watsonx/WatsonxAI/files/201/requirements.txt">requirements.txt</a></li>
  <li>Go back to your Anaconda Prompt. Make sure you're inside watsonaix-1 env and then cd it to the requirements.txt. location.</br>For example, my requirements.txt is located in <code>C:\Users\jackies\Downloads</code>. I will type this :</br><pre><code>cd C:\Users\jackies\Downloads</code></pre></li>
  <li>Run this command :<pre><code>conda install pip</code></pre><pre><code>pip install -r requirements.txt</code></pre></li>
</ol>
