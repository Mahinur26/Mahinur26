<!--
  INTERACTIVE TERMINAL README — neofetch style
  · The terminal card is assets/terminal.svg — a hand-authored SVG. The art
    inside it is the original braille bitmap (236x248 dots) emitted as vector
    rectangles, so nothing depends on the reader having a braille font.
  · Do NOT switch the panels below to ```ansi blocks: GitHub does not render
    ANSI escapes in markdown, they show up as literal [38;5;209m text.
  · The command chips are SVGs because GitHub offers no way to enlarge
    <summary> text (styles are stripped; a heading's 24px margin drops the
    disclosure triangle onto its own line). align="middle" centres the triangle
    on the chip, and the href-less <a name> wrapper stops GitHub auto-linking
    the image — an auto-linked chip opens the SVG instead of expanding.
  · Every "$ command" below is a <details> block: it expands inline, no JS.
    Those panels are ```yaml, so GitHub colours keys/values/comments for free
    and follows the reader's light or dark theme.
-->

<p align="center">
  <img src="assets/terminal.svg" width="846"
       alt="Terminal window titled Mahinur26 — -zsh — 120x30. Frieren line art on the left; on the right: Name Mahinur Mahi, Major Computer Science, Year Sophomore, Interests Full-Stack, AI/ML, Hardware and Databases.">
</p>

<samp>

<details>
<summary><a name="cmd-help"><img align="middle" src="assets/cmd-help.svg" height="28" alt="$ help"></a> &nbsp;<sub>start here</sub></summary>

<br>

```yaml
available commands:
  whoami        : who I am, in four lines
  ls ~/projects : things I have built
  cat stack.txt : languages, frameworks, tools
  contact --all : where to find me

# click any command to expand it · click again to collapse
```

</details>

<details>
<summary><a name="cmd-whoami"><img align="middle" src="assets/cmd-whoami.svg" height="28" alt="$ whoami"></a></summary>

<br>

```yaml
Mahinur Mahi:
  school   : University of South Florida — CS, sophomore
  building : full-stack apps, and learning Spring Boot
  learning : ML in Python, plus hardware that talks to the web
  off-clock: sensors, solenoids, and small tools that get used
```

</details>

<details>
<summary><a name="cmd-projects"><img align="middle" src="assets/cmd-projects.svg" height="28" alt="$ ls ~/projects"></a></summary>

<br>

| project | what it does | stack | |
|---|---|---|---|
| **[Brailliant](https://github.com/Mahinur26/Brailliant)** | camera or PDF in, braille dots out | `FastAPI` `ESP32` | [repo](https://github.com/Mahinur26/Brailliant) · [demo](https://www.youtube.com/watch?v=eGkaFCZrKGw) |
| **[PathSense](https://github.com/Mahinur26/PathSense)** | LiDAR cane that steers by haptics | `SwiftUI` `ARKit` | [repo](https://github.com/Mahinur26/PathSense) |
| **[Library Tracker](https://github.com/Mahinur26/USF-Library-Tracker)** | live floor counts from IR sensors | `Next.js` `Firebase` | [repo](https://github.com/Mahinur26/USF-Library-Tracker) |
| **[Food Pantry](https://github.com/Mahinur26/Food-Pantry)** | scans groceries, tracks expiry dates | `React` `YOLO` | [repo](https://github.com/Mahinur26/Food-Pantry) · [live](https://food-pantry-eight.vercel.app) |

<details>
<summary><a name="cmd-cat"><img align="middle" src="assets/cmd-cat.svg" height="24" alt="$ cat ~/projects/brailliant/README.md"></a></summary>

<br>

```yaml
Brailliant:
  problem : braille hardware is expensive and rarely within reach
  approach: camera, screenshot, or PDF → text → UEB grade-1 dots →
            six solenoids driven over serial by an ESP32
  result  : one physical cell you step through letter by letter, and
            the whole pipeline still runs with no hardware attached
```

</details>

</details>

<details>
<summary><a name="cmd-stack"><img align="middle" src="assets/cmd-stack.svg" height="28" alt="$ cat stack.txt"></a></summary>

<br>

![Python](https://img.shields.io/badge/Python-02557A?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-02557A?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-02557A?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-02557A?style=flat-square&logo=javascript&logoColor=white)
![C++](https://img.shields.io/badge/C++-02557A?style=flat-square&logo=cplusplus&logoColor=white)

![React](https://img.shields.io/badge/React-0D81C8?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-0D81C8?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-0D81C8?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0D81C8?style=flat-square&logo=fastapi&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0D81C8?style=flat-square&logo=tensorflow&logoColor=white)

![Firebase](https://img.shields.io/badge/Firebase-EE6B23?style=flat-square&logo=firebase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-EE6B23?style=flat-square&logo=vercel&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-EE6B23?style=flat-square&logo=arduino&logoColor=white)
![Git](https://img.shields.io/badge/Git-EE6B23?style=flat-square&logo=git&logoColor=white)

</details>

<details>
<summary><a name="cmd-contact"><img align="middle" src="assets/cmd-contact.svg" height="28" alt="$ contact --all"></a></summary>

<br>

<pre>
contact:
  github  : <a href="https://github.com/Mahinur26">github.com/Mahinur26</a>
  email   : mahinurmahi26@gmail.com
  linkedin: <a href="https://www.linkedin.com/in/mahinur-mahi">linkedin.com/in/mahinur-mahi</a>
  status  : open to internships and side projects
</pre>

</details>

</samp>
