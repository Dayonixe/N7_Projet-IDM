# Projet IDM

Team : Quentin G. & Théo Pirouelle

<img src="https://img.shields.io/badge/language-eCore-474a6d?style=flat-square" alt="laguage-eCore" /> <img src="https://img.shields.io/badge/language-OCL-c8e165?style=flat-square" alt="laguage-OCL" /> <img src="https://img.shields.io/badge/language-Xtext-7f769d?style=flat-square" alt="laguage-Xtext" />
<img src="https://img.shields.io/badge/language-Sirius-e6815d?style=flat-square" alt="laguage-Sirius" /> <img src="https://img.shields.io/badge/language-Java-yellow?style=flat-square" alt="laguage-Java" /> <img src="https://img.shields.io/badge/language-ATL-5c389a?style=flat-square" alt="laguage-ATL" /> <img src="https://img.shields.io/badge/language-Acceleo-56c5ab?style=flat-square" alt="laguage-Acceleo" />

<img src="https://projects.laas.fr/tina/images/tina.png" alt="Tina" width="71" /> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Eclipse-Luna-Logo.svg/2560px-Eclipse-Luna-Logo.svg.png" alt="eclispe" width="300" />

---

This mini-project consists in producing a verification chain of process models SimplePDL in order to check their consistency, in particular to know if the process described can be terminated or not. To answer this question, we use the model-checking tools defined on Petri nets through the Tina toolbox. We will translate a process model into a Petri net.

The main steps are the following:
1. Definition of the metamodels with `Ecore`
2. Definition of the static semantics with `OCL`
3. Use of the infrastructure provided by `EMF` to manipulate the models
4. Definition of concrete textual syntaxes with `Xtext`
5. Definition of graphical concrete syntaxes with `Sirius`
6. Definition of a model-to-model transformation (M2M) with `Java` and with `ATL`
7. Definition of model-to-text transformations (M2T) with `Acceleo`

For this project, we use various tools such as the [Tina toolbox](https://projects.laas.fr/tina/index.php) or the [Eclispe Modeling Project](https://www.eclipse.org/modeling/) IDE (Eclipse version with modeling tools).

---

Download links :
- [Eclispe Modeling Project](https://www.eclipse.org/downloads/packages/release/2022-03/r/eclipse-modeling-tools)
- [Tina toolbox](https://projects.laas.fr/tina/download.php)
