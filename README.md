# Sistema de Facturación Telefónica

## Diseño
Para el cálculo de costos se utilizó el patrón de diseño **Strategy**.

La clase `Llamada` no calcula directamente su costo, sino que delega esa responsabilidad a un objeto `Tarifa`. De esta manera, cada tipo de tarifa implementa su propia lógica de cálculo:

- `TarifaLocal`
- `TarifaNacional`
- `TarifaInternacional`

## Clases principales

- `Cliente`
- `Llamada`
- `Factura`
- `Tarifa`
- `TarifaLocal`
- `TarifaNacional`
- `TarifaInternacional`

## Ejecución

Importar el archivo `.st`
