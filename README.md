# Benchmark 2. 3D Modelling in VR

The Benchmark-2_3D_modelling_VR aims at benchmarking virtual environments for 3D modelling in virtual reality.

## Glossary

...

## Requirements





## Measures of performance

## Datasets

- [Robot arm]

## Comparison

| Category                |   Criteria            | [Mindesk](https://mindeskvr.com/) | SkyReal | [Gravity<br>Sketch](https://www.gravitysketch.com/) | Blender<br>OpenXR | Blender<br>VR | [Flying<br>Shapes](https://www.flyingshapes.com/) | [VR<br>Sketch](https://vrsketch.eu/) | [Bordot *et al*](https://dl.acm.org/doi/10.1016/j.cad.2008.10.014)    | [Martin *et al*](https://link.springer.com/chapter/10.1007/978-3-319-60922-5_17)    | [Feeman *et al*](https://www.tandfonline.com/doi/abs/10.1080/16864360.2018.1462570?journalCode=tcad20)    |
|-------------------------|---------------|---------|---------|-------------------|-------------------|---------------|------------------|--------------|--------|--------|--------|
| Dimensional constraints | Length        | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R]  |
|                         | Radius        | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R]  |
|                         | Distance      | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R]  |
|                         | Angle         | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R]  |
|                         | Total         | 0       | 0       | 0                 | 0                 | 0             | 0                | 0            | 0 [NA] | 0 [NA] | 4      |
| Geometrical constraints | Horizontal    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Vertical      | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Fix/UnFix     | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] |
|                         | End point     | 1 [T]   | 1 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Mid-Point     | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Perpendicular | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Concentric    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Coincident    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 1 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Tangent       | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Parallel      | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Symmetry      | 1 [T]   | 1 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Equidistant   | 0 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] |
|                         | Total         | 10      | 2 [NA]  | 1                 | 0                 | 0             | 2                | 9            | 0 [NA] |        | 0 [NA] |
| Canonical Shapes        | Cone          | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  |
|                         | Cylindre      | 1 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 0 [NA] | 0 [R]  |
|                         | Box           | 1 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 1 [R]  | 0 [NA] | 0 [R]  |
|                         | Sphere        | 1 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 1 [R]  | 1 [R]  | 0 [R]  |
|                         | Total         | 4       | 2       | 3                 | 4                 | 4             | 0                | 1            | 2      | 2      | 0      |
| Volumic Operators       | Extrude       | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 1 [T]        | 1 [R]  | 1 [R]  | 0 [NA] |
|                         | Sweep         | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [D]        | 0 [R]  | 0 [NA] | 0 [NA] |
|                         | Revolve       | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 0 [D]        | 0 [R]  | 1 [R]  | 0 [NA] |
|                         | Total         | 3       | 0       | 2                 | 2                 | 2             | 0                | 1            | 1      | 2      | 0 [NA] |
| Boolean Operators       | Union         | 0 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 1 [D]        | 0 [NA] | 1 [R]  | 0 [NA] |
|                         | Interset      | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [NA] |
|                         | Substract     | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 1 [R]  | 0 [NA] | 0 [NA] |
|                         | Total         | 0       | 1       | 1                 | 1                 | 1             | 0                | 1            | 1 [NA] | 2      | 0 [NA] |
| Surfacic Operators      | Offset        | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 0 [NA] | 0 [NA] | 0 [NA] |
|                         | Patch         | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 0 [T]        | 0 [NA] | 0 [NA] | 0 [NA] |
|                         | Total         | 2       | 0       | 1                 | 1                 | 1             | 1                | 1            | 0 [NA] | 0 [NA] | 0 [NA] |
| Engineering Features    | Hole          | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 1 [R]  | 1 [R]  | 0 [NA] |
|                         | Chamfer       | 0 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [NA] |
|                         | Ribs          | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 0 [NA] | 0 [NA] |
|                         | Total         | 0       | 0       | 0                 | 1                 | 1             | 0                | 1            | 1      | 2      | 0 [NA] |
| Entites Geometrique     | Spline        | 1 [T]   | 1 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  |
|                         | Circle        | 1 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 0 [R]  | 0 [NA] | 0 [R]  |
|                         | Rectangle     | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [T]            | 1 [T]        | 0 [R]  | 0 [NA] | 0 [R]  |
|                         | Point         | 0 [T]   | 0 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  |
|                         | Plane         | 0 [T]   | 1 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 1 [T]            | 1 [T]        | 0 [R]  | 1 [R]  | 0 [R]  |
|                         | Line          | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 1 [T]        | 0 [R]  | 1 [R]  | 0 [R]  |
|                         | Total         | 4       | 3       | 2                 | 2                 | 2             | 3                | 4            | 0      | 4      | 0      |
<td><img src="https://github.com/GIS-S-mart/Benchmark-2_3D_modelling_in_VR/blob/main/images/Capabilities.PNG"  width=1000 /></td>


## Meta-Analysis


