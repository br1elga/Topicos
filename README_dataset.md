# dataset_iot_simulation_building_sensors

**Resumen**: Conjunto de datos simulado de telemetría IoT para el proyecto *Seguridad en Redes IoT* (Packet Tracer). Contiene lecturas de sensores generadas durante la simulación y procesadas para análisis de comportamiento y detección de intrusos.

## Contenido
- `dataset_iot_sample.csv`: archivo CSV con 100 filas de ejemplo.
- `metadata_dataset.json`: metadatos y notas sobre el dataset.

## Estructura de campos
{
  "timestamp": "ISO 8601 timestamp of reading",
  "device_id": "unique device identifier",
  "device_type": "device hardware type",
  "sensor_type": "type of measured sensor",
  "value": "sensor reading value",
  "unit": "measurement unit",
  "location": "logical location in simulated building",
  "vlan": "assigned VLAN for the device",
  "ip": "IP address used in simulation",
  "note": "free text note, e.g., anomalies"
}

## Licencia
CC-BY-4.0

## Cómo citar
Briel [Apellido]. (2025). dataset_iot_simulation_building_sensors (Version 1.0) [Dataset]. GitHub. https://github.com/<tu_usuario>/iot-security-dataset

## Notas
Datos de demostración; generados para reproducibilidad académica.
