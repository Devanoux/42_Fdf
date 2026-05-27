# FDF

**Wireframe 3D landscape renderer — projects a heightmap file into an isometric 3D view using MiniLibX.**

![42](https://img.shields.io/badge/-42-black?style=for-the-badge&logo=42&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

---

##  FEATURES

| | Description |
|---|---|
| Z scaling | Increase or decrease elevation of the terrain |
| Colors | Custom color rendering per height level |
| Rotation | Rotate the model on all axes |
| Translation | Move the view across the screen |
| Zoom | Zoom in and out of the projection |

---

## OVERVIEW

**Mandatory — basic isometric projection**

![Mandatory](https://github.com/user-attachments/assets/abed95ad-e03b-4907-831e-b8e926c40d0a)

**Bonus — extended rendering**

![Bonus](https://github.com/user-attachments/assets/77d92ef3-907a-41f5-9416-bf38ea20f974)

---

## PREREQUISITES

For installing this project u must have MiniLibX for Linux who requires xorg, x11 and zlib, therefore you will need to install the following dependencies: xorg, libxext-dev and zlib1g-dev. Installing these dependencies on Ubuntu can be done as follows:

```bash
sudo apt-get update && sudo apt-get install xorg libxext-dev zlib1g-dev libbsd-dev
```

##  INSTALLATION

**1. Clone the repository**
```bash
git clone https://github.com/Ernst-Devan/Fdf.git Dernst_fdf
cd Dernst_fdf
```

**2. Compile**
```bash
make
```

**Bonus part**
```bash
make bonus
```

**3. Run**
```bash
./fdf <map_path>
```

---

##  CONTROLS

| Key | Action |
|---|---|
| `↑` `↓` `←` `→` `a` `e`| Rotate |
| `+` `-` | Zoom in / out |
| `z` `q` `s` `d` | Translate |
| `o` `l` | Increase / decrease Z scale |
| `ESC` | Quit |

---

##  REFERENCES

- [Bresenham's Line Algorithm](https://www.youtube.com/watch?v=RGB-wlatStc&ab_channel=AbdulBari)
- [Slope Line](https://personal.math.ubc.ca/~cass/courses/m308-02b/projects/puhalovic/index.html#Introduction)
- [Isometric Projection](https://en.wikipedia.org/wiki/Isometric_projection)

---

## CREDITS

- [Ernst-Devan](https://github.com/Ernst-Devan)

---

*42 school project.*
