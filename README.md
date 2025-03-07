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

![Screenshot 2025-03-07 152054](https://github.com/user-attachments/assets/2d88693e-f59a-461c-ac6b-610f77cfadda)
![Screenshot 2025-03-07 152210](https://github.com/user-attachments/assets/48b3e45e-aa22-4535-81ad-45230da0080b)
![Screenshot 2025-03-07 152222](https://github.com/user-attachments/assets/dc2ed3f3-8ab3-43e6-b6f1-fdf1662b7953)
![Screenshot 2025-03-07 152231](https://github.com/user-attachments/assets/709c54b9-341b-4b7e-82d5-6e6203373faa)
![Screenshot 2025-03-07 152246](https://github.com/user-attachments/assets/24afa84e-7c7d-4e84-aed2-9004094e0c14)
![Screenshot 2025-03-07 152254](https://github.com/user-attachments/assets/c07f1252-eecc-4793-ab8c-936e82f793fb)
![Screenshot 2025-03-07 152150](https://github.com/user-attachments/assets/c5fa856b-c6f9-4fdb-99ac-1c7f7c4fb037)
