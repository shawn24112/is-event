
# 🎨 **Patternforge**

> pattern generator for wallpapers, backgrounds, and design systems.

---

### Quickstart

```bash
npx patternforge create
```

choose from presets:

* geometric
* waves
* nebula
* lowpoly

### Example API

```js
import { generate } from "patternforge"

const canvas = document.querySelector("canvas")
generate(canvas, { mode: "waves", color: "#43e9d2" })
```

### Export formats

* PNG, SVG, WebGL snapshot

### Inspiration

Merging shader art with print design — minimal code, maximum impact.

MIT © [patternforge.studio](https://patternforge.studio)
