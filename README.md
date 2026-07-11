chris-torres-dev.github.io

My personal portfolio — live at chris-torres-dev.github.io

What it is

A single-file portfolio site. No framework, no build step, no dependencies to install — everything (HTML, CSS, JS, and even the profile photo as base64) lives in index.html.

Features


🌗 Dark / light theme with an animated pixel-sweep transition
🎨 Animated gradient accents, scroll-reveal sections, scroll progress bar
🖥️ Auto-scrolling tech chips under each role
📱 Responsive layout with a mobile-specific card treatment for experience
📬 Contact form that delivers straight to my inbox (Web3Forms)
🐈‍⬛ A resident black cat (white in dark mode)


Structure

index.html                        → the entire site
Christopher_Torres_Resume.pdf     → linked from the Resume button
profile.jpg                       → standalone copy of the photo (also embedded in the HTML)

Deploying changes

Edit index.html, then:

bashgit add -A
git commit -m "update site"
git push

GitHub Pages rebuilds automatically in about a minute.

Stack

Vanilla HTML/CSS/JS · Google Fonts (Sora, Inter, JetBrains Mono) · Web3Forms · GitHub Pages


Built by Christopher Torres · NYC
