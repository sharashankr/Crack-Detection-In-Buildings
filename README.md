# Crack-Detection-In-Buildings
Crack detection plays a critical role in structural health monitoring and building inspections, as early identification of cracks can prevent potential failures and costly repairs. It ensures the safety and longevity of structures by enabling timely maintenance, reducing risks, and enhancing the overall reliability of buildings and infrastructure.

## Overview

We will work with a **binary classification** problem, consisting of two classes:

- **Images of Cracked Concrete**  
- **Images of Concrete with No Cracks** (`y = 0`)

The dataset includes a total of **40,000 RGB (color) images**, divided as follows:

- **20,000 images with cracks** (positives)
- **20,000 images without cracks** (negatives)

### Dataset Split

- **75%** of the images will be used for **training**.
- **25%** of the images will be used for **validation**.

### Dataset Challenges

- Cracks may be confused with noise in the background texture or foreign objects.
- Inhomogeneous illumination and irregularities, such as exposure of jointing, can complicate crack detection.
