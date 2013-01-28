impressive-bootstrap
====================

[Impress.js](https://github.com/bartaz/impress.js) with Bootstrap hanging on…for making impressive html presentations with Bootstrap flavor added in.

I'm using [Bower](https://github.com/twitter/bower) for package management so you may need to install it.
<a name="installing-bower" class="anchor" href="#installing-bower"><span class="mini-icon mini-icon-link"></span></a>
<p>Bower is installed using <a href="http://nodejs.org/">Node</a> and <a href="http://npmjs.org/">npm</a> (oh my, how meta).</p>
<pre><code>npm install bower -g</code></pre>
Install the Libraries
<pre><code>bower install twitter/bootstrap</code></pre>
<pre><code>bower install bartaz/impress.js/</code></pre>
<pre><code>bower install cloudhead/less.js/</code></pre>
Move to Bootstrap and Make
<pre><code>$ cd components/bootstrap && make</code></pre>
Copy over the libraries
<pre><code>cp -r ../bootstrap/js ../../ && cp -r components/less.js/dist/less-1.3.3.min.js js/ && cp -r components/jquery/jquery.min.js js/ && cp -r components/impress.js/js/impress.js js/</pre></code>
