# Remote Assessment of Residential Properties for Maintenance and Repair Needs Using Satellite Image Analysis: A Case Study in Fulton County, GA

## Problem Statement and Objectives
Affordable housing is a critical issue in Georgia, with maintenance being a significant challenge for homeowners and communities. Timely repairs and upkeep are vital to prevent minor issues from escalating into untenable living conditions and financial burdens. There are existing government-funded home-repair programs in Georgia such as zero-interest loans and homeowner services, but it has been a challenge for local government workers to identify individual broken or abandoned houses due to a lack of data. Traditionally, housing surveys are done by city officials physically driving around the streets and recording housing conditions; however, this method faced high labor costs considering the need to maintain updated information/data on the rapid changes in housing conditions. 

This project proposes a novel approach to identifying homes that may require maintenance through the use of overhead imagery. By analyzing images of homes, particularly focusing on roof conditions, we aim to develop a predictive model that can serve as an early warning system for necessary repairs.

## Getting Started

### Prerequisites
You should have access to Python and relevant libraries such as TensorFlow or PyTorch, OpenCV, NumPy, Pandas, and Matplotlib. Additionally, access to overhead imagery of Fulton County, GA, is required for analysis.

## Project Parts

### 1. Tax Parcel Image Preparation
This section involves preparing images of individual tax parcels for analysis:
- **DataPreprocessing.ipynb**: A Jupyter notebook for initial data preparation and cleaning.
- **FindSaveImages.ipynb**: A Jupyter notebook dedicated to extracting and saving high-resolution images for each tax parcel in Fulton County, GA.

### 2. Database Creation
Create a database containing the highest resolution images available for all tax parcels in Fulton County, GA, ensuring data is ready for analysis.

### 3. Housing Condition Assessment
Develop a predictive model to assess housing conditions, with a focus on roof analysis, using overhead imagery:
- **RoofAnalysis.ipynb**: Includes two primary steps:
   1. **Roof Detection**: Identify the presence and location of roofs in images by using Roboflow platform. You can call Roboflow API and use the model we trained.
 
 
## Contact
For queries or collaboration inquiries, please open an issue in this repository or contact us directly at `contact@example.com`.
