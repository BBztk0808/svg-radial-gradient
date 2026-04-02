# svg-radial-gradient
HTML created by imitating triangles and rays on the [Vercel homepage](https://vercel.com/), with custom rainbow gradients, tapered beams, and opacity fading.

##  Parameter Explanation

| Parameter | Value | Description |
|-----------|-------|-------------|
| `WIDTH` | 1350 | Canvas width (pixels) |
| `HEIGHT` | 800 | Canvas height (pixels) |
| `TOTAL_RAINBOW_RAYS` | 700 | Total number of rainbow-colored rays |
| `RAY_THICKNESS` | 0.5 | Ray thickness at the starting point (pixels) |
| `RAY_OPACITY` | 0.58 | Overall ray transparency (0 = fully transparent, 1 = fully opaque) |
| `RAY_FADE_LENGTH` | 0.82 | Position where fading begins (82% of the ray length) |
| `TRIANGLE_SCALE` | 0.30 | Triangle size relative to the canvas |
| `WHITE_RAYS_COUNT` | 46 | Number of white rays inside the triangle |
| `WHITE_RAY_THICK` | 1.0 | White ray thickness (pixels) |
| `FADE_START_INDEX` | 0 | Index where white rays start fading (starting from the first ray) |

> `FADE_START_INDEX = WHITE_RAYS_COUNT - 46 = 46 - 46 = 0`, meaning white rays begin fading from the very first ray.


I found that the rays on the Vercel homepage are much more natural than my version, but I don't know why.
