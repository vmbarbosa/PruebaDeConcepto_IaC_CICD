# PruebaDeConcepto_IaC_CICD

![GitHub contributors](https://img.shields.io/github/contributors/vmbarbosa/FinalProjectFrotendCourse?style=flat-square)
![GitHub Languages](https://img.shields.io/github/languages/count/vmbarbosa/FinalProjectFrotendCourse?style=flat-square)
![GitHub Pull Request](https://img.shields.io/github/issues-pr/vmbarbosa/FinalProjectFrotendCourse?style=flat-square)
![GitHub Commit Activity](https://img.shields.io/github/commit-activity/w/vmbarbosa/FinalProjectFrotendCourse?style=flat-square)

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#requirements">Requirements</a>
      <ul>
        <li><a href="#extra points">Extra points</a></li>
      </ul>
    </li>
    <li><a href="#solution">Solution</a>
      <ul>
        <li><a href="#technologies">Technologies</a></li>
        <li><a href="#diagrams">Diagrams</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project:

El área de operaciones de una compañía requiere construir un modelo de Automatización de CI/CD para sus scripts de infraestructura como código, actualmente almacenan sus códigos en Github y están dispuestos a construir sus pipelines sobre cualquier herramienta.

Deberás construir una prueba de concepto (POC) con la solución diseñada para que el equipo pueda decidir.

## Requirements:

* Pasos definidos y su explicación.

* Buenas prácticas en la POC, todos los pipelines o pipeline como código.

* Buenas prácticas en la herramienta seleccionada para "infra as code".

* Buen uso del repositorio de código fuente.

* Creación de un video explicativo (no gastar mucho tiempo en la edición).


### Extra points
  * [x] Hacer la POC para una arquitectura montada sobre AWS
  * [x] Una VPC AWS
  * [x] Tres Subnets.
  * [x] Una máquina EC2 sobre la subnet privada
  * [x] Una máquina EC2 sobre la subnet pública 
  * [x] Una RDS sobre la otra subnet privada

## Solution

### Technologies

* **Pipeline Tool:** *Github Actions*
* **Cloud:** *Amazon Web Services (AWS)*
* **Infraestructure As Code:** *AWS Cloudformation Templates*

### Diagrams

#### Principal Stack
* Link image: https://drive.google.com/uc?export=view&id=14z_I67eBcfYXDxNgoGiNspKdM8QYx2oA

#### VPC Stack
* Link image: https://drive.google.com/uc?export=view&id=1zsJp1QzNq9vVYZTpydSifdHj3bCgaFL4

#### EC2 Public Instance Stack
* Link image: https://drive.google.com/uc?export=view&id=1Id5m1Vly0ZAC0kIKaczcqpiGxoYFClMm

#### EC2 Private Instance Stack
* Link image: https://drive.google.com/uc?export=view&id=1h4I-iHKjgQvVD1lpKvVTkyPMffPQDz1w

#### RDS Stack
* Link image: https://drive.google.com/uc?export=view&id=1-caHUDlAIDZz6l30XSf8w3fs2UQpc8du

## Contact

* [Victor Barbosa](https://github.com/vmbarbosa) | victormp2@gmail.com | +57 3008346619 