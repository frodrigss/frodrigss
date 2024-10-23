# Felipe S. Rodrigues 👨‍💻

[![Profile Views](https://komarev.com/ghpvc/?username=frodrigss&color=blueviolet)](https://github.com/frodrigss)
[![iCloud](https://img.shields.io/badge/iCloud-3693F3?style=flat&logo=iCloud&logoColor=white)](mailto:soaresrodriguesf07@icloud.com)

## 🚀 About Me

Passionate front-end  web and digital game programming student, constantly exploring the realms of technology and creativity. Currently honing my skills in JavaScript, TypeScript, HTML, and CSS while pursuing my studies at **Etec of Peruíbe**.

### 🎓 Education

- **Etec of Peruíbe**
  - High School with Professional Qualification as a Digital Game Programming Technician

## 💻 Technical Skills

```javascript
const skills = {
  languages: ['JavaScript', 'TypeScript' , 'HTML', 'CSS'],
  frameworks: ['Tailwind CSS'],
  tools: ['Git', 'VS Code', 'Cursor', 'Unity'],
  interests: ['Web Development', 'Game Development']
};
```

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" height="40" alt="unity logo"  />
</div>


## 🌱 Current Focus

- Advancing my knowledge in front-end technologies
- Exploring the intricacies of game development
- Seeking collaborators for small web projects

## 📊 GitHub Stats

<img align="center" src="https://github-readme-stats.vercel.app/api?username=frodrigss&show_icons=true&line_height=27&count_private=true&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" alt="Felipe's GitHub Stats" />

## 📫 Let's Connect!

I'm always open to interesting conversations and collaboration opportunities. Feel free to reach out!

- 📧 Email: [soaresrodriguesf07@icloud.com](mailto:soaresrodriguesf07@icloud.com)

---

<p align="center">💼 Open to internships and junior developer positions 💼</p>
  
<html lang="pt-br">
  <style>
	  * {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

html,
body {
	display: flex;
	align-items: center;
	justify-content: center;
	background-color: #101c36;
	height: 100%;
	user-select: none;
}

@font-face {
	font-family: "fonte";
	src: url(fonte.ttf);
}

@font-face {
	font-family: "comic";
	src: url(ComicNeue-Regular.ttf);
}

.container {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: space-between;
	background-color: #232222;
	border-radius: 2.5vh;
	box-shadow: 0 0.8vh 2.5vh rgba(0, 0, 0, 0.5);
	font-family: "fonte";
	height: 80vh;
	padding: 3vh;
	position: relative;
	width: 160vh;
}

/* .area {
  width: 100%;
  height: 90%;
  background-color: #3 3 3;
  border-radius: 1.8vh;
  position: relative;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
} */

.area {
	display: flex;
	align-items: center;
	justify-content: center;
	background-color: rgb(40, 40, 40);
	border-radius: 1.8vh;
	box-shadow: 0 0.6vh 1.3vh rgba(0, 0, 0, 0.4);
	color: #ecf0f1;
	font-family: "fonte";
	font-size: 1.6vw;
	height: 100%;
	width: 100%;
	margin-bottom: 2.8vh;
	overflow: hidden;
	position: relative;
}

#coringa {
	position: absolute;
	top: 50%;
	color: #e74c3c;
	font-size: 5vh;
	font-weight: bold;
	visibility: hidden;
}

.brilhando {
	box-shadow: 0 0 1.5vh rgba(255, 254, 254, 0.516);
}

#game-info {
	position: absolute;
	top: 1vh;
	left: 1vh;
	color: white;
	font-size: 1.8vh;
}

#mensagem-final {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	display: grid;
	text-align: center;
	font-size: 2vh;
	color: white;
	visibility: hidden;
}

.booster-info,
.estatisticas {
	font-size: 1.6vh;
	text-align: left;
}

#fim {
	font-size: 3vh;
}

.bola {
	position: absolute;
	background-color: red;
	border-radius: 50%;
	width: 8vh;
	height: 8vh;
	cursor: pointer;
	display: none;
	transition: top 0.45s ease, left 0.45s ease, width 0.45s ease, height 0.45s ease, box-shadow 0.25s ease;
}

#ranking {
	position: absolute;
	top: 1vh;
	right: 1vh;
	background-color: rgba(38, 31, 31, 0.645);
	border-radius: 0.8vh;
	color: white;
	font-family: "fonte";
	font-size: 1.4vh;
	padding: 1vh;
	margin-bottom: 2vh;
	visibility: hidden;
}

#ranking-list {
	font-size: 1.4vh;
	list-style-position: inside;
	margin: 0;
	padding: 0;
}

#barra-progresso-container {
	display: flex;
	justify-content: center;
	width: 30%;
	margin-top: 1.8vh;
}

#barra-progresso {
	background-color: #757575;
	border-radius: 2vh;
	height: 2vh;
	width: 40%;
	overflow: hidden;
	visibility: hidden;
	transition: width 0.3s ease;
}

#barra-progresso-inner {
	background-color: #39773b;
	height: 100%;
	width: 0%;
	transition: width 0.3s ease;
}

.booster {
	position: absolute;
	background-color: red;
	width: 1.3vw;
	height: 1.3vw;
	cursor: pointer;
	display: none;
	box-shadow: 0 0 0.5vw rgba(255, 0, 0, 0.575);
}

.booster.blue {
	background-color: blue;
	box-shadow: 0 0 0.5vw rgba(22, 18, 255, 0.596);
}

.controls {
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between;
	width: 100%;
}

.info-container {
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: center;
	gap: 2vh;
}

#level,
#score {
	font-family: "comic", sans-serif;
	color: white;
	font-size: 2.5vh;
}

.button-container {
	display: flex;
	flex-direction: column;
	align-items: flex-start;
	justify-content: flex-start;
	gap: 2vh;
	width: auto;
}

.primary-buttons {
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: flex-start;
	gap: 2vh;
	width: 100%;
}

.game-button {
	background-color: #58b058;
	color: white;
	font-family: "comic", sans-serif;
	font-size: 1.8vh;
	text-transform: uppercase;
	padding: 1vh 2vh;
	border: 0.5vh solid rgba(0, 0, 0, 0.425);
	border-radius: 2.2vh;
	box-shadow: 0 0.4vh 0.8vh rgba(9, 9, 9, 0.85);
	cursor: pointer;
	transition: all 0.2s ease, filter 0.3s ease;
	max-width: 14vw;
	width: auto;
}

.game-button:hover {
	background: #3f8a3f;
	box-shadow: 0 1.1vh 1.3vh rgba(9, 9, 9, 0.735);
	transform: translateY(-0.7vh);
}

.game-button:active {
	box-shadow: 0 0.4vh 0.8vh rgba(9, 9, 9, 0.85);
	transform: translateY(0vh);
}

.game-button:disabled {
	cursor: not-allowed;
	filter: saturate(30%);
}

#home {
	background-color: #49784a;
}

#timer,
#texto-tempo,
#level,
#score {
	visibility: hidden;
}
</style>
 <body>
		<div class="container">
			<div class="area">
				<div id="ranking"></div>
				<div class="booster"></div>
				<div id="game-info">
					<p id="menssagem">Pop Pop Ball!</p>
					<span id="timer">80</span>
					<span id="texto-tempo">segundos restantes</span>
				</div>
				<div id="coringa">CORINGA</div>
				<div class="bola"></div>
				<div id="mensagem-final"></div>
			</div>
			<div class="controls">
				<div class="button-container">
					<div class="primary-buttons">
						<button id="play" class="game-button">Play</button>
						<button id="home" class="game-button" onclick="home()">Home</button>
					</div>
				</div>
				<div id="barra-progresso-container">
					<div id="barra-progresso">
						<div id="barra-progresso-inner"></div>
					</div>
				</div>
				<div class="info-container">
					<span id="level">Nível: 1</span>
					<span id="score">Pontos: 0</span>
				</div>
			</div>
		</div>
	</body>
	<script src="../scripts/script.js"></script>
	
</html>

