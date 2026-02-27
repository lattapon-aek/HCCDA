# HCCDA Study Notes

## Table of Contents
- [Chapter 1: Diving into Huawei Cloud](#chapter-1-diving-into-huawei-cloud)
- [Chapter 2: Compute Services](#chapter-2-compute-services)
- [Chapter 3: Storage Services](#chapter-3-storage-services)
- [Chapter 4: Networking Services](#chapter-4-networking-services)
- [Chapter 5: Database Services](#chapter-5-database-services)
- [Chapter 6: Security Services](#chapter-6-security-services)
- [Chapter 7: Elastic Cloud Services for Distributed Deployment](#chapter-7-elastic-cloud-services-for-distributed-deployment)
- [Chapter 8: Cloud Native and Transformation](#chapter-8-cloud-native-and-transformation)
- [Chapter 9: Exam Outline and Sample Questions](#chapter-9-exam-outline-and-sample-questions)

### Chapter 1: Diving into Huawei Cloud - Images from PDF
<details>
<summary>Click to expand Chapter 1 images (41 pages)</summary>

![Chapter 1 PDF Page 01](assets/chapter1_pdf_pages/ch1-page-01.png)
![Chapter 1 PDF Page 02](assets/chapter1_pdf_pages/ch1-page-02.png)
![Chapter 1 PDF Page 03](assets/chapter1_pdf_pages/ch1-page-03.png)
![Chapter 1 PDF Page 04](assets/chapter1_pdf_pages/ch1-page-04.png)
![Chapter 1 PDF Page 05](assets/chapter1_pdf_pages/ch1-page-05.png)
![Chapter 1 PDF Page 06](assets/chapter1_pdf_pages/ch1-page-06.png)
![Chapter 1 PDF Page 07](assets/chapter1_pdf_pages/ch1-page-07.png)
![Chapter 1 PDF Page 08](assets/chapter1_pdf_pages/ch1-page-08.png)
![Chapter 1 PDF Page 09](assets/chapter1_pdf_pages/ch1-page-09.png)
![Chapter 1 PDF Page 10](assets/chapter1_pdf_pages/ch1-page-10.png)
![Chapter 1 PDF Page 11](assets/chapter1_pdf_pages/ch1-page-11.png)
![Chapter 1 PDF Page 12](assets/chapter1_pdf_pages/ch1-page-12.png)
![Chapter 1 PDF Page 13](assets/chapter1_pdf_pages/ch1-page-13.png)
![Chapter 1 PDF Page 14](assets/chapter1_pdf_pages/ch1-page-14.png)
![Chapter 1 PDF Page 15](assets/chapter1_pdf_pages/ch1-page-15.png)
![Chapter 1 PDF Page 16](assets/chapter1_pdf_pages/ch1-page-16.png)
![Chapter 1 PDF Page 17](assets/chapter1_pdf_pages/ch1-page-17.png)
![Chapter 1 PDF Page 18](assets/chapter1_pdf_pages/ch1-page-18.png)
![Chapter 1 PDF Page 19](assets/chapter1_pdf_pages/ch1-page-19.png)
![Chapter 1 PDF Page 20](assets/chapter1_pdf_pages/ch1-page-20.png)
![Chapter 1 PDF Page 21](assets/chapter1_pdf_pages/ch1-page-21.png)
![Chapter 1 PDF Page 22](assets/chapter1_pdf_pages/ch1-page-22.png)
![Chapter 1 PDF Page 23](assets/chapter1_pdf_pages/ch1-page-23.png)
![Chapter 1 PDF Page 24](assets/chapter1_pdf_pages/ch1-page-24.png)
![Chapter 1 PDF Page 25](assets/chapter1_pdf_pages/ch1-page-25.png)
![Chapter 1 PDF Page 26](assets/chapter1_pdf_pages/ch1-page-26.png)
![Chapter 1 PDF Page 27](assets/chapter1_pdf_pages/ch1-page-27.png)
![Chapter 1 PDF Page 28](assets/chapter1_pdf_pages/ch1-page-28.png)
![Chapter 1 PDF Page 29](assets/chapter1_pdf_pages/ch1-page-29.png)
![Chapter 1 PDF Page 30](assets/chapter1_pdf_pages/ch1-page-30.png)
![Chapter 1 PDF Page 31](assets/chapter1_pdf_pages/ch1-page-31.png)
![Chapter 1 PDF Page 32](assets/chapter1_pdf_pages/ch1-page-32.png)
![Chapter 1 PDF Page 33](assets/chapter1_pdf_pages/ch1-page-33.png)
![Chapter 1 PDF Page 34](assets/chapter1_pdf_pages/ch1-page-34.png)
![Chapter 1 PDF Page 35](assets/chapter1_pdf_pages/ch1-page-35.png)
![Chapter 1 PDF Page 36](assets/chapter1_pdf_pages/ch1-page-36.png)
![Chapter 1 PDF Page 37](assets/chapter1_pdf_pages/ch1-page-37.png)
![Chapter 1 PDF Page 38](assets/chapter1_pdf_pages/ch1-page-38.png)
![Chapter 1 PDF Page 39](assets/chapter1_pdf_pages/ch1-page-39.png)
![Chapter 1 PDF Page 40](assets/chapter1_pdf_pages/ch1-page-40.png)
![Chapter 1 PDF Page 41](assets/chapter1_pdf_pages/ch1-page-41.png)

</details>

## Chapter 1: Diving into Huawei Cloud

<!-- CHAPTER_FOCUS_CH1_START -->
### Focus Highlights (Chapter 1: Diving into Huawei Cloud)
- <mark>Cloud Value</mark>: on-demand + pay-as-you-go reduces CAPEX and improves agility
- <mark>Core Models</mark>: clearly distinguish IaaS / PaaS / SaaS responsibilities
- <mark>Region vs AZ</mark>: Region is geography; AZ is fault-isolated data center zone
<!-- CHAPTER_FOCUS_CH1_END -->

📚 สรุปเนื้อหา
1. Basic Concepts and Values of Cloud Computing
Cloud Computing คือการให้บริการ IT แบบ on-demand ผ่านอินเทอร์เน็ต จ่ายเฉพาะที่ใช้จริง
ปัญหา Traditional IT: Service rollout ช้า, Resource utilization ต่ำ, TCO สูง, Scaling ยาก, O&M ซับซ้อน
Cloud ช่วยลด fixed asset investment, ให้ abundant resources, รองรับ operations ข้ามภูมิภาค
Cloud Service Models: IaaS (Infrastructure), PaaS (Platform), SaaS (Software)
Cloud Deployment: Public Cloud, Private Cloud, Hybrid Cloud
2. Huawei Cloud Infrastructure Architecture
Huawei Cloud เป็นโครงสร้างพื้นฐานระดับโลกที่มีหลาย Region และหลาย Availability Zone (AZ)
Region = พื้นที่ทางภูมิศาสตร์ เช่น CN North-Beijing4, AP-Bangkok, AP-Singapore
AZ (Availability Zone) = Data center ที่มี power/network เป็นอิสระ ป้องกัน single point of failure
Infrastructure ครอบคลุมทุก scenario: Central Region, IES, IEC, IEF
3. Core Services on Huawei Cloud
Compute: ECS (Elastic Cloud Server), IMS (Image Management), AS (Auto Scaling)
Container: CCE (Cloud Container Engine), CCI (Cloud Container Instance), SWR
Storage: EVS (Elastic Volume), SFS (Scalable File), OBS (Object Storage)
การคิดค่าบริการ OBS ประกอบด้วย: พื้นที่เก็บข้อมูล (capacity) + ปริมาณข้อมูลออก (outbound traffic) + จำนวนคำขอ (requests)
Network: VPC, EIP, NAT Gateway, Network ACL, VPC Peering, ELB
Security: IAM (Identity & Access Management), DEW (Data Encryption), CTS (Cloud Trace)
4. Huawei Cloud Ecosystem
Huawei Cloud มี Partner ecosystem ครอบคลุม ISV, SI, Distributor
KooGallery เป็น Marketplace สำหรับ Software และ Services
Developer Institute สนับสนุนนักพัฒนาด้วย Training, Certification, Community
5. Log in to Huawei Cloud
เข้าใช้งานผ่าน Huawei Cloud Console: huaweicloud.com
Console แสดง Dashboard, Resource overview, My Resources (ECS, Storage ฯลฯ)
รองรับ Single Sign-On และการจัดการ Account หลายรูปแบบ

```text
+-------------------- Traditional IT --------------------+
| rollout ช้า | ใช้งานทรัพยากรไม่คุ้ม | Scale ยาก | TCO สูง |
+------------------------- v ----------------------------+
|            Cloud: on-demand + pay-as-you-go            |
+--------------------------------------------------------+
```

```text
+------------- Service Models -------------+
| IaaS | PaaS | SaaS                       |
+------------------------------------------+
| User control มากสุด -> น้อยสุด           |
+------------------------------------------+
```

```text
+---------------- Deployment ----------------+
| Public Cloud | Private Cloud | Hybrid Cloud |
+---------------------------------------------+
| Hybrid = ผสม public + private               |
+---------------------------------------------+
```

```text
+---------------- Infrastructure ----------------+
| Region (เช่น AP-Bangkok)                      |
|  ├─ AZ1                                       |
|  ├─ AZ2                                       |
|  └─ AZ3                                       |
+-----------------------------------------------+
| AZ แยก power/network ลด single point of failure|
+-----------------------------------------------+
```

```text
+---------------- Huawei Cloud Core ----------------+
| Compute | Storage | Network | Security            |
| ECS     | OBS     | VPC     | IAM                 |
| IMS/AS  | EVS/SFS | EIP/ELB | DEW/CTS             |
+---------------------------------------------------+
```

<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH1_START -->
```text
+---------------- Chapter 1 Snapshot ----------------+
| Cloud Value: on-demand + pay-as-you-go            |
| Models: IaaS | PaaS | SaaS                         |
| Deploy: Public | Private | Hybrid                  |
| Infra: Region -> Multi-AZ (fault isolation)        |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH1_END -->

### Practice Questions

**ข้อ 1: ข้อใดไม่ใช่ Cloud Service Model?**
- A. IaaS
- B. PaaS
- C. SaaS
- D. DaaS (Data as a Service ในความหมาย Traditional)
> **Answer:** D

**ข้อ 2: AZ (Availability Zone) คืออะไร?**
- A. ประเทศที่มี Huawei Cloud
- B. Data center อิสระภายใน Region เดียวกัน
- C. ชื่อ Region ในเอเชีย
- D. บริการ Auto Scaling
> **Answer:** B — AZ คือกลุ่มดาต้าเซ็นเตอร์ที่แยกอิสระด้านไฟฟ้า/เครือข่ายภายใน Region เดียวกัน

**ข้อ 3: ECS ย่อมาจากอะไร?**
- A. Elastic Computing System
- B. Elastic Cloud Server
- C. Enterprise Cloud Storage
- D. Extended Cloud Service
> **Answer:** B

**ข้อ 4: IMS ทำหน้าที่อะไร?**
- A. จัดการ Network
- B. จัดการ Image ของ VM
- C. จัดการ Database
- D. จัดการ Security
> **Answer:** B — IMS (Image Management Service) ใช้จัดการ OS/VM Image สำหรับสร้าง ECS

**ข้อ 5: Huawei Cloud มีกี่ Region ทั่วโลก (ตาม PDF)?**
- A. 10+
- B. 15+
- C. 27+
- D. 50+
> **Answer:** C
> **Note:** ตัวเลขในข้อนี้อ้างอิงตามเอกสารชุดเรียนเดิม; ข้อมูล Global Infrastructure ปัจจุบันมีจำนวน Region/AZ มากขึ้น

### Chapter 2: Compute Services - Images from PDF
<details>
<summary>Click to expand Chapter 2 images (30 pages)</summary>

![Chapter 2 PDF Page 01](assets/chapter2_pdf_pages/ch2-page-01.png)
![Chapter 2 PDF Page 02](assets/chapter2_pdf_pages/ch2-page-02.png)
![Chapter 2 PDF Page 03](assets/chapter2_pdf_pages/ch2-page-03.png)
![Chapter 2 PDF Page 04](assets/chapter2_pdf_pages/ch2-page-04.png)
![Chapter 2 PDF Page 05](assets/chapter2_pdf_pages/ch2-page-05.png)
![Chapter 2 PDF Page 06](assets/chapter2_pdf_pages/ch2-page-06.png)
![Chapter 2 PDF Page 07](assets/chapter2_pdf_pages/ch2-page-07.png)
![Chapter 2 PDF Page 08](assets/chapter2_pdf_pages/ch2-page-08.png)
![Chapter 2 PDF Page 09](assets/chapter2_pdf_pages/ch2-page-09.png)
![Chapter 2 PDF Page 10](assets/chapter2_pdf_pages/ch2-page-10.png)
![Chapter 2 PDF Page 11](assets/chapter2_pdf_pages/ch2-page-11.png)
![Chapter 2 PDF Page 12](assets/chapter2_pdf_pages/ch2-page-12.png)
![Chapter 2 PDF Page 13](assets/chapter2_pdf_pages/ch2-page-13.png)
![Chapter 2 PDF Page 14](assets/chapter2_pdf_pages/ch2-page-14.png)
![Chapter 2 PDF Page 15](assets/chapter2_pdf_pages/ch2-page-15.png)
![Chapter 2 PDF Page 16](assets/chapter2_pdf_pages/ch2-page-16.png)
![Chapter 2 PDF Page 17](assets/chapter2_pdf_pages/ch2-page-17.png)
![Chapter 2 PDF Page 18](assets/chapter2_pdf_pages/ch2-page-18.png)
![Chapter 2 PDF Page 19](assets/chapter2_pdf_pages/ch2-page-19.png)
![Chapter 2 PDF Page 20](assets/chapter2_pdf_pages/ch2-page-20.png)
![Chapter 2 PDF Page 21](assets/chapter2_pdf_pages/ch2-page-21.png)
![Chapter 2 PDF Page 22](assets/chapter2_pdf_pages/ch2-page-22.png)
![Chapter 2 PDF Page 23](assets/chapter2_pdf_pages/ch2-page-23.png)
![Chapter 2 PDF Page 24](assets/chapter2_pdf_pages/ch2-page-24.png)
![Chapter 2 PDF Page 25](assets/chapter2_pdf_pages/ch2-page-25.png)
![Chapter 2 PDF Page 26](assets/chapter2_pdf_pages/ch2-page-26.png)
![Chapter 2 PDF Page 27](assets/chapter2_pdf_pages/ch2-page-27.png)
![Chapter 2 PDF Page 28](assets/chapter2_pdf_pages/ch2-page-28.png)
![Chapter 2 PDF Page 29](assets/chapter2_pdf_pages/ch2-page-29.png)
![Chapter 2 PDF Page 30](assets/chapter2_pdf_pages/ch2-page-30.png)

</details>

## Chapter 2: Compute Services

<!-- CHAPTER_FOCUS_CH2_START -->
### Focus Highlights (Chapter 2: Compute Services)
- <mark>ECS</mark>: flexible VM; choose billing mode based on workload pattern
- <mark>DeH</mark>: dedicated host for strong isolation/compliance requirements
- <mark>BMS</mark>: best for high-performance workloads (HPC/Big Data)
<!-- CHAPTER_FOCUS_CH2_END -->

📚 สรุปเนื้อหา
1. Overview of Compute Cloud Services
Huawei Cloud มี Compute services หลากหลาย: ECS, DeH, BMS, CCE, CCI, FunctionGraph
แต่ละ service เหมาะกับ workload ที่แตกต่างกัน
2. Elastic Cloud Server (ECS)
ECS คือ Virtual Machine บน Cloud ใช้งานได้ทันทีแบบ on-demand
การสร้าง ECS ต้องกำหนด: Region/AZ, Instance type, Image, EVS disk, Network (VPC/Subnet/EIP), Security group
หมายเหตุ: Subnet ภายใน VPC สื่อสารกันได้จาก implicit distributed router ของ VPC ไม่ใช่เพราะ route table
Local Disk เร็วกว่าแต่ไม่ HA | EVS ช้ากว่าเล็กน้อยแต่มีความทนทานและสำรองข้อมูลได้
สำคัญ: Guest OS มอง EVS เป็น block device (เหมือนฮาร์ดดิสก์จริง) สามารถสร้าง filesystem/partition ได้
Billing Modes: On-demand (จ่ายรายชั่วโมง), Yearly/Monthly (ส่วนลดมากกว่า), Reserved instance, Spot instance
เพิ่มเติม: Spot Instance เหมาะกับงานที่ยอมรับการหยุดชั่วคราวได้ (interruptible workload) และมีต้นทุนต่ำกว่า
ECS Types: General-purpose, Compute-optimized, Memory-optimized, GPU-accelerated, High-performance computing
C6 = Compute-optimized, M6 = Memory-optimized, G series = GPU
3. Dedicated Host (DeH)
DeH คือ Physical server ที่จัดสรรให้ใช้คนเดียว (ไม่แชร์กับ tenant อื่น)
เหมาะสำหรับ: Compliance requirements, License binding (BYOL), High security
Common ECS ใช้ Physical host ร่วมกัน, DeH ใช้แยกต่างหาก
4. Bare Metal Server (BMS)
BMS คือ Physical server โดยตรง ไม่มี Virtualization overhead
Features: Dedicated computing resources, VPC + Security group, No virtualization performance loss, Disk backup
เหมาะกับงานที่ต้องการ Performance สูงสุด เช่น HPC, Big Data
5. Image Management Service (IMS)
IMS ให้บริการ OS Image สำหรับสร้าง ECS
Image Types: Public image (Huawei provided), Private image (สร้างเอง), Shared image, Marketplace image
สามารถ Export/Import image ระหว่าง Region หรือสร้างจาก ECS ที่มีอยู่
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH2_START -->
```text
+---------------- Chapter 2 Snapshot ----------------+
| Compute: ECS / DeH / BMS / IMS                     |
| ECS: flexible VM billing (on-demand/monthly/spot)  |
| DeH: dedicated host (no tenant sharing)            |
| BMS: bare metal for high-performance workloads      |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH2_END -->

### Practice Questions

**ข้อ 1: C6.2xlarge.4 ECS หมายความว่าอย่างไร?**
- A. 2 vCPU, 4 GB RAM
- B. 8 vCPU, 32 GB RAM
- C. 4 vCPU, 16 GB RAM
- D. 16 vCPU, 64 GB RAM
> **Answer:** B — C6.2xlarge.4 โดยทั่วไปคือ 8 vCPU และ 32 GB RAM

**ข้อ 2: ข้อใดคือความแตกต่างหลักของ DeH กับ Common ECS?**
- A. DeH ถูกกว่า ECS
- B. DeH ใช้ Physical host เฉพาะตัว ไม่แชร์กับ tenant อื่น
- C. DeH ใช้ Containerization
- D. DeH รองรับ GPU เท่านั้น
> **Answer:** B — DeH คือโฮสต์แบบ dedicated ไม่แชร์ physical host กับ tenant อื่น

**ข้อ 3: BMS เหมาะกับ workload ประเภทใดที่สุด?**
- A. เว็บไซต์ทั่วไป
- B. Email server
- C. HPC และ Big Data ที่ต้องการ performance สูง
- D. Static file hosting
> **Answer:** C — BMS เหมาะกับงานที่ต้องการประสิทธิภาพสูงมาก เช่น HPC และ Big Data

**ข้อ 4: Billing mode ใดเหมาะกับ workload ที่มีการใช้งานไม่สม่ำเสมอ?**
- A. Yearly/Monthly
- B. Reserved Instance
- C. On-demand
- D. Spot Instance
> **Answer:** C — On-demand เหมาะกับ workload ไม่สม่ำเสมอ; Spot ใช้ได้เมื่อยอมรับการถูกยุติได้ (interruptible) แต่ไม่ใช่คำตอบหลัก

**ข้อ 5: Private Image ใน IMS คืออะไร?**
- A. Image ที่ Huawei จัดเตรียมให้
- B. Image ที่ผู้ใช้สร้างเองจาก ECS หรืออัปโหลด
- C. Image จาก KooGallery
- D. Image ที่แชร์จาก tenant อื่น
> **Answer:** B — Private Image คือ image ที่ผู้ใช้สร้างจาก ECS (capture) หรืออัปโหลดเข้า IMS เอง ไม่ใช่ public/marketplace/shared

### Chapter 3: Storage Services - Images from PDF
<details>
<summary>Click to expand Chapter 3 images (34 pages)</summary>

![Chapter 3 PDF Page 01](assets/chapter3_pdf_pages/ch3-page-01.png)
![Chapter 3 PDF Page 02](assets/chapter3_pdf_pages/ch3-page-02.png)
![Chapter 3 PDF Page 03](assets/chapter3_pdf_pages/ch3-page-03.png)
![Chapter 3 PDF Page 04](assets/chapter3_pdf_pages/ch3-page-04.png)
![Chapter 3 PDF Page 05](assets/chapter3_pdf_pages/ch3-page-05.png)
![Chapter 3 PDF Page 06](assets/chapter3_pdf_pages/ch3-page-06.png)
![Chapter 3 PDF Page 07](assets/chapter3_pdf_pages/ch3-page-07.png)
![Chapter 3 PDF Page 08](assets/chapter3_pdf_pages/ch3-page-08.png)
![Chapter 3 PDF Page 09](assets/chapter3_pdf_pages/ch3-page-09.png)
![Chapter 3 PDF Page 10](assets/chapter3_pdf_pages/ch3-page-10.png)
![Chapter 3 PDF Page 11](assets/chapter3_pdf_pages/ch3-page-11.png)
![Chapter 3 PDF Page 12](assets/chapter3_pdf_pages/ch3-page-12.png)
![Chapter 3 PDF Page 13](assets/chapter3_pdf_pages/ch3-page-13.png)
![Chapter 3 PDF Page 14](assets/chapter3_pdf_pages/ch3-page-14.png)
![Chapter 3 PDF Page 15](assets/chapter3_pdf_pages/ch3-page-15.png)
![Chapter 3 PDF Page 16](assets/chapter3_pdf_pages/ch3-page-16.png)
![Chapter 3 PDF Page 17](assets/chapter3_pdf_pages/ch3-page-17.png)
![Chapter 3 PDF Page 18](assets/chapter3_pdf_pages/ch3-page-18.png)
![Chapter 3 PDF Page 19](assets/chapter3_pdf_pages/ch3-page-19.png)
![Chapter 3 PDF Page 20](assets/chapter3_pdf_pages/ch3-page-20.png)
![Chapter 3 PDF Page 21](assets/chapter3_pdf_pages/ch3-page-21.png)
![Chapter 3 PDF Page 22](assets/chapter3_pdf_pages/ch3-page-22.png)
![Chapter 3 PDF Page 23](assets/chapter3_pdf_pages/ch3-page-23.png)
![Chapter 3 PDF Page 24](assets/chapter3_pdf_pages/ch3-page-24.png)
![Chapter 3 PDF Page 25](assets/chapter3_pdf_pages/ch3-page-25.png)
![Chapter 3 PDF Page 26](assets/chapter3_pdf_pages/ch3-page-26.png)
![Chapter 3 PDF Page 27](assets/chapter3_pdf_pages/ch3-page-27.png)
![Chapter 3 PDF Page 28](assets/chapter3_pdf_pages/ch3-page-28.png)
![Chapter 3 PDF Page 29](assets/chapter3_pdf_pages/ch3-page-29.png)
![Chapter 3 PDF Page 30](assets/chapter3_pdf_pages/ch3-page-30.png)
![Chapter 3 PDF Page 31](assets/chapter3_pdf_pages/ch3-page-31.png)
![Chapter 3 PDF Page 32](assets/chapter3_pdf_pages/ch3-page-32.png)
![Chapter 3 PDF Page 33](assets/chapter3_pdf_pages/ch3-page-33.png)
![Chapter 3 PDF Page 34](assets/chapter3_pdf_pages/ch3-page-34.png)

</details>

## Chapter 3: Storage Services

<!-- CHAPTER_FOCUS_CH3_START -->
### Focus Highlights (Chapter 3: Storage Services)
- <mark>OBS</mark>: object storage for static/media/backup content
- <mark>EVS</mark>: block storage for ECS system/data disks
- <mark>SFS</mark>: shared file system for multi-ECS access
<!-- CHAPTER_FOCUS_CH3_END -->

📚 สรุปเนื้อหา
1. Overview of Storage Services
Huawei Cloud มี Storage services หลัก 3 ประเภท: OBS, EVS, SFS
การคิดค่าบริการ OBS ประกอบด้วย: พื้นที่เก็บข้อมูล (capacity) + ปริมาณข้อมูลออก (outbound traffic) + จำนวนคำขอ (requests)
เพิ่มเติม: DSS (Dedicated Distributed Storage), SDRS (Storage Disaster Recovery)
การเลือก Storage ขึ้นอยู่กับ: Access pattern, Performance, Cost, Use case
2. Object Storage Service (OBS)
การคิดค่าบริการ OBS ประกอบด้วย: พื้นที่เก็บข้อมูล (capacity) + ปริมาณข้อมูลออก (outbound traffic) + จำนวนคำขอ (requests)
OBS เหมาะกับ Unstructured data: รูปภาพ วิดีโอ log ไฟล์ สำรองข้อมูล
ไม่ต้องการ Pre-provisioned space ไม่มี Minimum cost จ่ายตามที่ใช้จริง
Billing: Storage + Traffic + API calls (Inbound traffic ฟรี)
Storage Classes: Standard (Hot data), Infrequent Access (Warm data), Archive (Cold data)
OBS ใช้ HTTP API (S3-compatible), รองรับ Versioning, Lifecycle policies, Cross-region replication
3. Elastic Volume Service (EVS)
EVS คือ Block storage ที่ Attach กับ ECS เหมือน Hard disk
Local Disk เร็วกว่าแต่ไม่ HA | EVS ช้ากว่าเล็กน้อยแต่มีความทนทานและสำรองข้อมูลได้
สำคัญ: Guest OS มอง EVS เป็น block device (เหมือนฮาร์ดดิสก์จริง) สามารถสร้าง filesystem/partition ได้
Types: Ultra-high I/O (SSD), High I/O (SAS), Common I/O (SATA)
EVS สามารถ Expand, Backup, Snapshot, Detach และ Re-attach กับ ECS ได้
Local Disk: Storage บน Physical host ของ ECS, latency ต่ำกว่า EVS แต่ไม่มี redundancy
4. Scalable File Service (SFS)
SFS คือ Shared file storage แบบ NFS protocol
ให้หลาย ECS เข้าถึง Shared folder เดียวกันพร้อมกันได้
SFS Turbo = High-performance version สำหรับ workload ที่ต้องการ IOPS สูง
เหมาะกับ: Content Management, HPC, ERP, Web server farm ที่ต้องแชร์ไฟล์
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH3_START -->
```text
+---------------- Chapter 3 Snapshot ----------------+
| OBS: object storage (static/media/backup)          |
| EVS: block disk for ECS (OS/data disks)            |
| SFS: shared file storage across multiple ECS        |
| Choose by pattern: object vs block vs shared file  |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH3_END -->

### Practice Questions

**ข้อ 1: Storage service ใดเหมาะกับการเก็บ Static website assets (รูปภาพ, วิดีโอ)?**
- A. EVS
- B. SFS
- C. OBS
- D. DSS
> **Answer:** C — OBS เหมาะกับ static assets และ static website hosting

**ข้อ 2: EVS ต่างจาก OBS อย่างไร?**
- A. EVS ถูกกว่า OBS
- B. EVS เป็น Block storage Attach กับ ECS, OBS เป็น Object storage ใช้ผ่าน API
- C. EVS รองรับข้อมูลขนาดใหญ่กว่า
- D. EVS ใช้ HTTP protocol
> **Answer:** B — EVS เป็น Block storage attach กับ ECS; OBS เป็น Object storage ใช้ผ่าน API/HTTP

**ข้อ 3: SFS เหมาะกับ use case ใด?**
- A. Database primary storage
- B. หลาย ECS ต้องการ Share ไฟล์เดียวกัน
- C. Archive data ที่ไม่ค่อยใช้
- D. OS Disk ของ ECS
> **Answer:** B — หลาย ECS แชร์ไฟล์เดียวกัน (shared file system)

**ข้อ 4: OBS Storage Class ใดเหมาะกับ Cold data ที่แทบไม่ได้ใช้?**
- A. Standard
- B. Infrequent Access
- C. Archive
- D. Premium
> **Answer:** C — Archive เหมาะกับข้อมูลที่แทบไม่ถูกเรียกใช้

**ข้อ 5: EVS Type ใดมี I/O Performance สูงที่สุด?**
- A. Common I/O (SATA)
- B. High I/O (SAS)
- C. Ultra-high I/O (SSD)
> **Answer:** C — Ultra-high I/O (SSD) ให้ IOPS/throughput สูงสุดในกลุ่ม EVS

### Chapter 4: Networking Services - Images from PDF
<details>
<summary>Click to expand Chapter 4 images (36 pages)</summary>

![Chapter 4 PDF Page 01](assets/chapter4_pdf_pages/ch4-page-01.png)
![Chapter 4 PDF Page 02](assets/chapter4_pdf_pages/ch4-page-02.png)
![Chapter 4 PDF Page 03](assets/chapter4_pdf_pages/ch4-page-03.png)
![Chapter 4 PDF Page 04](assets/chapter4_pdf_pages/ch4-page-04.png)
![Chapter 4 PDF Page 05](assets/chapter4_pdf_pages/ch4-page-05.png)
![Chapter 4 PDF Page 06](assets/chapter4_pdf_pages/ch4-page-06.png)
![Chapter 4 PDF Page 07](assets/chapter4_pdf_pages/ch4-page-07.png)
![Chapter 4 PDF Page 08](assets/chapter4_pdf_pages/ch4-page-08.png)
![Chapter 4 PDF Page 09](assets/chapter4_pdf_pages/ch4-page-09.png)
![Chapter 4 PDF Page 10](assets/chapter4_pdf_pages/ch4-page-10.png)
![Chapter 4 PDF Page 11](assets/chapter4_pdf_pages/ch4-page-11.png)
![Chapter 4 PDF Page 12](assets/chapter4_pdf_pages/ch4-page-12.png)
![Chapter 4 PDF Page 13](assets/chapter4_pdf_pages/ch4-page-13.png)
![Chapter 4 PDF Page 14](assets/chapter4_pdf_pages/ch4-page-14.png)
![Chapter 4 PDF Page 15](assets/chapter4_pdf_pages/ch4-page-15.png)
![Chapter 4 PDF Page 16](assets/chapter4_pdf_pages/ch4-page-16.png)
![Chapter 4 PDF Page 17](assets/chapter4_pdf_pages/ch4-page-17.png)
![Chapter 4 PDF Page 18](assets/chapter4_pdf_pages/ch4-page-18.png)
![Chapter 4 PDF Page 19](assets/chapter4_pdf_pages/ch4-page-19.png)
![Chapter 4 PDF Page 20](assets/chapter4_pdf_pages/ch4-page-20.png)
![Chapter 4 PDF Page 21](assets/chapter4_pdf_pages/ch4-page-21.png)
![Chapter 4 PDF Page 22](assets/chapter4_pdf_pages/ch4-page-22.png)
![Chapter 4 PDF Page 23](assets/chapter4_pdf_pages/ch4-page-23.png)
![Chapter 4 PDF Page 24](assets/chapter4_pdf_pages/ch4-page-24.png)
![Chapter 4 PDF Page 25](assets/chapter4_pdf_pages/ch4-page-25.png)
![Chapter 4 PDF Page 26](assets/chapter4_pdf_pages/ch4-page-26.png)
![Chapter 4 PDF Page 27](assets/chapter4_pdf_pages/ch4-page-27.png)
![Chapter 4 PDF Page 28](assets/chapter4_pdf_pages/ch4-page-28.png)
![Chapter 4 PDF Page 29](assets/chapter4_pdf_pages/ch4-page-29.png)
![Chapter 4 PDF Page 30](assets/chapter4_pdf_pages/ch4-page-30.png)
![Chapter 4 PDF Page 31](assets/chapter4_pdf_pages/ch4-page-31.png)
![Chapter 4 PDF Page 32](assets/chapter4_pdf_pages/ch4-page-32.png)
![Chapter 4 PDF Page 33](assets/chapter4_pdf_pages/ch4-page-33.png)
![Chapter 4 PDF Page 34](assets/chapter4_pdf_pages/ch4-page-34.png)
![Chapter 4 PDF Page 35](assets/chapter4_pdf_pages/ch4-page-35.png)
![Chapter 4 PDF Page 36](assets/chapter4_pdf_pages/ch4-page-36.png)

</details>

## Chapter 4: Networking Services

<!-- CHAPTER_FOCUS_CH4_START -->
### Focus Highlights (Chapter 4: Networking Services)
- <mark>Security Group</mark> = stateful (instance-level)
- <mark>Network ACL</mark> = stateless (subnet-level)
- <mark>SNAT vs DNAT/EIP</mark>: use SNAT for outbound, use DNAT/EIP for inbound
<!-- CHAPTER_FOCUS_CH4_END -->

📚 สรุปเนื้อหา
1. Cloud Network - VPC (Virtual Private Cloud)
VPC คือ Private network บน Cloud เหมือน LAN ส่วนตัว
VPC ประกอบด้วย: Subnet, Route Table, Security Group, Network ACL
หมายเหตุ: Subnet ภายใน VPC สื่อสารกันได้จาก implicit distributed router ของ VPC ไม่ใช่เพราะ route table
Security Group = Firewall ระดับ Instance (Stateful), กำหนด Inbound/Outbound rules
Network ACL = Firewall ระดับ Subnet (Stateless), กำหนด Allow/Deny rules
Route Table: default route (0.0.0.0/0) ใช้สำหรับออก Internet/NAT ไม่ใช่กลไกหลักที่ทำให้ subnet ภายใน VPC คุยกัน
2. Cloud Network Connectivity
EIP (Elastic IP): Public IP ที่ Bind กับ ECS เพื่อให้เข้าถึงจาก Internet
NAT Gateway: ให้หลาย ECS ใช้ Public IP เดียวกัน (SNAT) หรือรับ traffic จาก internet (DNAT)
VPC Peering: เชื่อมต่อ 2 VPC เข้าหากัน (ภายใน Region เดียวกัน)
VPN: เชื่อมต่อ On-premise network กับ Huawei Cloud VPC ผ่าน Encrypted tunnel
Direct Connect: Dedicated network connection ระหว่าง On-premise และ Huawei Cloud (ความเร็วสูง, Latency ต่ำ)
ELB (Elastic Load Balance): กระจาย Traffic ไปยังหลาย ECS
3. Networking Best Practices
ออกแบบ VPC ให้รองรับ workload แยก: Dev, Test, Prod ควรอยู่ใน VPC แยกกัน
ใช้ Security Group ควบคุม Access ระดับ Instance
ใช้ NAT Gateway แทน EIP เพื่อลดการ expose Public IP โดยตรง
ใช้ VPC Peering หรือ Transit Gateway เชื่อมต่อหลาย VPC
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH4_START -->
```text
+---------------- Chapter 4 Snapshot ----------------+
| VPC = private network (subnet / route / SG / ACL)  |
| SG: stateful (instance level)                      |
| ACL: stateless (subnet level)                      |
| EIP/NAT/VPN/DC/ELB for connectivity and traffic    |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH4_END -->

### Practice Questions

**ข้อ 1: VPC ย่อมาจากอะไร และทำหน้าที่อะไร?**
- A. Virtual Personal Computer — เครื่องคอมพิวเตอร์เสมือน
- B. Virtual Private Cloud — Private network บน Cloud
- C. Virtual Proxy Connection — การเชื่อมต่อผ่าน Proxy
- D. Variable Protocol Cluster — กลุ่ม Protocol
> **Answer:** B — VPC (Virtual Private Cloud) คือ private network บน Cloud สำหรับกำหนด IP, subnet, routing และ security

**ข้อ 2: ความแตกต่างหลักระหว่าง Security Group และ Network ACL คืออะไร?**
- A. Security Group ใช้กับ Subnet, Network ACL ใช้กับ Instance
- B. Security Group ใช้กับ Instance (Stateful), Network ACL ใช้กับ Subnet (Stateless)
- C. Security Group ฟรี, Network ACL มีค่าใช้จ่าย
- D. ไม่มีความแตกต่าง
> **Answer:** B — Security Group ผูกกับ Instance และเป็น Stateful; Network ACL ผูกกับ Subnet และเป็น Stateless

**ข้อ 3: ต้องการให้ ECS หลายตัวใช้ Public IP เดียวกันในการออก Internet ควรใช้อะไร?**
- A. EIP ให้ทุก ECS
- B. NAT Gateway (SNAT)
- C. VPC Peering
- D. Direct Connect
> **Answer:** B — ใช้ NAT Gateway (SNAT) ให้หลาย ECS ออก Internet ผ่าน Public IP เดียว

**ข้อ 4: VPN กับ Direct Connect ต่างกันอย่างไร?**
- A. VPN เร็วกว่าและแพงกว่า Direct Connect
- B. Direct Connect เป็น Dedicated link ความเร็วสูง Latency ต่ำ, VPN ใช้ Internet เข้ารหัส
- C. ทั้งคู่ใช้ Internet สาธารณะ
- D. Direct Connect ใช้ได้เฉพาะใน Region เดียวกัน
> **Answer:** B — Direct Connect เป็น dedicated link latency ต่ำ; VPN ใช้ Internet และเข้ารหัส

**ข้อ 5: ELB ทำหน้าที่อะไร?**
- A. เข้ารหัสข้อมูล
- B. กระจาย Traffic ไปยังหลาย ECS
- C. สร้าง VPN connection
- D. จัดการ DNS
> **Answer:** B — กระจาย Traffic ไปยังหลาย ECS
 
### Chapter 5: Database Services - Images from PDF
<details>
<summary>Click to expand Chapter 5 images (37 pages)</summary>

![Chapter 5 PDF Page 01](assets/chapter5_pdf_pages/ch5-page-01.png)
![Chapter 5 PDF Page 02](assets/chapter5_pdf_pages/ch5-page-02.png)
![Chapter 5 PDF Page 03](assets/chapter5_pdf_pages/ch5-page-03.png)
![Chapter 5 PDF Page 04](assets/chapter5_pdf_pages/ch5-page-04.png)
![Chapter 5 PDF Page 05](assets/chapter5_pdf_pages/ch5-page-05.png)
![Chapter 5 PDF Page 06](assets/chapter5_pdf_pages/ch5-page-06.png)
![Chapter 5 PDF Page 07](assets/chapter5_pdf_pages/ch5-page-07.png)
![Chapter 5 PDF Page 08](assets/chapter5_pdf_pages/ch5-page-08.png)
![Chapter 5 PDF Page 09](assets/chapter5_pdf_pages/ch5-page-09.png)
![Chapter 5 PDF Page 10](assets/chapter5_pdf_pages/ch5-page-10.png)
![Chapter 5 PDF Page 11](assets/chapter5_pdf_pages/ch5-page-11.png)
![Chapter 5 PDF Page 12](assets/chapter5_pdf_pages/ch5-page-12.png)
![Chapter 5 PDF Page 13](assets/chapter5_pdf_pages/ch5-page-13.png)
![Chapter 5 PDF Page 14](assets/chapter5_pdf_pages/ch5-page-14.png)
![Chapter 5 PDF Page 15](assets/chapter5_pdf_pages/ch5-page-15.png)
![Chapter 5 PDF Page 16](assets/chapter5_pdf_pages/ch5-page-16.png)
![Chapter 5 PDF Page 17](assets/chapter5_pdf_pages/ch5-page-17.png)
![Chapter 5 PDF Page 18](assets/chapter5_pdf_pages/ch5-page-18.png)
![Chapter 5 PDF Page 19](assets/chapter5_pdf_pages/ch5-page-19.png)
![Chapter 5 PDF Page 20](assets/chapter5_pdf_pages/ch5-page-20.png)
![Chapter 5 PDF Page 21](assets/chapter5_pdf_pages/ch5-page-21.png)
![Chapter 5 PDF Page 22](assets/chapter5_pdf_pages/ch5-page-22.png)
![Chapter 5 PDF Page 23](assets/chapter5_pdf_pages/ch5-page-23.png)
![Chapter 5 PDF Page 24](assets/chapter5_pdf_pages/ch5-page-24.png)
![Chapter 5 PDF Page 25](assets/chapter5_pdf_pages/ch5-page-25.png)
![Chapter 5 PDF Page 26](assets/chapter5_pdf_pages/ch5-page-26.png)
![Chapter 5 PDF Page 27](assets/chapter5_pdf_pages/ch5-page-27.png)
![Chapter 5 PDF Page 28](assets/chapter5_pdf_pages/ch5-page-28.png)
![Chapter 5 PDF Page 29](assets/chapter5_pdf_pages/ch5-page-29.png)
![Chapter 5 PDF Page 30](assets/chapter5_pdf_pages/ch5-page-30.png)
![Chapter 5 PDF Page 31](assets/chapter5_pdf_pages/ch5-page-31.png)
![Chapter 5 PDF Page 32](assets/chapter5_pdf_pages/ch5-page-32.png)
![Chapter 5 PDF Page 33](assets/chapter5_pdf_pages/ch5-page-33.png)
![Chapter 5 PDF Page 34](assets/chapter5_pdf_pages/ch5-page-34.png)
![Chapter 5 PDF Page 35](assets/chapter5_pdf_pages/ch5-page-35.png)
![Chapter 5 PDF Page 36](assets/chapter5_pdf_pages/ch5-page-36.png)
![Chapter 5 PDF Page 37](assets/chapter5_pdf_pages/ch5-page-37.png)

</details>

## Chapter 5: Database Services

<!-- CHAPTER_FOCUS_CH5_START -->
### Focus Highlights (Chapter 5: Database Services)
- <mark>RDS</mark>: managed relational DB with backup/failover capabilities
- <mark>Engine/Version</mark>: always verify availability by Region
- <mark>DAS</mark>: O&M/SQL web tool, not a database engine
<!-- CHAPTER_FOCUS_CH5_END -->

📚 สรุปเนื้อหา
1. Introduction to Database Services
Database แบ่งเป็น 2 ประเภทหลัก: Relational (SQL) และ Non-Relational (NoSQL)
Relational DB: Structured data, ACID transactions เช่น MySQL, PostgreSQL, SQL Server
Non-Relational DB: Flexible schema, High scalability เช่น MongoDB, Redis, Cassandra
Huawei Cloud มีบริการ Database ครบทั้ง 2 ประเภท พร้อม Managed service
2. Relational Database Services (RDS)
RDS รองรับ: MySQL, PostgreSQL, Microsoft SQL Server, MariaDB
หมายเหตุ: ความพร้อมใช้งานของ engine/เวอร์ชันขึ้นกับแต่ละ Region ของ Huawei Cloud
Features: Automated backup, HA (High Availability) with standby, Read replica, Auto scaling
RDS จัดการ: Patching, Backup, Monitoring, Failover อัตโนมัติ
GaussDB: Huawei's Enterprise-grade relational DB, compatible with Oracle
DDM (Distributed Database Middleware): แก้ปัญหา Database sharding
3. Non-Relational Database Services
DCS (Distributed Cache Service): Redis/Memcached ใช้สำหรับ Caching, Session management
DDS (Document Database Service): MongoDB-compatible ใช้สำหรับ Document storage
GaussDB NoSQL: เหมาะกับ IoT, Log analytics, Wide-column data
CSS (Cloud Search Service): Elasticsearch-based สำหรับ Full-text search
4. Data Admin Service (DAS)
DAS คือ Web-based Database management tool บน Huawei Cloud
ใช้จัดการ Database ผ่าน Browser โดยไม่ต้องติดตั้ง Client
รองรับ: Query editor, Table management, Data import/export, Monitoring
เหมาะกับ DBA และ Developer ที่ต้องการ เข้าถึง DB แบบ Secure บน Cloud
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH5_START -->
```text
+---------------- Chapter 5 Snapshot ----------------+
| RDS: managed relational DB (MySQL/PostgreSQL etc.) |
| DCS: in-memory cache (Redis/Memcached)             |
| DDS: document DB (MongoDB-compatible)              |
| DAS: web-based DB O&M and SQL operations           |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH5_END -->

### Practice Questions

**ข้อ 1: ข้อใดคือ Relational Database ที่ RDS รองรับ?**
- A. MongoDB
- B. Redis
- C. MySQL
- D. Cassandra
> **Answer:** C — RDS รองรับ MySQL (เชิงสัมพันธ์)

**ข้อ 2: DCS ใช้สำหรับอะไร?**
- A. Block storage
- B. In-memory caching (Redis/Memcached)
- C. File sharing
- D. Full-text search
> **Answer:** B — In-memory caching (Redis/Memcached)

**ข้อ 3: ข้อใดคือข้อดีของ Managed Database (RDS) เทียบกับ Self-managed?**
- A. ราคาถูกกว่าเสมอ
- B. Huawei จัดการ Backup, Patching, Failover อัตโนมัติ
- C. Performance สูงกว่าเสมอ
- D. รองรับ Database engine มากกว่า
> **Answer:** B — จัดการ Backup, Patching และ Failover อัตโนมัติ

**ข้อ 4: GaussDB มีจุดเด่นอะไร?**
- A. เป็น Open-source NoSQL
- B. Enterprise-grade DB ที่ Compatible กับ Oracle
- C. เหมาะกับ IoT เท่านั้น
- D. ใช้ได้เฉพาะกับ Linux
> **Answer:** B — Enterprise-grade DB ที่มีความเข้ากันได้กับ Oracle

**ข้อ 5: DAS คืออะไร?**
- A. Database ชนิดหนึ่ง
- B. Web-based tool จัดการ Database ผ่าน Browser
- C. Data Archive Service
- D. Distributed Application Server
> **Answer:** B — Web-based tool จัดการ Database ผ่าน Browser

### Chapter 6: Security Services - Images from PDF
<details>
<summary>Click to expand Chapter 6 images (35 pages)</summary>

![Chapter 6 PDF Page 01](assets/chapter6_pdf_pages/ch6-page-01.png)
![Chapter 6 PDF Page 02](assets/chapter6_pdf_pages/ch6-page-02.png)
![Chapter 6 PDF Page 03](assets/chapter6_pdf_pages/ch6-page-03.png)
![Chapter 6 PDF Page 04](assets/chapter6_pdf_pages/ch6-page-04.png)
![Chapter 6 PDF Page 05](assets/chapter6_pdf_pages/ch6-page-05.png)
![Chapter 6 PDF Page 06](assets/chapter6_pdf_pages/ch6-page-06.png)
![Chapter 6 PDF Page 07](assets/chapter6_pdf_pages/ch6-page-07.png)
![Chapter 6 PDF Page 08](assets/chapter6_pdf_pages/ch6-page-08.png)
![Chapter 6 PDF Page 09](assets/chapter6_pdf_pages/ch6-page-09.png)
![Chapter 6 PDF Page 10](assets/chapter6_pdf_pages/ch6-page-10.png)
![Chapter 6 PDF Page 11](assets/chapter6_pdf_pages/ch6-page-11.png)
![Chapter 6 PDF Page 12](assets/chapter6_pdf_pages/ch6-page-12.png)
![Chapter 6 PDF Page 13](assets/chapter6_pdf_pages/ch6-page-13.png)
![Chapter 6 PDF Page 14](assets/chapter6_pdf_pages/ch6-page-14.png)
![Chapter 6 PDF Page 15](assets/chapter6_pdf_pages/ch6-page-15.png)
![Chapter 6 PDF Page 16](assets/chapter6_pdf_pages/ch6-page-16.png)
![Chapter 6 PDF Page 17](assets/chapter6_pdf_pages/ch6-page-17.png)
![Chapter 6 PDF Page 18](assets/chapter6_pdf_pages/ch6-page-18.png)
![Chapter 6 PDF Page 19](assets/chapter6_pdf_pages/ch6-page-19.png)
![Chapter 6 PDF Page 20](assets/chapter6_pdf_pages/ch6-page-20.png)
![Chapter 6 PDF Page 21](assets/chapter6_pdf_pages/ch6-page-21.png)
![Chapter 6 PDF Page 22](assets/chapter6_pdf_pages/ch6-page-22.png)
![Chapter 6 PDF Page 23](assets/chapter6_pdf_pages/ch6-page-23.png)
![Chapter 6 PDF Page 24](assets/chapter6_pdf_pages/ch6-page-24.png)
![Chapter 6 PDF Page 25](assets/chapter6_pdf_pages/ch6-page-25.png)
![Chapter 6 PDF Page 26](assets/chapter6_pdf_pages/ch6-page-26.png)
![Chapter 6 PDF Page 27](assets/chapter6_pdf_pages/ch6-page-27.png)
![Chapter 6 PDF Page 28](assets/chapter6_pdf_pages/ch6-page-28.png)
![Chapter 6 PDF Page 29](assets/chapter6_pdf_pages/ch6-page-29.png)
![Chapter 6 PDF Page 30](assets/chapter6_pdf_pages/ch6-page-30.png)
![Chapter 6 PDF Page 31](assets/chapter6_pdf_pages/ch6-page-31.png)
![Chapter 6 PDF Page 32](assets/chapter6_pdf_pages/ch6-page-32.png)
![Chapter 6 PDF Page 33](assets/chapter6_pdf_pages/ch6-page-33.png)
![Chapter 6 PDF Page 34](assets/chapter6_pdf_pages/ch6-page-34.png)
![Chapter 6 PDF Page 35](assets/chapter6_pdf_pages/ch6-page-35.png)

</details>

## Chapter 6: Security Services

<!-- CHAPTER_FOCUS_CH6_START -->
### Focus Highlights (Chapter 6: Security Services)
- <mark>Shared Responsibility</mark>: provider handles infra, tenant handles OS/app/data/config
- <mark>IAM/KMS/CTS</mark>: identity + key management + audit trail
- <mark>WAF vs Anti-DDoS</mark>: L7 web attacks vs L3/L4 volumetric
<!-- CHAPTER_FOCUS_CH6_END -->

📚 สรุปเนื้อหา
1. The Shared Responsibility Model
Security บน Cloud เป็นความรับผิดชอบร่วมระหว่าง Huawei Cloud และ Tenant
Huawei Cloud รับผิดชอบ: Physical security, Infrastructure, Hypervisor, Managed services
Tenant รับผิดชอบ: OS, Application, Data, Access management บน VM
Platform Services: Huawei รับผิดชอบมากกว่า, Application Services: Tenant รับผิดชอบมากกว่า
2. Huawei Cloud Security Certifications
Huawei Cloud ได้รับ Certification มากกว่า 50 ใบทั่วโลก
รวมถึง: ISO 27001, SOC 1/2/3, PCI-DSS, CSA STAR, GDPR compliance
ใบรับรองเหล่านี้แสดงถึงมาตรฐาน Security ระดับสากล
3. Systematic Security Design
IAM (Identity & Access Management): จัดการ User, Role, Policy, MFA
IAM สนับสนุน: Fine-grained permission, Federation (SSO), Service Account
DEW (Data Encryption Workshop): จัดการ Encryption Key (KMS - Key Management Service)
CTS (Cloud Trace Service): บันทึก Audit log การกระทำทุกอย่างบน Console/API
HSS (Host Security Service): Anti-malware, Vulnerability scan สำหรับ ECS
WAF (Web Application Firewall): ป้องกัน OWASP Top 10, DDoS
WAF ป้องกัน L7 web attacks (SQLi, XSS, OWASP Top10) ส่วน volumetric DDoS ใช้ Anti-DDoS service แยกต่างหาก
Security หลายชั้น: Network (Security Group, WAF) → Host (HSS) → Data (KMS, CTS)
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH6_START -->
```text
+---------------- Chapter 6 Snapshot ----------------+
| Shared responsibility: provider + tenant            |
| IAM/KMS/CTS: identity, keys, audit                 |
| WAF: Layer-7 web attacks (SQLi/XSS)                |
| Anti-DDoS: volumetric Layer-3/4 attacks            |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH6_END -->

### Practice Questions

**ข้อ 1: ใน Shared Responsibility Model ใครรับผิดชอบ Physical security ของ Data center?**
- A. Tenant
- B. Huawei Cloud
- C. ทั้งคู่เท่ากัน
- D. Third-party auditor
> **Answer:** B — Huawei Cloud รับผิดชอบ physical security ของดาต้าเซ็นเตอร์

**ข้อ 2: IAM ย่อมาจากอะไร?**
- A. Internet Access Management
- B. Identity and Access Management
- C. Image and Asset Management
- D. Intelligent API Monitor
> **Answer:** B — Identity and Access Management

**ข้อ 3: KMS ใน DEW ทำหน้าที่อะไร?**
- A. Monitor Network traffic
- B. จัดการ Encryption Key สำหรับเข้ารหัสข้อมูล
- C. Scan Vulnerability บน ECS
- D. บันทึก Audit log
> **Answer:** B — จัดการ Encryption Key สำหรับการเข้ารหัส/ถอดรหัสข้อมูล

**ข้อ 4: CTS (Cloud Trace Service) ใช้ทำอะไร?**
- A. ตรวจสอบ Performance ของ ECS
- B. บันทึก Audit trail ของ Action ทั้งหมดบน Huawei Cloud
- C. Encrypt ข้อมูลใน OBS
- D. Block DDoS attack
> **Answer:** B — บันทึก Audit trail ของการกระทำทั้งหมดบน Huawei Cloud

**ข้อ 5: WAF ป้องกันอะไร?**
- A. Physical intrusion
- B. Web Application attacks เช่น SQL Injection, XSS (OWASP Top 10)
- C. Network packet loss
- D. Disk failure
> **Answer:** B — Web Application attacks เช่น SQL Injection, XSS (OWASP Top 10)

### Chapter 7: Elastic Cloud Services for Distributed Deployment - Images from PDF
<details>
<summary>Click to expand Chapter 7 images (40 pages)</summary>

![Chapter 7 PDF Page 01](assets/chapter7_pdf_pages/ch7-page-01.png)
![Chapter 7 PDF Page 02](assets/chapter7_pdf_pages/ch7-page-02.png)
![Chapter 7 PDF Page 03](assets/chapter7_pdf_pages/ch7-page-03.png)
![Chapter 7 PDF Page 04](assets/chapter7_pdf_pages/ch7-page-04.png)
![Chapter 7 PDF Page 05](assets/chapter7_pdf_pages/ch7-page-05.png)
![Chapter 7 PDF Page 06](assets/chapter7_pdf_pages/ch7-page-06.png)
![Chapter 7 PDF Page 07](assets/chapter7_pdf_pages/ch7-page-07.png)
![Chapter 7 PDF Page 08](assets/chapter7_pdf_pages/ch7-page-08.png)
![Chapter 7 PDF Page 09](assets/chapter7_pdf_pages/ch7-page-09.png)
![Chapter 7 PDF Page 10](assets/chapter7_pdf_pages/ch7-page-10.png)
![Chapter 7 PDF Page 11](assets/chapter7_pdf_pages/ch7-page-11.png)
![Chapter 7 PDF Page 12](assets/chapter7_pdf_pages/ch7-page-12.png)
![Chapter 7 PDF Page 13](assets/chapter7_pdf_pages/ch7-page-13.png)
![Chapter 7 PDF Page 14](assets/chapter7_pdf_pages/ch7-page-14.png)
![Chapter 7 PDF Page 15](assets/chapter7_pdf_pages/ch7-page-15.png)
![Chapter 7 PDF Page 16](assets/chapter7_pdf_pages/ch7-page-16.png)
![Chapter 7 PDF Page 17](assets/chapter7_pdf_pages/ch7-page-17.png)
![Chapter 7 PDF Page 18](assets/chapter7_pdf_pages/ch7-page-18.png)
![Chapter 7 PDF Page 19](assets/chapter7_pdf_pages/ch7-page-19.png)
![Chapter 7 PDF Page 20](assets/chapter7_pdf_pages/ch7-page-20.png)
![Chapter 7 PDF Page 21](assets/chapter7_pdf_pages/ch7-page-21.png)
![Chapter 7 PDF Page 22](assets/chapter7_pdf_pages/ch7-page-22.png)
![Chapter 7 PDF Page 23](assets/chapter7_pdf_pages/ch7-page-23.png)
![Chapter 7 PDF Page 24](assets/chapter7_pdf_pages/ch7-page-24.png)
![Chapter 7 PDF Page 25](assets/chapter7_pdf_pages/ch7-page-25.png)
![Chapter 7 PDF Page 26](assets/chapter7_pdf_pages/ch7-page-26.png)
![Chapter 7 PDF Page 27](assets/chapter7_pdf_pages/ch7-page-27.png)
![Chapter 7 PDF Page 28](assets/chapter7_pdf_pages/ch7-page-28.png)
![Chapter 7 PDF Page 29](assets/chapter7_pdf_pages/ch7-page-29.png)
![Chapter 7 PDF Page 30](assets/chapter7_pdf_pages/ch7-page-30.png)
![Chapter 7 PDF Page 31](assets/chapter7_pdf_pages/ch7-page-31.png)
![Chapter 7 PDF Page 32](assets/chapter7_pdf_pages/ch7-page-32.png)
![Chapter 7 PDF Page 33](assets/chapter7_pdf_pages/ch7-page-33.png)
![Chapter 7 PDF Page 34](assets/chapter7_pdf_pages/ch7-page-34.png)
![Chapter 7 PDF Page 35](assets/chapter7_pdf_pages/ch7-page-35.png)
![Chapter 7 PDF Page 36](assets/chapter7_pdf_pages/ch7-page-36.png)
![Chapter 7 PDF Page 37](assets/chapter7_pdf_pages/ch7-page-37.png)
![Chapter 7 PDF Page 38](assets/chapter7_pdf_pages/ch7-page-38.png)
![Chapter 7 PDF Page 39](assets/chapter7_pdf_pages/ch7-page-39.png)
![Chapter 7 PDF Page 40](assets/chapter7_pdf_pages/ch7-page-40.png)

</details>

## Chapter 7: Elastic Cloud Services for Distributed Deployment

<!-- CHAPTER_FOCUS_CH7_START -->
### Focus Highlights (Chapter 7: Elastic Cloud Services for Distributed Deployment)
- <mark>Scale Up</mark>: increase spec on existing instance
- <mark>Scale Out</mark>: increase number of ECS instances
- <mark>ELB + AS</mark>: load distribution + policy-based auto scaling
<!-- CHAPTER_FOCUS_CH7_END -->

📚 สรุปเนื้อหา
1. Scalability Implementation
Scalability คือความสามารถรองรับ Traffic ที่เพิ่มขึ้นโดยไม่กระทบ Performance
ความสำคัญ: Traffic ของแอปพลิเคชันมีความผันผวน เช่น Double 11, Flash sales
Scaling Up (Vertical): เพิ่ม CPU/RAM ของ ECS ตัวเดิม — ง่ายแต่มี Limit
Scaling Out (Horizontal): เพิ่มจำนวน ECS — ยืดหยุ่นกว่า ไม่มี Single point of failure
2. How to Build Scalable Applications
ELB (Elastic Load Balance): กระจาย Traffic ไปยังหลาย ECS อัตโนมัติ
ELB Types: Dedicated ELB, Shared ELB
ELB Protocols: HTTP/HTTPS, TCP/UDP
AS (Auto Scaling): ปรับจำนวน ECS อัตโนมัติตาม Policy ที่กำหนด
AS Policy Types: Alarm-based (CPU > 80% → เพิ่ม ECS), Scheduled (เวลาที่กำหนด), Periodic
AS Group กำหนด Min/Max/Desired instances เพื่อควบคุม Cost
3. Typical Scalable Website Architecture
สถาปัตยกรรมมาตรฐาน: DNS → ELB → ECS Group (AS) → RDS (HA) + OBS
Cache layer: DCS (Redis) ลด Load ให้ Database
CDN: กระจาย Static content ใกล้ผู้ใช้ ลด Latency
Scalable applications ช่วย optimize cost และ improve resource utilization เมื่อเทียบกับการเตรียมทรัพยากรแบบ fixed capacity
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>

<!-- DIAGRAM_SNAPSHOT_CH7_START -->
```text
+---------------- Chapter 7 Snapshot ----------------+
| Scale Up: increase spec of existing ECS            |
| Scale Out: increase number of ECS                  |
| ELB + AS: distribute load and auto-adjust capacity |
| Typical path: DNS -> ELB -> ECS -> DB/Cache        |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH7_END -->

### Practice Questions

**ข้อ 1: Scaling Up แตกต่างจาก Scaling Out อย่างไร?**
- A. Scaling Up เพิ่มจำนวน Server, Scaling Out เพิ่ม Spec Server
- B. Scaling Up เพิ่ม CPU/RAM เครื่องเดิม, Scaling Out เพิ่มจำนวน Server
- C. ทั้งคู่เหมือนกัน
- D. Scaling Up ใช้กับ Database, Scaling Out ใช้กับ Web server เท่านั้น
> **Answer:** B — Scaling Up เพิ่ม CPU/RAM ของเครื่องเดิม; Scaling Out เพิ่มจำนวนเครื่อง (ECS)

**ข้อ 2: AS (Auto Scaling) ทำงานอย่างไร?**
- A. เพิ่ม RAM ของ ECS อัตโนมัติ
- B. ปรับจำนวน ECS อัตโนมัติตาม Policy เช่น CPU threshold หรือ Schedule
- C. Backup ข้อมูลอัตโนมัติ
- D. อัปเดต OS อัตโนมัติ
> **Answer:** B — ปรับจำนวน ECS อัตโนมัติตาม Policy (เช่น CPU threshold หรือ Schedule)

**ข้อ 3: ELB Algorithm ใดกระจาย Request ไปยัง ECS ที่มี Connection น้อยที่สุด?**
- A. Round Robin
- B. Weighted Round Robin
- C. Least Connections
- D. IP Hash
> **Answer:** C — Least Connections

**ข้อ 4: ทำไมต้องใช้ Cache (DCS/Redis) ใน Web architecture?**
- A. เพื่อเพิ่ม Storage space
- B. เพื่อลด Load ให้ Database โดยเก็บ Frequently accessed data ใน Memory
- C. เพื่อ Encrypt ข้อมูล
- D. เพื่อ Monitor performance
> **Answer:** B — ลดโหลดฐานข้อมูลโดยเก็บข้อมูลที่เรียกใช้บ่อยไว้ในหน่วยความจำ

**ข้อ 5: Multi-AZ deployment มีประโยชน์อย่างไร?**
- A. ลดค่าใช้จ่าย
- B. เพิ่ม High Availability โดยป้องกัน AZ failure
- C. เพิ่มความเร็ว Processing
- D. ลด Network latency
> **Answer:** B — เพิ่ม High Availability โดยป้องกัน AZ failure

### Chapter 8: Cloud Native and Transformation - Images from PDF
<details>
<summary>Click to expand Chapter 8 images (25 pages)</summary>

![Chapter 8 PDF Page 01](assets/chapter8_pdf_pages/ch8-page-01.png)
![Chapter 8 PDF Page 02](assets/chapter8_pdf_pages/ch8-page-02.png)
![Chapter 8 PDF Page 03](assets/chapter8_pdf_pages/ch8-page-03.png)
![Chapter 8 PDF Page 04](assets/chapter8_pdf_pages/ch8-page-04.png)
![Chapter 8 PDF Page 05](assets/chapter8_pdf_pages/ch8-page-05.png)
![Chapter 8 PDF Page 06](assets/chapter8_pdf_pages/ch8-page-06.png)
![Chapter 8 PDF Page 07](assets/chapter8_pdf_pages/ch8-page-07.png)
![Chapter 8 PDF Page 08](assets/chapter8_pdf_pages/ch8-page-08.png)
![Chapter 8 PDF Page 09](assets/chapter8_pdf_pages/ch8-page-09.png)
![Chapter 8 PDF Page 10](assets/chapter8_pdf_pages/ch8-page-10.png)
![Chapter 8 PDF Page 11](assets/chapter8_pdf_pages/ch8-page-11.png)
![Chapter 8 PDF Page 12](assets/chapter8_pdf_pages/ch8-page-12.png)
![Chapter 8 PDF Page 13](assets/chapter8_pdf_pages/ch8-page-13.png)
![Chapter 8 PDF Page 14](assets/chapter8_pdf_pages/ch8-page-14.png)
![Chapter 8 PDF Page 15](assets/chapter8_pdf_pages/ch8-page-15.png)
![Chapter 8 PDF Page 16](assets/chapter8_pdf_pages/ch8-page-16.png)
![Chapter 8 PDF Page 17](assets/chapter8_pdf_pages/ch8-page-17.png)
![Chapter 8 PDF Page 18](assets/chapter8_pdf_pages/ch8-page-18.png)
![Chapter 8 PDF Page 19](assets/chapter8_pdf_pages/ch8-page-19.png)
![Chapter 8 PDF Page 20](assets/chapter8_pdf_pages/ch8-page-20.png)
![Chapter 8 PDF Page 21](assets/chapter8_pdf_pages/ch8-page-21.png)
![Chapter 8 PDF Page 22](assets/chapter8_pdf_pages/ch8-page-22.png)
![Chapter 8 PDF Page 23](assets/chapter8_pdf_pages/ch8-page-23.png)
![Chapter 8 PDF Page 24](assets/chapter8_pdf_pages/ch8-page-24.png)
![Chapter 8 PDF Page 25](assets/chapter8_pdf_pages/ch8-page-25.png)

</details>

## Chapter 8: Cloud Native and Transformation

<!-- CHAPTER_FOCUS_CH8_START -->
### Focus Highlights (Chapter 8: Cloud Native and Transformation)
- <mark>Cloud Native</mark>: microservices + containers + DevOps/CI-CD
- <mark>CCE</mark>: managed Kubernetes service
- <mark>FunctionGraph</mark>: serverless, pay-per-execution
<!-- CHAPTER_FOCUS_CH8_END -->

📚 สรุปเนื้อหา
1. Overview of Cloud Native Transformation
Cloud Native คือ การออกแบบ Application ให้ใช้ประโยชน์จาก Cloud เต็มที่
Digital Transformation ช่วยองค์กรพัฒนา: Customer experience, Intelligent operations, Strategic decision
Cloud Native คือการออกแบบสถาปัตยกรรมให้เหมาะกับ Cloud (stateless, automation, elasticity) ไม่ใช่เพียงการย้ายระบบขึ้น Cloud หรือใช้ Container
เหตุผลที่ต้อง Cloud Native: ลด Time-to-market, เพิ่ม Agility, ลด Cost, รองรับ Scale
2. Key Technologies for Cloud Native Transformation
Container: Docker เป็น Standard packaging สำหรับ Application (Lightweight, Portable)
Kubernetes (K8s): Container Orchestration ควบคุม Container lifecycle
CCE (Cloud Container Engine): Managed Kubernetes บน Huawei Cloud
Microservices: แบ่ง Application เป็น Service เล็กๆ อิสระ Deploy ได้แยกกัน
ServiceMesh (Istio): จัดการ Service-to-service communication, Observability
DevOps + CI/CD: CodeArts บน Huawei Cloud รองรับ Code hosting, Build, Test, Deploy
Observability: Logging, Monitoring (AOM), Tracing เพื่อ Debug และ Optimize
<span style="background-color: #fff3e0; color: #e65100; font-weight: bold; padding: 2px 6px; border-radius: 4px;">🧪 แบบทดสอบ (5 ข้อ)</span>
<!-- DIAGRAM_SNAPSHOT_CH8_START -->
```text
+---------------- Chapter 8 Snapshot ----------------+
| Cloud Native: microservices + containers + DevOps  |
| CCE: managed Kubernetes on Huawei Cloud            |
| Serverless (FunctionGraph): run code per execution |
| Goal: agility, faster delivery, elastic operations |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH8_END -->

### Practice Questions

**ข้อ 1: ข้อใดสะท้อนองค์ประกอบหลักของ Cloud Native ได้ถูกต้องที่สุด?**
- A. 2 ข้อ: Container, Kubernetes
- B. 4 ข้อ: Microservices, Container, DevOps, CI/CD
- C. 3 ข้อ: IaaS, PaaS, SaaS
- D. 5 ข้อ: VM, Container, Serverless, DevOps, AI
> **Answer:** B — Cloud Native ประกอบด้วย Microservices, Container, DevOps และ CI/CD

**ข้อ 2: Container ต่างจาก Virtual Machine (VM) อย่างไร?**
- A. Container ต้องการ Full OS แยกต่างหาก, VM ไม่ต้องการ
- B. Container เบากว่า share OS kernel, VM มี Full OS แยกแต่ละ Instance
- C. Container ช้ากว่า VM
- D. ไม่มีความแตกต่าง
> **Answer:** B — Container share OS kernel และเบากว่า; VM มี Full OS แยกแต่ละ instance

**ข้อ 3: CCE บน Huawei Cloud คืออะไร?**
- A. Cloud Compute Engine — บริการ VM
- B. Cloud Container Engine — Managed Kubernetes Service
- C. Cloud Cache Environment — บริการ Redis
- D. Custom Configuration Environment — ตั้งค่า VM
> **Answer:** B — Cloud Container Engine คือ Managed Kubernetes Service

**ข้อ 4: FunctionGraph / Serverless มีข้อดีอะไร?**
- A. ต้องจัดการ Server เอง
- B. Run code โดยไม่ต้องจัดการ Server, จ่ายเฉพาะเมื่อ Function ทำงาน
- C. ต้องจองทรัพยากรล่วงหน้า
- D. เหมาะกับ Long-running process เท่านั้น
> **Answer:** B — รันโค้ดโดยไม่ต้องจัดการ Server และจ่ายเฉพาะตอนที่ฟังก์ชันทำงาน

**ข้อ 5: DevOps และ CI/CD ช่วยองค์กรอย่างไร?**
- A. ลด Security
- B. เพิ่ม Time-to-market โดย Automate Build, Test, Deploy
- C. เพิ่มจำนวน Manual step
- D. ลด Collaboration ระหว่างทีม
> **Answer:** B — เพิ่ม Time-to-market โดย Automate Build, Test, Deploy

## <span style="color: #c0392b;">Chapter 9: Exam Outline and Sample Questions</span>

> <span style="background-color: #ffebee; color: #b71c1c; font-weight: bold; padding: 3px 8px; border-radius: 4px;">🎯 EXAM SECTION — ข้อสอบจริง 30 ข้อ (T/F 10 + Single Choice 10 + Multiple Choice 10)</span>

<!-- CHAPTER_FOCUS_CH9_START -->
### Focus Highlights (Chapter 9: Exam Outline and Sample Questions)
- <mark>Exam Logic</mark>: ใช้การวิเคราะห์สถานการณ์ ไม่ยึดแค่การจำคีย์เวิร์ด
- <mark>Must-Know</mark>: shared responsibility, HA/Multi-AZ, elasticity
- <mark>Network & Security</mark>: SG/ACL/NAT/ELB/CTS/WAF ต้องแยกบทบาทให้ชัด
<!-- CHAPTER_FOCUS_CH9_END -->

<!-- DIAGRAM_SNAPSHOT_CH9_START -->
```text
+---------------- Chapter 9 Snapshot ----------------+
| Exam mix: T/F + Single Choice + Multiple Choice    |
| Focus: compute/network/storage/security fundamentals|
| Key logic: shared responsibility + HA + elasticity |
| Validate by scenario, not keyword matching only    |
+----------------------------------------------------+
```
<!-- DIAGRAM_SNAPSHOT_CH9_END -->

Total 30 questions | T/F: 10 | Single Choice: 10 | Multiple Choice: 10

### Part 1: True / False (1-10)

1) **If there are not enough servers, you can increase server quotas or upgrade the specifications of existing servers.**
*(หากเซิร์ฟเวอร์ไม่เพียงพอ สามารถเพิ่ม Quota หรืออัปเกรดสเปกเซิร์ฟเวอร์ที่มีอยู่ได้)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
2) **An RDS for MySQL primary/standby DB instance can be deployed only in one region.**
*(DB Instance แบบ Primary/Standby ของ RDS for MySQL สามารถ Deploy ได้ใน Region เดียวเท่านั้น)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
3) **A customer using Direct Connect or VPN between cloud and on-premises should use different CIDR blocks to avoid conflicts.**
*(ลูกค้าที่ใช้ Direct Connect หรือ VPN เชื่อม Cloud กับ On-premises ควรใช้ CIDR Block ที่แตกต่างกันเพื่อป้องกัน IP ชนกัน)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
4) **FunctionGraph enables users to focus on service logic instead of building container images.**
*(FunctionGraph ช่วยให้ผู้ใช้โฟกัสที่ Service Logic โดยไม่ต้องสร้าง Container Image เอง)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
5) **If one AZ fails, other AZs in the same region are generally isolated from that fault.**
*(หาก AZ หนึ่งล้มเหลว AZ อื่นใน Region เดียวกันโดยทั่วไปจะแยกตัวออกจากความผิดพลาดนั้น)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
6) **Yearly/monthly ECS can save money, but may cost more if not suitable for the workload.**
*(ECS แบบรายปี/รายเดือนประหยัดค่าใช้จ่ายได้ แต่อาจแพงกว่าหากรูปแบบไม่เหมาะกับ Workload)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
7) **ELB can route requests to backend servers across regions.**
*(ELB สามารถส่ง Request ไปยัง Backend Server ข้าม Region ได้)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **B. False**

</details>
8) **Elastic design improves reliability while helping with cost and performance targets.**
*(การออกแบบแบบ Elastic ช่วยเพิ่มความน่าเชื่อถือพร้อมควบคุมต้นทุนและประสิทธิภาพไปด้วยกัน)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
9) **Huawei Cloud is responsible for all security, including tenant data security.**
*(Huawei Cloud รับผิดชอบด้านความปลอดภัยทั้งหมด รวมถึงความปลอดภัยของข้อมูล Tenant ด้วย)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **B. False**

</details>
10) **OBS is pay-per-use while EVS billing is based on allocated disk capacity.**
*(OBS คิดค่าบริการตามการใช้งานจริง ส่วน EVS คิดตามความจุดิสก์ที่จัดสรรไว้)*
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A. True**

</details>
### Part 2: Single Choice (11-20)

11) **Which can be used to prevent resources in a VPC from communicating with each other?**
*(บริการใดสามารถใช้ป้องกันไม่ให้ทรัพยากรใน VPC สื่อสารกันเองได้?)*

- A. VPC
- B. NAT gateway
- C. Route table
- D. Security group
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **D**

</details>
12) **Which statement is true about ECS?**
*(ข้อใดกล่าวถูกต้องเกี่ยวกับ ECS?)*

- A. An ECS is a blade server.
- B. You only have limited permissions on guest OS.
- C. You must buy monthly/yearly for long-term use.
- D. You cannot control hypervisor version/patches.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **D**

</details>
13) **Which statement is true about VPC Peering and Cloud Connect?**
*(ข้อใดกล่าวถูกต้องเกี่ยวกับ VPC Peering และ Cloud Connect?)*

- A. VPC Peering can only connect VPCs of the same account.
- B. Cloud Connect is free.
- C. VPC Peering can connect VPCs across regions.
- D. Cloud Connect can connect different VPCs in the same region.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **D**

</details>
14) **Which statement about cloud native is FALSE?**
*(ข้อใดกล่าวผิดเกี่ยวกับ Cloud Native?)*

- A. Once migrated to cloud, an app is cloud native.
- B. Cloud native is not only containerization.
- C. Serverless lets developers focus on features.
- D. Containers reduce coupling to servers.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A**

</details>
15) **Which statement is TRUE?**
*(ข้อใดกล่าวถูกต้อง?)*

- A. There are more regions than AZs.
- B. A region with three AZs is geo-redundant DR.
- C. Edge nodes are closer to users and more distributed than regions.
- D. VPN is required between nodes in two AZs.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **C**

</details>
16) **For DDS testing without special availability/performance requirements, what is recommended?**
*(สำหรับการทดสอบ DDS ที่ไม่มีความต้องการพิเศษด้าน Availability หรือ Performance ควรใช้รูปแบบใด?)*

- A. Single node
- B. Replica set
- C. Cluster
- D. Primary/standby
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A**

</details>
17) **Which statement is FALSE about ECS flavor C6.2xlarge.4?**
*(ข้อใดกล่าวผิดเกี่ยวกับ ECS Flavor C6.2xlarge.4?)*

- A. Suitable for high-performance stable computing.
- B. Roughly half of c6.4xlarge.4 in spec and price.
- C. It has 2 vCPUs.
- D. Memory:vCPU ratio is 4 GB:1 vCPU.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **C**

</details>
18) **What does ELB do when a backend server is unhealthy?**
*(ELB จะทำอะไรเมื่อ Backend Server ผิดปกติ?)*

- A. Continue sending traffic and notify AS
- B. Stop sending traffic to that backend
- C. Only alarm and wait for user action
- D. Replace backend automatically
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **B**

</details>
19) **Which statement about EVS is FALSE?**
*(ข้อใดกล่าวผิดเกี่ยวกับ EVS?)*

- A. EVS provides 12-nines durability.
- B. EVS disk space is pre-allocated and can be up to 32 TB per disk.
- C. EVS is used as block storage by guest OS through OS APIs.
- D. EVS backups are stored in OBS.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A**

</details>
20) **According to shared responsibility model, which is the responsibility of customers?**
*(ตาม Shared Responsibility Model ข้อใดเป็นความรับผิดชอบของลูกค้า?)*

- A. Provide cloud security services for servers
- B. Apply security group firewall rules
- C. Maintain physical infrastructure
- D. Control ECS login permissions
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **B**

</details>
### Part 3: Multiple Choice (21-30)

21) **Which information can IAM use to identify a visitor?**
*(IAM สามารถใช้ข้อมูลใดในการระบุตัวตนผู้เข้าใช้งาน? (เลือกได้หลายข้อ))*

- A. Linux root password
- B. Windows administrator password
- C. Account/IAM user name + password for console login
- D. AK/SK for API access
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **C, D**

</details>
22) **Which benefits can a distributed system provide?**
*(ระบบ Distributed สามารถมอบประโยชน์ใดได้บ้าง? (เลือกได้หลายข้อ))*

- A. Large resource pool
- B. Balanced request pressure
- C. Better fault recovery
- D. Loosely coupled architecture
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, B, C, D**

</details>
23) **Which image types are available on Huawei Cloud?**
*(ประเภท Image ใดบ้างที่มีให้บน Huawei Cloud? (เลือกได้หลายข้อ))*

- A. Public images
- B. User data center images
- C. Private images
- D. Shared images
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, C, D**

</details>
24) **Which database engines are supported by RDS?**
*(Database Engine ใดบ้างที่ RDS รองรับ? (เลือกได้หลายข้อ))*

- A. MySQL
- B. MongoDB
- C. PostgreSQL
- D. Oracle
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, C**

</details>
25) **Which statements about cloud-computing benefits are FALSE?**
*(ข้อใดบ้างกล่าวผิดเกี่ยวกับประโยชน์ของ Cloud Computing? (เลือกได้หลายข้อ))*

- A. No need to worry about security attacks.
- B. Services can be provided in multiple geographies.
- C. Abundant resources are available.
- D. Resources are quickly obtained by making a phone call.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, D**

</details>
26) **Which statements are TRUE about RDS?**
*(ข้อใดบ้างกล่าวถูกต้องเกี่ยวกับ RDS? (เลือกได้หลายข้อ))*

- A. Automated backups use binlogs for point-in-time recovery.
- B. Manual backups use binlogs.
- C. Manual backups support PITR but automated backups do not.
- D. Backups are stored in OBS.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, D**

</details>
27) **Which methods can ELB use for backend health checks?**
*(ELB สามารถใช้วิธีใดในการตรวจสอบสุขภาพ Backend? (เลือกได้หลายข้อ))*

- A. Ping backend server
- B. TCP connection to backend port
- C. HTTP request to backend port
- D. Check backend host power supply
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **B, C**

</details>
28) **Which components are related to Huawei Cloud VPC?**
*(ส่วนประกอบใดบ้างที่เกี่ยวข้องกับ Huawei Cloud VPC? (เลือกได้หลายข้อ))*

- A. Subnet
- B. Router
- C. Security group
- D. Switch
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, C**

</details>
29) **Which statements are FALSE about Cloud Trace Service (CTS)?**
*(ข้อใดบ้างกล่าวผิดเกี่ยวกับ Cloud Trace Service (CTS)? (เลือกได้หลายข้อ))*

- A. It records access to Huawei Cloud APIs.
- B. It is used for security audit and traceability.
- C. CTS is not free and must always be charged.
- D. Long-term trace storage in OBS is always free of charge.
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **C, D**

</details>
30) **What functions does DAS provide for database development and O&M?**
*(DAS มีฟังก์ชันใดบ้างสำหรับการพัฒนาและดูแล Database? (เลือกได้หลายข้อ))*

- A. Online SQL/database operations without local client installation
- B. Host/instance performance analysis
- C. Real-time performance diagnosis
- D. Rich development features (for example SQL prompt/sync tooling)
<details><summary><mark><strong>Show Answer</strong></mark></summary>

**Answer:** **A, B, C, D**

</details>

## Corrections & Clarifications (High-Yield)

### Highlights (Must Remember)
> <mark><strong>FOCUS</strong>: Check region-specific docs before production deployment.</mark>

- <mark>**Region/AZ count**</mark> ในข้อสอบอาจยึดเลขจากสไลด์รุ่นที่ใช้เรียน; หากอ้างอิงใช้งานจริงให้ตรวจหน้า Global Infrastructure ล่าสุด
- <mark>**RDS engines and versions**</mark> ต้องเช็กตาม <mark>**Region**</mark> เสมอ เพราะเปิดใช้ไม่เท่ากันทุกพื้นที่
- <mark>**EVS capacity**</mark> โดยทั่วไปเห็นเพดานที่ 32 TB ต่อดิสก์ในระดับพื้นฐาน; บางกรณีสามารถขอเพิ่มเพดานผ่านช่องทางซัพพอร์ตได้
- <mark>**Shared responsibility**</mark>: ผู้ให้บริการรับผิดชอบชั้นโครงสร้างพื้นฐาน ส่วน tenant รับผิดชอบ data/OS/app/configuration
- <mark>**WAF vs Anti-DDoS**</mark>: WAF ป้องกัน L7 web attacks; Anti-DDoS เน้น L3/L4 volumetric attacks

### Quick Clarifications
- **SNAT vs Inbound**: SNAT is for private subnet outbound Internet access. For inbound access from Internet to ECS, use **EIP or DNAT**.
- **RDS HA vs DR**: Primary/Standby is Multi-AZ high availability within one region. Cross-region is DR, not the same thing.
- **DAS**: DAS is a database O&M platform, not a database engine.
- **Storage quick map**: OBS for object/static content, EVS for VM block disks, SFS for shared file (NFS-like) workloads.

## <span style="color: #c0392b;">Additional Practice Questions by Chapter</span>

> <span style="background-color: #ffebee; color: #b71c1c; font-weight: bold; padding: 3px 8px; border-radius: 4px;">📝 ข้อสอบเพิ่มเติม — แยกตามบท (ฝึกก่อนสอบ)</span>

### Chapter 1: Diving into Huawei Cloud
**Question: Which best describes cloud computing value?**  
A. One-time purchase with fixed capacity only  
B. On-demand IT resources with pay-as-you-go billing  
C. Physical server dedicated to one team only  
D. Offline software delivery model  
Answer: **B**

### Chapter 2: Compute Services
**Question: Which service provides a dedicated physical host for one tenant?**  
A. ECS  
B. IMS  
C. DeH  
D. CCE  
Answer: **C**

### Chapter 3: Storage Services
**Question: Which service is most suitable for static website hosting (images/videos)?**  
A. EVS  
B. SFS  
C. OBS  
D. DSS  
Answer: **C**

### Chapter 4: Networking Services
**Question: Which is stateful?**  
A. Network ACL  
B. Security Group  
C. Route Table  
D. NAT Gateway  
Answer: **B**

**Question: For Internet-to-ECS inbound access in a private subnet, what should be used?**  
A. SNAT  
B. VPC Peering  
C. EIP or DNAT  
D. ELB only  
Answer: **C**

### Chapter 5: Database Services
**Question: Can RDS Primary/Standby be deployed across regions?**  
A. True  
B. False  
Answer: **B**

**Question: What does DAS provide?**  
A. Create new database engine  
B. Monitoring/Diagnosis/SQL Insight  
C. Load balancing  
D. Object storage  
Answer: **B**

### Chapter 6: Security Services
**Question: Which attack is more suitable for Anti-DDoS than WAF?**  
A. SQL Injection  
B. XSS  
C. SYN Flood  
D. CC Attack  
Answer: **C**

**Question: IAM policy defines permissions over what?**  
A. User only  
B. Group only  
C. Resource + Action  
D. Project only  
Answer: **C**

### Chapter 7: Elastic Cloud Services for Distributed Deployment
**Question: What does ELB do when health check finds an unhealthy ECS?**  
A. Disable VPC  
B. Stop routing traffic to that ECS  
C. Delete ECS  
D. Reboot immediately  
Answer: **B**

### Chapter 8: Cloud Native and Transformation
**Question: What is the smallest deployable unit in Kubernetes?**  
A. Node  
B. Service  
C. Pod  
D. Container Registry  
Answer: **C**

**Question: How is FunctionGraph billed?**  
A. Monthly  
B. Reserved  
C. Pay-per-execution  
D. Free  
Answer: **C**

### Chapter 9: Exam Outline and Sample Questions
**Question: In shared responsibility model, who is responsible for setting ECS security group rules?**  
A. Cloud provider only  
B. Customer/tenant  
C. Internet service provider  
D. Hardware vendor  
Answer: **B**




