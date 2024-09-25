# Medical Image Annotation Job - Pneumonia Detection

## Project Goal
My goal for this project was to build a product that could help doctors quickly identify cases of pneumonia (الالتهاب الرئوي) in children. To achieve this, I decided to create a classification system that could:

1. Help flag serious cases of pneumonia
2. Quickly identify healthy cases 
3. Act as a diagnostic aid for doctors

I needed to create a labeled dataset that distinguished between healthy and pneumonia X-ray images to build this classification system. Machine learning engineers would use this dataset to develop the final classification product.

## The Dataset
The dataset for this project was a modified version of the [Kaggle chest x-ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). The dataset contained chest X-ray images, with most labels removed. I needed to design a data labeling job using Appen's platform to annotate the images as: 

- Healthy - Normal x-rays with no pneumonia signs
- Pneumonia - X-rays clearly show pneumonia
- Uncertain - Ambiguous cases, not healthy or pneumonia

## Data Labeling Job Design
To design the data labeling job, I used Appen's platform and created an HTML file with the following components:

1. **Instructions for Annotation**: I included clear instructions and examples to guide annotators in identifying pneumonia symptoms, such as areas of opacity in the lungs and obscured diaphragm shadows.

- Healthy Case: 
![healthy-example](https://github.com/user-attachments/assets/021a6b99-e5ef-4d6a-8db2-3619b32a1cce)
- pneumonia Cases: 
![pneumonia-examples](https://github.com/user-attachments/assets/d3492df7-280f-434b-a97f-614de05de572)
- To clarify to non-experts annotators I provided a clear description of the structure of a child's chest as shown in the image below: 
![annotated-chest-xray](https://github.com/user-attachments/assets/cebe74d4-2dcb-4de7-b6e6-6684e2d3fc8a)

2. **Example Test Questions**: I created sample test questions to ensure annotators understood the task and could accurately identify pneumonia cases. 

In the accompanying Proposal document, I discussed my design choices and the steps I would take to ensure the quality of the dataset, such as:

- Handling uncertainty in annotations
- Implementing quality assurance measures
- Iterating on the job design based on feedback and performance

## Conclusion
By creating a high-quality labeled dataset of chest X-ray images, I enabled machine learning engineers to build a classification system that could aid doctors in quickly identifying cases of pneumonia in children. This would be a valuable tool in improving patient outcomes and supporting medical professionals in their diagnosis and treatment process.

## Contact 
If you have any questions, feedback, or inquiries regarding this project, please feel free to reach out to me through my Email: NouvAlqahtani@gmail.com.
