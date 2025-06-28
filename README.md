# 🤖 มาตรฐาน EMC สำหรับหุ่นยนต์ขับเคลื่อนอัตโนมัติในโรงพยาบาล

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg)](README.md)
[![EMC Standards](https://img.shields.io/badge/EMC-IEC%2061000-blue.svg)](https://www.iec.ch/)

> 📋 คู่มือรวบรวมมาตรฐาน EMC สำหรับการพัฒนาหุ่นยนต์ขับเคลื่อนอัตโนมัติในโรงพยาบาล เพื่อการตรวจจับข้อมูล Vital Signs จากเครื่องวัดสัญญาณชีพ

## 📑 สารบัญ

- [IEC 61000-6-1](#1-iec-61000-6-1)
- [IEC 61000-6-2](#2-iec-61000-6-2)
- [EN 55032 (CISPR 32)](#3-en-55032-cispr-32)
- [EN 55035 (CISPR 35)](#4-en-55035-cispr-35)

---

## 1. [IEC 61000-6-1](https://webstore.iec.ch/en/publication/25628)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility (EMC) - Part 6-1: Generic standards - Immunity for residential, commercial and light-industrial environments](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID:1316)
- **ชื่อไทย**: [ความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) - ส่วนที่ 6-1: มาตรฐานทั่วไป - มาตรฐานภูมิคุ้มกันสำหรับสภาพแวดล้อมที่อยู่อาศัย เชิงพาณิชย์ และอุตสาหกรรมเบา](https://a.tisi.go.th/t/?n=7447)
- **มาตรฐานไทย**: [มอก.61000 เล่ม 6(1)-2566](https://a.tisi.go.th/t/?n=7447)

### 🏢 ขอบเขตการใช้งาน
- อุปกรณ์ที่ต่อเชื่อมโดยตรงกับโครงข่ายไฟฟ้าแรงต่ำสาธารณะ
- อุปกรณ์ที่ขับเคลื่อนด้วยแบตเตอรี่ในสภาพแวดล้อมที่ไม่ใช่อุตสาหกรรม
- ครอบคลุมช่วงความถี่ 0 Hz ถึง 400 GHz

### 🏠 สภาพแวดล้อมที่ครอบคลุม
- **ที่อยู่อาศัย**: บ้าน, อพาร์ตเมนต์
- **พาณิชย์**: ร้านค้า, ซูเปอร์มาร์เก็ต, สำนักงาน, ธนาคาร
- **สาธารณะ**: โรงภาพยนต์, บาร์สาธารณะ, ห้องเต้นรำ
- **กลางแจ้ง**: ปั๊มน้ำมัน, ลานจอดรถ, ศูนย์กีฬา
- **อุตสาหกรรมเบา**: เวิร์กช็อป, ห้องปฏิบัติการ, ศูนย์บริการ

### 🎯 ตัวชี้วัดและระดับการทดสอบ

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | หมายเหตุ |
|-----------|----------------|-------------|----------|
| **ESD** | [IEC 61000-4-2](https://webstore.iec.ch/en/publication/4190) | Contact: ±4 kV<br>Air: ±8 kV | 10 ครั้งต่อขั้ว |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://webstore.iec.ch/en/publication/4180) | 3 V/m | 80 MHz - 1 GHz |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://webstore.iec.ch/en/publication/4210) | 3 V (rms) | 0.15 - 80 MHz |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://webstore.iec.ch/en/publication/4195) | AC Mains: ±1 kV<br>Signal/Data: ±0.5 kV | - |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | AC Mains: ±1 kV (L-L), ±2 kV (L-E)<br>Signal: ±0.5 kV | - |
| **Power Frequency Magnetic Field** | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | 3 A/m (50/60 Hz) | - |
| **Voltage Dips/Interruptions** | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | Dip: 70% residual, 25 cycles<br>Interrupt: <5% residual, 250 cycles | - |

---

## 2. [IEC 61000-6-2](https://webstore.iec.ch/en/publication/25630)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility (EMC) - Part 6-2: Generic standards - Immunity for industrial environments](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID:1316)
- **ชื่อไทย**: [ความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) - ส่วนที่ 6-2: มาตรฐานทั่วไป - มาตรฐานภูมิคุ้มกันสำหรับสภาพแวดล้อมอุตสาหกรรม](https://a.tisi.go.th/t/?n=7448)
- **มาตรฐานไทย**: [มอก.61000 เล่ม 6(2)-2566](https://a.tisi.go.th/t/?n=7448)

### 🏭 ขอบเขตการใช้งาน
- อุปกรณ์ที่ต่อเชื่อมกับเครือข่ายไฟฟ้าที่จ่ายจากหม้อแปลงแรงสูงหรือแรงกลาง
- อุปกรณ์ที่ใช้ในโรงงานหรือติดตั้งใกล้กับสถานที่อุตสาหกรรม

### 🔧 ลักษณะสภาพแวดล้อมอุตสาหกรรม
- มีอุปกรณ์ ISM (Industrial, Scientific and Medical) ตาม [CISPR 11](https://webstore.iec.ch/en/publication/62231)
- มีการสวิตช์โหลดแบบ inductive หรือ capacitive บ่อยครั้ง
- มีกระแสไฟฟ้าขนาดใหญ่

### 🎯 ตัวชี้วัดและระดับการทดสอบ (สูงกว่า IEC 61000-6-1)

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ความแตกต่าง |
|-----------|----------------|-------------|-------------|
| **ESD** | [IEC 61000-4-2](https://webstore.iec.ch/en/publication/4190) | Contact: ±4 kV<br>Air: ±8 kV | เท่ากับ 61000-6-1 |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://webstore.iec.ch/en/publication/4180) | **10 V/m** | 🔺 สูงกว่า 61000-6-1 |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://webstore.iec.ch/en/publication/4210) | **10 V** | 🔺 สูงกว่า 61000-6-1 |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://webstore.iec.ch/en/publication/4195) | AC Mains: **±2 kV**<br>Signal/Data: **±1 kV** | 🔺 สูงกว่า 61000-6-1 |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | AC Mains: ±2 kV (L-L), ±4 kV (L-E)<br>Signal: ±1 kV | 🔺 สูงกว่า 61000-6-1 |

---

## 3. [EN 55032 (CISPR 32)](https://www.cenelec.eu/dyn/www/f?p=104:110:0::::FSP_PROJECT,FSP_ORG_ID:25144,1258)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility of multimedia equipment - Emission requirements](https://www.cispr.org/site/data/32_cis_a_e.pdf)
- **ชื่อไทย**: [ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดเรื่องการปล่อยมลพิษ](https://www.muayene.net/th/cispr-testleri-199)

### 🎛️ ขอบเขตการใช้งาน
- อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V
- รวมอุปกรณ์ IT, เสียง, วิดีโอ, อุปกรณ์รับสัญญาณกระจายเสียง
- แทนที่ EN 55022, EN 55013, และ EN 55103-1

### 🏷️ การจำแนกประเภท

#### **Class A (อุตสาหกรรม/พาณิชย์)**
- อุปกรณ์ที่ใช้ในสภาพแวดล้อมอื่นนอกเหนือจากที่อยู่อาศัย
- ขีดจำกัดการแผ่รังสีสูงกว่า Class B

#### **Class B (ที่อยู่อาศัย)**
- อุปกรณ์ที่ใช้หลักในสภาพแวดล้อมที่อยู่อาศัย
- ขีดจำกัดการแผ่รังสีเข้มงวดกว่า

### 📏 ตัวชี้วัดและขีดจำกัดการแผ่รังสี

#### **Conducted Emissions (0.15 - 30 MHz)**

| ช่วงความถี่ | Class A | Class B |
|-------------|---------|---------|
| **0.15-0.5 MHz** | 79 dBμV (quasi-peak)<br>66 dBμV (average) | 66-56 dBμV (quasi-peak)<br>56-46 dBμV (average) |
| **0.5-30 MHz** | 73 dBμV (quasi-peak)<br>60 dBμV (average) | 60-50 dBμV (quasi-peak)<br>50-40 dBμV (average) |

#### **Radiated Emissions**

| ช่วงความถี่ | Class A | Class B |
|-------------|---------|---------|
| **30-230 MHz** | 40 dBμV/m @10m | 30 dBμV/m @10m |
| **230 MHz-1 GHz** | 47 dBμV/m @10m | 37 dBμV/m @10m |
| **1-6 GHz** | 76 dBμV/m @3m | 60 dBμV/m @3m |

#### **Network/Wired Ports Conducted Emissions**
- ขีดจำกัดเดียวกับ AC Mains ports สำหรับ Ethernet และพอร์ตข้อมูลอื่นๆ

---

## 4. [EN 55035 (CISPR 35)](https://www.cenelec.eu/dyn/www/f?p=104:110:0::::FSP_PROJECT,FSP_ORG_ID:65534,1258)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility of multimedia equipment - Immunity requirements](https://www.cispr.org/site/data/35_cis_a_e.pdf)
- **ชื่อไทย**: ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดด้านภูมิคุ้มกัน

### 🔄 ขอบเขตการใช้งาน
- อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V
- แทนที่ EN 55024 (IT equipment), EN 55020 (broadcast receivers), EN 55103-2

### 🎯 ตัวชี้วัดและระดับการทดสอบ

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ช่วงความถี่/เงื่อนไข |
|-----------|----------------|-------------|---------------------|
| **ESD** | [IEC 61000-4-2](https://webstore.iec.ch/en/publication/4190) | Contact: ±4 kV<br>Air: ±8 kV | 10 ครั้งต่อขั้ว |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://webstore.iec.ch/en/publication/4180) | 3 V/m | 80 MHz - 2.7 GHz |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://webstore.iec.ch/en/publication/4210) | 0.15-10 MHz: 3 V (rms)<br>10-30 MHz: 3→1 V (rms)<br>30-80 MHz: 1 V (rms) | Linear decrease |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://webstore.iec.ch/en/publication/4195) | AC Mains: ±1 kV<br>Signal/Data: ±0.5 kV | - |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | Unshielded: 1 kV (no protection), 4 kV (with protection)<br>Coaxial/shielded: 0.5 kV<br>AC Mains: 1 kV (L-L), 2 kV (L-E) | - |
| **Power Frequency Magnetic Field** | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | 3 A/m (50/60 Hz) | - |
| **Voltage Dips/Interruptions** | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | Dip: 70% residual, 25 cycles<br>Interrupt: <5% residual, 250 cycles | - |
| **Broadband Impulse Conducted Disturbances** | Custom | 0.15-0.5 MHz: 107 dBμV<br>0.5-10 MHz: 107→36 dBμV<br>10-30 MHz: 36→30 dBμV | xDSL ports |

---

## 📚 การอ้างอิง

### 🌐 มาตรฐานสากล
- [IEC (International Electrotechnical Commission)](https://www.iec.ch/)
- [CISPR (International Special Committee on Radio Interference)](https://www.cispr.org/)
- [CENELEC (European Committee for Electrotechnical Standardization)](https://www.cenelec.eu/)

### 🇹🇭 มาตรฐานไทย
- [สำนักงานมาตรฐานผลิตภัณฑ์อุตสาหกรรม (สมอ.)](https://www.tisi.go.th/)

---

## 📄 ใบอนุญาต

โครงการนี้อยู่ภายใต้ [MIT License](LICENSE)
