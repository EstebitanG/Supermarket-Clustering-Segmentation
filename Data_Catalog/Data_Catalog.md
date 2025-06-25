# Diccionario de datos para proyecto de Clustering

Descripción General

Se detallan las columnas existentes en el dataset (customer_segmentation.csv), las cuales fueron procesadas para la aplicación posterior de algoritmos.

### customer_segmentation.csv

Propósito: almacena información sociodemográfica y de comportamiento de compra de clientes de un supermercado particular.

| Columna              | Tipo de Dato (Python) | Descripción |
|----------------------|-----------------------|-------------|
| Id                   | int64                 | Identificador único para cada individuo en el dataset. |
| Year_Birth           | int64                 | Año de nacimiento del individuo. |
| Education            | object                | Nivel educacional más alto alcanzado por el individuo. |
| Marital_Status       | object                | Estado civil del individuo. |
| Income               | float64               | Ingreso anual del individuo (en dólares). |
| Kidhome              | int64                 | Número de niños pequeños en el hogar. |
| Teenhome             | int64                 | Número de adolescentes en el hogar. |
| Dt_Customer          | object                | Fecha en que el cliente fue registrado en la base de datos de la compañía. |
| Recency              | int64                 | Días desde la última compra o interacción. |
| MntWines             | int64                 | Monto total gastado en vinos. |
| MntFruits            | int64                 | Monto total gastado en frutas. |
| MntMeatProducts      | int64                 | Monto total gastado en productos cárnicos. |
| MntFishProducts      | int64                 | Monto total gastado en productos del mar. |
| MntSweetProducts     | int64                 | Monto total gastado en productos dulces. |
| MntGoldProds         | int64                 | Monto total gastado en productos de oro. |
| NumDealsPurchases    | int64                 | Número de compras realizadas con descuento o promoción. |
| NumWebPurchases      | int64                 | Número de compras realizadas a través del sitio web. |
| NumCatalogPurchases  | int64                 | Número de compras realizadas mediante catálogos. |
| NumStorePurchases    | int64                 | Número de compras realizadas en tiendas físicas. |
| NumWebVisitsMonth    | int64                 | Número de visitas mensuales al sitio web. |
| AcceptedCmp3         | int64                 | Indicador binario: si aceptó la campaña de marketing 3. |
| AcceptedCmp4         | int64                 | Indicador binario: si aceptó la campaña de marketing 4. |
| AcceptedCmp5         | int64                 | Indicador binario: si aceptó la campaña de marketing 5. |
| AcceptedCmp1         | int64                 | Indicador binario: si aceptó la campaña de marketing 1. |
| AcceptedCmp2         | int64                 | Indicador binario: si aceptó la campaña de marketing 2. |
| Complain             | int64                 | Indicador binario: si el cliente ha realizado una queja. |
| Z_CostContact        | int64                 | Costo constante asociado al contacto con el cliente. |
| Z_Revenue            | int64                 | Ingreso constante asociado a una respuesta exitosa en campaña. |
| Response             | int64                 | Indicador binario: si respondió a la última campaña de marketing. |
