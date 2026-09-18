<h1 align="center">Procedural Climate Stone</h1>

<p align="center">
  <em>A stone that generates procedurally from a seed,<br>
  using 3D fractal Perlin noise.</em>
</p>

<p align="center">
  <img alt="seed" src="https://img.shields.io/badge/seed-driven-5b6d5b?style=flat-square">
  <img alt="noise" src="https://img.shields.io/badge/3D%20fractal-Perlin%20noise-6b7f8f?style=flat-square">
  <img alt="inputs" src="https://img.shields.io/badge/vertex%20colors-temperature%20%C2%B7%20humidity-8f7a5b?style=flat-square">
  <img alt="built with" src="https://img.shields.io/badge/Unreal%20Engine-C%2B%2B-4a4a55?style=flat-square">
</p>

<p align="center">
  <a href="procedural-climate-stone.mp4">
    <img src="preview.gif" width="720" alt="A procedurally generated stone turning in the viewport">
  </a>
</p>

<p align="center">
  <sub>▶ Full 53&nbsp;s capture: <a href="procedural-climate-stone.mp4"><b>procedural-climate-stone.mp4</b></a></sub>
</p>

---

### What it is

One seed in, one stone out. The silhouette and surface come from **3D fractal Perlin noise**
— octaves layered over the mesh so every seed yields a different, believable rock.
Built in **Unreal Engine**, generated in **C++**.

### Climate

The stone takes **temperature** and **humidity** as arguments, passed in as **vertex colors**.
They drive how the surface weathers: warm and dry reads as bare, bleached rock; cool and wet
grows moss, damp patches and darker crevices.

| Channel | Argument | Range |
| :-----: | :------- | :---- |
| **R** | temperature | `0.0` cold → `1.0` hot |
| **G** | humidity | `0.0` dry → `1.0` wet |

<p align="center"><sub>Made with Unreal Engine and C++ &nbsp;·&nbsp; one-video presentation repository.</sub></p>
