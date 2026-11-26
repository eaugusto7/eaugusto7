<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:0D1117,50:2E1065,100:7F1D1D&text=Eduardo%20Augusto&fontColor=F5F5F5&fontSize=64&fontAlignY=38&desc=Navega%C3%A7%C3%A3o%20INS%2FGNSS%20%E2%80%A2%20Sistemas%20Embarcados%20%E2%80%A2%20Full%20Stack&descAlignY=58&descSize=18&animation=fadeIn&stroke=E11D48&strokeWidth=1" width="100%" />
</p>

<p align="center">
  <a href="https://www.youtube.com/@EAugusto">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=E11D48&center=true&vCenter=true&multiline=false&repeat=true&width=720&height=50&lines=Doutorando+em+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+%40+UFLA;Analista+de+TI+%40+IFSP;Fus%C3%A3o+INS%2FGNSS+%C2%B7+RTK+%C2%B7+PPP-RT+%C2%B7+EKF;Factor+Graphs+em+hardware+low-cost;C%2B%2B+em+tempo+real+no+Raspberry+Pi;Go+%2B+Angular+%2B+MongoDB+%2B+MQTT;Criando+a+Sombra+OS+%F0%9F%90%A7;Gamedev+com+Unity+%2B+Blender+%F0%9F%8E%AE;GTA+VI+ao+vivo+no+YouTube+%F0%9F%94%B4" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.youtube.com/@EAugusto"><img src="https://img.shields.io/badge/YouTube-EAugusto-E11D48?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0D1117" /></a>
  <a href="https://github.com/eaugusto7?tab=followers"><img src="https://img.shields.io/github/followers/eaugusto7?style=for-the-badge&label=Seguidores&logo=github&color=9F1239&labelColor=0D1117" /></a>
  <img src="https://komarev.com/ghpvc/?username=eaugusto7&label=Visitas&color=4C1D95&style=for-the-badge" />
</p>

<br>

<table align="center">
<tr>
<td width="58%" valign="top">

```go
package main

type Desenvolvedor struct {
	Nome       string
	Cargo      string
	Formacao   []string
	Pesquisa   []string
	Linguagens []string
	Hobbies    []string
}

func main() {
	eduardo := Desenvolvedor{
		Nome:  "Eduardo Augusto",
		Cargo: "Analista de TI @ IFSP",
		Formacao: []string{
			"Doutorado em Ciência da Computação @ UFLA",
			"Mestre em Eng. de Sistemas e Automação @ UFLA",
			"Engenheiro de Computação",
		},
		Pesquisa: []string{
			"RT-PPP/INS tightly coupled",
			"EKF 17 estados", "Fixed-lag Factor Graphs",
			"RTK centimétrico em embarcados low-cost",
		},
		Linguagens: []string{"C++", "Python", "Go", "TypeScript", "MATLAB"},
		Hobbies:    []string{"Retro games", "Gamedev", "Lives de GTA VI"},
	}
	_ = eduardo
}
```

</td>
<td width="42%" valign="top">

### 🛰️ Agora
- 📡 Fusão **INS + GNSS** com EKF e **Factor Graphs** rodando em **Raspberry Pi 4**
- 🗺️ **Monitor GNSS** (Go/Gin + Angular 17 + MongoDB + MQTT)
- 🐧 **Sombra OS**, minha distro Linux baseada em Debian
- 🦇 **Réquiem Carmesim**, um survivors gótico para a Steam

### 🏆 Destaques
- 📄 2 publicações **IEEE** (uma no **ITSC 2024**)
- 💾 Software de navegação RT-PPP/INS com **registro no INPI**
- 🎙️ Lives e retro games no YouTube

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:E11D48,100:0D1117" width="100%" />

<h2 align="center">⚙️ Arsenal</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,python,go,ts,angular,flask,django&theme=dark&perline=8" /><br>
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,docker,linux,debian,ubuntu,raspberrypi,cmake&theme=dark&perline=8" /><br>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,matlab,unity,blender,bash&theme=dark&perline=8" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7C3AED,100:0D1117" width="100%" />

<h2 align="center">🚀 Projetos em destaque</h2>

<table align="center">
<tr>
<td width="50%" valign="top">

#### 🛰️ INS-RT-PPP-GNSS
Navegação RT-PPP/INS fortemente acoplada em C++ no Raspberry Pi 4. Quatro estimadores em paralelo (WLS, EKF, LC, TC), dashboard Flask com mapa Leaflet e streaming SSE, API REST com Swagger.

<sub>`C++` `Eigen` `Python` `Flask` `ARM64`</sub>

</td>
<td width="50%" valign="top">

#### 📡 Monitor GNSS
Monitoramento de receptores e bases GNSS low-cost em parceria VALE/UFLA. Coletores Python via MQTT, backend Go/Gin, frontend Angular 17 e coleta por celulares Android.

<sub>`Go` `Gin` `Angular` `MongoDB` `MQTT`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🌐 Cliente NTRIP RBMC
Cliente NTRIP em Python com interface web, inspirado no BNC, para receber e gravar correções da RBMC-IP do IBGE.

<sub>`Python` `NTRIP` `RTCM` `GNSS`</sub>

</td>
<td width="50%" valign="top">

#### 🐧 Sombra OS
Distro Linux leve baseada em Debian, com GNOME personalizado, tema dark sci-fi e ambiente de desenvolvimento pronto para C, C++, Go, Java, Node e Angular.

<sub>`Debian` `live-build` `GNOME` `Docker`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💳 Totem de Pagamentos
Totem de autoatendimento com PIX e cartões, frontend Angular e backend Go.

<sub>`Angular` `Go` `MongoDB` `CI/CD`</sub>

</td>
<td width="50%" valign="top">

#### 🦇 Réquiem Carmesim
Roguelite survivors gótico com sprites renderizados no Blender, visão isométrica e três heróis jogáveis.

<sub>`Unity` `C#` `Blender`</sub>

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:E11D48,100:0D1117" width="100%" />

<h2 align="center">📊 No GitHub</h2>

<p align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%" />
</p>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=eaugusto7&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=E11D48&icon_color=A855F7&text_color=C9D1D9&ring_color=E11D48&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=eaugusto7&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=E11D48&text_color=C9D1D9" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=eaugusto7&hide_border=true&background=0D1117&ring=E11D48&fire=F43F5E&currStreakLabel=E11D48&sideNums=C9D1D9&sideLabels=A855F7&dates=6B7280&stroke=2E1065&locale=pt_BR" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=eaugusto7&bg_color=0D1117&color=C9D1D9&line=E11D48&point=A855F7&area=true&area_color=7F1D1D&hide_border=true&custom_title=Contribui%C3%A7%C3%B5es%20nos%20%C3%BAltimos%2031%20dias" width="100%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=eaugusto7&theme=darkhub&no-bg=true&no-frame=true&margin-w=6&row=1&column=7" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7C3AED,100:0D1117" width="100%" />

<h2 align="center">🔴 Últimos vídeos no YouTube</h2>

<p align="center">
<!-- YOUTUBE:START --><a href="https://www.youtube.com/shorts/9zM-UABwxlI"><img width="24%" src="https://i.ytimg.com/vi/9zM-UABwxlI/mqdefault.jpg" alt="GTA 6 VIROU THE SIMS?! 🏠 #shorts" title="GTA 6 VIROU THE SIMS?! 🏠 #shorts" /></a><a href="https://www.youtube.com/watch?v=DI-e5yK8-tE"><img width="24%" src="https://i.ytimg.com/vi/DI-e5yK8-tE/mqdefault.jpg" alt="GTA 6 AO VIVO - UM NOVO RECOMEÇO - PARTE 4" title="GTA 6 AO VIVO - UM NOVO RECOMEÇO - PARTE 4" /></a><a href="https://www.youtube.com/shorts/6ke-vjymUFc"><img width="24%" src="https://i.ytimg.com/vi/6ke-vjymUFc/mqdefault.jpg" alt="O MAPA DO GTA 6 É GIGANTE! 🗺️ #shorts" title="O MAPA DO GTA 6 É GIGANTE! 🗺️ #shorts" /></a><a href="https://www.youtube.com/shorts/OMNGYFIRElo"><img width="24%" src="https://i.ytimg.com/vi/OMNGYFIRElo/mqdefault.jpg" alt="MORRI NO TUTORIAL DO GTA 6 💀 #shorts" title="MORRI NO TUTORIAL DO GTA 6 💀 #shorts" /></a><!-- YOUTUBE:END -->
</p>

<p align="center">
  <a href="https://www.youtube.com/@EAugusto"><img src="https://img.shields.io/badge/Ver%20canal%20completo-E11D48?style=for-the-badge&logo=youtube&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:E11D48,100:0D1117" width="100%" />

<h2 align="center">🐍 A cobra comendo minhas contribuições</h2>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/eaugusto7/eaugusto7/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/eaugusto7/eaugusto7/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/eaugusto7/eaugusto7/output/github-snake-dark.svg" width="100%" />
  </picture>
</p>

<h3 align="center">💬 Bora conversar sobre</h3>

<p align="center">
  <img src="https://img.shields.io/badge/INS%2FGNSS-0D1117?style=flat-square&logo=satellite&logoColor=E11D48" />
  <img src="https://img.shields.io/badge/RTK%20%7C%20PPP--RT-0D1117?style=flat-square&logo=googlemaps&logoColor=A855F7" />
  <img src="https://img.shields.io/badge/EKF%20%7C%20Factor%20Graphs-0D1117?style=flat-square&logo=wolframmathematica&logoColor=E11D48" />
  <img src="https://img.shields.io/badge/Go%20%2B%20Angular-0D1117?style=flat-square&logo=go&logoColor=A855F7" />
  <img src="https://img.shields.io/badge/Embarcados-0D1117?style=flat-square&logo=raspberrypi&logoColor=E11D48" />
  <img src="https://img.shields.io/badge/Gamedev-0D1117?style=flat-square&logo=unity&logoColor=A855F7" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:7F1D1D,50:2E1065,100:0D1117&animation=twinkling" width="100%" />
</p>
