# Práctica Calificada: Estadística Espacial - QGIS

Este repositorio contiene las evidencias de la evaluación práctica del curso de Estadística Espacial, fundamentado en los conceptos teóricos del **Capítulo 1.1: Datos Vectoriales y Raster (Fred Torres-Cruz)**.

## 1. Evidencia de Instalación de QGIS
Se ha instalado con éxito la versión **QGIS 3.44 LTR (Long Term Release)**, recomendada para garantizar la estabilidad en la integración de procesos geoespaciales y estadísticas zonales.
* [Ver captura de instalación de QGIS](evidencias/1_instalacion_qgis.png)

## 2. Modelo Espacial Raster
Siguiendo la teoría de que *el modelo raster representa variaciones continuas en el espacio mediante una matriz regular de celdas*, se adjunta un Modelo Digital de Elevación (DEM) de la zona de Puno.
* **Archivo:** `capas/capa_raster_elevacion.asc`
* [Ver evidencia de la capa Raster cargada en QGIS](evidencias/2_capa_raster.png)

## 3. Modelo Espacial Vectorial
De acuerdo con la literatura, *el modelo vectorial es idóneo para representar objetos discretos con límites definidos*. Se ha elaborado una capa de polígonos correspondiente a provincias de Puno, incluyendo una tabla de atributos con variables socio-demográficas (Población y Superficie).
* **Archivo:** `capas/capa_vectorial_puno.geojson`
* [Ver evidencia de la capa Vectorial cargada en QGIS](evidencias/3_capa_vectorial.png)

---
*Trabajo elaborado para la evaluación de Estadística Espacial.*
