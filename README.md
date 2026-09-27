# From Sketches to UML

This repository is the official companion for the research paper on using **Multimodal Large Language Models (MM-LLMs)** to generate **UML class models** from images of hand-drawn or digital class diagrams.

## Repository Contents

* **`*.jpg`**: A collection of public domain images representing various UML class diagrams used as test cases in the paper's experiments and evaluations.
* **`prompt_class_models_from_images.txt`**: The prompt template utilized by the MM-LLMs evaluated in the paper to interpret diagram images and construct corresponding UML class models.

## Overview

The goal of this research is to evaluate the capability of modern MM-LLMs to bridge the gap between visual software architectural sketches and formal software models. By leveraging multimodal vision-language understanding, the models process input images (`*.jpg`) alongside structured instructions (`prompt_class_models_from_images.txt`) to extract classes, attributes, methods, and relationships.

## License & Usage

* The image dataset (`*.jpg`) consists of public domain resources and is freely available for benchmarking and further research.
* Please cite the associated paper if you use these prompt templates or dataset images in your own research.