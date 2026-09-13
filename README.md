# Servicios de computación en la nube

Presentación interactiva de la actividad 1.4 de **IH745 Optativa V** (Unidad 1, Actividad 4).
Licenciatura en Desarrollo de Sistemas Web, Universidad de Guadalajara. Asesora: Nancy Ruiz Monroy.

**Autor:** Hiram Agustín Acevedo López
**Fecha de la actividad:** 12 de septiembre de 2026

## Abrir la presentación

**https://hiramacevedo.github.io/ih745-1-4-servicios-nube/**

Se navega con las flechas del teclado o tocando los bordes. Con `Esc` se ve el mapa completo.
El menú de la diapositiva 6 salta a cada marca; dentro de cada marca, la flecha hacia abajo
recorre sus tres diapositivas y la barra superior cambia de marca o regresa al menú.

## Qué compara

Tres marcas de computación en la nube, AWS, Google Cloud y Microsoft Azure, bajo los tres
criterios que pide la actividad, para sus servicios de Big data, bases de datos y tableros:

| Marca | Big data | Base de datos | Tablero |
|---|---|---|---|
| AWS | Amazon Redshift | Amazon RDS for PostgreSQL | Amazon Quick Sight |
| Google Cloud | BigQuery | Cloud SQL for PostgreSQL | Looker Studio |
| Microsoft Azure | Microsoft Fabric | Azure SQL Database | Power BI |

- **a. Costos:** precio oficial de cada servicio, consultado el 12 de septiembre de 2026, en la
  región base de Estados Unidos de cada marca y, donde la página lo muestra, en la región de
  México. Conversión a pesos con el FIX de Banxico del 11 de septiembre de 2026 (16.9707 MXN por USD).
- **b. Interoperabilidad con otras tecnologías:** formatos y estándares abiertos, conectores y
  drivers, y fuentes externas que se consultan sin mover datos, ordenados con los cuatro casos
  de uso de interoperabilidad de Chopra (2017).
- **c. Hardware mínimo:** en dos niveles, el cliente que pone el usuario (navegador y conexión)
  y la instancia mínima que reserva el proveedor.

El marco conceptual sale de los capítulos 1 y 2 de Chopra, R. (2017), *Cloud computing: An
introduction*, Mercury Learning and Information.

## Estructura de la presentación

1. Portada
2. Qué se compara y cómo se navega
3. La nube según Chopra: elástica y cobrada por uso
4. Modelos de servicio: dónde cae cada producto
5. Interoperabilidad y hardware: cómo se leen los criterios b y c
6. Menú de marcas
7. AWS: qué ofrece, los tres criterios (pestañas), captura real de la página de precios
8. Google Cloud: qué ofrece, los tres criterios (pestañas), captura real de la página de precios
9. Microsoft Azure: qué ofrece, los tres criterios (pestañas), captura real de la página de precios
10. Las tres marcas en una matriz, con filtro "sólo donde difieren"
11. Decisor de tres preguntas que recomienda una marca
12. Conclusión
13. Referencias en APA 7

## Cómo está hecha

- HTML con [reveal.js](https://revealjs.com/) 5.1.0, sin proceso de construcción: `index.html` y la carpeta `assets/`.
- Tipografías Bodoni Moda, IBM Plex Sans y JetBrains Mono desde Google Fonts.
- Las capturas de `assets/` son de las páginas oficiales de precios, tomadas el 12 de septiembre de 2026.
- Los logos de las marcas provienen de los sitios de cada fabricante y se usan de forma nominativa dentro de un trabajo escolar.

## Referencias

Todas las fuentes están en la última diapositiva. Las principales:

- Chopra, R. (2017). *Cloud computing: An introduction*. Mercury Learning and Information.
- Amazon Web Services. (2026). Páginas oficiales de precios y documentación de Amazon Redshift, Amazon RDS y Amazon Quick Sight.
- Google Cloud. (2026). Páginas oficiales de precios y documentación de BigQuery, Cloud SQL y Looker Studio.
- Microsoft. (2026). Páginas oficiales de precios y Microsoft Learn de Microsoft Fabric, Azure SQL Database y Power BI.
- Banco de México. (2026). Tipos de cambio y resultados históricos de las subastas. https://www.banxico.org.mx/tipcamb/tipCamMIAction.do
