Krittaya Nikornkul 663020277-7

# SC663403 Data Preparation and Data Mining 📊
## ✨Overview
**รหัสวิชา:** SC663403

**ชื่อวิชา:** Data Preparation and Data Mining 
การเตรียมข้อมูลและการทำเหมืองข้อมูล

**คำอธิบายรายวิชา:**
แนวคิดของการเตรียมข้อมูล ชนิดและประเภทของข้อมูล เครื่องมือที่ใช้ในการเตรียมข้อมูล การจัดการข้อมูลในรูปแบบต่าง ๆ พื้นฐานของการทำเหมืองข้อมูลและแนวคิดเชิงพรรณนา การสกัดความรู้จากข้อมูล อัลกอริทึมการสร้างตัวแบบเพื่อการทำนายการค้นพบความสัมพันธ์ในการทำเหมืองข้อมูล การจัดกลุ่มข้อมูล เทคนิคการประเมินตัวแบบ การเรียนรู้จากตัวแบบที่หลากหลาย และ กรณีศึกษาที่เกี่ยวข้อง

**อาจารย์:** ผศ.ดร.ธนพงศ์ อินทระ

## 📝Course Work and Grading

| รายการ | รายละเอียด | สัดส่วนคะแนน (%) |
|:---:|---|:---:|
| Midterm | ปฏิบัติเดี่ยว เรื่อง Data Preprocessing | 25% |
| Final | ทฤษฎีเดี่ยว เรื่อง Data Mining | 25% |
| Project | งานกลุ่ม (5–6 คน) ครอบคลุม Data Preprocessing + Data Mining | 20% |
| Homework | งานกลุ่ม โดยมีการ แบ่งกลุ่มใหม่ทุกครั้ง | 15% |
| Quiz | ทดสอบเดี่ยว โดยการ ถามในห้องเรียน | 10% |
| GitHub | การส่งงานหรือกิจกรรมที่เกี่ยวข้องผ่าน GitHub | 5% |

Final Score = Score × %attendance

## 📚Contents

### **Chapter 1** Introduction to Data Mining ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/01Intro.pdf))

เนื้อหา: 
- บทนำสู่ Data Mining
- อธิบายความหมาย ความสำคัญ ประเภทของข้อมูลที่นำมาทำ data mining
- ภาพรวมของกระบวนการค้นหาความรู้จากฐานข้อมูล (KDD)

### **Chapter 2** Getting to Know Your Data ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/02Data.pdf))
เนื้อหา: 
- การทำความรู้จักกับข้อมูล
- ประเภทของ Attribute
- การสรุปข้อมูลเชิงสถิติ (Mean, Median, Mode, Variance)
- การวัดความเหมือน/ต่าง (Similarity & Dissimilarity)

### **Chapter 3** Data Preprocessing ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/03Preprocessing.pdf))
เนื้อหา: 
- ขั้นตอนการเตรียมข้อมูลก่อนนำไปใช้จริง ประกอบด้วย
- Data Cleaning (ล้างข้อมูล)
- Data Integration (รวมข้อมูล)
- Data Reduction (ลดขนาด)
- Data Transformation (การแปลงข้อมูล)

### **Chapter 6** Mining Frequent Patterns & Associations ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/06FPBasic.pdf))
เนื้อหา:
- การค้นหา Frequent Patterns และ Association Rules
- อัลกอริทึม Apriori
- การวิเคราะห์ตะกร้าสินค้า (Market Basket Analysis)

### **Chapter 8** Classification - Basic Concepts ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/08ClassBasic.pdf))
เนื้อหา:
- พื้นฐานการสร้างโมเดลจำแนกประเภท
- แนะนำ Decision Tree, Naïve Bayes, โมเดลแบบ Linear
- การประเมินประสิทธิภาพของโมเดล (Evaluation)

### **Chapter 9** Classification - Advanced Methods ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/09ClassAdvanced.pdf))
เนื้อหา:
- เทคนิคการจำแนกประเภทขั้นสูง
- Bayesian Belief Networks
- Support Vector Machines (SVM), Neural Networks
- Deep Learning
- K-Nearest Neighbors (KNN)

### **Chapter 10** Cluster Analysis ([Dowload](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/10ClusBasic.pdf))
เนื้อหา:
- แนวคิดพื้นฐานการจัดกลุ่มข้อมูล (Unsupervised Learning)
- แนะนำเทคนิค Partitioning (k-means), Hierarchical Methods และ Density-based Methods (DBSCAN)
- ANN Tutorial: 📄 ([เอกสาร ANN](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/AI%20%E0%B8%9A%E0%B8%B8%E0%B8%8D%E0%B9%80%E0%B8%AA%E0%B8%A3%E0%B8%B4%E0%B8%A1.pdf))
** หมายเหตุ: ศึกษาเรื่อง Perceptron Learning ที่หน้า 169 ในเอกสาร

## 📝Midterm: Rainfall Data Preprocessing
การทำ Data Cleaning และ Data Aggregation ข้อมูลปริมาณน้ำฝนรายวันจากสถาบันสารสนเทศทรัพยากรน้ำ (HII) เพื่อเตรียมข้อมูลสำหรับแบบจำลองพยากรณ์หรือวิเคราะห์ทางอุทกวิทยา
### สรุปขั้นตอน ([Code](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Midterm_663020277_7.ipynb))
- Data Integration: รวมข้อมูลน้ำฝนรายวันปี 2025 จากหลายไฟล์ CSV เข้าด้วยกัน
- Station Filtering: คัดเฉพาะสถานีที่อยู่ในโมเดล (384 สถานี)
- Quality Control: ตัดสถานีที่มีข้อมูลหาย >= 20% ออก (เหลือ 339 สถานี)
- Missing Imputation: เติมค่าว่างด้วย Median จากสถิติย้อนหลัง (2012-2024) รายวัน
- Monthly Aggregation: รวมผลรวมน้ำฝน (Sum) รายเดือน แยกตามสถานี

## 🌧️Final Project: Rainfall Prediction Model Comparison
### Group 4: Mahalanobis
### Code: ([Code Final Project](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Group4_final_project.ipynb))
### Presentation : ([Slide Final Project](https://www.canva.com/design/DAHD7QeY6AQ/NoYAkGl7-4UdB4CTaOizSQ/view?utm_content=DAHD7QeY6AQ&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h80002e3179)) 

### โจทย์
เปรียบเทียบโมเดลพยากรณ์ปริมาณน้ำฝน เพื่อหาโมเดลที่มีประสิทธิภาพดีที่สุด

### โมเดลที่ใช้
1. LSTM
2. Hist Gradient Boosting Regressor
3. Gaussian Process Regression
4. VotingRegressor
   
### การทำงาน
- ประยุกต์ใช้เทคนิคการเรียนรู้จากข้อมูลย้อนหลัง (Sliding Window) เพื่อสร้างแบบจำลองสำหรับการพยากรณ์ข้อมูลในอนาคต (Forecasting Horizon)
- บูรณาการชุดข้อมูลปริมาณน้ำฝนจากหลากหลายสถานีตรวจวัด ควบคู่ไปกับตัวแปรปัจจัยทางสภาพภูมิอากาศ เพื่อเพิ่มความแม่นยำในการวิเคราะห์
- บริหารจัดการชุดข้อมูลด้วยการแบ่งส่วนแบบอนุกรมเวลา (Time Series Split) ซึ่งประกอบด้วยส่วนการฝึกสอน (Train), การปรับจูน (Validation) และการทดสอบประสิทธิภาพ (Test)

### การวิเคราะห์และแสดงผล
* **Model Performance Comparison:** ดำเนินการเปรียบเทียบขีดความสามารถและประสิทธิภาพของแต่ละโมเดลอย่างละเอียด
* **Data Visualization & Export:** จัดเก็บผลลัพธ์การวิเคราะห์ในรูปแบบไฟล์ CSV พร้อมจัดทำกราฟเปรียบเทียบระหว่างค่าจริง (Actual) และค่าที่แบบจำลองทำนาย (Predicted) เพื่อให้เห็นความแตกต่างที่ชัดเจน

### สรุปผล
จากการทดสอบพบว่าแต่ละแบบจำลองมีประสิทธิภาพที่แตกต่างกัน โดยได้ทำการคัดเลือกโมเดลที่เหมาะสมที่สุดผ่านเกณฑ์การวัดผลทางสถิติ ได้แก่ **MSE (Mean Squared Error)**, **R² (Coefficient of Determination)** และ **Accuracy** เพื่อนำไปประยุกต์ใช้ในการพยากรณ์ปริมาณน้ำฝนที่จะเกิดขึ้นจริงในอนาคตต่อไป


# 📚 ภาพรวมบทเรียนและงาน

| บทเรียน | แหล่งเรียนรู้ | งานและแบบทดสอบ |
| :--- | :--- | :--- |
| **Chapter 1:** Introduction to Data Mining | ([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/01Intro.pdf)) |  - |
| **Chapter 2:** Getting to Know Your Data | ([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/02Data.pdf)) | - |
| **Chapter 3:** Data Preprocessing |([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/03Preprocessing.pdf))<br>([💻Code](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Ch3_Data_Prepocessing.ipynb))<br>[💻Code ตัวอย่าง PCA](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Ch3_dimensionality_reduction_PCA.ipynb))| - |
| **Chapter 6:** Mining Frequent Patterns & Associations |([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/06FPBasic.pdf))<br>([💻Code](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Ch4_Frequent_Patterns_(Association_Rules).ipynb))|  📝 **Quiz7** - คำนวณ Apriori Algorithm<br>📝 **HW3** - วิเคราะห์พฤติกรรมลูกค้า |
| **Chapter 8:** Classification - Basic Concepts |([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/08ClassBasic.pdf))<br>([💻Code](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Ch5_Classification.ipynb))|  📝 **Quiz10** - Naïve Bayes<br>📝 **Quiz13** - F1 Score<br>📝 **HW4** - Decision Tree |
| **Chapter 9:** Classification - Advanced Methods | ([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/09ClassAdvanced.pdf) | - |
| **Chapter 10:** Cluster Analysis |([📄 เอกสารประกอบการสอน](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/10ClusBasic.pdf))<br>([📖 ANN Tutorial (หน้า 169)](https://github.com/AI-Krittaya/BSC_DPDM2025/blob/main/Slide/AI%20%E0%B8%9A%E0%B8%B8%E0%B8%8D%E0%B9%80%E0%B8%AA%E0%B8%A3%E0%B8%B4%E0%B8%A1.pdf))| - |

---
