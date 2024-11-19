# Peer-to-Peer File Sharing System  

Welcome to the **Peer-to-Peer File Sharing System**! This project implements a robust file transfer system with **sender** and **receiver** GUIs, allowing users to securely share files over a network. Built with **socket programming** and a dashboard-style interface, this application prioritizes simplicity, functionality, and user experience.  

---

## Features  

### General Features  
- **GUI-Based Dashboard**: User-friendly interface for both sender and receiver.  
- **Cross-Platform Support**: Compatible with Windows, macOS, and Linux.  
- **Authentication**: Secure transfers with password-based authentication.  
- **Pause, Resume, and Stop**: Control file transfers with ease.  

### Sender Features  
- **Multi-File Selection**: Send multiple files at once using the file explorer.  
- **Transfer Progress**: Real-time display of progress, speed, and estimated time remaining.  
- **Transfer History**: View logs of previously sent files with timestamps and sizes.  

### Receiver Features  
- **Save Directory Selection**: Customize the directory where files are saved.  
- **Real-Time Progress**: Monitor the speed, progress, and remaining time during file reception.  
- **Transfer Logs**: View detailed records of received files.  

---

## How It Works  

1. **Sender-Side**:  
   - Choose files to send and provide the receiver's IP address, port, and authentication password.  
   - Monitor transfer details and manage ongoing transfers with pause, resume, and stop options.  

2. **Receiver-Side**:  
   - Start the server to listen for incoming file transfers.  
   - Authenticate the sender, receive files, and save them to the designated directory.  

---

## Getting Started  

### Prerequisites  
- Python 3.7 or later  
- Required Python libraries (Tkinter, socket, threading, etc.)  

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/username/p2p-file-sharing.git  
   cd p2p-file-sharing  
   ```  

2. Install required dependencies (if applicable):  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## Usage  

### Sender Application  
1. Run the **Sender GUI**:  
   ```bash  
   python sender.py  
   ```  
2. Select files to send, enter the receiver's details, and start the transfer.  

### Receiver Application  
1. Run the **Receiver GUI**:  
   ```bash  
   python receiver.py  
   ```  
2. Set the save directory, start the server, and monitor incoming transfers.  

---

## File Structure  
```plaintext  
p2p-file-sharing/  
├── sender.py               # Sender-side application code  
├── receiver.py             # Receiver-side application code  
├── requirements.txt        # Required Python libraries  
├── README.md               # Documentation  
├── utils/                  # Utility scripts (if applicable)  
└── assets/                 # Images or assets for documentation/UI  
```  

---

## Technologies Used  
- **Python**: Core programming language.  
- **Tkinter**: GUI development.  
- **Socket Programming**: Network communication.  
- **Threading**: Multi-client support and concurrency.  

---

## Contributing  
Contributions are welcome! Follow these steps to contribute:  
1. Fork the repository.  
2. Create a feature branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Add new feature"  
   ```  
4. Push the branch:  
   ```bash  
   git push origin feature-name  
   ```  
5. Open a pull request.  

---

## Contact  
For questions, suggestions, or bug reports, contact:  
- **Email**: dhruvmenon2003@gmail.com  
- **GitHub**: [DrvMen](https://github.com/DrvMen)  

Enjoy seamless file sharing! 🚀
