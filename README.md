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
