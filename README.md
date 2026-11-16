# CSS 3D Animation Lab

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-3d-animation-lab/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A standalone recreation of the 18-second screen recording titled **CSS 3D Animation**.

## Included demonstrations
1. 3D Rotating Cube
2. 3D Flip Card (tap/click to flip)
3. 3D Depth Text
4. 3D Tilt Effect (pointer tracking)
5. 3D Carousel

Each tab updates the preview and displays the relevant CSS snippet. This project uses vanilla HTML, CSS and JavaScript; no package installation or build step is needed.

## Run
Open `index.html` directly, or run:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000.

## What was readable in the recording
- Heading: `CSS 3D Animation`
- Cube snippet: `.cube { transform-style: preserve-3d; animation: spin 5s infinite linear; }`
- Flip snippet: `.card:active .inner { transform: rotateY(180deg); }` (the screen shows the active/inner selector and 180-degree Y rotation)
- Depth text keyframe: `@keyframes pop { transform: translateZ(40px); }`
- Tilt snippet: `.tilt:active { transform: rotateX(20deg) rotateY(20deg); }`
- Carousel snippet: `.carousel { animation: rotate 8s linear infinite; }`

The screen recording is a visual presentation of snippets, not a full source repository. The project reproduces the demonstrated effects and UI; unreadable or unshown original declarations are implemented as a functional reconstruction rather than claimed as exact original source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
