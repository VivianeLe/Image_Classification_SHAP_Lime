# **Oxford Pet Classification with SHAP and LIME**

This project focuses on **image classification** using a pre-trained convolutional neural network and interprets the model's predictions using **SHAP** (SHapley Additive exPlanations) and **LIME** (Local Interpretable Model-Agnostic Explanations). The project leverages the **Oxford-IIIT Pet Dataset** for multi-class classification, demonstrating how to train a robust image classifier and explain its predictions using interpretable AI methods.

---

## **Features**
1. **Image Classification**:
   - Utilizes a pre-trained convolutional neural network (e.g., ResNet, VGG, or another backbone) to classify pet images into multiple categories.

2. **Model Training and Validation**:
   - Includes training a model on the Oxford-IIIT Pet Dataset with appropriate data augmentation and validation strategies.

3. **Explainability**:
   - Implements SHAP and LIME to provide detailed insights into the model's predictions:
     - **SHAP** highlights pixel importance for predictions.
     - **LIME** explains predictions by locally perturbing image inputs.

4. **Visualization**:
   - Provides clear visualizations of model predictions and the explanations generated by SHAP and LIME.

---

## **Dependencies**
To run the project, ensure the following libraries are installed:
- Python 3.x
- TensorFlow or PyTorch (depending on the model implementation)
- NumPy
- Matplotlib
- SHAP
- LIME
- scikit-learn
- OpenCV (optional, for image processing)

---

## **Usage**

1. Clone the repository:
   ```bash
   git clone https://github.com/VivianeLe/Image_Classification_SHAP_Lime.git
   cd Image_Classification_SHAP_Lime
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook OxfordPet-Classification.ipynb
   ```

3. Run the cells sequentially to:
   - Load and preprocess the Oxford-IIIT Pet Dataset.
   - Train the classification model.
   - Visualize SHAP and LIME explanations for selected predictions.

---

## **Results**
- **Classification Accuracy**: The model achieves high accuracy on the validation set, showcasing its ability to classify pet images correctly.
- **Explainability Outputs**:
  - SHAP produces heatmaps highlighting important image regions influencing the model's decisions.
  - LIME generates perturbed explanations for individual image predictions.

---

## **References**
- [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/)
- [SHAP Documentation](https://shap.readthedocs.io/)
- [LIME Documentation](https://github.com/marcotcr/lime)
- Relevant research papers and blogs on model interpretability.

---

## **Contributing**
Contributions are welcome! Feel free to submit issues or pull requests for improvements or new features.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
