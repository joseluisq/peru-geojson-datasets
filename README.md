# Perú GeoJSON

> Estructuras de datos geográficos [GeoJSON](https://geojson.org/) representando departamentos, provincias y distritos del Perú.


## Distritos (Lima / Callao)

Los siguientes archivos presentan polígonos de los distritos de Lima y Callao. 

- **Versión detallada:** [lima_callao_distritos.geojson](lima_callao_distritos.geojson) (`1,7M`)
- **Versión simplificada:** [lima_callao_distritos_simple.geojson](lima_callao_distritos_simple.geojson) (`144k`)

```json
{
  "type": "Feature",
  "geometry": {
    "type": "Polygon",
    "coordinates": [
      [
        [ -77.049736, -12.070172 ],
        [ -77.045747, -12.065347 ],
        [ -77.04151, -12.060201 ],
        [ -77.042404, -12.050873 ],
        [ -77.045596, -12.050689 ],
        [ -77.052076, -12.04934 ],
        [ -77.053746, -12.049131 ],
        [ -77.055402, -12.052617 ],
        [ -77.057555, -12.055551 ],
        [ -77.059256, -12.062066 ],
        [ -77.06117, -12.067525 ],
        [ -77.054199, -12.066547 ],
        [ -77.049736, -12.070172 ]
      ]
    ]
  },
  "properties": {
    "id": 16,
    "departamento": "LIMA",
    "provincia": "LIMA",
    "distrito": "BREÑA",
    "institucion": "IGN",
    "distrito2": null
  }
}
```

## Conjunto de datos

- [Geoservidor MINAM / geoservidor.minam.gob.pe](https://geoservidor.minam.gob.pe/)
- [GEOIDEP / minam.gob.pe](https://www.geoidep.gob.pe/)
- [juaneladio/peru-geojson](https://github.com/juaneladio/peru-geojson)
- [CARTO - Datasets by nicolasb](https://nicolasb.carto.com/datasets)
- [CARTO - Datasets by properati-datos](https://properati-datos.carto.com/tables/distritos_lima_y_callao_formatted_for_carto/public)

## Contribuciones

A menos que usted declare explícitamente lo contrario, cualquier contribución enviada intencionadamente por usted para su inclusión en el trabajo actual, como se define en la licencia de Apache-2.0, tendrá una doble licencia como se describe a continuación, sin ningún término o condición adicional.

Siéntase libre de enviar algún [Pull request](https://github.com/joseluisq/peru-geojson/pulls) o [issue](https://github.com/joseluisq/peru-geojson/issues).

## Licencia

Este trabajo se distribuye principalmente bajo los términos de la licencia [MIT](LICENSE-MIT) y [Apache License (Version 2.0)](LICENSE-APACHE).

© 2020 [Jose Quintana](https://git.io/joseluisq)
