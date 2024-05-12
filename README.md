# render-json-server

**itech-Vedio-Server**
Hello everyone in this video you will learn to deploy your db.json file on **render.com** step by step.

**Step 1** -   Create git repository

**Step 2** - Clone it on your device

**Step 3** - Add package.json by using this command `npm init -y`

**Step 4** - Install some dependency by using this command `npm i json-server cors json-serve` and add ` "start": "node index.js" ` in script 

**Step 6** - Create index.js file copy the code from my GitHub repository

```javaScript
const jsonServer = require("json-server"); // importing json-server library
const server = jsonServer.create();
const router = jsonServer.router("db.json");
const middlewares = jsonServer.defaults();
const port = process.env.PORT || 8080; //  chose port from here like 8080, 3001

server.use(middlewares);
server.use(router);

server.listen(port);

```

**Step 7** - Add db.json and add .gitignore file


After all this steps are completed use this command to push the code in your Github account.

`git add .`

`git commit -m "Your message"`

`git push origin main`


If you find this video helpful please subscribe to my channel and share this with your friends. If you have any queries ask in the comment section below I will be happy to answer you all.

<!-- - 🌱 I’m currently learning **Django , Python ,React etc.** -->
<table width="100%">
	<tr>
		<td width="60%">
👨‍💻 All of my projects are available at <a href="https://motalibhossain.github.io/portfolio/">Motalib Hossain</a>

💬 Ask me about **web technologies.**

📫 How to reach me **motalibhossainrbk33@gmail.com**

📄 Know about my experiences 👉 [Here..](https://motalibhossain.github.io/portfolio/)
<p>❤️ Programming | 🖤 Music | 💙 Traveling</p>
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/motalibhossain" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="motalibhossain" height="30" width="40" /></a>
<a href="https://twitter.com/motalibhossai13" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="motalibhossai13" height="30" width="40" /></a>
<a href="https://fb.com/https://www.facebook.com/s.motalibhossain/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="https://www.facebook.com/s.motalibhossain/" height="30" width="40" /></a>
</p>
		</td>
		<td width="40%"><img width="400px" src="https://github.com/MotalibHossain/MotalibHossain/blob/main/code.gif?raw=true" alt="motalibhossain" /></td>
	</tr>
</table>

