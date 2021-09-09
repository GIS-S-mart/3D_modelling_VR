# Benchmark 2. 3D Modelling in VR

The Benchmark-2_3D_modelling_VR aims at benchmarking virtual environments for 3D modelling in virtual reality.

## Glossary

...

## Requirements

- The VE shall enable the designer to define dimensional constraints (length, raduis, distance, angle)
- The VE shall enable the designer to define geometrical constraints (horizontal, vertical, fix/unfix, end point, mid-point, perpendicular, concentric, parallel, tangent, equidistant)
- The VE shall enable the designer to define canonical shapes (cone, cylinder, box, sphere)
- The VE shall enable the designer to define volumic operators (extrude, sweep, revolve)
- The VE shall enable the designer to define boolean operators (union, intesect, substract)
- The VE shall enable the designer to define surfacic operators (offset, patch)
- The VE shall enable the designer to define engineering features (hole, chamfer, ribs)
- The VE shall enable the designer to geometric entities (spline, circle, rectangle, point, plane, line)

## Measures of performance

## Datasets

- [Robot arm]

## Comparison

| Category                |   Criteria            | [Mindesk](https://mindeskvr.com/) | SkyReal | [Gravity<br>Sketch](https://www.gravitysketch.com/) | Blender<br>OpenXR | Blender<br>VR | [Flying<br>Shapes](https://www.flyingshapes.com/) | [VR<br>Sketch](https://vrsketch.eu/) | [Bordot *et al*](https://dl.acm.org/doi/10.1016/j.cad.2008.10.014)    | [Martin *et al*](https://link.springer.com/chapter/10.1007/978-3-319-60922-5_17)    | [Feeman *et al*](https://www.tandfonline.com/doi/abs/10.1080/16864360.2018.1462570?journalCode=tcad20)    | [VRSM](https://gricad-gitlab.univ-grenoble-alpes.fr/vision-r-public/architool/-/tree/master/Structural%20view)
|-------------------------|---------------|---------|---------|-------------------|-------------------|---------------|------------------|--------------|--------|--------|--------|--------|
| Dimensional constraints | Length        | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R] | 1 [T] |
|                         | Radius        | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R]  | 1 [T] |
|                         | Distance      | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R] | 1 [T]  |
|                         | Angle         | 0 [T]   | 0 [D]   | 0 [D]             | 0 [D]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] | 0 [NA] | 1 [R] | 1 [T]  |
|                         | Total         | 0       | 0       | 0                 | 0                 | 0             | 0                | 0            | 0 [NA] | 0 [NA] | 4   | 1 [T]    |
| Geometrical constraints | Horizontal    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Vertical      | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Fix/UnFix     | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | End point     | 1 [T]   | 1 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Mid-Point     | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Perpendicular | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Concentric    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Coincident    | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 1 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Tangent       | 1 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Parallel      | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Symmetry      | 1 [T]   | 1 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Equidistant   | 0 [T]   | 0 [NA]  | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [NA] |        | 0 [NA] | 1 [T] |
|                         | Total         | 10      | 2 [NA]  | 1                 | 0                 | 0             | 2                | 9            | 0 [NA] |        | 0 [NA] | 1 [T] |
| Canonical Shapes        | Cone          | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Cylindre      | 1 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 0 [NA] | 0 [R]  | 1 [T] |
|                         | Box           | 1 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 1 [R]  | 0 [NA] | 0 [R]  | 1 [T] |
|                         | Sphere        | 1 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 0 [T]        | 1 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Total         | 4       | 2       | 3                 | 4                 | 4             | 0                | 1            | 2      | 2      | 0   | 1 [T]    |
| Volumic Operators       | Extrude       | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 1 [T]        | 1 [R]  | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Sweep         | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [D]        | 0 [R]  | 0 [NA] | 0 [NA] | 1 [T] |
|                         | Revolve       | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 0 [D]        | 0 [R]  | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Total         | 3       | 0       | 2                 | 2                 | 2             | 0                | 1            | 1      | 2      | 0 [NA] | 1 [T] |
| Boolean Operators       | Union         | 0 [T]   | 1 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 1 [D]        | 0 [NA] | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Intersect      | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Substract     | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 1 [R]  | 0 [NA] | 0 [NA] | 1 [T] |
|                         | Total         | 0       | 1       | 1                 | 1                 | 1             | 0                | 1            | 1 [NA] | 2      | 0 [NA] | 1 [T] |
| Surfacic Operators      | Offset        | 1 [T]   | 0 [D]   | 1 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 0 [NA] | 0 [NA] | 0 [NA] | 1 [T] |
|                         | Patch         | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 0 [T]        | 0 [NA] | 0 [NA] | 0 [NA] | 1 [T] |
|                         | Total         | 2       | 0       | 1                 | 1                 | 1             | 1                | 1            | 0 [NA] | 0 [NA] | 0 [NA] | 1 [T] |
| Engineering Features    | Hole          | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 1 [T]        | 1 [R]  | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Chamfer       | 0 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [NA] | 1 [T] |
|                         | Ribs          | 0 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [D]            | 0 [T]        | 0 [R]  | 0 [NA] | 0 [NA] | 1 [T] |
|                         | Total         | 0       | 0       | 0                 | 1                 | 1             | 0                | 1            | 1      | 2      | 0 [NA] | 1 [T] |
| Geometric entities     | Spline        | 1 [T]   | 1 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Circle        | 1 [T]   | 0 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 0 [T]            | 1 [T]        | 0 [R]  | 0 [NA] | 0 [R]  | 1 [T] |
|                         | Rectangle     | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 0 [T]            | 1 [T]        | 0 [R]  | 0 [NA] | 0 [R]  | 1 [T] |
|                         | Point         | 0 [T]   | 0 [D]   | 1 [D]             | 0 [T]             | 0 [D]         | 0 [T]            | 0 [T]        | 0 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Plane         | 0 [T]   | 1 [D]   | 0 [D]             | 1 [T]             | 1 [D]         | 1 [T]            | 1 [T]        | 0 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Line          | 1 [T]   | 0 [D]   | 0 [D]             | 0 [T]             | 0 [D]         | 1 [T]            | 1 [T]        | 0 [R]  | 1 [R]  | 0 [R]  | 1 [T] |
|                         | Total         | 4       | 3       | 2                 | 2                 | 2             | 3                | 4            | 0      | 4      | 0      | 1 [T] |
<td><img src="https://github.com/GIS-S-mart/Benchmark-2_3D_modelling_in_VR/blob/main/images/Capabilities.PNG"  width=1000 /></td>


## Datasets

- [Preliminary design of an electro-mechanical actuator (EMA)]()


## Meta-Analysis


## References

[Tran, T., Foucault, G., Pinquié, R., (2021) "Benchmarking of 3D modelling in virtual reality". CAD Conference, 2021, Barcelona.](https://rpinquie.github.io/publications/CAD21.pdf)


