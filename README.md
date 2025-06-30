# 🚀 My Journey: Introduction to Deep Learning with Keras

> A personal learning log of the 4-hour intermediate-level course on DataCamp: [Introduction to Deep Learning with Keras](https://app.datacamp.com/learn/courses/introduction-to-deep-learning-with-keras)

---

## 🧑‍💻 Why I Chose This Course

I’d been curious about how neural networks really work under the hood, and I wanted a hands-on introduction to Keras—the high-level API for TensorFlow. This course promised to take me from my very first regression model all the way through convolutional nets and LSTMs, so I decided to give it a try.

---

## 📚 What I Learned

1. **Keras Basics**  
   - How to build **Sequential** and **Functional** models  
   - Core objects: layers, activations, optimizers, and loss functions  
   - Training loops, evaluation, and saving models  

2. **Classic Tasks**  
   - **Regression**: predicted meteor trajectories with a small dense network  
   - **Binary & Multi-class**: detected fake dollar bills and classified dart throws  
   - **Multi-label**: built a mini “smart irrigation” system  

3. **Model Tuning & Diagnostics**  
   - Plotting learning curves to spot under- and over-fitting  
   - Using **callbacks** (EarlyStopping, ModelCheckpoint)  
   - Hyperparameter search with `GridSearchCV` wrapping my Keras models  

4. **Advanced Architectures**  
   - **Autoencoders**: built a denoising network for MNIST  
   - **Convolutional Neural Networks**: visualized filters, fine-tuned ResNet50  
   - **Recurrent Networks (LSTMs)**: created a text predictor with embedding layers  

---

## 🗂️ Repo Structure & How I Organized My Notes

```text
├── 01_keras_basics/
│   ├── 01_regression_meteor.ipynb
│   ├── 02_binary_classification.ipynb
│   └── 03_multi_label_irrigation.ipynb
├── 02_model_performance/
│   ├── 01_learning_curves.ipynb
│   └── 02_hyperparameter_search.ipynb
├── 03_advanced_architectures/
│   ├── 01_autoencoder_denoising.ipynb
│   ├── 02_cnn_filters_resnet.ipynb
│   └── 03_lstm_text_prediction.ipynb
└── README.md
