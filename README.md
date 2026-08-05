# pixel-pipeline-show-lab
pixel-pipeline-show-lab,show sub function change for pixel.

## Demos

| File | Description |
|------|-------------|
| `msaa_demo.html` | **MSAA Comparison** — A large diagonal edge covering 80% of the screen. Side-by-side 1× vs 8× comparison with an 8× zoomed inset showing how sub-pixel coverage eliminates jaggies. |
| `gamma_demo.html` | **Gamma Correction** — A dark dungeon scene with brick textures, floor cracks, and a green EXIT sign. Drag the gamma slider to see how γ=2.2 recovers detail that is completely crushed to black at γ=1.0. |
| `swizzle_demo.html` | **Channel Swizzle** — A four-quadrant RGBA test pattern. Apply presets (BGR, Grayscale, Alpha Mask, Normal Map) or manually remap R/G/B/A to see how channel reordering works. |
| `format_convert_demo.html` | **Precision & Banding** — A full hue rainbow gradient. Quantize to U8/U6/U5/U4 and watch the automatic edge-detection highlight every banding boundary in white. Real-time stats show unique color count. |
| `dither_demo.html` | **Dithering** — A night sky with stars. Compare no-dither (clear contour bands) vs Bayer ordered dither vs blue-noise dither. Adjustable target bit-depth from 2-bit to 6-bit. |
| `blend_demo.html` | **Blend Modes** — An RPG battle scene (grass, knight, orc). Overlay a magic shield / explosion fire / tree shadow / screen flash / damage vignette. Switch between Normal, Add, Multiply, Screen, and Overlay blend modes. |
| `logic_ops_demo.html` | **Logic Ops (Bitwise)** — A character silhouette (stencil) and a moving light cone (mask). Toggle AND / OR / XOR / NOT to see how stencil-buffer operations control per-pixel visibility. |
| `memory_layout_demo.html` | **Memory Layout** — A 16×16 grid showing Linear vs Twiddle (Z-Order / Morton code) address mapping. Heat-map colors show access order; animation traces the traversal path to visualize cache locality. |
| `lod_dither_blend_demo.html` | This demo compares LOD transition strategies: hard cut, Bayer dither (with and without TAA), and linear blend. It illustrates how TAA's temporal filtering effectively integrates dithering noise into a continuous gradient, approximating blend quality with single‑LOD shading cost. |


