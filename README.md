Krittaya Nikornkul 663020277-7

# 📘 Introduction to Data Mining

---

## 🎯 Why Data Mining?
- ปริมาณข้อมูลเติบโตจาก **terabytes → petabytes**
- ข้อมูลมาจากธุรกิจ วิทยาศาสตร์ เว็บ และโซเชียลต่าง ๆ
- “We are drowning in data, but starving for knowledge.”
- Data Mining ช่วยเปลี่ยนข้อมูลจำนวนมากให้กลายเป็น **insight ที่มีมูลค่า**

---

## 🔍 What Is Data Mining?
กระบวนการค้นหาความรู้ (Knowledge Discovery) จากข้อมูลขนาดใหญ่
ค้นหารูปแบบที่ “น่าสนใจ,ใหม่,มีประโยชน์,ไม่ชัดเจนในตอนแรก”

ชื่อเรียกอื่น ๆ
- Knowledge Discovery in Databases (KDD)
- Knowledge extraction
- Business Intelligence (BI)
- Data/pattern analysis

---

## 🔄 Knowledge Discovery (KDD) Process  
กระบวนการสกัดความรู้จากข้อมูล
1. **Data Cleaning** – ลบ noise / ข้อมูลไม่สมบูรณ์
2. **Integration** – รวมข้อมูลจากหลายแหล่ง
3. **Selection** – เลือกเฉพาะ data ที่เกี่ยวข้อง
4. **Transformation** – แปลงข้อมูลให้พร้อมสำหรับ mining  
5. **Data Mining** – ค้นหารูปแบบ / pattern
6. **Pattern Evaluation** – คัดกรองรูปแบบที่ “มีค่า”
7. **Knowledge Presentation** – แสดงผลลัพธ์ในรูปที่เข้าใจง่าย
---

## Multi-Dimensional View of Data Mining
### 📚 What Data Can Be Mined?
รองรับข้อมูลหลากหลายประเภท เช่น:
- Relational databases
- Data warehouse
- Time-series, sensor, streaming data
- Text, Web, multimedia data
- Graphs & Social networks
- Spatial & spatiotemporal data

---

### 🧩 What Patterns Can Be Mined?

#### **1) Generalization**
- การสรุปลักษณะข้อมูลระดับสูง  
- ใช้ OLAP, Data Cube

#### **2) Pattern Discovery**
- หา frequent patterns 
- Association rules  
- Example: Diapers → Beer [0.5%, 75%] (support, confidence)

#### **3) Classification**
- Predict labels  
- Tools: Decision Tree, SVM, Naive Bayes, Neural Networks

#### **4) Clustering**
- จัดกลุ่มข้อมูลแบบไม่มี label
- หาโครงสร้างในข้อมูล
- Example: K-means, hierarchical clustering

#### **5) Outlier Detection**
- ตรวจจับข้อมูลผิดปกติ  
- ใช้ใน fraud detection, anomaly detection

#### **6) Sequential / Trend Analysis**
- การวิเคราะห์ลำดับเวลา  
- Example: Trend, Time-series, Sequential patterns

#### **7) Structure & Network Analysis**
- Graph mining  
- Social network analysis  
- Web mining (PageRank, Community detection)

---
## 🧪Evaluation of Knowledge
การประเมินรูปแบบที่ค้นพบ
- เชิงพรรณนา vs เชิงทำนาย (Descriptive vs. predictive)
- ความครอบคลุม (Coverage)
- ความใหม่ (Novelty)
- ความถูกต้องแม่นยำ (Accuracy)
- ความทันเวลา (timeliness)
  
---
## 🧠 Techniques Used
- Machine Learning    
- Pattern Recognition
- Statistics  
- Visualization
- High Performance Computing
- Database Technology
- Applications
- Algorithm
    
เนื่องจากข้อมูลมีความซับซ้อนมากขึ้น → ต้องบูรณาการหลายสาขาเข้าด้วยกัน

---

## 🏭 Applications of Data Mining
- Web page classification & clustering
- Recommender systems  
- Targeted marketing (market basket analysis)  
- Bioinformatics & Medical data
- Software engineering
- Text analysis  
- Social network analysis  
- Search engines & ranking algorithms
- แพลตฟอร์มใหญ่เช่น Google / Facebook มี data mining แบบ “มองไม่เห็น” (invisible mining)
- เครื่องมือสำหรับ data mining เช่น SAS, MS SQL-Server Analysis Manager, Oracle Data Mining Tools

---

## ⚠️ Major Issues
### **1) Methodology**
- จัดการข้อมูลหลายมิติ
- รวมหลายเทคนิค
- จัดการ noise และข้อมูลไม่สมบูรณ์

### **2) User Interaction**
- Interactive mining  
- Visualization ที่เข้าใจง่าย  
- ใช้ Background knowledge 

### **3) Efficiency & Scalability**
- อัลกอริทึมต้องเร็วและรองรับ big data
- รองรับ parallel / distributed / streaming

### **4) Diversity of data types**
- การจัดการข้อมูลประเภทที่ซับซ้อน
- การใช้คลังข้อมูลแบบไดนามิก เครือข่าย และทั่วโลก
  
### **5) Data Mining & Society**
- ความเป็นส่วนตัว (Privacy)
- ผลกระทบทางสังคม (Ethical concerns)  
- ความโปร่งใส (Invisible data mining)

---

## 🕰️ Brief History of Data Mining
- 1989 – IJCAI Workshop on KDD
- 1991 – หนังสือ KDD โดย Piatetsky-Shapiro & Frawley
- 1991–1994 – Workshops on KDD
- 1995–1998 – International Conferences on KDD
- 1997 – Journal of Data Mining and Knowledge Discovery
- 1998–ปัจจุบัน – ประชุม ACM SIGKDD
- การเติบโตของงานประชุม: PAKDD, PKDD, SIAM-DM, ICDM, WSDM
- 2007 – เปิดตัววารสาร ACM TKDD

---

## 📚 Recommended Books
- Charu C. Aggarwal, Data Mining: The Textbook, Springer, 2015
- E. Alpaydin. Introduction to Machine Learning, 2nd ed., MIT Press, 2011
- R. O. Duda, P. E. Hart, and D. G. Stork, Pattern Classification, 2ed., Wiley-Interscience, 2000
- U. Fayyad, G. Grinstein, and A. Wierse, Information Visualization in Data Mining and Knowledge
Discovery, Morgan Kaufmann, 2001
- J. Han, M. Kamber, and J. Pei, Data Mining: Concepts and Techniques. Morgan Kaufmann, 3rd ed. ,
2011
- T. Hastie, R. Tibshirani, and J. Friedman, The Elements of Statistical Learning: Data Mining, Inference,
and Prediction, 2nd ed., Springer, 2009
- T. M. Mitchell, Machine Learning, McGraw Hill, 1997
- P.-N. Tan, M. Steinbach and V. Kumar, Introduction to Data Mining, Wiley, 2005 (2nd ed. 2016)
- I. H. Witten and E. Frank, Data Mining: Practical Machine Learning Tools and Techniques with Java
Implementations, Morgan Kaufmann, 2nd ed. 2005
- Mohammed J. Zaki and Wagner Meira Jr., Data Mining and Analysis: Fundamental Concepts and
Algorithms 2014

---

## ✔️ Summary
- Data mining คือการค้นหารูปแบบที่มีประโยชน์จากข้อมูลจำนวนมาก
- เกิดจากการพัฒนาเทคโนโลยีฐานข้อมูล + ML + การประมวลผล
- เป็นส่วนหนึ่งของกระบวนการ KDD  
- ครอบคลุมทั้ง descriptive และ predictive analytics  
- ใช้ในหลายสาขา ตั้งแต่ web, marketing, bioinformatics จนถึง social networks  
- มีความท้าทายด้านความเป็นส่วนตัว ขนาดข้อมูล และความซับซ้อนของ data

---
