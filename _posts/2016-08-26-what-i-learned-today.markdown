---
published: true
title: What I learned today
layout: post
---
You can create sort of responsive font sizes and avoid ```@media``` blocks by implementing one simple line of css.

```css
font-size: calc(1em + 1vw);
```

And there you have it, font size cross device. Probably not useful with strict design but great as a start.
