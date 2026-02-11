# The Last Race: Lewis Hamilton COYA

A small Choose Your Own Adventure** story made with only HTML pages and links.  
You guide Lewis Hamilton, an F1 driver, through the key decisions of his final race.

**Author:** Daniel Sandoval - 24885

---

## Overview

This project uses multiple HTML files. Every page includes:
- an image
- a short scene
- at least **two choices** using links

No CSS and no JavaScript were used.

---

## Technologies Used
- HTML
- NGINX
- Git and GitHub

---

## Getting Started

### How to open the story (local)
Open this file in your browser:
- `inicio/index.html`

---

## Link of the Video on YouTube
- https://youtu.be/JW-Mo2SuBUA

---

## Open in the browser (NGINX)
- `http://localhost:8080/adventure/inicio/index.html`

---

## Installation and Deployment (NGINX)

This is how I served it with NGINX on macOS (Homebrew):

```bash
PREFIX="$(brew --prefix)"
sudo rm -rf "$PREFIX/var/www/adventure"
sudo mkdir -p "$PREFIX/var/www/adventure"
sudo cp -R ~/Documents/laboratorio1-adventure/* "$PREFIX/var/www/adventure/"
sudo chmod -R 755 "$PREFIX/var/www/adventure"
