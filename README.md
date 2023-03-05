# [JSON] Regiones, provincias, ciudades y comunas de Chile

Regiones, provincias, ciudades y comunas de Chile en formato **JSON**

## resumen.json

Ejemplo del formato del archivo `resumen.json`

```json
{
  "Región de Arica y Parinacota": {
    "id": 15,
    "capital": "Arica",
    "provincias": {
      "Arica": {
        "capital": "Arica",
        "comunas": [
          "Arica",
          "Camarones"
        ]
      },
      "Parinacota": {
        "capital": "Putre",
        "comunas": [
          "General Lagos",
          "Putre"
        ]
      }
    },
    "comunas": [
      "Arica",
      "Camarones",
      "General Lagos",
      "Putre"
    ]
  },
...
}
```

### Referencias
* **INE**: https://web.archive.org/web/20190713152439/https://geoarchivos.ine.cl/File/pub/Cd_Pb_Al_Cs_2019.pdf
* **Wikipedia**: https://es.wikipedia.org/wiki/Anexo:Ciudades_de_Chile
* **Gobierno de Chile**: https://www.gob.cl/instituciones/#regions