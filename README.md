# Relevo de Competencia — Captura de Campo + Excel + Power BI

## Descripción

Proyecto de analítica comercial orientado a digitalizar el levantamiento de información de competencia en puntos de venta.

La solución integra un formulario web para supervisores, generación de reportes Excel y un dashboard desarrollado en Power BI.

## Flujo de la solución

```text
Supervisor
   ↓
Formulario HTML/CSS
   ↓
Registro del cuestionario
   ↓
Generación de Excel
   ↓
Envío / distribución por WhatsApp
   ↓
Base consolidada BD_RC
   ↓
Proceso ELT
   ↓
Power BI
   ↓
Dashboard de Relevo de Competencia
```

## Componentes

### 1. Formulario web

`formulario/index.html`

Aplicación web desarrollada con HTML, CSS y JavaScript.

Permite registrar:

- Punto de venta
- Supervisor
- Marcas competidoras
- Beneficios comerciales
- Personal de competencia
- Frecuencia de visitas
- Actividades
- Elementos de visibilidad
- Oportunidades comerciales
- Observaciones

El formulario también genera un archivo Excel con tres vistas de información:

- `PDV`
- `Por marca`
- `Visitas por rol`

### 2. Base de datos

`datos/DB_RC_PORTAFOLIO.xlsx`

Versión preparada para portafolio. Los datos son demostrativos y no representan información confidencial de una empresa real.

### 3. Dashboard

`powerbi/BI_Relevos.pbix`

Dashboard desarrollado en Power BI para analizar la información consolidada del relevo de competencia.

## Tecnologías

- HTML5
- CSS3
- JavaScript
- Excel
- Power BI
- Modelado y transformación de datos
- Procesos ELT

## Objetivo de negocio

Centralizar información de campo sobre la actividad de marcas competidoras y convertir los registros operativos en información útil para el análisis comercial.

## Nota de confidencialidad

Este repositorio utiliza información ficticia/demostrativa para fines de portafolio. No contiene datos oficiales de clientes, empresas, colaboradores ni información comercial confidencial.
