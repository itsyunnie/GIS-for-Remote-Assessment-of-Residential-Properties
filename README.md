# Affordable Housing Maintenance Detection Project

## Project Overview
Affordable housing is a pressing issue in Georgia, with maintenance being a significant challenge for homeowners and communities. This project leverages overhead imagery to identify homes requiring maintenance, focusing on roof conditions, to aid in timely repairs and prevent minor issues from escalating into major problems. By automating the detection of housing requiring maintenance, this project aims to assist government-funded home-repair programs and reduce labor costs associated with traditional housing surveys.

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
   1. **Roof Detection**: Identify the presence and location of roofs in images.
   2. **Roof Condition Classification**: Assess and categorize the condition of detected roofs.

## Contributing
Contributions to this project are welcome. Please review the guidelines before making a contribution.

## License
This project is licensed under the MIT License. Please see the LICENSE file for more details.

## Acknowledgments
Special thanks to all contributors and supporters of the affordable housing initiative, including local government bodies and community organizations in Georgia.

## Contact
For queries or collaboration inquiries, please open an issue in this repository or contact us directly at `contact@example.com`.
