# Bengaluru-Mobility-Challenge-2024
This project aims to develop innovative solutions to address traffic congestion in Bengaluru, India as part of the 2024 Bengaluru Mobility Challenge hackathon. The hackathon is co-organized by the Bengaluru Traffic Police, Centre for Data for Public Good, and Indian Institute of Science (IISc), with prizes sponsored by the IEEE Foundation.
Certainly! Below is a detailed README template for your Bengaluru Mobility Challenge project. You can customize it further based on your specific implementation and requirements.

# Bengaluru Mobility Challenge 2024

## Overview

The Bengaluru Mobility Challenge 2024 is an initiative aimed at addressing the pressing issue of traffic congestion in Bengaluru, India. This project seeks to develop innovative solutions that leverage data and technology to improve urban mobility. Our focus is on two primary objectives: short-term traffic volume prediction and vehicle re-identification.

## Objectives

1. **Short-term Traffic Volume Prediction**: 
   - Utilize video feeds from 23 Safe City cameras located in northern Bengaluru.
   - Develop predictive models to estimate vehicle counts by type and turning patterns at various intersections 30 minutes into the future.

2. **Vehicle Re-identification**: 
   - Create algorithms capable of re-identifying vehicles captured at different locations within the city.
   - Estimate origin-destination flows to aid in transportation planning and analysis.

## Project Structure

The project is organized into two main phases:

- **Phase 1: Short-term Traffic Prediction**
  - Data collection and preprocessing from video feeds.
  - Development of machine learning models for traffic prediction.
  - Evaluation and validation of model accuracy.

- **Phase 2: Vehicle Re-identification**
  - Implementation of computer vision techniques for vehicle tracking.
  - Development of algorithms for vehicle re-identification across multiple camera feeds.
  - Analysis of origin-destination patterns based on re-identified vehicles.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: 
  - OpenCV for computer vision tasks
  - TensorFlow or PyTorch for deep learning models
  - Pandas and NumPy for data manipulation
  - Scikit-learn for model evaluation
- **Data Sources**: Video feeds from Safe City cameras in Bengaluru

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Python 3.x
- Required Python libraries (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bengaluru-mobility-challenge.git
   cd bengaluru-mobility-challenge
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Data Preparation**: 
   - Place your video data in the `data/videos` directory.
   - Ensure the data is organized according to the expected format.

2. **Run the Traffic Prediction Model**:
   ```bash
   python traffic_prediction.py
   ```

3. **Run the Vehicle Re-identification Model**:
   ```bash
   python vehicle_reidentification.py
   ```

### Evaluation

- The models will output predictions and visualizations that can be found in the `outputs` directory.
- Use the provided scripts to evaluate model performance based on accuracy, precision, and recall.

## Contributing

We welcome contributions to improve this project! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Bengaluru Traffic Police
- Centre for Data for Public Good
- Indian Institute of Science (IISc)
- IEEE Foundation

## Contact

For any inquiries or feedback, please reach out to sinhaprachi447@gmail.com
