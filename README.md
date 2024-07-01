# Brew-Tex

Brew-Tex is an ambitious project aimed at developing an application that can convert flexible documents and screenshots into editable LaTeX code. Currently in its research and development phase, the project is exploring various deep learning models, with a focus on YOLOv8, trained on the PubLayNet dataset.

## Project Goal

The end goal of Brew-Tex is to create a robust system capable of:
1. Accepting various input formats (images, screenshots, PDFs)
2. Recognizing and categorizing document elements
3. Generating corresponding LaTeX code for the identified elements

## Current Status

Brew-Tex is in active research and development. Key aspects of the current work include:

- Training YOLOv8 models on the PubLayNet dataset
- Exploring other potential models for document understanding
- Evaluating model performance on document layout detection

## Technologies and Datasets

- **Main Model**: YOLOv8
- **Dataset**: PubLayNet
- **Potential Future Models**: To be determined based on research outcomes

## Setup for Researchers and Contributors

1. Clone the repository:
   ```
   git clone https://github.com/your-username/brew-tex.git
   cd brew-tex
   ```

2. Set up a Python environment (recommended Python 3.8+)

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Download the PubLayNet dataset (instructions to be added)

5. Set up YOLOv8 (instructions to be added)

## Current Development Focus

- Implementing and fine-tuning YOLOv8 for document layout detection
- Preprocessing strategies for the PubLayNet dataset
- Post-processing techniques to improve model predictions
- Exploring methods to convert detected layouts to LaTeX structure

## Future Roadmap

- [ ] Achieve satisfactory performance on document layout detection
- [ ] Develop a system for optical character recognition (OCR) integration
- [ ] Create a module for converting detected layouts to LaTeX code
- [ ] Implement a user interface for easy document/image input
- [ ] Develop post-processing for LaTeX code refinement
- [ ] Create a system for handling complex mathematical expressions

## Contributing

We welcome contributions from researchers and developers interested in document understanding and LaTeX generation. If you're interested in contributing:

1. Fork the repository
2. Create a new branch for your feature or research
3. Commit your changes with clear, descriptive messages
4. Push to your fork and submit a pull request with a detailed description of your work

## Research Collaboration

We're open to collaboration with researchers in the fields of computer vision, natural language processing, and document understanding. If you're interested in collaborating, please open an issue to discuss potential research directions.

## Contact

For any queries, suggestions, or collaboration proposals, please open an issue in the GitHub repository.

---

Brew-Tex is an open-source research project. We appreciate your interest and contributions in advancing the field of document understanding and LaTeX generation.
