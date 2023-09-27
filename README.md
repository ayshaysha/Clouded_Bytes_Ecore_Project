# Modeling Data-Oriented Web Pages: An Exploration using Ecore
## An Ecore Modeling representation of my blog website CloudedBytes.com

# Overview

This repository encapsulates the work completed as part of our exploration into modeling data-oriented web pages. Using the Eclipse Modeling Framework (EMF) and Ecore, I have developed a metamodel that abstracts and represents the structure and relationships inherent in the chosen webpage.

# Web Page under Study

I have selected [CloudedBytes.com](https://cloudedbytes.com/) as the data-oriented web page for this study. CloudedBytes is a tech blog platform rich with varied structures such as articles, categories, authors, comments, and more. This balanced complexity provides an excellent foundation for developing a nuanced Ecore metamodel.

# Assignment Objectives

The main objectives of this assignment were to:

1. Understand the intrinsic structures within a data-oriented web page.
2. Develop an Ecore metamodel capturing the essential domain concepts while avoiding redundancy.
3. Ensure the metamodel does not mirror the visual structure of the web page.
4. Generate corresponding Java code from the Ecore metamodel.
5. Integrate non-trivial constraints and derived features to further refine the model.

# Structure of the Repository

1. Ecore Model: Located in "CloudedBytes\model\cloudedBytes.ecore", this file represents the high-level structure and relationships identified in the CloudedBytes web page.
2. Generated Java Code: The Java classes generated from the Ecore model can be found at "CloudedBytes\src\cloudedBytes". This code serves as the backbone for potential applications or further research based on the model.
3. Instances: Representative instances that demonstrate the applicability and flexibility of the metamodel can be found in "CloudedBytes\model\Dynamic Instances".
4. Screenshots: For a visual comparison, I've included screenshots of CloudedBytes, highlighting the areas under study. Check them out in the Screenshots folder at path "CloudedBytes\model\Dynamic Instances\Screenshots".

# Class Diagram

![cloudedBytes](https://github.com/ayshaysha/Clouded_Bytes_Ecore_Project/assets/49022953/60efca70-1368-4218-98f3-e8cdd8e9fd85)

# Conclusion
This project serves as a testament to the power of model-driven engineering in dissecting and understanding complex data structures inherent in modern web platforms. Our study of CloudedBytes offers insights not just into the domain of blogs but extends into the broader realm of web content management and delivery.


