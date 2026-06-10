# Smart Deconstruction Digital Twin

This repository supports the Master's Thesis project focused on intelligent selective deconstruction using UAV photogrammetry, YOLO-based computer vision, digital twins and robotic simulation in CoppeliaSim.

The original reference case study of the project is an abandoned and unfinished building located in Atalaya Dorada, La Oliva, Fuerteventura (Canary Islands, Spain). This site was used as the conceptual and territorial reference case for the methodological framework developed in the thesis.

However, due to access, safety and operational limitations associated with the original building, the preliminary experimental validation was carried out using a smaller-scale analogous building located in Abades, Tenerife (Canary Islands, Spain), approximately at coordinates 28°08'42.6"N, 16°26'50.6"W.

The Abades building was selected because it presents similar constructive and operational characteristics: an unfinished reinforced concrete structure, exposed columns and slabs, open voids, visible reinforcement bars and absence of complete enclosures. Therefore, it provides a suitable real-world scenario to test the proposed workflow under accessible and controlled conditions.

## Repository structure

- `dataset/`: preliminary image dataset and YOLO annotations.
- `photogrammetry/`: 3D reconstruction resources and simplified building models.
- `simulation/`: CoppeliaSim scenes, robot models and UAV simulation resources.
- `yolo/`: YOLO configuration files and training/inference scripts.
- `docs/`: methodological diagrams and technical documentation.
- `results/`: preliminary results, figures and screenshots.
- `annex/`: complementary material related to the experimental validation.

## Research scope

The repository contains complementary technical material associated with:
- UAV-based data acquisition
- Photogrammetric reconstruction
- Preliminary YOLO validation
- Risk identification
- Robotic simulation
- Digital twin generation
- Smart selective deconstruction workflows

## Experimental validation

The preliminary experimental validation is based on a visual dataset composed of 106 images captured from the analogous building located in Abades, Tenerife.

These images document general views of the structure, façades, columns, slabs, open voids, exposed reinforcement bars, accessible interior areas, degraded zones and potential risk points. The purpose of this dataset is not to replace a certified structural inspection, but to provide a visual basis for testing the applicability of the proposed methodological workflow.

The dataset is intended to support future phases related to:

- Preliminary photogrammetric reconstruction;
- YOLO image annotation and object detection;
- Identification of visible construction elements and risk areas;
- Digital twin generation;
- Robotic simulation in CoppeliaSim;
- Technical traceability and reproducibility of the workflow.

## Purpose

The objective of this repository is to improve the technical traceability and reproducibility of the proposed workflow for smart selective deconstruction within Construction 4.0, Industry 5.0 and circular economy environments.

The repository should be understood as complementary technical material associated with the Master's Thesis. It provides supporting resources for the methodological proof of concept, while the full academic justification, methodology and discussion are developed in the written thesis document.
