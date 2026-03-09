# LEGO-Vision-Real-Time-Image-to-Brick-Reconstruction
Developed a Python-based computer vision system for COMP 4423 Computer Vision course that transforms live camera feeds into stylized LEGO mosaics. The project focuses on the full engineering pipeline: from real-world image acquisition to algorithmic brick-mapping and inventory generation.

## Project Overview

The core task was to build a generation system that approximates a real-world scene using a combination of LEGO bricks. The project emphasizes sound engineering and practical problem-solving over absolute visual perfection.

## Core Functionality

* **Camera Integration:** The system interfaces with the local camera to capture real-time images for processing.


* **Constrained Processing:** Images are converted into a LEGO-style format using a grid limited to $100\times100$ bricks.


* **Multi-Size Brick Logic:** The implementation supports various brick dimensions (e.g., $1\times1$, $1\times2$, $2\times4$) to visually approximate the source image.


* **Inventory Reporting:** The program generates a summary detailing the total number of bricks and a specific count for each brick type used.



## Real-World Testing and Problem Solving

A major component of this project involved testing the algorithm in a real-world scenario to identify and solve practical issues. Key areas of focus included:

* **Algorithm Refinement:** Developing a clearly justified pipeline for converting pixels into brick data.


* **Handling Environmental Factors:** Identifying problems encountered during camera capture and finding corresponding solutions to improve the output.


* **Human-AI Collaboration:** The foundational implementation was developed in collaboration with Generative AI, followed by manual modifications to ensure the system functioned correctly in practice.



## Repository Structure

* **`Assignment1.ipynb`**: The Python notebook containing the image processing logic and camera interface.


* **`Assignment1_Report.pdf`**: A technical report documenting the design process, algorithm logic, and findings.
