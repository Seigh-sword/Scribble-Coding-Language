# 🖋️ Scribble Coding Language

Welcome to **Scribble** — a powerful, playful, and tag-based coding language for the browser.  
Inspired by Scratch, HTML, CSS, and JavaScript, **Scribble** lets you build interactive pages with simple, beautiful syntax.  
Whether you're creating glowing buttons, floating text, or rainbow-tweens, **Scribble makes coding fun** 🦆✨

---

## 🔥 Features

✅ Clean, tag-style syntax (no closing tags needed!)  
✅ Built-in animation with tween support  
✅ Works directly in the browser (no install!)  
✅ Combo logic like JavaScript and visual styling like CSS  
✅ Supports variables, math, loops, and effects  
✅ Fully customizable elements (size, font, color, glow, etc.)

---

## ✨ Example Code

```scribble
<start>

{text="Hello Scribble!";
[type="heading=1"]
[font="comic sans"]
[colour="blue"]
[size="32px"]
[align="center"]}

{tween="";
[scale(1.5)]
[glow(4)]
[colorShift(0-255)]
[float(20)]
<loop>}
<end>
```

## 📜 Syntax Overview

| Element   | Format |
|-----------|--------|
| **Text**      | `{text="Hello"; [type="heading=1"]}` |
| **Button**    | `{button="Click me!"; [colour="red"]}` |
| **Variable**  | `{var="score"; [key="$score$"]}` |
| **Tween**     | `{tween=""; [scale(2)] [glow(5)] [fade(in)]}` |
| **Loop**      | `<loop>` *(repeats tween forever)* |

## 🎨 Supported Tweens

- `[scale(n)]` → Grows/shrinks the element  
- `[glow(n)]` → Adds glowing effect with `n` intensity  
- `[pos(x-y)]` → Moves element from `x` to `y` position  
- `[rotate(deg)]` → Rotates the element by degrees  
- `[fade(in/out)]` → Fades the element in or out  
- `[float(px)]` → Element floats up/down in a loop  
- `[delay(ms)]` → Delays the start of the animation in milliseconds  
- `[colorShift(min-max)]` → Shifts color between RGB values from `min` to `max`  
  *(Max is 255 — RGB standard!)*  
- `<loop>` → Used after tween to repeat animation forever


