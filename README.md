<h1 align="center">👾 Discord Clone 👾 </h1>

<p align="center"><img src="--" alt="Screenshot"></p>

<p align="center">
  <img src="https://img.shields.io/github/license/M0nkeyroger/Space-InvadersJS" alt="License">
  <img src="https://img.shields.io/github/stars/M0nkeyroger/Space-InvadersJS" alt="Stars">
  <img src="https://img.shields.io/github/forks/M0nkeyroger/Space-InvadersJS" alt="Forks"> <br>
  <img alt="Next.js" src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="Socket.io" src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101">
  <img alt="TailwindCSS" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white">
</div>

</p>

<h2 align="center">👾 Description</h2>

<p align="center">Full-stack Discord clone built using a cutting-edge tech stack that includes Next.js 13, React, Socket.io, Prisma, Tailwind CSS, and MySQL. It aims to replicate the functionality and user experience of Discord, a popular communication platform, while incorporating real-time features, user management, server customization, and more.</p>

<h2 align="center">📋 Table of Contents</h2>

<p align="center">
  <a href="#demo">☁️ Demo</a> •
  <a href="#features">✨ Features</a> •
  <a href="#installation">🛠️ Prerequisites</a> •
  <a href="#how-to-play">🛢️ Setup Prisma</a> •
  <a href="#controls">▶️ Start the App</a> •
  <a href="#gameplay">✅ Available Commands</a> •
  <a href="#license">📄 License</a>
</p>

<h2 align="center">☁️ Demo</h2>

<p align="center">You can access the site here: <a href="https://team-chat-webapp-production.up.railway.app/">Team Chat App</a></p>

<h2 align="center">✨ Features</h2>

<p align="center">
  • Real-time messaging using Socket.io.<br>
  • Send attachments as messages using UploadThing.<br>
  • Delete & Edit messages in real time for all users.<br>
  • Create Text, Audio, and Video call Channels.<br>
  • 1:1 conversation between members.<br>
  • 1:1 video calls between members.<br>
  • Member management (Kick, Role change Guest / Moderator).<br>
  • Unique invite link generation & full working invite system.<br>
  • Infinite loading for messages in batches of 10 (tanstack/query).<br>
  • Server creation and customization.<br>
  • Fully responsive and mobile UI.<br>
  • Light / Dark mode.<br>
  • Websocket fallback: Polling with alerts.<br>
  • ORM using Prisma.<br>
  • MySQL database using Planetscale.<br>
  • Authentication with Clerk.<br>
  
</p>

<h2 align="center">🛠️Prerequisites🛠️</h2>
<p align="center">Node version 18.x.x</p>

<h2 align="center">Cloning the Repository📥</h2>
<pre><code>git clone https://github.com/M0nkeyroger/Team-Chat-Webapp.git</code></pre>

<h2 align="center">Install Packages📦</h2>
<pre><code>npm i</code></pre>

<h2 align="center">Setup .env File⚙️</h2>
<p align="center">Create a <code>.env</code> file in the project root and add the following environment variables:</p>
<pre><code>NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
</code></pre>

<h2 align="center">Setup Prisma🛢️</h2>
<ol>
  <li>Add a MySQL Database (Used PlanetScale).</li>
  <li>Generate Prisma client:</li>
</ol>
<pre><code>npx prisma generate</code></pre>
<ol start="3">
  <li>Push the database schema:</li>
</ol>
<pre><code>npx prisma db push</code></pre>

<h2 align="center">Start the App▶️</h2>
<pre><code>npm run dev</code></pre>

<h2 align="center">Available Commands✅</h2>
<p align="center">You can run the following commands using npm:</p>
<pre><code>npm run dev: Starts a development instance of the app</code></pre>

<h2 align="center">📄 License</h2>

<p align="center">This project is licensed under the MIT License. Feel free to explore, modify, and enjoy the Space Invaders adventure to the fullest! 🌠</p>
