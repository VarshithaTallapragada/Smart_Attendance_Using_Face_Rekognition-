# Smart_Attendance_Using_Face_Rekognition-


## 📌 Project Overview
The **Smart Attendance System** is an automated attendance management system that leverages **face recognition technology** to mark attendance accurately and efficiently. This system eliminates manual attendance taking, reduces errors, and prevents proxy attendance.

Using **AWS Rekognition** and **DynamoDB**, the system can recognize faces from images captured via a webcam or uploaded by users, identify the person, and mark their attendance in real-time.

---

## 🏗️ System Architecture
1. **Frontend**: HTML / Flask web interface to capture or upload images  
2. **Backend**: Python (Flask) handles image processing and AWS integration  
3. **AWS Rekognition**: Detects and matches faces with a stored collection  
4. **AWS DynamoDB**: Stores user details (FaceId, Name, Roll Number)  
5. **Attendance Database**: Maintains daily attendance records

---

## ⚙️ Features
- ✅ Automated attendance marking  
- ✅ Real-time face recognition  
- ✅ Accurate and contactless system  
- ✅ Scalable for large classrooms or offices  
- ✅ Attendance reports stored in DynamoDB  

---

## 🧠 How It Works
1. **Enrollment**: Capture face images of students/employees and register them in the Rekognition collection. Store the mapping of FaceId → Name in DynamoDB.  
2. **Recognition & Attendance**:  
   - User uploads or captures an image.  
   - AWS Rekognition searches for a match in the collection.  
   - If matched, the system fetches the name from DynamoDB and marks attendance.  
   - If not matched, displays *“Person not recognized”*.  
3. **Storage & Reporting**: Attendance data is stored with Date, Time, and Status.

---

## 🖥️ Technologies Used
- **Python** (Flask)  
- **AWS Rekognition** (Face detection & recognition)  
- **AWS DynamoDB** (Database for storing user info and attendance)  
- **Pillow (PIL)** for image processing  
- **HTML/CSS** for frontend interface  

---

## ⚡ Advantages
- Contactless and hygienic  
- Reduces manual errors  
- Prevents proxy attendance  
- Cloud-based and scalable  

---

## ⚠️ Limitations
- Requires good lighting for accurate recognition  
- Internet connectivity needed  
- Face masks or sunglasses may reduce accuracy  

---

## 📷 Sample Images
- Cricketers or student faces can be used for demo purposes  

---

## ✅ Conclusion
The Smart Attendance System using Face Recognition provides a **fast, reliable, and contactless** solution for managing attendance. Leveraging **AWS Rekognition** and **DynamoDB**, it can automatically identify individuals, reduce errors, prevent proxy attendance, and maintain accurate records. 
                          This project demonstrates how **cloud-based AI services** can be integrated into practical applications, making attendance management **efficient, scalable, and secure** for educational institutions or workplaces.


