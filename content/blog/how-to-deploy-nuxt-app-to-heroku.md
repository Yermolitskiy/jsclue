---
title: How to deploy Nuxt App to heroku
description: Some commands that had to be done by me, when I've deployed a Nuxt App to Heroku
slug: how-to-deploy-nuxt-app-to-heroku
img: https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flogos-download.com%2Fwp-content%2Fuploads%2F2016%2F09%2FHeroku_logo.png&f=1&nofb=1
---

# How to deploy Nuxt App to heroku

This website is the actual example of howt the <a href="https://heroku.com/">Heroku</a> works together with <a href="https://nuxtjs.org/">Nuxt</a>
<br>
<p>
    <ol>
        <li>create a git repository*</li>
        <li>install Heroku*</li>
        <li>create a Heroku App:
            <div>
                <p>
                    <ul>
                        <li><code>heroku create your-app-name</code></li>
                        <h5>Also run this two commands in order to preset Heroku for our Nuxt project:</h5>
                        <li><code>heroku buildpacks:set heroku/nodejs</code></li>
                        <li><code>heroku config:set HOST=0.0.0.0</code></li>
                    </ul>            
                </p>
            </div>
        </li>
        <li>add this lines to your package.json file:<br/>
<code>
<pre>
"scripts": {
    "dev": "nuxt",
    "build": "nuxt build",
    "generate": "nuxt generate",
    "start": "nuxt start"
},
</pre>
</code>
        </li>
        <li>change .gitignore</li>
        <li>add Procfile</li>
        <li>In your Nuxt app folder run: <br/>
            <code>npm run build</code> <br/>
            <code>npm run generate</code>
        </li>        
        <li>Run command:<br/>
            <code>git push heroku master</code>
        </li>
    </ol>
</p>