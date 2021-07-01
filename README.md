# Benchmark 2. 3D Modelling in VR

The Benchmark-2_3D_modelling_VR aims at benchmarking methods and tools for 3D modelling in virtual reality.

## Glossary

...

## Requirements





## Measures of performance

## Datasets

- [Robot arm]

## Comparison

| Criteria                |[Mindesk](https://mindeskvr.com/)| SkyReal  | [Gravity Sketch](https://www.gravitysketch.com/) | Blender OpenXR | Blender VR | [Flying Shapes](https://www.flyingshapes.com/) | [VR Sketch](https://vrsketch.eu/) | \[3\]    | \[1\]    | \[[2](https://gricad-gitlab.univ-grenoble-alpes.fr/vision-r/projets/architool/-/tree/UpdateJuin24)\]    |
| ----------------------- | ---------- | -------- | -------------- | -------------- | ---------- | ------------- | --------- | -------- | -------- | -------- |
| Dimensional constraints| Length     | 0 \[T\]  | 0 \[D\]        | 0 \[D\]        | 0 \[D\]    | 0 \[D\]       | 0 \[D\]   | 0 \[T\]  | 1 \[R\]  | 0 \[NA\] | 0 \[NA\] |
| |Radius                  | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[D\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 1 \[R\]  | 0 \[NA\] | 0 \[NA\] |
| |Distance                | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[D\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 1 \[R\]  | 0 \[NA\] | 0 \[NA\] |
| |Angle                   | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[D\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 1 \[R\]  | 0 \[NA\] | 0 \[NA\] |
| Total                   | 0          | 0        | 0              | 0              | 0          | 0             | 0         | 4        | 0 \[NA\] | 0 \[NA\] |
| Geometrical constraints | Horizontal | 1 \[T\]  | 0 \[NA\]       | 0 \[D\]        | 0 \[T\]    | 0 \[D\]       | 0 \[D\]   | 1 \[T\]  | 0 \[NA\] | 0 \[NA\] |  |
| |Vertical                | 1 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |Fix/UnFix               | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |End point               | 1 \[T\]    | 1 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 1 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
|| Mid-Point               | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |Perpendicular           | 1 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |Concentric              | 1 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |Coincident              | 1 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 1 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| |Tangent                 | 1 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
|| Parallel                | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
|| Symmetry                | 1 \[T\]    | 1 \[D\]  | 1 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 1 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
|| Equidistant             | 0 \[T\]    | 0 \[NA\] | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[NA\] |          |
| Total                   | 10         | 2 \[NA\] | 1              | 0              | 0          | 2             | 9         | 0 \[NA\] | 0 \[NA\] |          |
| Canonical Shapes        | Cone       | 1 \[T\]  | 0 \[D\]        | 1 \[D\]        | 1 \[T\]    | 1 \[D\]       | 0 \[T\]   | 0 \[T\]  | 0 \[R\]  | 0 \[R\]  | 1 \[R\] |
| |Cylindre                | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[T\]       | 0 \[T\]   | 0 \[R\]  | 0 \[R\]  | 0 \[NA\] |
| |Box                     | 1 \[T\]    | 1 \[D\]  | 1 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[T\]       | 1 \[T\]   | 0 \[R\]  | 1 \[R\]  | 0 \[NA\] |
| |Sphere                  | 1 \[T\]    | 1 \[D\]  | 1 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[T\]       | 0 \[T\]   | 0 \[R\]  | 1 \[R\]  | 1 \[R\]  |
| Total                   | 4          | 2        | 3              | 4              | 4          | 0             | 1         | 0        | 2        | 2        |
| Volumic Operators       | Extrude    | 1 \[T\]  | 0 \[D\]        | 1 \[D\]        | 1 \[T\]    | 1 \[D\]       | 0 \[D\]   | 1 \[T\]  | 0 \[NA\] | 1 \[R\]  | 1 \[R\] |
|| Sweep                   | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[D\]   | 0 \[NA\] | 0 \[R\]  | 0 \[NA\] |
| |Revovle                 | 1 \[T\]    | 0 \[D\]  | 1 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[D\]       | 0 \[D\]   | 0 \[NA\] | 0 \[R\]  | 1 \[R\]  |
| Total                   | 3          | 0        | 2              | 2              | 2          | 0             | 1         | 0 \[NA\] | 1        | 2        |
| Boolean Operators       | Union      | 0 \[T\]  | 1 \[D\]        | 1 \[D\]        | 1 \[T\]    | 1 \[D\]       | 0 \[D\]   | 1 \[D\]  | 0 \[NA\] | 0 \[NA\] | 1 \[R\] |
| |Interset                | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[R\]  | 1 \[R\]  |
| |Substract               | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 1 \[R\]  | 0 \[NA\] |
| Total                   | 0          | 1        | 1              | 1              | 1          | 0             | 1         | 0 \[NA\] | 1 \[NA\] | 2        |
| Surfacic Operators      | Offset     | 1 \[T\]  | 0 \[D\]        | 1 \[D\]        | 1 \[T\]    | 1 \[D\]       | 0 \[T\]   | 1 \[T\]  | 0 \[NA\] | 0 \[NA\] | 0 \[NA\] |
|| Patch                   | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 1 \[T\]       | 0 \[T\]   | 0 \[NA\] | 0 \[NA\] | 0 \[NA\] |
| Total                   | 2          | 0        | 1              | 1              | 1          | 1             | 1         | 0 \[NA\] | 0 \[NA\] | 0 \[NA\] |
| Engineering Features    | Hole       | 0 \[T\]  | 0 \[D\]        | 0 \[D\]        | 0 \[T\]    | 0 \[D\]       | 0 \[D\]   | 1 \[T\]  | 0 \[NA\] | 1 \[R\]  | 1 \[R\] |
|| Chamfer                 | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[R\]  | 1 \[R\]  |
| |Ribs                    | 0 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[D\]       | 0 \[T\]   | 0 \[NA\] | 0 \[R\]  | 0 \[NA\] |
| Total                   | 0          | 0        | 0              | 1              | 1          | 0             | 1         | 0 \[NA\] | 1        | 2        |
| Entites Geometrique     | Spline     | 1 \[T\]  | 1 \[D\]        | 1 \[D\]        | 0 \[T\]    | 0 \[D\]       | 1 \[T\]   | 0 \[T\]  | 0 \[R\]  | 0 \[R\]  | 1 \[R\] |
|| Circle                  | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 1 \[T\]        | 1 \[D\]    | 0 \[T\]       | 1 \[T\]   | 0 \[R\]  | 0 \[R\]  | 0 \[NA\] |
| |Rectangle               | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[T\]       | 1 \[T\]   | 0 \[R\]  | 0 \[R\]  | 0 \[NA\] |
| |Point                   | 0 \[T\]    | 0 \[D\]  | 1 \[D\]        | 0 \[T\]        | 0 \[D\]    | 0 \[T\]       | 0 \[T\]   | 0 \[R\]  | 0 \[R\]  | 1 \[R\]  |
| |Plane                   | 0 \[T\]    | 1 \[D\]  | 0 \[D\]        | 1 \[T\]        | 1 \[D\]    | 1 \[T\]       | 1 \[T\]   | 0 \[R\]  | 0 \[R\]  | 1 \[R\]  |
| |Line                    | 1 \[T\]    | 0 \[D\]  | 0 \[D\]        | 0 \[T\]        | 0 \[D\]    | 1 \[T\]       | 1 \[T\]   | 0 \[R\]  | 0 \[R\]  | 1 \[R\]  |
| Total                   | 4          | 3        | 2              | 2              | 2          | 3             | 4         | 0        | 0        | 4        |

<td><img src="https://github.com/GIS-S-mart/Benchmark-2_3D_modelling_in_VR/blob/main/images/Capabilities.PNG"  width=1000 /></td>


## Meta-Analysis


