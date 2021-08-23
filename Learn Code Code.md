<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Learn Code Code</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#learn-code-code">Learn Code Code</a>
<ul>
<li><a href="#system">System</a></li>
<li><a href="#git--github">Git & GitHub</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <h1 id="learn-code-code">Learn Code Code</h1>
<blockquote>
<p>David Ramsay</p>
</blockquote>
<h2 id="system">System</h2>
<p><a href="https://zorin.com/os/">Zorin OS</a></p>
<h2 id="git--github">Git &amp; GitHub</h2>
<h3 id="install-git">Install Git</h3>
<ol>
<li>
<p>Install</p>
<pre class=" language-bash"><code class="prism  language-bash">apt <span class="token function">install</span> <span class="token function">git</span>
</code></pre>
</li>
<li>
<p>Setting your Git username for <em>every</em> repository on your computer</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> config --global user.name <span class="token string">"davidjpramsay"</span>
</code></pre>
</li>
<li>
<p>Setting your commit email address in Git</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> config --global user.email <span class="token string">"david.jp.ramsay@me.com"</span>
</code></pre>
</li>
</ol>
<h3 id="connect-to-github-with-ssh">Connect to GitHub with SSH</h3>
<ol>
<li>
<p>Generate a new SSH key</p>
<pre class=" language-bash"><code class="prism  language-bash">$ ssh-keygen -t ed25519 -C <span class="token string">"david.jp.ramsay@me.com"</span>
</code></pre>
</li>
<li>
<p>Start the ssh-agent in the background.</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">eval</span> <span class="token string">"<span class="token variable"><span class="token variable">$(</span>ssh-agent -s<span class="token variable">)</span></span>"</span>
</code></pre>
</li>
<li>
<p>Add your SSH private key to the ssh-agent</p>
<pre class=" language-bash"><code class="prism  language-bash">ssh-add ~/.ssh/id_ed25519
</code></pre>
</li>
<li>
<p>Add SSH to GitHub</p>
</li>
</ol>

    </div>
  </div>
</body>

</html>