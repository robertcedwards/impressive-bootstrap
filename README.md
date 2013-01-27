impressive-bootstrap
====================

Impress.js with Bootstrap hanging on…for making impressive html presentations with Bootstrap flavor added in.

I'm using [Bower](https://github.com/twitter/bower) for package management so you may need to install it.

<a name="installing-bower" class="anchor" href="#installing-bower"><span class="mini-icon mini-icon-link"></span></a>Installing Bower</h3>
<p>Bower is installed using <a href="http://nodejs.org/">Node</a> and <a href="http://npmjs.org/">npm</a> (oh my, how meta).</p>

<pre><code>npm install bower -g</code></pre>

<pre><code>bower install twitter/bootstrap</code></pre>
<pre><code>bower install bartaz/impress.js/</code></pre>

<pre><code>$ cd components/bootstrap && make</code></pre>
cp -r ../bootstrap/js ../../
cp -r ../bootstrap/less ../../


<pre><code>$ rm -rf ../static/bootstrap</code></pre>
<pre><code>$ mv bootstrap/js ../js</code></pre>


<pre><code>cp -r components/impress.js/js/impress.js js/</pre></code>

Install Less.js
<pre><code>bower install cloudhead/less.js/</code></pre>
Copy it over
<pre><code>cp -r components/less.js/dist/less-1.3.3.min.js js/</pre></code>
Copy jquery over
<pre><code>cp -r components/jquery/jquery.min.js js/</pre></code>


