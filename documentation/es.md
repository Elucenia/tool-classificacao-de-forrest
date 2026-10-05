<!-- ELUCENIA technical documentation · classificacao-de-forrest · es · no clinical/professional/rights approval -->

# Clasificación de Forrest

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/classificacao-de-forrest)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Aspecto de la úlcera en la endoscopia

`classe`

- `Ia` — Ia – sangrado activo en chorro
- `Ib` — Ib – sangrado activo babeante
- `IIa` — IIa – vaso visible sin sangrado
- `IIb` — IIb – coágulo adherido
- `IIc` — IIc – mancha plana pigmentada (hematina)
- `III` — III – base limpia (fibrina)

## Edición del método

Forrest 1974: Ia/Ib/IIa/IIb/IIc/III; contexto ESGE 2021

## Fórmula documentada

Forrest I (sangrado activo): Ia en chorro, Ib babeante. Forrest II (estigmas de sangrado reciente): IIa vaso visible, IIb coágulo adherido, IIc hematina plana. Forrest III: base limpia.

## Límites y población

Forrest clasifica el aspecto endoscópico de la úlcera péptica sangrante, no toda hemorragia digestiva. Seleccione la clase a partir del examen; la herramienta no analiza imágenes ni identifica la causa del sangrado. La guía ESGE de 2021 reconoce limitaciones en la concordancia entre observadores. La clase y los posibles porcentajes históricos no proporcionan, por sí solos, una predicción individual de resangrado ni determinan el alta o el tratamiento.

## Referencias

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
