# Braço Robótico com ESP32 / ESP32 Robotic Arm

> Projeto de TCC desenvolvido no curso técnico em Eletrônica, utilizando ESP32, módulo PCA9685, servos motores e interface web para controle de um braço robótico.

> Final technical course project: robotic arm controlled by ESP32, PCA9685 module, servo motors and a web-based control interface.

---

## Equipe do Projeto / Project Team

Projeto desenvolvido como Trabalho de Conclusão de Curso do curso técnico em Eletrônica da ETEC Philadelpho Gouvêa Netto.

Project developed as a final technical course project for the Electronics Technical Program at ETEC Philadelpho Gouvêa Netto.

### Integrantes / Team members

* **Pedro Evangelista**
* **Pedro Bevilaqua**
* **Marcelo Henrique**

---

## Sobre o projeto / About the project

Este repositório contém os arquivos de um braço robótico de baixo custo, desenvolvido em equipe como Trabalho de Conclusão de Curso. O sistema utiliza um ESP32 como controlador principal, um módulo PCA9685 para controle dos servos motores e uma interface web para movimentação do braço.

This repository contains the files of a low-cost robotic arm developed by a team as a final technical course project. The system uses an ESP32 as the main controller, a PCA9685 module to control the servo motors, and a web interface for robotic arm movement.

---

## Galeria do Projeto / Project Gallery
Algumas imagens do desenvolvimento, montagem, testes e sua a estrutura final do braço robótico abaixo.

Some images of the development process, assembly, tests and final structure of the robotic arm are shown below.

| Image 01 | Image 03 | Image 07 |
|---|---|---|
| <img src="images/IMG_0020-%20editada.jpg" alt="Project image 01" width="250"> | <img src="images/IMG_1122-%20editada.jpg" alt="Project image 03" width="250"> | <img src="images/IMG_1550-%20editada.jpg" alt="Project image 07" width="250"> |

| Image 10 | Image 15 | Image 17 |
|---|---|---|
| <img src="images/IMG_2575-%20editada.jpg" alt="Project image 10" width="250"> | <img src="images/IMG_2582-%20editada.jpg" alt="Project image 15" width="250"> | <img src="images/IMG_2592-%20editada.jpg" alt="Project image 17" width="250"> |

## Componentes / Components

- ESP32 DevKit
- PCA9685 16-channel module
- MG995 servo motors
- SG90 servo motor for the gripper
- ESP32-CAM
- HTML, CSS and JavaScript
- Arduino IDE

---

## Licenses and Credits

The source code and documentation developed specifically for this project are licensed under the MIT License.

The 3D models used as the basis for the mechanical structure of this robotic arm were obtained from Thingiverse and belong to their original author:

**ESP32 BT Robotic Arm with High Torque Servos + Android App**  
Author: DavTech_3D  
Source: https://www.thingiverse.com/thing:6896222  
Original license: Creative Commons - Attribution - Share Alike

These 3D models were used as a base/reference for the physical construction of the prototype. Any adaptations made were intended to fit the requirements of this final technical course project.

The MIT License in this repository applies only to the source code and original documentation developed for this project. The 3D models follow the license defined by their original author.

## Estrutura do repositório / Repository Structure

```text
article/        Final article about the developing of this project
firmware/       ESP32 and ESP32-CAM source-code
images/         Photos from the development and testing
modelos-3d/     3D files
schmatics/      Circuits and diagrams

