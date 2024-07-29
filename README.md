# AgriVision: A Way to Find Cultivatable Lands Using Satellite Imagery

AgriVision is a project aimed at identifying cultivatable land for agricultural needs using computer technology and image processing techniques. With the increasing population and demand for food, AgriVision serves as a starting point for further research and development in the field of agriculture and food production.

## Features
- Utilizes real-time satellite images and advanced image processing techniques to identify cultivatable land.
- Provides a user-friendly interface through an R Shiny app.
- Marks regions with greener areas as potential cultivatable land.
- Allows users to enter specific locations.
- Provides precise crop suitability and cultivatable land recommendations.

- ![image](https://github.com/user-attachments/assets/26bfafd0-abc8-4db1-9c4c-31659b2336c0)


## Application Interface
### App
The main interface where users can upload satellite images of the land to be processed and view the results.

![image](https://github.com/user-attachments/assets/4ddb7900-1611-44d9-9456-3ff3f72abdb8)


### About
The about page of the app provides a brief description of the project and the team members.



### Map
A user-controlled map that opens when the user presses "Open Map". Users can zoom in and out, take snapshots of the map, and find cultivatable lands in acres. For accurate measurements, zoom in up to 126 yards and then take the snapshot.

![image](https://github.com/user-attachments/assets/c4914dc6-8f0e-45be-98ed-e22e241d30ee)

### Result
Displays the green areas segregated visually as a plot within the app interface.

![image](https://github.com/user-attachments/assets/cceb6c69-cf6a-4936-aa6f-39c4be67f465)

![image](https://github.com/user-attachments/assets/e2658d04-44af-4620-a209-65fe10b3bf32)



### Console
Shows the output of the image processing, including the area in acres. It also displays the output of the "migrate" button, which moves screenshots saved in a default folder to the project's folder for the program to read.

![image](https://github.com/user-attachments/assets/cd503500-8492-4f56-83c0-53e0f2a98bc1)


### Outputs
- **Output 1**: Shows the results after feeding in the attributes to the GPT-4 model.
- **Output 2**: Shows additional processed results.

- ![image](https://github.com/user-attachments/assets/37756a06-95d4-45d0-a465-52088dada4ee)

- ![image](https://github.com/user-attachments/assets/7f374443-542b-4329-b18c-00288e7f6827)



## Getting Started
To get started with AgriVision, follow these steps:

1. Clone the repository.
2. Install the necessary dependencies.
3. Run the `app.R` file.
4. Upload the satellite image of the land to be processed.
5. View the processed images and the mapped cultivatable land.
6. Enter location, find details, and refresh the page.
7. View the location-specific details and attributes.

## Usage
AgriVision can be used to identify and map cultivatable land for agricultural needs. The results obtained from the image processing techniques can help farmers and agricultural organizations make informed decisions, contributing to the growth and development of the agriculture sector.

## Conclusion
AgriVision is a step forward in meeting the increasing demand for food. By bridging the gap between modern technology and agriculture, this project paves the way for a sustainable and self-sufficient future.

**"Empowering agriculture with technology for a sustainable future."**



## Requirements
- R
- Shiny
- Required R packages (listed in the `DESCRIPTION` file)

## Installation
```sh
# Clone the repository
git clone https://github.com/Raghu-2005/AgriVision_AI.git

# Navigate to the project directory
cd AgriVision_AI

# Install dependencies
# Make sure you have R and required packages installed
