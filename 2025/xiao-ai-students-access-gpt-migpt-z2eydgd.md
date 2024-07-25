<h1>小爱同学接入GPT(mi-gpt)</h1>
<pre><code class="language-shell">docker pull idootop/mi-gpt:4.0.0

docker run -d --restart=always \
--env-file /volume1/docker/mi-gpt/.env \
-v /volume1/docker/mi-gpt/.migpt.js:/app/.migpt.js \
--name mi-gpt \
idootop/mi-gpt:4.0.0
</code></pre>
