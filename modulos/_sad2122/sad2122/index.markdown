---
title: "Seguridad y Alta Disponibilidad"
layout: default
---

Para obtener una shell completamente interactiva (Full interactive TTY) tendremos que hacer lo siguiente:

```bash
script /dev/null -c bash
# Ctrl + Z
stty raw -echo; fg
	reset
# Tipo de terminal:
xterm
export TERM=xterm
export SHELL=bash
```
