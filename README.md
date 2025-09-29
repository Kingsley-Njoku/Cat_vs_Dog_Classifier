🐾 Cat vs Dog Classifier

An interactive deep learning web app that classifies images of cats 🐱 and dogs 🐶 using a ResNet-18 model trained in PyTorch, deployed with Streamlit, and hosted on the Hugging Face Hub.

📸 Demo

🔗 https://checkcatordog.streamlit.app/ 

Upload an image of a cat or dog and the app will predict the class along with confidence score:

⚙️ Features

Deep Learning: ResNet-18 architecture fine-tuned for binary image classification.

Beautiful UI: Custom-styled Streamlit app with gradient background and styled predictions.

Deployment: Model hosted on Hugging Face Hub, integrated into Streamlit Cloud.

Lightweight & Fast: Efficient preprocessing and inference pipeline for quick results.

🛠️ Tech Stack

Frameworks: PyTorch, Torchvision

Deployment: Streamlit, Hugging Face Hub, GitHub

Other Tools: PIL, Python

🚀 Getting Started
1. Clone the repo
git clone https://github.com/YOUR-USERNAME/cat-vs-dog-classifier.git
cd cat-vs-dog-classifier

2. Install dependencies
pip install -r requirements.txt

3. Run locally
streamlit run app.py

📂 Project Structure
cat-vs-dog-classifier/
│── app.py                 # Streamlit app
│── requirements.txt       # Dependencies
│── README.md              # Project documentation

🌐 Deployment

The model was too large for GitHub, so it’s hosted on the Hugging Face Hub and automatically loaded into the Streamlit app.

📊 Results

High accuracy on validation set.

Correct classification of test images with strong confidence.

✨ Acknowledgments

PyTorch
 for deep learning

Streamlit
 for deployment

Hugging Face Hub
 for model hosting
