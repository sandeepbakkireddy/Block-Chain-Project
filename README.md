 🔒 Innovative Use of Noise Images for File Encryption within a Cloud-Based Environment

## 📌 Overview  
This project introduces an **innovative approach to cloud security** by utilizing **noise images for file encryption**. Traditional encryption methods rely on mathematical algorithms, which can be vulnerable to attacks. Instead, this project leverages **visual cryptography** and **blockchain technology** to enhance data confidentiality and integrity in cloud environments.  

## 🚀 Features  
- **Noise Image-Based Encryption**: Converts files into noise images, making them secure and unrecognizable.  
- **Visual Cryptography**: Uses encrypted noise patterns as cryptographic keys.  
- **Blockchain Integration**: Logs encryption and decryption activities securely.  
- **Cloud Compatibility**: Designed for seamless file storage and retrieval in cloud environments.  
- **Django Web Application**: Provides an intuitive UI for users to encrypt, store, and retrieve files.  

## 📂 Project Structure  
```
📦 Block-Chain-Project
 ┣ 📂 algorithm/          # Encryption and decryption algorithms
 ┣ 📂 base/              # Core configurations and utilities
 ┣ 📂 templates/         # HTML templates for the web UI
 ┣ 📂 static/            # CSS, JS, and media assets
 ┣ 📜 db.sqlite3         # SQLite database for storing file metadata
 ┣ 📜 manage.py          # Django project management script
 ┣ 📜 README.md         # Project documentation
 ┣ 📜 requirements.txt   # Python dependencies
 ┗ 📜 LICENSE            # License information
```

## 🛠️ Technologies Used  
- **Frontend**: HTML, CSS, Bootstrap  
- **Backend**: Python, Django  
- **Encryption**: AES Algorithm with Noise Image Keys  
- **Database**: SQLite (can be extended to MySQL/PostgreSQL)  
- **Blockchain Framework**: (Specify if Ethereum, Hyperledger, or other is used)  

## 📊 Methodology  
1. **File Encryption**:  
   - Convert the uploaded file into an encrypted **noise image**.  
   - AES encryption is applied to enhance security.  
2. **Blockchain Logging**:  
   - Each encryption event is **stored on the blockchain** for integrity.  
3. **File Retrieval**:  
   - Users can upload their **key image** to decrypt and restore the original file.  
4. **Web Application**:  
   - A Django-based platform for **uploading, encrypting, and decrypting files** securely.  

## ▶️ How to Run the Project  

### Prerequisites  
- Python 3.x  
- Virtual environment tool (recommended)  
- Django  

### Installation Steps  
1. Clone the repository:  
   ```sh
   git clone https://github.com/sandeepbakkireddy/Block-Chain-Project.git
   cd Block-Chain-Project
   ```
2. Create and activate a virtual environment:  
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```
4. Apply database migrations:  
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```
5. Create a superuser (for admin access):  
   ```sh
   python manage.py createsuperuser
   ```
6. Run the development server:  
   ```sh
   python manage.py runserver
   ```
7. Open the application in a browser:  
   ```
   http://127.0.0.1:8000/
   ```

## 🎮 User Guide  
- **Encrypt a File**: Upload a file and get a **noise image encryption key**.  
- **Decrypt a File**: Upload your key image to recover the original file.  
- **Admin Panel**: Manage encrypted files and user requests.  

## 🛡️ Security Considerations  
- **AES Encryption with Noise Images**: Ensures high-security encryption.  
- **Blockchain Storage**: Prevents tampering of encryption logs.  
- **User Authentication**: Only verified users can encrypt or decrypt files.  
- **HTTPS Support**: Secure cloud-based storage.  



![Screenshot 2025-03-16 204758](https://github.com/user-attachments/assets/308d5b78-6236-4ca5-a9b3-edbb78c9ec3b)
![Screenshot 2025-03-16 204820](https://github.com/user-attachments/assets/beda5b97-28bd-4c25-800b-a3dc0b65ada5)
![Screenshot 2025-03-16 205229](https://github.com/user-attachments/assets/8487c070-b3b8-466d-a23a-6de30aefd264)
![Screenshot 2025-03-16 205326](https://github.com/user-attachments/assets/523bbd29-8740-4c3c-ba61-7b65d19c0372)
![Screenshot 2025-03-16 205339](https://github.com/user-attachments/assets/658c109c-7d5a-4bfc-9073-4bf6f14f8234)
![Screenshot 2025-03-16 205419](https://github.com/user-attachments/assets/1604d54d-48f2-48a5-9a9b-a7c73230e719)
![Screenshot 2025-03-16 205443](https://github.com/user-attachments/assets/9cc72b87-b02f-4b8a-8e79-aa19855f13e5)
![Screenshot 2025-03-16 205959](https://github.com/user-attachments/assets/62b6fabd-90d8-4b2a-bbef-87bf67bb10a4)
![Screenshot 2025-03-16 210100](https://github.com/user-attachments/assets/533920ae-84ba-464c-8e1d-77e4e89c2b0c)
![Screenshot 2025-03-16 204735](https://github.com/user-attachments/assets/7450f913-a63d-42c8-bab9-05fa3daf1bb3)
