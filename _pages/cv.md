---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Ph.D Candidate in Mechanical Engineering, Duke University, 2025 (expected)
* B.S. in Aerospace Engineering, North Carolina State University, 2020

## Thesis Research

* Partnered with Sandia National Laboratories to perform research on high-speed ductile fracture
  * A corner stone is the combination of phase-field with a thermo-mechanical solve that captures shear failure in a thermo-dynamically consistent fashion
  * Key techniques used:
    * Finite element methods
    * Variational framework development
    * C++ framework development
    * Parallel computing
* As a part of this research, I currently maintain RACCOON, a phase-field framework build upon the MOOSE framework built by the Dolbow lab at Duke University
  * Doing so involves:
    * Adding in new physics
    * Resolving issues
    * Keeping the repository up to date with the shifting requirement of the MOOSE framework

## Graduate Work experience

* 2024-2024 Intern, Idaho National Laboratory, Idaho Falls, ID
  * Worked in the CMDT (Computational Materials Design Team)
    * Made improvements to the solid mechanics module of the MOOSE framework
      * Fixed issues with current explicit contact implementation
      * Pushed improvements to the central difference time integrator
      * Created an improved implementation of explicit contact

## Undergraduate Work experience

* 2019-2020 Undergraduate Researcher, North Carolina State University, NC
  * Performed research in structural engineering under Dr. Landon Grace
    * Assisted in the testing and fabrication of deployable carbon fiber space booms
    * Conducted layups and refinement of boom samples
* 2018-2018 Intern, NASA John C. Stennis Space Center, MS
  * Worked at Stennis Space Center under the mentorship of Robert Gargiulo
    * Assisted the Safety and Mission Assurance team with the updating of their fault tree documents
    * Supported safety personnel during walk downs of testing structures by assisting in document verification
* 2018-2018 Lab Assistance, North Carolina State University, Raleigh, NC
  * Performed research in Bio-molecular engineering under Dr. Ruben Carbonell
    * Investigated novel approaches to purifying the enzyme Butyrycholinesterase (BChE)
    * Performed peptide synthesis, binding studies, and protein assays
* 2016-2017 Intern, North Carolina State University, Raleigh, NC
  * Performed research in computational chemistry under Dr. Elena Jakubikova
    * Conducted independent research on dye complexes with applications in solar energy capture
    * Gathered and processed data on dye complex configurations
    * Work published in *Chemical Science*

<!-- ## Skills

* Skill 1
* Skill 2
  *
  *
  *
* Skill 3 -->

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Graduate Classes

| Class Name                        | Date Taken  | Grade | Description                                                                        |
| --------------------------------- | ----------- | ----- | ---------------------------------------------------------------------------------- |
| Finite Element Methods            | Sprint 2020 | A-    | Introductory course to linear finite element methods                               |
| Continuum Mechanics               | Spring 2020 | A     | Introductory course to continuum methods                                           |
| Partial Differential Equations    | Fall 2020   | B-    | Course covering techniques for solving PDE's analytically                          |
| Intro to Programming              | Spring 2021 | B+    | Introductory course to C/C++ and object oriented programming                       |
| Non Linear Finite Element Methods | Spring 2021 | A     | Course covering methods for solving non-linear systems with finite element methods |
| Mathematical Modeling             | Spring 2021 | B+    | Course covering popular methods for approximating PDE's                            |
| Intermediate Dynamics             | Fall 2021   | A     | Course covering dynamics of very high dimensional systems                          |
| Plasticity                        | Fall 2021   | A     | Introductory course to material plasticity                                         |
| Fracture Mechanics                | Fall 2022   | A     | A course covering methods for representing fracture                                |
| Parallel Computing                | Spring 2024 | A-    | An introductory course to parallel computing                                       |
