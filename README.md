# Ocupaciones, habilidades y exposición a la IA en los sectores exportadores dinámicos

Contraparte laboral de la Nota Técnica sobre exportaciones y cadenas de valor en
México y Centroamérica. Presentación de resultados para el equipo del
Departamento de Países CID.

**Página:** https://etorresram.github.io/CID-Technical-Note/

## Qué hay aquí

| | |
|---|---|
| `index.html` | La página. Estática y sin dependencias externas. |
| `Presentacion_CID_IA_Sectores.pptx` | La presentación para la reunión: 18 láminas en lenguaje llano. |
| `figuras/` | Las nueve figuras del cuerpo (W1–W9) y las dos del anexo (A1–A2). |
| `datos/` | Cuadros agregados que respaldan cada figura. Sin microdatos. |

### Cobertura de países en los cuadros

| Cuadro | Países | Por qué faltan los demás |
|---|---|---|
| `comparacion_paises_*.csv` | los 6 con encuesta | El Salvador sin vacantes (no entregadas); Panamá sin ninguna fuente |
| `capas_*.csv` | MEX, CRI, DOM, HND, SLV | Guatemala publica la ocupación a 2 dígitos. México aporta el 82% del empleo |
| `formalidad_pais_anual.csv` | los 6 | — |
| `habilidades_*.csv` | los 5 con vacantes | El Salvador y Panamá no tienen vacantes |
| `intensidad_demanda_*.csv` | los 5 con vacantes | ídem; el panel de tendencia solo los 3 con serie completa |
| `escalamiento_oferta.csv` | MEX y CRI | son las dos únicas encuestas con periodicidad trimestral |
| `escalamiento_demanda.csv` | los 5 con vacantes | El Salvador y Panamá no tienen vacantes |

## El panorama

Con una sola medida —la β canónica CIUO-08— y las dos fuentes, seis países:

| País | Encuesta | Empleo total | Formal | Vacantes |
|---|---|---|---|---|
| México | ENOE 2025 | 0,285 | 0,347 | 0,446 |
| Costa Rica | ECE 2025 | 0,283 | 0,328 | 0,446 |
| Rep. Dominicana | ENCFT 2024 | 0,263 | 0,328 | 0,430 |
| El Salvador | EHPM 2025 | 0,243 | 0,303 | — |
| Honduras | EPHPM 2025 | 0,237 | 0,325 | 0,459 |
| Guatemala | ENCOVI 2023 | 0,209 | 0,327 | 0,422 |

La brecha entre vacantes y empleo total correlaciona **+0,89** con la
informalidad; restringida al empleo formal **desaparece (−0,01)**. El empleo
formal de los seis países está expuesto casi por igual.

## Los cuatro hallazgos

1. **La exposición crece con la calificación.** El 54% del empleo sectorial
   tiene β por debajo de 0,15 —los ensambladores, 224 mil ocupados, están en
   0,11— pero la capa expuesta es la calificada: 0,41 en técnicos, 0,48 en
   apoyo administrativo y 0,56 en profesionales. Es la misma capa que habilita
   el escalamiento exportador.
2. **La cadena regional reparte los nodos.** En cables, la capa
   técnica-profesional es 26% en México, 19% en Honduras y 18% en Rep. Dominicana.
3. **Tener el capital humano no basta.** Rep. Dominicana tiene el stock terciario
   de México y la estructura ocupacional de un país de ensamble.
4. **La demanda de habilidades de IA se multiplica por 2,7** entre 2022 y 2026,
   neta del alargamiento de las descripciones.

## Método en una línea

Puntaje β de exposición de Eloundou et al. (2023) —tareas de exposición directa
más la mitad de las mediadas por software; mide ahorro potencial de tiempo, no
reemplazo— transferido por
O*NET/SOC-2018 → SOC-2010 → CIUO-08 con correspondencias oficiales, cruzados con
las encuestas de empleo de cinco países y con 2 586 172 vacantes en línea del
Observatorio Laboral del BID (junio 2022 – mayo 2026).

## Aviso

Insumo interno de trabajo. Los resultados acompañan una Nota Técnica en
preparación, no constituyen una publicación del Banco Interamericano de
Desarrollo ni reflejan necesariamente su posición.
