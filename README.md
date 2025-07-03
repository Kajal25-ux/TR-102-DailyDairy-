# 📘 TR102 - Smartfusion Training Daily Diary

## 🗓️ Duration: 4 Weeks  
## 👩‍💻 Topics: IoT | AI | ML | Arduino | Raspberry Pi | Cloud | Sensors | Actuators

---

### 📝 Day 1 – *25 June 2025*

#### 📌 Topics Covered:
- Introduction to IoT and real-life applications
- Basic concepts of Machine Learning (ML) and Artificial Intelligence (AI)
- Difference between IoT, ML, and AI with examples
- Types of Machine Learning: Supervised, Unsupervised, Reinforcement
- Introduction to Arduino and its components (sensors, microcontroller, etc.)

#### ✅ Task Given:
- Study and understand the concept of **Smart Umbrella** (IoT-based project)
- Research and explore different **simulators** for practice

#### 🔍 Key Learnings:
- Understood real-life functioning of IoT devices
- Learned applications of ML and AI in smart systems
- Basic knowledge of **Arduino** and **Raspberry Pi**
- Role of simulators in testing before hardware implementation

---

### 📝 Day 2 – *26 June 2025*

#### 📘 Topics Covered:
- IoT Architecture and its 7 levels
- Introduction to **sensors**, **smart sensors**, **actuators**, and **smart actuators**
- Overview of robotic systems and smart appliances

#### 🧪 Simulators:
- Understood how IoT simulators work
- Practiced testing virtual connections

#### 🔌 Hardware Connections:
- Connected **LED**, **DHT11**, and **PIR motion sensor** with Arduino
- Learned pin configuration and wiring

#### 💻 Arduino Code:
- Code explained for reading sensor data
- Understood simulation and code uploading process

#### ✅ Task Given:
- Write Arduino code to read **humidity and temperature** using **DHT11**
- Install **Anaconda**
- Learn difference between **Arduino**, **NodeMCU**, and **Raspberry Pi**

#### 🔍 Key Learnings:
- Hands-on with Arduino hardware and sensor wiring
- Better understanding of hardware platforms (Arduino vs NodeMCU vs Raspberry Pi)
- Simulators help validate logic before real-world deployment

---

### 📝 Day 3 – *27 June 2025*

#### 📚 Topics Covered:
- Introduction to **Cloud Computing** in IoT
- Concepts: Traditional, Distributed, Cluster, Grid, and Cloud Computing
- Client-Server Architecture
- Virtualization and its types
- Cloud Deployment Models & Frameworks
- Importance of Cloud in IoT
- Introduction to **ThingSpeak** platform
- Setup ThingSpeak channel
- Program to connect **NodeMCU** to Wi-Fi and read **DHT11** data

#### ✅ Task Given:
- Explore platforms: Google App Engine, Microsoft Azure, Amazon AWS
- Read about **Amazon EC2**
- Study IoT platforms: ThingSpeak, Exhibly, Nimbit, Cosm
- Complete assignment on IoT concepts
- Start IoT mini-project

#### 💡 Key Learnings:
- Understood computing models and architecture in IoT
- Explored **ThingSpeak** for IoT cloud integration
- Benefits of cloud for data storage, analysis, and sharing

---

### 📝 Day 4 – *30 June 2025*

#### 📚 Topics Covered:
- **Data Acquisition** in IoT
- Sensor interfacing using **ESP32** and **DHT22**
- Reading temperature & humidity using Arduino code
- Wi-Fi connection with ESP32 using **Wokwi simulation**
- Sending data to **ThingSpeak** via **HTTP GET request**
- Viewing real-time data on ThingSpeak dashboard

#### ✅ Task Given:
- Simulate **ESP32 + DHT22** in **Wokwi**
- Write code to send data to **ThingSpeak**
- Use API Key and validate channel data
- Observe HTTP response codes (e.g., 200 OK)

#### 💡 Key Learnings:
- Working knowledge of **Data Acquisition Systems**
- Practical use of **ESP32** with sensors
- HTTP request handling for cloud data uploads
- Real-time data visualization with **ThingSpeak**

---

### 📝 Day 5 – *1 July 2025*

#### 📚 Topics Covered:
- Overview of **Photoresistor (LDR)** and light detection
- Interfacing **Servo Motor** with Arduino
- Understanding analog input using LDR
- Introduction to **PWM (Pulse Width Modulation)**

#### ✅ Task Given:
- Task 1: Detect light using **LDR**
- Task 2: Interface a **servo motor** and control angle via Arduino

#### 💡 Key Learnings:
- Learned how **LDR** changes resistance with light intensity
- Understood analog signal reading using Arduino
- Explored PWM and servo motor movement
- Improved sensor and actuator interfacing skills

---

# 📝 Day 6  
📅 **Date:** 2 July 2025  

---

## 📚 Topics Covered
- Introduction to **Data Preprocessing** in Machine Learning  
- Understanding **Train-Test Split** (80% training, 20% testing)  
- Key Preprocessing Techniques:
  - Handling **Missing Values** (NaN)
  - **Scaling** using `MinMaxScaler`
  - **Normalization**

- Installation of important Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

---

## ✅ Task Given
1. Create a CSV file named `student_data.csv` including:
   - **Columns:** Name, ID, Math, Science, English
   - **Rows:** 5–10 entries with some missing values (NaN)
2. Load the dataset into a **pandas DataFrame**
3. Count missing values in each column using:
   ```python
   df.isnull().sum()
   
