---
tipo: contenedor
categoria: LIT
titulo: Teoría Literaria
sistema: Biblioteca_Javitanus
jdr: "808.100"
parent: Catálogo General
estado: borrador
etiquetas: [teoría]
subtipo_doc: hub_compuesto
doc_hijo: nota_atomica
plantilla: Plantilla_pasoApaso_1d
---

# Teoría Literaria
---
Una obra literaria o audiovisual puede ser comprendida desde distintas perspectivas: estructural, funcional, temática, las que a su vez pueden desglosarse para el análisis en:

---

## 👥 Elementos Clave
_(Este Hub (Tipo: hub_compuesto) contiene Fichas Atómicas de nota_atomica)_  

---
Estructuralmente, la obra puede ser dividida en partes específicas. Sin embargo, estas partes cumplen una o más funciones en la construcción y desarrollo de una historial, temas que pueden ser comprendidos desde diversas perspectivas y modelos.

+ [[Estructuras dramáticas]]
+ [[Categorías de historias]]
+ [[Temas literarios]]
+ [[Tipos de historias]]
+ [[Géneros literarios]]
+ [[Subgéneros literarios]]
+ [[36 Situaciones dramáticas]]
+ [[Aventura del Héroe]]

Las funciones que cumplen pueden a su vez agruparse en grandes familias con subtipos claros que pueden identificarse en el contexto como **funciones primarias**, **funciones secundarias**, **funciones terciarias o complementarias**:

+ [[Funciones por finalidad]]
+ [[Funciones estructurales]]
+ [[Funciones narrativas]]
+ [[Funciones dramáticas]]
+ [[Funciones simbólicas]]
+ [[Funciones pragmáticas]]

## 🔗 Contenido Referenciado (Tipo: nota atómica)


```dataview
TABLE subtipo_doc AS "Subtipo", 
      jdr AS "JDR",
      titulo AS "Descripción",
      estado AS "Estado"
FROM ""
WHERE parent = this.file.name 
  AND tipo = "nota"
SORT jdr ASC, file.name ASC
```
