# 📺 Web Streaming Website
### *Graduation Project – CMSE405/406, Eastern Mediterranean University*

This project presents the design and implementation of a **YouTube-like video streaming platform**, focusing on **scalability**, **efficiency**, and **user experience**.  
It allows users to upload, stream, and interact with video content through an intuitive and secure web interface.

---

## 🧠 Project Overview

The **Web Streaming Website** aims to provide a high-performance platform for video content creators and viewers.  
It includes secure authentication, adaptive streaming, live streaming support, and an admin-controlled moderation system.

Key objectives:
- Build a **scalable architecture** using Node.js and MySQL.
- Ensure **low-latency playback** through CDN integration.
- Support **multi-quality transcoding** for diverse devices.
- Maintain **data security and reliability** across all components.

---

## 👩‍💻 Team Members

| Name | ID | Role |
|------|----|------|
| **Zeynep Pelin Çolak** | 17300009 | UI Designer |
| **Doğukan Ramazan Sapsızoğlu** | 20450049 | Database Developer |
| **Abdulaziz Mahmoud** | 18700859 | Project Manager / Lead Programmer |

**Supervisor:** Asst. Prof. Dr. Ahmet Ünveren  
**Department:** Computer Engineering – Eastern Mediterranean University  

---

## 🧩 Key Features

- 🎞️ **Video Uploading & Processing:** Upload, transcode, and store videos in multiple resolutions.  
- 🖥️ **Adaptive Streaming:** Uses CDN and protocols like MPEG-DASH for smooth playback.  
- 👥 **User System:** Authentication with login, signup, and role-based access.  
- 💬 **Comments & Reactions:** Engage with videos via likes, comments, and subscriptions.  
- 📺 **Live Streaming Support:** Real-time streaming with minimal latency.  
- 🧮 **Recommendation System:** Personalized video suggestions based on watch history.  
- 🔒 **Secure Storage:** Data encryption and access control mechanisms.  
- ⚙️ **Admin Panel:** Manage users, content moderation, and platform analytics.  

---

## 🧰 Technologies Used

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | Node.js |
| **Database** | MySQL |
| **Video Libraries** | Video.js / Plyr.js |
| **Deployment** | GitHub & Netlify |
| **Design Tools** | Adobe XD |
| **Version Control** | Git & GitHub |

---

## 🧮 System Architecture

The system consists of the following main modules:

- **Client (Web/Mobile App):** User interface for browsing and watching videos.  
- **API Server:** Handles user authentication, uploads, and data requests.  
- **Video Processing Server:** Transcodes and manages uploaded videos.  
- **Database Layer:** Stores metadata, comments, and user data.  
- **CDN (Content Delivery Network):** Delivers videos efficiently with low latency.

---

## ⚙️ Core Algorithms

### 1️⃣ User Authentication  
- Validates login credentials and manages secure session tokens.

### 2️⃣ Video Upload  
- Checks file size and format, uploads, stores metadata, and updates database.

### 3️⃣ Video Recommendation  
- Uses watch history and preferences to suggest personalized videos.

---

## 🧾 Quality & Testing

- **Unit Testing:** Tested main modules (upload, playback, authentication).  
- **Integration Testing:** Verified communication between backend and database.  
- **User Acceptance Testing:** Conducted real-user testing for UI/UX feedback.  
- **Tools Used:** Selenium, Mocha, Jasmine.  

### Quality Models Applied:
- Kano Model  
- SWOT Analysis  
- Pareto Chart  
- Affinity Diagram  
- Quality Metrics & Checklists  

---

## 🧱 Database Design

**Main Tables:**
- `User(UserID, Username, Password, Email, DateJoined)`  
- `Video(VideoID, Title, Description, UserID, CategoryID, UploadDate)`  
- `Comment(CommentID, Content, UserID, VideoID, DatePosted)`  
- `Category(CategoryID, CategoryName)`

**Normalization:** Up to 3NF (Third Normal Form).  

---

## 📊 Project Management

- **Planning Method:** Work Packages & Gantt Chart  
- **Effort Estimation:** Basic COCOMO Model  
- **Duration:** 9 months total  
- **Team Size:** 4 members  

---

## 🏗️ Tools & Standards

- **W3C HTML/CSS Standards**  
- **ECMAScript 6 JavaScript Standard**  
- **WCAG Accessibility Guidelines**  
- **OWASP Security Principles**  

---

## 🧩 Future Enhancements

- Implement **AI-based content moderation**  
- Add **real-time chat during live streams**  
- Introduce **monetization for creators**  
- Expand to **mobile app using React Native**

---

## 🧍‍♀️ Developer Highlight

👩‍💻 **Zeynep Pelin Çolak**  
- UI Designer & Documentation Lead  
- Responsible for: Interface design, system documentation, and integration testing.  

---

## 🏫 Course Information

**Course:** CMSE405 / CMSE406 – Graduation Project  
**Instructor:** Asst. Prof. Dr. Ahmet Ünveren  
**Department:** Computer Engineering  
**University:** Eastern Mediterranean University  

---

## ✅ Conclusion

The **Web Streaming Website** provides a scalable, efficient, and user-centric video streaming solution.  
It successfully integrates **cloud services**, **CDN optimization**, and **secure architectures**, making it suitable for large-scale online content platforms.

---

## 🔗 References

- [Node.js Documentation](https://nodejs.org/)  
- [MySQL Official Docs](https://dev.mysql.com/doc/)  
- [Bootstrap Framework](https://getbootstrap.com/)  
- [OWASP Guidelines](https://owasp.org/)  
