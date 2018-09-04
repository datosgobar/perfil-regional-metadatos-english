Annex
===

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
 

- [Annex I - Theme taxonomy (table)](#Annex-i-taxonomia-tematica-tabla)
- [Annex II - Theme taxonomy (JSON)](#Annex-ii-taxonomia-tematica-json)
- [Annex III - Guidelines for tags selection](#Annex-iii-pautas-para-la-seleccion-de-etiquetas)
- [Annex IV - Frequency specification (ISO-8601)](#Annex-iv-especificacion-de-frecuencias-segun-iso-8601)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Annex I - Theme taxonomy (tabla)

The Regional Metadata Profile recommends using the [theme taxonomy defined by European Union](http://publications.europa.eu/mdr/authority/data-theme/index.html) for most cases.

This taxonomy has 13 general themes, under which any data asset can be classified. Nevertheless, **some countries may want to develop a more detailed theme taxonomy**, with more specific topics.

<table>
  <colgroup>
    <col style="width:33%">
    <col style="width:33%">
    <col style="width:33%">
  </colgroup>
  <tbody>
    <tr>
      <td>Code</td>
      <td>Label</td>
      <td>Description</td>
    </tr>
    <tr>
      <td>AGRI</td>
      <td>Agroganadería, pesca y forestación</td>
      <td>Datos referidos a agroganadería, pesca y forestación. Por ejemplo: 'Lechería: precio pagado al productor' o 'Superficie forestada'.</td>
    </tr>
    <tr>
      <td>ECON</td>
      <td>Economía y finanzas</td>
      <td>Datos referidos a economía y finanzas. Por ejemplo: 'Deuda pública'.</td>
    </tr>
    <tr>
      <td>EDUC</td>
      <td>Educación, cultura y deportes</td>
      <td>Datos referidos a educación, cultura y deportes. Por ejemplo: 'Registro de Establecimientos Educativos'.</td>
    </tr>
    <tr>
      <td>ENER</td>
      <td>Energía</td>
      <td>Datos referidos a energía. Por ejemplo: 'Productos mineros exportados' o 'Precios del GNC'.</td>
    </tr>
    <tr>
      <td>ENVI</td>
      <td>Medio ambiente</td>
      <td>Datos referidos a medio ambiente. Por ejemplo: 'Operadores de residuos peligrosos'.</td>
    </tr>
    <tr>
      <td>GOVE</td>
      <td>Gobierno y sector público</td>
      <td>Datos referidos a gobierno y sector público. Por ejemplo: 'Inmuebles del estado Nacional'.</td>
    </tr>
    <tr>
      <td>HEAL</td>
      <td>Salud</td>
      <td>Datos referidos a salud. Por ejemplo: 'Estadísticas nacionales de VIH/SIDA'.</td>
    </tr>
    <tr>
      <td>INTR</td>
      <td>Asuntos internacionales</td>
      <td>Datos referidos a asuntos internacionales. Por ejemplo: 'Representaciones argentinas en el exterior'.</td>
    </tr>
    <tr>
      <td>JUST</td>
      <td>Justicia, seguridad y legales</td>
      <td>Datos referidos a justicia, seguridad y legales. Por ejemplo: 'Censo penitenciario'.</td>
    </tr>
    <tr>
      <td>REGI</td>
      <td>Regiones y ciudades</td>
      <td>Datos referidos a regiones y ciudades. Por ejemplo: 'Departamentos de la provincia de Río Negro'.</td>
    </tr>
    <tr>
      <td>SOCI</td>
      <td>Población y sociedad</td>
      <td>Datos referidos a población y sociedad. Por ejemplo: 'Turistas residentes que viajan por Argentina'.</td>
    </tr>
    <tr>
      <td>TECH</td>
      <td>Ciencia y tecnología</td>
      <td>Datos referidos a ciencia y tecnología. Por ejemplo: 'Recursos humanos en ciencia y tecnología'.</td>
    </tr>
    <tr>
      <td>TRAN</td>
      <td>Transporte</td>
      <td>Datos referidos a transporte. Por ejemplo: 'Estadísticas viales'.</td>
    </tr>
    </tbody>
</table>

## Annex II - Theme taxonomy (JSON)

This is the [Theme taxonomy of European Union](https://raw.githubusercontent.com/datosgobar/perfil-regional-metadatos/master/standards/themeTaxonomy.json) in JSON format:

```json
[
    {
        "id":"AGRI",
        "label":"Agroganadería, pesca y forestación",
        "description":"Datos referidos a agroganadería, pesca y forestación. Por ejemplo: 'Lechería: precio pagado al productor' o 'Superficie forestada'."
    },
    {
        "id":"ECON",
        "label":"Economía y finanzas",
        "description":"Datos referidos a economía y finanzas. Por ejemplo: 'Deuda pública'."
    },
    {
        "id":"EDUC",
        "label":"Educación, cultura y deportes",
        "description":"Datos referidos a educación, cultura y deportes. Por ejemplo: 'Registro de Establecimientos Educativos'."
    },
    {
        "id":"ENER",
        "label":"Energía",
        "description":"Datos referidos a energía. Por ejemplo: 'Productos mineros exportados' o 'Precios del GNC'."
    },
    {
        "id":"ENVI",
        "label":"Medio ambiente",
        "description":"Datos referidos a medio ambiente. Por ejemplo: 'Operadores de residuos peligrosos'."
    },
    {
        "id":"GOVE",
        "label":"Gobierno y sector público",
        "description":"Datos referidos a gobierno y sector público. Por ejemplo: 'Inmuebles del estado Nacional'."
    },
    {
        "id":"HEAL",
        "label":"Salud",
        "description":"Datos referidos a salud. Por ejemplo: 'Estadísticas nacionales de VIH/SIDA'."
    },
    {
        "id":"INTR",
        "label":"Asuntos internacionales",
        "description":"Datos referidos a asuntos internacionales. Por ejemplo: 'Representaciones argentinas en el exterior'."
    },
    {
        "id":"JUST",
        "label":"Justicia, seguridad y legales",
        "description":"Datos referidos a justicia, seguridad y legales. Por ejemplo: 'Censo penitenciario'."
    },
    {
        "id":"REGI",
        "label":"Regiones y ciudades",
        "description":"Datos referidos a regiones y ciudades. Por ejemplo: 'Departamentos de la provincia de Río Negro'."
    },
    {
        "id":"SOCI",
        "label":"Población y sociedad",
        "description":"Datos referidos a población y sociedad. Por ejemplo: 'Turistas residentes que viajan por Argentina'."
    },
    {
        "id":"TECH",
        "label":"Ciencia y tecnología",
        "description":"Datos referidos a ciencia y tecnología. Por ejemplo: 'Recursos humanos en ciencia y tecnología'."
    },
    {
        "id":"TRAN",
        "label":"Transporte",
        "description":"Datos referidos a transporte. Por ejemplo: 'Estadísticas viales'."
    }
]
```

## Annex III - Guidelines for tags selection

Choosing good labels make is it easier for user to search for data assets. The larger and homogeneous is the tag list, the more effective will be.

These guidelines apply to define labels used in the *keyword* metadata of the Dataset class:

* Writing correctly and in plural.

* Use upper case only where is necessary.

* Identify key words.

* Re-use previous labels, rather than creating similar new ones.

* Add different sinonims and use natural language.

* Use only one word. Only use more words if really necessary.

* If the tag has more than one word, should be space separated as in: "legal declarations".

Useful questions to think about tags:

* ¿What is the topic?

* ¿What aspects of the data asset will be interesting for users?

* ¿In what different ways users will look for this information?

* ¿What kind of information is this about?

* ¿What organization provide this data?

## Annex IV - Frequency specification (ISO-8601)

<table>
  <tr>
    <td>Frequency</td>
    <td>Value under ISO-8601</td>
  </tr>
  <tr>
    <td>Every ten years</td>
    <td>R/P10Y</td>
  </tr>
  <tr>
    <td>Every four years</td>
    <td>R/P4Y</td>
  </tr>
  <tr>
    <td>Every three years</td>
    <td>R/P3Y</td>
  </tr>
  <tr>
    <td>Every two years</td>
    <td>R/P2Y</td>
  </tr>
  <tr>
    <td>Yearly</td>
    <td>R/P1Y</td>
  </tr>
  <tr>
    <td>Every half year</td>
    <td>R/P6M</td>
  </tr>
  <tr>
    <td>Every four years</td>
    <td>R/P4M</td>
  </tr>
  <tr>
    <td>Quarterly</td>
    <td>R/P3M</td>
  </tr>
  <tr>
    <td>Every two years</td>
    <td>R/P2M</td>
  </tr>
  <tr>
    <td>Monthly</td>
    <td>R/P1M</td>
  </tr>
  <tr>
    <td>Every 15 days</td>
    <td>R/P0.5M</td>
  </tr>
  <tr>
    <td>Three times per month</td>
    <td>R/P0.33M</td>
  </tr>
  <tr>
    <td>Weekly</td>
    <td>R/P1W</td>
  </tr>
  <tr>
    <td>Two times per week</td>
    <td>R/P0.5W</td>
  </tr>
  <tr>
    <td>Three times per week</td>
    <td>R/P0.33W</td>
  </tr>
  <tr>
    <td>Daily</td>
    <td>R/P1D</td>
  </tr>
  <tr>
    <td>Every hour</td>
    <td>R/PT1H</td>
  </tr>
  <tr>
    <td>Continuously updated</td>
    <td>R/PT1S</td>
  </tr>
  <tr>
    <td>Eventual</td>
    <td>eventual</td>
  </tr>
</table>
