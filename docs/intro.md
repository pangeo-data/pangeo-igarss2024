---
# File metadata may be provided as frontmatter YAML
title: Earthly marvels revealed - Pangeo, AI, and Copernicus in action
subtitle: IGARSS 2024
description: this tutorial will provide a comprehensive introduction along with hands-on examples to help you understand how these technologies can be used for Earth science data analysis and interpretation.
date: 2024-04-09
authors:
  - id: annefou
    name: Anne Fouilloux
    orcid: 0000-0002-1784-2920
    corresponding: false
    roles:
      - Pangeo
    affiliations:
      - simula
  - id: tinaok
    name: Tina Erica Odaka
    orcid: 0000-0002-1500-0156
    corresponding: false
    roles:
      - Pangeo
    affiliations:
      - ifremer
affiliations:
  - id: simula
    name: Simula Research Laboratory
    city: Oslo
    country: Norway
    url: https://www.simula.no
    ror: https://ror.org/00vn06n10
  - id: ifremer
    name: IFREMER
    city: Brest
    country: France
    url: https://www.ifremer.fr
    ror: https://ror.org/044jxhp58
tags:
  - pangeo
  - copernicus
  - AI
  - machine-learning
thumbnail: images/pangeo-logo.png
---

#  Earthly marvels revealed: Pangeo, AI, and Copernicus in action 

+++ {"part":"abstract"}

% The article should include an abstract block at the beginning. The block is delimited by `+++` before and after, and you must specify `"part": "abstract"` as JSON metadata on the block opener. This metadata is required for recognizing the content of this cell as the abstract.
% The abstract should begin with a short description of the problem addressed, briefly describe the new data or analyses, then briefly state the main conclusion(s) and how they are supported, and address any uncertainty.

This tutorial is created in collaboration with European Pangeo community and [Horizon Europe EO4EU projec](https://www.eo4eu.eu) community for a tutorial session of [2024 IEEE International Geoscience and Remote Sensing Symposium](https://www.2024.ieeeigarss.org/tutorials.php#tut8).  


This tutorial will provide a comprehensive introduction along with hands-on examples to help you understand how these technologies can be used for Earth science data analysis and interpretation.

+++


# Time, Location and registration. 
The tutorial will be at **Sun, 7 Jul, 12:30 - 15:30 Greece Time (UTC +3)**
The room assigned to the tutorial is **MC 3.4**
To particpate this tutorial, please register at [IGARSS 2024 Registration site](https://www.2024.ieeeigarss.org/registration.php). There will be no 


# Overview 
In this tutorial, participants will learn how to 1) navigate the Pangeo ecosystem for scalable Earth Science workflows and 2) exploit Earth Observation (EO) data, and in particular from Copernicus, with Artificial Intelligence (AI) using open and reproducible tools and methodologies from Horizon Europe EO4EU project, the Pangeo community, and other open source projects that leverage the Pangeo ecosystem. Participants will gain practical experience in leveraging AI techniques on Copernicus datasets through hands-on sessions. By the end of this tutorial, participants will possess the skills and knowledge needed to harness the power of AI for transformative EO applications using the Pangeo ML e.g. xbatcher and zen3geo and other advanced packages handling EO data based on the Pangeo stack for ML/AI, e.g. DeepSensor. Participants will also be introduced to some computer vision foundation models hosted on the EO4EU platform, learn how to prepare earth observation data, prompt these models to perform segmentation and object detection tasks and visualise the obtained results using visualisation and GIS tools.

By the end of this tutorial, participants will possess the skills and knowledge needed to harness the power of AI for transformative EO applications using the Pangeo ML ecosystem and EO4EU platform. All the training material will be collaboratively developed and made available online with CC-BY-4 licence. To facilitate user on-boarding the Pangeo@EOSC platform will be made available to participants. However, all the information needed to set up and run the training material on different platforms will be provided too. This tutorial will provide a comprehensive introduction along with hands-on examples to help you understand how these technologies can be used for Earth science data analysis and interpretation.

## Tutorial Learning Objectives

By the end of this tutorial, learners will be able to:

- Understand the Pangeo ecosystem
- Learn to access, load, and analyse data using Xarray, visualising data with Hvplot, and scaling ML workflows with Dask.
- Learn to exploit and combine Pangeo tools, methodologies and services to create complex and efficient EO workflows.
- Learn about the EO4EU platform.
- Computer vision foundation model hands-on.
- Learn to use the EO4EU Knowledge Graph tools to discover and use EO data.

## Prerequisites

Before starting this tutorial, learners should have:

- Basic knowledge of Python or another programming language;
- Basic knowledge of geospatial data structures;
- Basic knowledge of Earth Observation concepts like Copernicus offer and structure;
- Prior exposure to AI concepts and tools is recommended.

## Set up

If you are participating in this training as part of the IGARSS 2024 Conference, you will be provided access to [Pangeo@EOSC](https://pangeo-data.github.io/pangeo-eosc/) through a training user identifier and corresponding credentials during the course. If you wish to continue using the Pangeo@EOSC infrastructure after the course ends, please register yourself following the instructions given at [getting started for users](https://pangeo-data.github.io/pangeo-eosc/users/users-getting-started.html).
