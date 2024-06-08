# LipNet: Lip-Reading Full Stack Application 💬👄

Welcome to LipNet, a full-stack application for lip reading, originally developed from the LipNet deep learning model. This project combines deep learning with web development to provide a functional lip-reading application that predicts spoken words from video inputs.
LipNet utilizes a deep learning model trained to read lips from video sequences. The application processes video inputs, extracts relevant frames, and uses a pre-trained model to predict the spoken words. The web interface allows users to upload videos, view the processed frames, and see the model's predictions in real-time.

## 🎥 Demo Video



## 🛠️ System Diagrams

![diagram](https://github.com/DhruvSharma19/LipNet/assets/112254552/4c5a36aa-d84a-4b45-a452-55ef94139c1a)
![diagram](https://github.com/DhruvSharma19/LipNet/assets/112254552/53d8d27e-d177-4a2d-b243-82a3d2f07260)

## 🌟 Key Features

- **Video Processing** 📹: Upload and process video files to extract frames and prepare them for model input.
- **Real-Time Predictions** ⏱️: Display model predictions in real-time, showing the output as text.
- **User-Friendly Interface** 👥: Streamlit-based web application providing an intuitive user experience.
- **Visualization** 👁️: View the original video and the processed frames that the model uses for predictions.
- **Pre-trained Model** 🧠: Utilize a pre-trained LipNet model for accurate lip-reading predictions.

## 🛠 Technologies Used

- **Deep Learning**: TensorFlow and Keras for building and running the lip-reading model.
- **Web Framework**: Streamlit for creating the web interface.
- **Video Processing**: OpenCV for video frame extraction and processing.
- **Data Handling**: Numpy and TensorFlow for data manipulation and preprocessing.
- **Visualization**: Matplotlib and Imageio for visualizing frames and animations.

## 🖼️ Screenshots

## Getting Started 🚀

### Prerequisites 📋

- Python 3.7 or later
- Pip (Python package installer)

### Installation 💻

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/DhruvSharma19/LipNet.git
    cd LipNet
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download and Extract Data**:
    Download the necessary data from [Google Drive](https://drive.google.com/uc?id=1YlvpDLix3S-U8fd-gqRwPcWXAXm8JwjL) and extract it:
    ```python
    import gdown
    url = 'https://drive.google.com/uc?id=1YlvpDLix3S-U8fd-gqRwPcWXAXm8JwjL'
    output = 'data.zip'
    gdown.download(url, output, quiet=False)
    gdown.extractall('data.zip')
    ```

4. **Run the Application**:
    ```bash
    streamlit run streamlitapp.py
    ```

5. **Access the Web Interface**:
    Open your web browser and go to `http://localhost:8501` to use the LipNet application.

## Contributions 🤝

Contributions are welcome! If you have ideas for improvements or new features, feel free to fork the repository and submit a pull request. Please make sure to follow the project's coding standards and include appropriate tests for any new functionality.

1. **Fork the Repository**
2. **Create a Feature Branch**:
    ```bash
    git checkout -b feature/YourFeature
    ```
3. **Commit Your Changes**:
    ```bash
    git commit -m 'Add some feature'
    ```
4. **Push to the Branch**:
    ```bash
    git push origin feature/YourFeature
    ```
5. **Open a Pull Request**

## 🙏 Acknowledgements

A big thank you to everyone who contributed to this project! We appreciate your support and feedback.

If you have any questions or need assistance, feel free to open an issue or reach out to the project maintainers. Enjoy using LipNet and happy coding! ✨
