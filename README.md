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

**วัตถุประสงค์**: [กำหนดระดับความต้านทานต่อสัญญาณรบกวนแม่เหล็กไฟฟ้าขั้นต่ำสำหรับอุปกรณ์ไฟฟ้าและอิเล็กทรอนิกส์ที่ใช้ในสภาพแวดล้อมที่อยู่อาศัย พาณิชย์ และอุตสาหกรรมเบา](https://www.dlsemc.com/iec-en-61000-6-1-electromagnetic-compatibility-emc-generic-standards-immunity-for-residential-commercial-and-light-industrial-environments/)

### 🏢 ขอบเขตการใช้งาน
- [อุปกรณ์ที่ต่อเชื่อมโดยตรงกับโครงข่ายไฟฟ้าแรงต่ำสาธารณะ](https://www.intertekinform.com/en-us/Standards/EN-IEC-61000-6-1-2019-1143543_SAIG_CENELEC_CENELEC_2709694/)
- [อุปกรณ์ที่ขับเคลื่อนด้วยแบตเตอรี่ในสภาพแวดล้อมที่ไม่ใช่อุตสาหกรรม](https://www.intertekinform.com/en-us/Standards/EN-IEC-61000-6-1-2019-1143543_SAIG_CENELEC_CENELEC_2709694/)
- [ครอบคลุมช่วงความถี่ 0 Hz ถึง 400 GHz](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/2832235670)

### 🏠 สภาพแวดล้อมที่ครอบคลุม
- **ที่อยู่อาศัย**: [บ้าน, อพาร์ตเมนต์](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- **พาณิชย์**: [ร้านค้า, ซูเปอร์มาร์เก็ต, สำนักงาน, ธนาคาร](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- **สาธารณะ**: [โรงภาพยนต์, บาร์สาธารณะ, ห้องเต้นรำ](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- **กลางแจ้ง**: [ปั๊มน้ำมัน, ลานจอดรถ, ศูนย์กีฬา](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- **อุตสาหกรรมเบา**: [เวิร์กช็อป, ห้องปฏิบัติการ, ศูนย์บริการ](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)

### 🎯 ตัวชี้วัดและระดับการทดสอบ

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | หมายเหตุ |
|-----------|----------------|-------------|----------|
| **ESD** | [IEC 61000-4-2](https://en.wikipedia.org/wiki/IEC_61000-4-2) | [Contact: ±4 kV, Air: ±8 kV](https://transientspecialists.com/blogs/blog/conducted-immunity-testing) | [10 ครั้งต่อขั้ว](https://emcfastpass.com/emc-testing-beginners-guide/emc-immunity-testing/) |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [3 V/m](https://keystonecompliance.com/iec-61000-6-1/) | [80 MHz - 1 GHz](https://www.academyofemc.com/emc-standards) |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [3 V (rms)](https://keystonecompliance.com/iec-61000-6-1/) | [0.15 - 80 MHz](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: ±1 kV, Signal/Data: ±0.5 kV](https://keystonecompliance.com/iec-61000-6-1/) | - |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [AC Mains: ±1 kV (L-L), ±2 kV (L-E), Signal: ±0.5 kV](https://keystonecompliance.com/iec-61000-6-1/) | - |
| **Power Frequency Magnetic Field** | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | [3 A/m (50/60 Hz)](https://keystonecompliance.com/iec-61000-6-1/) | - |
| **Voltage Dips/Interruptions** | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | [Dip: 70% residual, 25 cycles, Interrupt: <5% residual, 250 cycles](https://keystonecompliance.com/iec-61000-6-1/) | - |

---

## 2. [IEC 61000-6-2](https://webstore.iec.ch/en/publication/25630)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility (EMC) - Part 6-2: Generic standards - Immunity for industrial environments](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID:1316)
- **ชื่อไทย**: [ความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) - ส่วนที่ 6-2: มาตรฐานทั่วไป - มาตรฐานภูมิคุ้มกันสำหรับสภาพแวดล้อมอุตสาหกรรม](https://a.tisi.go.th/t/?n=7448)
- **มาตรฐานไทย**: [มอก.61000 เล่ม 6(2)-2566](https://a.tisi.go.th/t/?n=7448)

**วัตถุประสงค์**: [กำหนดระดับความต้านทานต่อสัญญาณรบกวนแม่เหล็กไฟฟ้าสูงกว่าสำหรับอุปกรณ์ที่ใช้ในสภาพแวดล้อมอุตสาหกรรม](https://www.dlsemc.com/iec-en-61000-6-2-generic-standards-immunity-for-industrial-environments/)

### 🏭 ขอบเขตการใช้งาน
- [อุปกรณ์ที่ต่อเชื่อมกับเครือข่ายไฟฟ้าที่จ่ายจากหม้อแปลงแรงสูงหรือแรงกลาง](https://keystonecompliance.com/iec-61000-6-2/)
- [อุปกรณ์ที่ใช้ในโรงงานหรือติดตั้งใกล้กับสถานที่อุตสาหกรรม](https://keystonecompliance.com/iec-61000-6-2/)

### 🔧 ลักษณะสภาพแวดล้อมอุตสาหกรรม
- [มีอุปกรณ์ ISM (Industrial, Scientific and Medical) ตาม CISPR 11](https://keystonecompliance.com/iec-61000-6-2/)
- [มีการสวิตช์โหลดแบบ inductive หรือ capacitive บ่อยครั้ง](https://keystonecompliance.com/iec-61000-6-2/)
- [มีกระแสไฟฟ้าขนาดใหญ่](https://keystonecompliance.com/iec-61000-6-2/)

### 🎯 ตัวชี้วัดและระดับการทดสอบ (สูงกว่า IEC 61000-6-1)

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ความแตกต่าง |
|-----------|----------------|-------------|-------------|
| **ESD** | [IEC 61000-4-2](https://en.wikipedia.org/wiki/IEC_61000-4-2) | [Contact: ±4 kV, Air: ±8 kV](https://keystonecompliance.com/iec-61000-6-2/) | เท่ากับ 61000-6-1 |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [**10 V/m**](https://keystonecompliance.com/iec-61000-6-2/) | 🔺 สูงกว่า 61000-6-1 |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [**10 V**](https://keystonecompliance.com/iec-61000-6-2/) | 🔺 สูงกว่า 61000-6-1 |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: **±2 kV**, Signal/Data: **±1 kV**](https://keystonecompliance.com/iec-61000-6-2/) | 🔺 สูงกว่า 61000-6-1 |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [AC Mains: ±2 kV (L-L), ±4 kV (L-E), Signal: ±1 kV](https://keystonecompliance.com/iec-61000-6-2/) | 🔺 สูงกว่า 61000-6-1 |

---

## 3. [EN 55032 (CISPR 32)](https://www.cenelec.eu/dyn/www/f?p=104:110:0::::FSP_PROJECT,FSP_ORG_ID:25144,1258)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility of multimedia equipment - Emission requirements](https://www.cispr.org/site/data/32_cis_a_e.pdf)
- **ชื่อไทย**: [ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดเรื่องการปล่อยมลพิษ](https://www.muayene.net/th/cispr-testleri-199)

**วัตถุประสงค์**: [จำกัดการแผ่รังสีแม่เหล็กไฟฟ้าจากอุปกรณ์มัลติมีเดียเพื่อป้องกันการรบกวนวิทยุ](https://www.celectronics.com/learning-center/en-55032-cispr-32)

### 🎛️ ขอบเขตการใช้งาน
- [อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V](https://keystonecompliance.com/en-55032-multi-media-emission-testing/)
- [รวมอุปกรณ์ IT, เสียง, วิดีโอ, อุปกรณ์รับสัญญาณกระจายเสียง](https://www.elitetest.com/blog/emc-emi-testing/cispr-32-emissions-multimedia-equipment-end-of-cispr-22/)
- [แทนที่ EN 55022, EN 55013, และ EN 55103-1](https://www.emcbayswater.com.au/blog/emc-testing/commercial-emc-testing/en-55032-2012-multi-media-equipment/)

### 🏷️ การจำแนกประเภท

#### **Class A (อุตสาหกรรม/พาณิชย์)**
- [อุปกรณ์ที่ใช้ในสภาพแวดล้อมอื่นนอกเหนือจากที่อยู่อาศัย](https://www.tuvsud.com/en-gb/services/testing/electromagnetic-compatibility-testing/emc-testing-multimedia-equipment)
- [ขีดจำกัดการแผ่รังสีสูงกว่า Class B](https://www.academyofemc.com/emc-standards)

#### **Class B (ที่อยู่อาศัย)**
- [อุปกรณ์ที่ใช้หลักในสภาพแวดล้อมที่อยู่อาศัย](https://www.tuvsud.com/en-gb/services/testing/electromagnetic-compatibility-testing/emc-testing-multimedia-equipment)
- [ขีดจำกัดการแผ่รังสีเข้มงวดกว่า](https://www.tuvsud.com/en-gb/services/testing/electromagnetic-compatibility-testing/emc-testing-multimedia-equipment)

### 📏 ตัวชี้วัดและขีดจำกัดการแผ่รังสี

#### **Conducted Emissions (0.15 - 30 MHz)**

| ช่วงความถี่ | Class A | Class B |
|-------------|---------|---------|
| **0.15-0.5 MHz** | [79 dBμV (quasi-peak), 66 dBμV (average)](https://www.powerctc.com/en/node/5883) | [66-56 dBμV (quasi-peak), 56-46 dBμV (average)](https://www.powerctc.com/en/node/5883) |
| **0.5-30 MHz** | [73 dBμV (quasi-peak), 60 dBμV (average)](https://www.powerctc.com/en/node/5883) | [60-50 dBμV (quasi-peak), 50-40 dBμV (average)](https://www.powerctc.com/en/node/5883) |

#### **Radiated Emissions**

| ช่วงความถี่ | Class A | Class B |
|-------------|---------|---------|
| **30-230 MHz** | [40 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) | [30 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) |
| **230 MHz-1 GHz** | [47 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) | [37 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) |
| **1-6 GHz** | [76 dBμV/m @3m](http://www.rfemcdevelopment.eu/en/emc-emi-standards/en-55032-2012) | [60 dBμV/m @3m](http://www.rfemcdevelopment.eu/en/emc-emi-standards/en-55032-2012) |

#### **Network/Wired Ports Conducted Emissions**
- [ขีดจำกัดเดียวกับ AC Mains ports สำหรับ Ethernet และพอร์ตข้อมูลอื่นๆ](https://www.emcbayswater.com.au/blog/emc-testing/commercial-emc-testing/en-55032-2012-multi-media-equipment/)

---

## 4. [EN 55035 (CISPR 35)](https://www.cenelec.eu/dyn/www/f?p=104:110:0::::FSP_PROJECT,FSP_ORG_ID:65534,1258)

### 📝 ชื่อและวัตถุประสงค์
- **ชื่อเต็ม (EN)**: [Electromagnetic compatibility of multimedia equipment - Immunity requirements](https://www.cispr.org/site/data/35_cis_a_e.pdf)
- **ชื่อไทย**: ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดด้านภูมิคุ้มกัน

**วัตถุประสงค์**: [กำหนดความต้านทานต่อสัญญาณรบกวนของอุปกรณ์มัลติมีเดีย](https://www.celectronics.com/learning-center/en-550352017-cispr-35)

### 🔄 ขอบเขตการใช้งาน
- [อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V](https://keystonecompliance.com/en-55035-multimedia-emc-testing/)
- [แทนที่ EN 55024 (IT equipment), EN 55020 (broadcast receivers), EN 55103-2](https://www.element.com/nucleus/2020/what-you-need-to-know-about-en-55032-and-55035-cispr-32-and-35)

### 🎯 ตัวชี้วัดและระดับการทดสอบ

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ช่วงความถี่/เงื่อนไข |
|-----------|----------------|-------------|---------------------|
| **ESD** | [IEC 61000-4-2](https://en.wikipedia.org/wiki/IEC_61000-4-2) | [Contact: ±4 kV, Air: ±8 kV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [10 ครั้งต่อขั้ว](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) |
| **Radiated RF Immunity** | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [3 V/m](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) | [80 MHz - 2.7 GHz](https://www.celectronics.com/learning-center/en-550352017-cispr-35) |
| **Conducted RF Immunity** | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [0.15-10 MHz: 3 V (rms), 10-30 MHz: 3→1 V (rms), 30-80 MHz: 1 V (rms)](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [Linear decrease](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) |
| **Electrical Fast Transient/Burst** | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: ±1 kV, Signal/Data: ±0.5 kV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| **Surge** | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [Unshielded: 1 kV (no protection), 4 kV (with protection), Coaxial/shielded: 0.5 kV, AC Mains: 1 kV (L-L), 2 kV (L-E)](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| **Power Frequency Magnetic Field** | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | [3 A/m (50/60 Hz)](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) | - |
| **Voltage Dips/Interruptions** | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | [Dip: 70% residual, 25 cycles, Interrupt: <5% residual, 250 cycles](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| **Broadband Impulse Conducted Disturbances** | Custom | [0.15-0.5 MHz: 107 dBμV, 0.5-10 MHz: 107→36 dBμV, 10-30 MHz: 36→30 dBμV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [xDSL ports](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) |

---

## 📚 การอ้างอิง

### 🌐 มาตรฐานสากล
- [IEC (International Electrotechnical Commission)](https://www.iec.ch/)
- [CISPR (International Special Committee on Radio Interference)](https://www.cispr.org/)
- [CENELEC (European Committee for Electrotechnical Standardization)](https://www.cenelec.eu/)

### 🇹🇭 มาตรฐานไทย
- [สำนักงานมาตรฐานผลิตภัณฑ์อุตสาหกรรม (สมอ.)](https://www.tisi.go.th/)

### 📖 แหล่งข้อมูลที่ใช้อ้างอิง
1. [D.L.S. Electronic Systems - IEC 61000-6-1](https://www.dlsemc.com/iec-en-61000-6-1-electromagnetic-compatibility-emc-generic-standards-immunity-for-residential-commercial-and-light-industrial-environments/)
2. [D.L.S. Electronic Systems - IEC 61000-6-2](https://www.dlsemc.com/iec-en-61000-6-2-generic-standards-immunity-for-industrial-environments/)
3. [Keystone Compliance - IEC 61000-6-1 Testing](https://keystonecompliance.com/iec-61000-6-1/)
4. [Keystone Compliance - IEC 61000-6-2 Testing](https://keystonecompliance.com/iec-61000-6-2/)
5. [Keystone Compliance - EN 55032 Testing](https://keystonecompliance.com/en-55032-multi-media-emission-testing/)
6. [Keystone Compliance - EN 55035 Testing](https://keystonecompliance.com/en-55035-multimedia-emc-testing/)
7. [Academy of EMC - EMC Standards](https://www.academyofemc.com/emc-standards)
8. [EMC Bayswater - EN 55032 & CISPR 32](https://www.emcbayswater.com.au/blog/emc-testing/commercial-emc-testing/en-55032-2012-multi-media-equipment/)
9. [EMC Bayswater - EN 55035 & CISPR 35](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/)
10. [Element - EN 55032 and 55035](https://www.element.com/nucleus/2020/what-you-need-to-know-about-en-55032-and-55035-cis
