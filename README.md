# NeoLock

**Smart Screen Lock System Powered by AI Face Recognition**

**Authors:** Saadat Nurbekova & Latifa Salyeva

---

## 📌 Overview

**NeoLock** is a smart screen lock system designed to protect device security using AI face recognition technology. The system replaces traditional screen lock methods with a secure, convenient, and adaptive authentication process.

* **Enhance Computer Security:** Protect devices dynamically based on authorized user presence.


* **AI Authorization:** Utilize computer vision for real-time face matching.


* **Automatic Screen Lock:** Instantly trigger a system lock if an unrecognized person appears in front of the camera.


* **User Control:** Provide an easy-to-use interface with full flexibility to manage authorized users.



---

## ⚙️ How It Works

1. **Continuous Camera Scanning:** The system streams live video to continuously scan for faces.


2. **Setup / Training:** Users complete an initial setup process to register their face encodings into the system.


3. **Active Authorization:**
* If **only registered faces** are detected, the screen remains unlocked.


* If an **unknown face** appears in the frame, the system instantly triggers a OS screen lock command.




4. **User Management:** Registered faces can be added or removed manually at any time.



---

## 🛠️ System Architecture & Technologies

* **`face_recognition` Library:** Core AI backend for real-time facial feature extraction and comparison against saved encodings.


* **Real-time Camera Feed:** Processes live frames continuously for zero-lag detection.


* **`Tkinter` GUI:** Simple desktop interface for system management, configuration, and setup.


* **OS-Level Locking:** Directly invokes platform system commands to securely lock the workstation upon detection of unauthorized users.



---

## 💡 Why NeoLock?

1. **Market Need:** Addresses the lack of accessible, simple face-recognition security software for desktop environments.


2. **Modern Cyber Security:** Upgrades static password protection to adaptive, continuous authentication.


3. **Smart Adaptation:** Built to evolve beyond a simple scanner into an intelligent security assistant.



---

## 🚀 Future Roadmap

* **Multi-Platform Support:** Expand compatibility to **macOS**, **Android**, and **iOS** (currently Windows prototype).


* **Enhanced AI Accuracy:** Improve detection in low-light environments and adapt to facial changes (glasses, hair, accessories).


* **Background Mode & Autostart:** Seamless boot integration to run automatically in the background.


* **Operating Modes:** Implementation of operational modes:
* *Normal Mode*
* *Strict Mode*
* *Custom Mode*



* **UI/UX Refinement:** Redesign the user interface for a modern, modern desktop experience.


Link to the project: https://drive.google.com/drive/folders/1ocBCIw6gb3fgKVNhU82Sdh2bOncTWukv?usp=drive_link
