🔐 Geneix – DNA-RNA Based Image Encryption System
Geneix is a bio-inspired image security application that uses DNA and RNA computing principles combined with chaotic cryptographic techniques to securely encrypt and decrypt digital images.

The system converts image pixel data into DNA sequences, applies RNA mutation and translation operations, and generates a highly secure encrypted image. The encrypted image can then be decrypted back to the original image using the reverse algorithm.

The application is built with Python and Streamlit, providing an interactive web interface where users can upload images, perform encryption, and visually compare the original, encrypted, and decrypted images.

🚀 Features
🔒 DNA-RNA Inspired Encryption

Uses DNA encoding, RNA transcription, mutation, and translation techniques.

🧠 Chaotic Cryptography

Chaotic sequences generate unpredictable encryption keys.

🔁 Secure Image Decryption

Recovers the original image using reverse transformations.

🖼 Side-by-Side Image Comparison

Displays Original | Encrypted | Decrypted images.

⏱ Encryption Time Measurement

Shows processing time for encryption and decryption.

🌐 Interactive Web Interface

Built using Streamlit for easy image upload and visualization.

🧬 Encryption Workflow
The encryption process follows these stages:

Image Upload & Preprocessing

Convert image to RGB and resize.

SHA-256 Hash Generation

A cryptographic hash is generated from image pixel values.

Chaotic Parameter Generation

Chaotic maps generate unpredictable sequences.

DNA Encoding

Binary pixel data is converted into DNA bases (A, T, C, G).

DNA Transcription

DNA sequences are converted into RNA sequences.

RNA Mutation

Mutation rules modify RNA sequences using chaotic values.

RNA Translation

Transformed sequences introduce additional randomness.

RNA Computing

XOR-like operations are performed using RNA rules.

Encrypted Image Generation

The transformed sequences are converted back into pixel values.

Decryption

The reverse algorithm reconstructs the original image.

🖥 Application Interface
The application allows users to:

Upload one or multiple images

Encrypt images securely

Decrypt encrypted images

Compare results visually

🛠 Technologies Used
Python

Streamlit

NumPy

Pillow (PIL)

Matplotlib

Hashlib

📂 Project Structure
Geneix-Image-Encryption
│
├── app1.py
├── README.md
└── requirements.txt
⚙ Installation
Clone the repository:

git clone https://github.com/your-username/geneix-image-encryption.git
Navigate to the project folder:

cd geneix-image-encryption
Install dependencies:

pip install -r requirements.txt
▶ Run the Application
Start the Streamlit server:

streamlit run app1.py
The app will open in your browser:

http://localhost:8501
🔒 Security Approach
The project combines multiple security techniques:

Cryptographic hashing (SHA-256)

Chaotic systems for randomness

DNA encoding rules

RNA mutation and translation

RNA computing operations

These layers create a highly complex encryption pipeline, making the system resistant to statistical and brute-force attacks.

📌 Future Improvements
Faster encryption using optimized algorithms

Support for larger image resolutions

GPU acceleration

Video frame encryption

👩‍💻 Author
Developed as part of a project exploring bio-inspired cryptography and secure image processing techniques.

