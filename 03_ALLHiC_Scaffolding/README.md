ALLHiC Scaffolding
=

Se usó el flujo de trabajo de ALLHiC para el scaffolding, se usaron múltiples estrategias variando los datos de entrada y el genoma de referencia utilizado para el synteny.

----------------
#### Ensamblaje inicial:

- Ensamblaje Canu v1: Ensamblaje de HiCanu 
- Ensamblaje Canu v2: Salida de ALLHIC_correccion, como entrada Canu v1 y los datos crudos de Hi-C.
- Ensamblaje Canu v3: Salida de ALLHIC_correccion, como entrada Canu v1 y los contactos válidos HiC 

----------------
#### Genoma de referencia:

- [RH89-039-16](https://www.nature.com/articles/s41588-020-0699-x)
- [DMv6](https://academic.oup.com/gigascience/article/9/9/giaa100/5910251)

----------------

| Estrategia  | Genoma de referencia | Ensamblaje Inicial | Lecturas HiC |
| ------------- | ------------- | ------------- | ------------- |
| st0  | RH89-039-16   | Ensamblaje Canu v1 | lecturas crudas HiC |
| st1  | RH89-039-16   | Ensamblaje Canu v2 | raw Hi-C reads|
| st2  | RH89-039-16   | Ensamblaje Canu v2 | Contactos válidos HiC|
| st3  | RH89-039-16   | Ensamblaje Canu v1  | Contactos válidos HiC|
| st4  | RH89-039-16   | Ensamblaje Canu v3  | Contactos válidos HiC|
| st5  | DMv6    | Ensamblaje Canu v1  | Contactos válidos HiC|
| st6  | DMv6    | Ensamblaje Canu v2 | Contactos válidos HiC|
| st7  | DMv6    | Ensamblaje Canu v3 | Contactos válidos HiC|

