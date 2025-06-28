# 📋 คู่มือรวบรวมมาตรฐาน EMC สำหรับการพัฒนาหุ่นยนต์ขับเคลื่อนอัตโนมัติในโรงพยาบาล เพื่อการตรวจจับข้อมูล Vital Signs จากเครื่องวัดสัญญาณชีพ

## 🎯 วัตถุประสงค์ของเอกสาร
คู่มือฉบับนี้จัดทำขึ้นเพื่อรวบรวมข้อมูลมาตรฐานด้านความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) และมาตรฐานความปลอดภัยที่จำเป็นสำหรับการพัฒนาหุ่นยนต์ขับเคลื่อนอัตโนมัติในสภาพแวดล้อมโรงพยาบาล เพื่อให้นักพัฒนาและวิศวกรสามารถออกแบบระบบที่ปลอดภัยและเข้ากันได้กับอุปกรณ์ทางการแพทย์อื่นๆ

---

## 📊 มาตรฐาน EMC ทั่วไป (Generic EMC Standards)

### 🏠 IEC 61000-6-1: สภาพแวดล้อมที่อยู่อาศัย เชิงพาณิชย์ และอุตสาหกรรมเบา

- **ชื่อเต็ม (EN):** [Electromagnetic compatibility (EMC) - Part 6-1: Generic standards - Immunity for residential, commercial and light-industrial environments](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID:1316)
- **ชื่อไทย:** [ความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) - ส่วนที่ 6-1: มาตรฐานทั่วไป - มาตรฐานภูมิคุ้มกันสำหรับสภาพแวดล้อมที่อยู่อาศัย เชิงพาณิชย์ และอุตสาหกรรมเบา](https://a.tisi.go.th/t/?n=7447)
- **มาตรฐานไทย:** [มอก.61000 เล่ม 6(1)-2566](https://a.tisi.go.th/t/?n=7447)

**วัตถุประสงค์:** [กำหนดระดับความต้านทานต่อสัญญาณรบกวนแม่เหล็กไฟฟ้าขั้นต่ำสำหรับอุปกรณ์ไฟฟ้าและอิเล็กทรอนิกส์ที่ใช้ในสภาพแวดล้อมที่อยู่อาศัย พาณิชย์ และอุตสาหกรรมเบา](https://www.dlsemc.com/iec-en-61000-6-1-electromagnetic-compatibility-emc-generic-standards-immunity-for-residential-commercial-and-light-industrial-environments/)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์ที่ต่อเชื่อมโดยตรงกับโครงข่ายไฟฟ้าแรงต่ำสาธารณะ](https://www.intertekinform.com/en-us/Standards/EN-IEC-61000-6-1-2019-1143543_SAIG_CENELEC_CENELEC_2709694/)
- [อุปกรณ์ที่ขับเคลื่อนด้วยแบตเตอรี่ในสภาพแวดล้อมที่ไม่ใช่อุตสาหกรรม](https://www.intertekinform.com/en-us/Standards/EN-IEC-61000-6-1-2019-1143543_SAIG_CENELEC_CENELEC_2709694/)
- [ครอบคลุมช่วงความถี่ 0 Hz ถึง 400 GHz](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/2832235670)

**สภาพแวดล้อมที่ครอบคลุม:**
- ที่อยู่อาศัย: [บ้าน, อพาร์ตเมนต์](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- พาณิชย์: [ร้านค้า, ซูเปอร์มาร์เก็ต, สำนักงาน, ธนาคาร](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- สาธารณะ: [โรงภาพยนต์, บาร์สาธารณะ, ห้องเต้นรำ](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- กลางแจ้ง: [ปั๊มน้ำมัน, ลานจอดรถ, ศูนย์กีฬา](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)
- อุตสาหกรรมเบา: [เวิร์กช็อป, ห้องปฏิบัติการ, ศูนย์บริการ](https://www.amazon.com/IEC-61000-6-1-Electromagnetic-compatibility-light-industrial/dp/B000Y2LQ0M)

**การทดสอบความต้านทาน (Immunity Tests):**

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | หมายเหตุ |
|---|---|---|---|
| ESD | [IEC 61000-4-2](https://transientspecialists.com/blogs/blog/conducted-immunity-testing) | [Contact: ±4 kV, Air: ±8 kV](https://transientspecialists.com/blogs/blog/conducted-immunity-testing) | [10 ครั้งต่อขั้ว](https://emcfastpass.com/emc-testing-beginners-guide/emc-immunity-testing/) |
| RF Radiated | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [3 V/m](https://keystonecompliance.com/iec-61000-6-1/) | [80 MHz - 1 GHz](https://www.academyofemc.com/emc-standards) |
| RF Conducted | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [3 V (rms)](https://keystonecompliance.com/iec-61000-6-1/) | [0.15 - 80 MHz](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) |
| EFT/Burst | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: ±1 kV, Signal/Data: ±0.5 kV](https://keystonecompliance.com/iec-61000-6-1/) | - |
| Surge | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [AC Mains: ±1 kV (L-L), ±2 kV (L-E), Signal: ±0.5 kV](https://keystonecompliance.com/iec-61000-6-1/) | - |
| Magnetic Field | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | [3 A/m (50/60 Hz)](https://keystonecompliance.com/iec-61000-6-1/) | - |
| Voltage Dips/Interruptions | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | [Dip: 70% residual, 25 cycles, Interrupt: <5% residual, 250 cycles](https://keystonecompliance.com/iec-61000-6-1/) | - |

---

### 🏭 IEC 61000-6-2: สภาพแวดล้อมอุตสาหกรรม

- **ชื่อเต็ม (EN):** [Electromagnetic compatibility (EMC) - Part 6-2: Generic standards - Immunity for industrial environments](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID:1316)
- **ชื่อไทย:** [ความเข้ากันได้ทางแม่เหล็กไฟฟ้า (EMC) - ส่วนที่ 6-2: มาตรฐานทั่วไป - มาตรฐานภูมิคุ้มกันสำหรับสภาพแวดล้อมอุตสาหกรรม](https://a.tisi.go.th/t/?n=7448)
- **มาตรฐานไทย:** [มอก.61000 เล่ม 6(2)-2566](https://a.tisi.go.th/t/?n=7448)

**วัตถุประสงค์:** [กำหนดระดับความต้านทานต่อสัญญาณรบกวนแม่เหล็กไฟฟ้าสูงกว่าสำหรับอุปกรณ์ที่ใช้ในสภาพแวดล้อมอุตสาหกรรม](https://www.dlsemc.com/iec-en-61000-6-2-generic-standards-immunity-for-industrial-environments/)

**ลักษณะสภาพแวดล้อมอุตสาหกรรม:**
- [อุปกรณ์ที่ต่อเชื่อมกับเครือข่ายไฟฟ้าที่จ่ายจากหม้อแปลงแรงสูงหรือแรงกลาง](https://keystonecompliance.com/iec-61000-6-2/)
- [อุปกรณ์ที่ใช้ในโรงงานหรือติดตั้งใกล้กับสถานที่อุตสาหกรรม](https://keystonecompliance.com/iec-61000-6-2/)
- [มีอุปกรณ์ ISM (Industrial, Scientific and Medical) ตาม CISPR 11](https://keystonecompliance.com/iec-61000-6-2/)
- [มีการสวิตช์โหลดแบบ inductive หรือ capacitive บ่อยครั้ง](https://keystonecompliance.com/iec-61000-6-2/)
- [มีกระแสไฟฟ้าขนาดใหญ่](https://keystonecompliance.com/iec-61000-6-2/)

**การทดสอบความต้านทาน (เปรียบเทียบกับ IEC 61000-6-1):**

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ความแตกต่าง |
|---|---|---|---|
| ESD | [IEC 61000-4-2](https://keystonecompliance.com/iec-61000-6-2/) | [Contact: ±4 kV, Air: ±8 kV](https://keystonecompliance.com/iec-61000-6-2/) | เท่ากัน |
| RF Radiated | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [10 V/m](https://keystonecompliance.com/iec-61000-6-2/) | **สูงกว่า 3.3 เท่า** |
| RF Conducted | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [10 V](https://keystonecompliance.com/iec-61000-6-2/) | **สูงกว่า 3.3 เท่า** |
| EFT/Burst | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: ±2 kV, Signal/Data: ±1 kV](https://keystonecompliance.com/iec-61000-6-2/) | **สูงกว่า 2 เท่า** |
| Surge | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [AC Mains: ±2 kV (L-L), ±4 kV (L-E), Signal: ±1 kV](https://keystonecompliance.com/iec-61000-6-2/) | **สูงกว่า 2 เท่า** |

---

## 📻 มาตรฐาน EMC สำหรับอุปกรณ์มัลติมีเดีย

### 📡 CISPR 32 (EN 55032): การปล่อยคลื่นแม่เหล็กไฟฟ้า

- **ชื่อเต็ม (EN):** [Electromagnetic compatibility of multimedia equipment - Emission requirements](https://www.cispr.org/site/data/32_cis_a_e.pdf)
- **ชื่อไทย:** [ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดเรื่องการปล่อยมลพิษ](https://www.muayene.net/th/cispr-testleri-199)

**วัตถุประสงค์:** [จำกัดการแผ่รังสีแม่เหล็กไฟฟ้าจากอุปกรณ์มัลติมีเดียเพื่อป้องกันการรบกวนวิทยุ](https://www.celectronics.com/learning-center/en-55032-cispr-32)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V](https://keystonecompliance.com/en-55032-multi-media-emission-testing/)
- [รวมอุปกรณ์ IT, เสียง, วิดีโอ, อุปกรณ์รับสัญญาณกระจายเสียง](https://www.elitetest.com/blog/emc-emi-testing/cispr-32-emissions-multimedia-equipment-end-of-cispr-22/)
- [แทนที่ EN 55022, EN 55013, และ EN 55103-1](https://www.emcbayswater.com.au/blog/emc-testing/commercial-emc-testing/en-55032-2012-multi-media-equipment/)

**ข้อกำหนดการปล่อยคลื่นทางสาย (Conducted Emissions):**

| ช่วงความถี่ | Class A | Class B |
|---|---|---|
| 0.15-0.5 MHz | [66-56 dBμV (quasi-peak), 56-46 dBμV (average)](https://www.powerctc.com/en/node/5883) | [56-46 dBμV (quasi-peak), 46-36 dBμV (average)](https://www.powerctc.com/en/node/5883) |
| 0.5-5 MHz | [56 dBμV (quasi-peak), 46 dBμV (average)](https://www.powerctc.com/en/node/5883) | [46 dBμV (quasi-peak), 36 dBμV (average)](https://www.powerctc.com/en/node/5883) |
| 5-30 MHz | [73 dBμV (quasi-peak), 60 dBμV (average)](https://www.powerctc.com/en/node/5883) | [60-50 dBμV (quasi-peak), 50-40 dBμV (average)](https://www.powerctc.com/en/node/5883) |

**ข้อกำหนดการปล่อยคลื่นทางอากาศ (Radiated Emissions):**

| ช่วงความถี่ | Class A | Class B |
|---|---|---|
| 30-230 MHz | [40 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) | [30 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) |
| 230-1000 MHz | [47 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) | [37 dBμV/m @10m](https://emc-compliance.co.uk/2024/04/01/standards-limit-en55032-lines-for-emissions/) |
| หรือ @3m | [76 dBμV/m @3m](http://www.rfemcdevelopment.eu/en/emc-emi-standards/en-55032-2012) | [60 dBμV/m @3m](http://www.rfemcdevelopment.eu/en/emc-emi-standards/en-55032-2012) |

---

### 🛡️ CISPR 35 (EN 55035): ความต้านทานต่อสัญญาณรบกวน

- **ชื่อเต็ม (EN):** [Electromagnetic compatibility of multimedia equipment - Immunity requirements](https://www.cispr.org/site/data/35_cis_a_e.pdf)
- **ชื่อไทย:** ความเข้ากันได้ทางแม่เหล็กไฟฟ้าของอุปกรณ์มัลติมีเดีย - ข้อกำหนดด้านภูมิคุ้มกัน

**วัตถุประสงค์:** [กำหนดความต้านทานต่อสัญญาณรบกวนของอุปกรณ์มัลติมีเดีย](https://www.celectronics.com/learning-center/en-550352017-cispr-35)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์มัลติมีเดีย (MME) ที่มีแรงดันไฟฟ้า AC/DC ≤ 600 V](https://keystonecompliance.com/en-55035-multimedia-emc-testing/)
- [แทนที่ EN 55024 (IT equipment), EN 55020 (broadcast receivers), EN 55103-2](https://www.element.com/nucleus/2020/what-you-need-to-know-about-en-55032-and-55035-cispr-32-and-35)

**การทดสอบความต้านทาน:**

| การทดสอบ | มาตรฐานอ้างอิง | ระดับทดสอบ | ช่วงความถี่/เงื่อนไข |
|---|---|---|---|
| ESD | [IEC 61000-4-2](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [Contact: ±4 kV, Air: ±8 kV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [10 ครั้งต่อขั้ว](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) |
| RF Radiated | [IEC 61000-4-3](https://www.academyofemc.com/emc-standards) | [3 V/m](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) | [80 MHz - 2.7 GHz](https://www.celectronics.com/learning-center/en-550352017-cispr-35) |
| RF Conducted | [IEC 61000-4-6](https://www.atecorp.com/compliance-standards/iec/iec-61000-4-6) | [0.15-10 MHz: 3 V (rms), 10-30 MHz: 3→1 V (rms), 30-80 MHz: 1 V (rms)](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [Linear decrease](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) |
| EFT/Burst | [IEC 61000-4-4](https://transientspecialists.com/blogs/blog/electrical-fast-transient-burst-iec-61000-4-4) | [AC Mains: ±1 kV, Signal/Data: ±0.5 kV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| Surge | [IEC 61000-4-5](https://webstore.iec.ch/en/publication/4201) | [Unshielded: 1 kV (no protection), 4 kV (with protection), Coaxial/shielded: 0.5 kV, AC Mains: 1 kV (L-L), 2 kV (L-E)](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| Magnetic Field | [IEC 61000-4-8](https://webstore.iec.ch/en/publication/4233) | [3 A/m (50/60 Hz)](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) | - |
| Voltage Dips/Interruptions | [IEC 61000-4-11](https://webstore.iec.ch/en/publication/4240) | [Dip: 70% residual, 25 cycles, Interrupt: <5% residual, 250 cycles](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | - |
| Click and Pops | EN 55035 | [0.15-0.5 MHz: 107 dBμV, 0.5-10 MHz: 107→36 dBμV, 10-30 MHz: 36→30 dBμV](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/) | [xDSL ports](https://keystonecompliance.com/en-55035-multimedia-emc-testing/) |

---

## 🏥 มาตรฐานความปลอดภัยสำหรับอุปกรณ์ทางการแพทย์

### 🩺 IEC 60601-1: ความปลอดภัยพื้นฐานและประสิทธิภาพที่จำเป็น

- **ชื่อเต็ม (EN):** [Medical electrical equipment - Part 1: General requirements for basic safety and essential performance](https://webstore.iec.ch/en/publication/2594)
- **ชื่อไทย:** [อุปกรณ์ไฟฟ้าทางการแพทย์ - ส่วนที่ 1-2: ข้อกำหนดทั่วไปสำหรับความปลอดภัยพื้นฐานและประสิทธิภาพที่จำเป็น - มาตรฐานกลุ่ม: การรบกวนทางแม่เหล็กไฟฟ้า - ข้อกำหนดและการทดสอบ](http://www.ptec.or.th/home/contentdetail/41.html)
- **มาตรฐานไทย:** ใช้อ้างอิงในระบบมาตรฐานไทยที่เกี่ยวข้องกับอุปกรณ์ทางการแพทย์

**วัตถุประสงค์:** [กำหนดข้อกำหนดทั่วไปและการทดสอบสำหรับความปลอดภัยพื้นฐานและประสิทธิภาพที่จำเป็นเกี่ยวกับการรบกวนทางแม่เหล็กไฟฟ้าและการปล่อยคลื่นแม่เหล็กไฟฟ้าจากอุปกรณ์ทางการแพทย์](https://webstore.iec.ch/en/publication/67554)

**รุ่นปัจจุบัน:** [IEC 60601-1-2:2014+A1:2020 (ฉบับที่ 4 รุ่น 4.1)](https://webstore.iec.ch/en/publication/67554)

**การเปลี่ยนแปลงสำคัญในฉบับที่ 4:**
- [การกำหนดระดับการทดสอบตามสภาพแวดล้อมการใช้งาน: สถานพยาบาล, การดูแลสุขภาพที่บ้าน, และสภาพแวดล้อมพิเศษ](https://webstore.iec.ch/en/publication/67554)
- [การปรับปรุงการทดสอบเมื่อมีอุปกรณ์สื่อสาร RF แบบพกพาใกล้อุปกรณ์ทางการแพทย์](https://webstore.iec.ch/en/publication/67554)
- [การระบุการทดสอบตามพอร์ตของอุปกรณ์ทางการแพทย์](https://webstore.iec.ch/en/publication/67554)

**ขอบเขตการใช้งาน:**
- [ความปลอดภัยพื้นฐานและประสิทธิภาพที่จำเป็นของอุปกรณ์ ME และระบบ ME ในสภาพแวดล้อมที่มีการรบกวนทางแม่เหล็กไฟฟ้า](https://www.johner-institute.com/articles/product-development/and-more/iec-60601-1-2/)
- [อุปกรณ์ทางการแพทย์และอุปกรณ์เสริมที่มี applied part (ส่วนที่ต้องสัมผัสกับผู้ป่วย)](https://www.johner-institute.com/articles/product-development/and-more/iec-60601-1-2/)
- [อุปกรณ์ไฟฟ้าที่ใช้ในสภาพแวดล้อมทางการแพทย์ เช่น คอมพิวเตอร์เวชระเบียน, จอแสดงผลในห้องผ่าตัด](https://www.johner-institute.com/articles/product-development/and-more/iec-60601-1-2/)

**สภาพแวดล้อมการใช้งาน:**
- **สถานพยาบาลมืออาชีพ (Professional Healthcare Facility):** โรงพยาบาล, คลินิก
- **การดูแลสุขภาพที่บ้าน (Home Healthcare):** บ้านผู้ป่วย, สถานที่อื่นนอกสถานพยาบาล
- **สภาพแวดล้อมพิเศษ (Special Environments):** รถพยาบาล, เครื่องบินพยาบาล

**การทดสอบ EMC สำหรับอุปกรณ์ทางการแพทย์:**

| การทดสอบ | มาตรฐานอ้างอิง | สถานพยาบาล | บ้าน | หมายเหตุ |
|---|---|---|---|---|
| ESD | [IEC 61000-4-2](https://www.intertek.com/medical/regulatory-requirements/emc-testing/) | [±6 kV contact, ±8 kV air](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [±8 kV contact, ±15 kV air](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | - |
| RF Radiated | [IEC 61000-4-3](https://www.intertek.com/medical/regulatory-requirements/emc-testing/) | [3 V/m](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [10 V/m](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [80 MHz - 2.7 GHz](https://www.sunfiretesting.com/IEC-60601-1-2-Testing-Guide-for-Medical-Device-EMC/) |
| RF Conducted | [IEC 61000-4-6](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [3 V](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [10 V](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [0.15 - 80 MHz](https://www.sunfiretesting.com/IEC-60601-1-2-Testing-Guide-for-Medical-Device-EMC/) |
| EFT/Burst | [IEC 61000-4-4](https://www.intertek.com/medical/regulatory-requirements/emc-testing/) | [±2 kV AC mains, ±1 kV signal](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [±2 kV AC mains, ±1 kV signal](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | - |
| Surge | [IEC 61000-4-5](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [±1 kV differential, ±2 kV common](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | [±2 kV differential, ±4 kV common](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | - |
| Magnetic Field | [IEC 61000-4-8](https://www.intertek.com/medical/regulatory-requirements/emc-testing/) | [30 A/m](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [30 A/m](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [50/60 Hz](https://www.sunfiretesting.com/IEC-60601-1-2-Testing-Guide-for-Medical-Device-EMC/) |
| Voltage Dips | [IEC 61000-4-11](https://www.mddionline.com/news/using-iec-60601-1-2-testing-medical-devices) | ตามมาตรฐาน | ตามมาตรฐาน | - |
| Proximity Fields | [IEC 61000-4-39](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [30 kHz, 134.2 kHz, 13.56 MHz](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | [30 kHz, 134.2 kHz, 13.56 MHz](https://www.testups.com/iec-60601-1-2-medical-emc-standard/) | **ใหม่ในรุ่น 4.1** |

**แนวคิดสำคัญ:**
- **ความปลอดภัยพื้นฐาน (Basic Safety):** [การป้องกันอันตรายที่อาจเกิดขึ้นจากการใช้อุปกรณ์](https://www.medicaldesignbriefs.com/component/content/article/mdb/pub/features/articles/33060)
- **ประสิทธิภาพที่จำเป็น (Essential Performance):** [ประสิทธิภาพที่จำเป็นในการรักษาความเสี่ยงในระดับที่ยอมรับได้](https://www.medicaldesignbriefs.com/component/content/article/mdb/pub/features/articles/33060)
- **แผนการทดสอบ (Test Plan):** [ต้องจัดทำตามภาคผนวก G และส่งให้ห้องทดสอบก่อนการทดสอบ](https://www.medicaldesignbriefs.com/component/content/article/mdb/pub/features/articles/33060)

---

## 🔋 มาตรฐานความปลอดภัยแบตเตอรี่

### ⚡ IEC 62133: ความปลอดภัยแบตเตอรี่แบบชาร์จได้

- **ชื่อเต็ม (EN):** [Secondary cells and batteries containing alkaline or other non-acid electrolytes - Safety requirements for portable sealed secondary cells, and for batteries made from them, for use in portable applications](https://webstore.iec.ch/en/publication/32662)
- **ชื่อไทย:** [เซลล์และแบตเตอรี่ทุติยภูมิที่มีอิเล็กโทรไลต์อัลคาไลน์หรืออิเล็กโทรไลต์ที่ไม่ใช่กรด - ข้อกำหนดความปลอดภัยสำหรับเซลล์ทุติยภูมิแบบผนึกแบบพกพาและแบตเตอรี่ที่ผลิตจากเซลล์เหล่านั้น สำหรับการใช้งานแบบพกพา](https://www.labaratuvar.com/th/iec-62133-standardi/)
- **มาตรฐานไทย:** [มอก. 62133 เล่ม 1-2565](https://www.tisi.go.th/data/standard/pdf/3_a62133_1_25xx.pdf)

**วัตถุประสงค์:** [กำหนดข้อกำหนดและการทดสอบสำหรับการทำงานที่ปลอดภัยของเซลล์และแบตเตอรี่ลิเธียมแบบพกพาในการใช้งานตามที่ตั้งใจและการใช้งานผิดที่คาดการณ์ได้อย่างสมเหตุสมผล](https://www.intertek.com/batteries/iec-62133/)

**การเปลี่ยนแปลงสำคัญในปี 2017:**
- [แยกมาตรฐานออกเป็น 2 ส่วน: IEC 62133-1 (นิกเกิล) และ IEC 62133-2 (ลิเธียม)](https://webstore.iec.ch/en/publication/32662)
- [IEC 62133-2:2017 เป็นมาตรฐานที่รู้จักมากที่สุดสำหรับการส่งออกแบตเตอรี่ลิเธียม-ไอออน](https://www.benzoenergy.com/blog/post/li-ion-battery-test-report-iec-62133.html)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์ IT, GPS, ผลิตภัณฑ์สวมใส่, นาฬิกาอัจฉริยะ, อุปกรณ์บลูทูธ, เซ็นเซอร์ไร้สาย, เครื่องมือ, ห้องปฏิบัติการ, ครัวเรือน และอุปกรณ์ทางการแพทย์](https://www.benzoenergy.com/blog/post/li-ion-battery-test-report-iec-62133.html)

---

### 🔋 IEC 62133-2: ความปลอดภัยแบตเตอรี่ลิเธียม

- **ชื่อเต็ม (EN):** [Secondary cells and batteries containing alkaline or other non-acid electrolytes - Safety requirements for portable sealed secondary cells, and for batteries made from them, for use in portable applications - Part 2: Lithium systems](https://webstore.iec.ch/en/publication/32662)
- **ชื่อไทย:** [เซลล์และแบตเตอรี่ทุติยภูมิที่มีอิเล็กโทรไลต์อัลคาไลน์หรืออิเล็กโทรไลต์ที่ไม่ใช่กรด - ข้อกำหนดความปลอดภัยสำหรับเซลล์ทุติยภูมิแบบผนึกแบบพกพาและแบตเตอรี่ที่ผลิตจากเซลล์เหล่านั้น สำหรับการใช้งานแบบพกพา - ส่วนที่ 2: ระบบลิเธียม](https://www.labaratuvar.com/th/iec-62133-standardi/)
- **มาตรฐานไทย:** [มอก. 62133 เล่ม 2-2565](https://www.tisi.go.th/data/standard/pdf/3_a62133_1_25xx.pdf)

**วัตถุประสงค์:** [ระบุข้อกำหนดและการทดสอบสำหรับการทำงานที่ปลอดภัยของเซลล์และแบตเตอรี่ลิเธียมทุติยภูมิแบบผนึกแบบพกพาที่มีอิเล็กโทรไลต์ที่ไม่ใช่กรด](https://webstore.iec.ch/en/publication/32662)

**การเปลี่ยนแปลงสำคัญจาก IEC 62133:2012:**
- [แยกระบบนิกเกิลออกเป็นส่วนที่ 1 แยกต่างหาก](https://webstore.iec.ch/en/publication/32662)
- [รวมข้อกำหนดเซลล์แบบเหรียญ (coin cell)](https://webstore.iec.ch/en/publication/32662)
- [อัปเดตการประกอบเซลล์เป็นแบตเตอรี่](https://webstore.iec.ch/en/publication/32662)
- [เพิ่มการทดสอบเชิงกล: การสั่นสะเทือน, การกระแทก](https://webstore.iec.ch/en/publication/32662)

**ประโยชน์ของการทดสอบ IEC 62133:**
- [ให้ความมั่นใจในความปลอดภัยของผลิตภัณฑ์โดยการปฏิบัติตามข้อกำหนดและการทดสอบ](https://www.intertek.com/batteries/iec-62133/)
- [ลดความเสี่ยงของอุบัติเหตุ เช่น ไฟไหม้ หรือระเบิด](https://www.ufinebattery.com/blog/what-is-the-iec62133-certification/)
- [ช่วยในการเข้าถึงตลาดระหว่างประเทศ](https://www.intertek.com/batteries/iec-62133/)
- [สร้างความมั่นใจให้กับผู้บริโภค](https://www.ufinebattery.com/blog/what-is-the-iec62133-certification/)

**การทดสอบหลัก:**

| การทดสอบ | วัตถุประสงค์ | เงื่อนไข | ผลลัพธ์ที่คาดหวัง |
|---|---|---|---|
| [Overcharge Protection](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html) | ทดสอบการป้องกันการชาร์จเกิน | [ชาร์จตามที่ผู้ผลิตระบุเป็นเวลา 7 วัน](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html) | [ไม่มีไฟไหม้, ไม่ระเบิด, ไม่รั่วซึม](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html) |
| [Temperature Test](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html) | ทดสอบในอุณหภูมิสูง | [75°C±2°C เป็นเวลา 7 ชั่วโมง](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html) | ไม่มีไฟไหม้, ไม่ระเบิด |
| [Vibration Test](https://www.dnkpower.com/battery-iec-62133/) | ทดสอบความทนต่อการสั่นสะเทือน | ตามพารามิเตอร์ UN 38.3 | ไม่เกิดความเสียหาย |
| [Shock Test](https://www.dnkpower.com/battery-iec-62133/) | ทดสอบการกระแทก | ตามพารามิเตอร์ UN 38.3 | ไม่เกิดความเสียหาย |
| [Short Circuit Test](https://www.envi-chambers.com/iec-62133-2-testing-for-lithium-systems/) | ทดสอบการลัดวงจร | อุณหภูมิห้อง | ไม่มีไฟไหม้, ไม่ระเบิด |

**ข้อกำหนดความต้านทานฉนวน:**
- [ความต้านทานฉนวนระหว่างเคสโลหะที่เข้าถึงได้และขั้วบวก > 5 MΩ](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html)

**ความแตกต่างจากมาตรฐานอื่น:**
- [IEC 62133 เป็นมาตรฐานสำหรับระบบลิเธียมและนิกเกิล](https://blog.clevercompliance.io/electrical-product-compliance/international-safety-standards-for-batteries/)
- [UL 1642 และ UL 2054 สำหรับอเมริกาเหนือ](https://blog.clevercompliance.io/electrical-product-compliance/international-safety-standards-for-batteries/)
- [JIS C8714 สำหรับญี่ปุ่น](https://blog.clevercompliance.io/electrical-product-compliance/international-safety-standards-for-batteries/)

---

## 🎵 มาตรฐานความปลอดภัยอุปกรณ์เสียงและวิดีโอ

### 🔌 IEC 62368-1: ความปลอดภัยอุปกรณ์เสียง/วิดีโอและ ICT

- **ชื่อเต็ม (EN):** [Audio/video, information and communication technology equipment - Part 1: Safety requirements](https://webstore.iec.ch/en/publication/69308)
- **ชื่อไทย:** [อุปกรณ์เสียง/วิดีโอ เทคโนโลยีสารสนเทศและการสื่อสาร - ส่วนที่ 1: ข้อกำหนดความปลอดภัย](https://www.laboratuvar.org/th/testler/standardizasyon-testleri/iec-en-62368-1-audio-video-bilgi-ve-iletisim-teknolojileri-donanimi-bolum-1-guvenlik-kurallari-(eski-iec-en-60950-1)/)
- **มาตรฐานไทย:** [มอก. 62368 เล่ม 1-2563](https://www.tisi.go.th/data/standard/pdf/a62368_1_2563_17052564.pdf)

**วัตถุประสงค์:** [เป็นมาตรฐานความปลอดภัยผลิตภัณฑ์ที่จำแนกแหล่งพลังงาน กำหนดมาตรการป้องกันแหล่งพลังงานเหล่านั้น และให้คำแนะนำเกี่ยวกับการใช้และข้อกำหนดสำหรับมาตรการป้องกันเหล่านั้น](https://webstore.iec.ch/en/publication/69308)

**แนวคิดหลัก:** [มาตรฐานนี้ใช้แนวทาง Hazard-Based Safety Engineering (HBSE) ที่เน้นการระบุอันตรายที่อาจเกิดขึ้นและการใช้มาตรการลดความเสี่ยงเหล่านั้น](https://www.candtsolution.com/news_events-detail/what-is-iec-62368-1/)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์ไฟฟ้าและอิเล็กทรอนิกส์ในด้านเสียง วิดีโอ เทคโนโลยีสารสนเทศและการสื่อสาร และเครื่องจักรธุรกิจและสำนักงานที่มีแรงดันไฟฟ้าไม่เกิน 600 V](https://www.dlsemc.com/iec-en-62368-1-audio-video-information-and-communication-technology-equipment-part-1-safety-requirements/)

**ประเภทอุปกรณ์ที่ครอบคลุม:**
- **ผลิตภัณฑ์คอมพิวเตอร์และเครือข่าย:** [เซิร์ฟเวอร์, PC, เราเตอร์, คอมพิวเตอร์แล็ปท็อป, แท็บเล็ตและแหล่งจ่ายไฟ](https://www.ul.com/services/iec-62368-1-testing-certification)
- **อิเล็กทรอนิกส์สำหรับผู้บริโภค:** [เครื่องขยายเสียง, ระบบโฮมเธียเตอร์, กล้องดิจิทัลและเครื่องเล่นเพลงส่วนบุคคล](https://www.ul.com/services/iec-62368-1-testing-certification)
- **จอแสดงผลและหน่วยแสดงผล:** [จอภาพ, ทีวีและโปรเจ็กเตอร์ดิจิทัล](https://www.ul.com/services/iec-62368-1-testing-certification)
- **ผลิตภัณฑ์โทรคมนาคม:** [อุปกรณ์โครงสร้างพื้นฐานเครือข่าย, โทรศัพท์ไร้สายและมือถือ และอุปกรณ์สื่อสารที่คล้ายกัน รวมถึงอุปกรณ์ที่ใช้แบตเตอรี่](https://www.ul.com/services/iec-62368-1-testing-certification)
- **อุปกรณ์สำนักงาน:** [เครื่องถ่าเอกสารและเครื่องทำลายเอกสาร](https://www.ul.com/services/iec-62368-1-testing-certification)

**การเปลี่ยนแปลงจากมาตรฐานเดิม:**
- [แทนที่ IEC 60065 สำหรับอุปกรณ์เสียง/วิดีโอ และ IEC 60950-1 สำหรับอุปกรณ์เทคโนโลยีสารสนเทศ](https://www.candtsolution.com/news_events-detail/what-is-iec-62368-1/)
- [ใช้แนวทางที่เน้นอันตราย (hazard-based approach) แทนการกำหนดกฎเฉพาะ](https://onlinestandart.com/en/iec-62368-1-standards-in-audio-video-and-information-technology/)

**ประโยชน์ของการปฏิบัติตาม:**
- [การเข้าถึงตลาดระหว่างประเทศ](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [เพิ่มความมั่นใจของผู้ใช้งาน](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [การปฏิบัติตามกฎหมาย](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)

**ความแตกต่างระหว่าง IEC 62368-1 และ UL 62368-1:**
- **การใช้งานตามภูมิภาค:** [IEC 62368-1 เป็นมาตรฐานระหว่างประเทศ ในขณะที่ UL 62368-1 ได้รับการยอมรับหลักในตลาดอเมริกาเหนือ](https://www.candtsolution.com/news_events-detail/what-is-iec-62368-1/)
- **ข้อกำหนดเฉพาะ:** [UL อาจมีเกณฑ์เพิ่มเติมหรือปรับเปลี่ยนเพื่อให้สอดคล้องกับขั้นตอนการรับรองและข้อพิจารณาในระดับภูมิภาค](https://www.candtsolution.com/news_events-detail/what-is-iec-62368-1/)

**หลักการความปลอดภัยหลัก:**
- [การประเมินความเสี่ยงและการวิเคราะห์อันตราย](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [ข้อกำหนดการก่อสร้างเกี่ยวกับความแข็งแรงเชิงกล, ฉนวน, การระบายอากาศ และการป้องกันไฟฟ้าดูด](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [การป้องกันอันตรายจากไฟไหม้และไฟฟ้าดูด](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [ประสิทธิภาพการใช้พลังงาน](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)

**รุ่นปัจจุบัน:** [IEC 62368-1:2023 (ฉบับที่ 4)](https://webstore.iec.ch/en/publication/69308)

**หมายเหตุ:** ในประเทศไทย [สมอ. ได้เตรียมออกมาตรฐานควบคุม "อะแดปเตอร์" ชาร์จโทรศัพท์มือถือ/แท็บเล็ต ภายใต้ มอก. 62368 เล่ม 1-2563](https://www.thaigov.go.th/news/contents/details/41223)

---

## 📝 สรุปการเลือกใช้มาตรฐาน

### 🎯 แนวทางการเลือกมาตรฐานสำหรับหุ่นยนต์ในโรงพยาบาล

**มาตรฐานหลักที่จำเป็น:**
1. **IEC 60601-1** - ความปลอดภัยพื้นฐานสำหรับอุปกรณ์ทางการแพทย์
2. **IEC 60601-1-2** - EMC สำหรับอุปกรณ์ทางการแพทย์ (สภาพแวดล้อมโรงพยาบาล)
3. **IEC 62133-2** - ความปลอดภัยแบตเตอรี่ลิเธียม (หากใช้แบตเตอรี่)
4. **IEC 62368-1** - ความปลอดภัยระบบควบคุมและการสื่อสาร

**มาตรฐานเสริม (ขึ้นอยู่กับสภาพแวดล้อม):**
- **IEC 61000-6-1** - หากใช้งานในพื้นที่อื่นนอกโรงพยาบาล
- **IEC 61000-6-2** - หากใช้งานในสภาพแวดล้อมอุตสาหกรรม
- **CISPR 32/35** - หากมีระบบมัลติมีเดียหรือการสื่อสาร

### 🔄 ลำดับการทดสอบที่แนะนำ

1. **ขั้นที่ 1: การออกแบบ**
   - ศึกษามาตรฐาน IEC 60601-1 และ IEC 60601-1-2
   - วิเคราะห์ความเสี่ยงตาม IEC 62368-1
   - เลือกแบตเตอรี่ที่ผ่านมาตรฐาน IEC 62133-2

2. **ขั้นที่ 2: การทดสอบความปลอดภัย**
   - ทดสอบตาม IEC 60601-1 (ความปลอดภัยพื้นฐาน)
   - ทดสอบตาม IEC 62368-1 (ระบบควบคุม)
   - ทดสอบแบตเตอรี่ตาม IEC 62133-2

3. **ขั้นที่ 3: การทดสอบ EMC**
   - ทดสอบ Emissions ตาม CISPR 32 (หากมี)
   - ทดสอบ Immunity ตาม IEC 60601-1-2 (สภาพแวดล้อมโรงพยาบาล)
   - ทดสอบ Immunity ตาม CISPR 35 (หากมี)

### ⚠️ ข้อควรระวังสำคัญ

**สำหรับการใช้งานในโรงพยาบาล:**
- ใช้ระดับการทดสอบ EMC ของสภาพแวดล้อมโรงพยาบาลตาม IEC 60601-1-2
- ต้องมีการประเมิน Basic Safety และ Essential Performance
- ต้องจัดทำ Test Plan ตามภาคผนวก G ของ IEC 60601-1-2

**สำหรับระบบที่มีแบตเตอรี่:**
- ใช้แบตเตอรี่ที่ผ่านการทดสอบ IEC 62133-2
- พิจารณาการทดสอบ UN 38.3 สำหรับการขนส่ง
- ระวังการชาร์จเกินและการระบายความร้อน

**สำหรับระบบสื่อสาร:**
- ปฏิบัติตาม IEC 62368-1 สำหรับระบบควบคุม
- ใช้ CISPR 32/35 หากมีฟังก์ชันมัลติมีเดีย
- พิจารณา RED (Radio Equipment Directive) หากมีการสื่อสารไร้สาย

---

## 📚 แหล่งข้อมูลอ้างอิง

### 🏛️ องค์กรมาตรฐานหลัก
- [IEC (International Electrotechnical Commission)](https://www.iec.ch/)
- [CISPR (International Special Committee on Radio Interference)](https://www.cispr.org/)
- [CENELEC (European Committee for Electrotechnical Standardization)](https://www.cenelec.eu/)

### 📖 แหล่งข้อมูลเชิงลึก
- [D.L.S. Electronic Systems - IEC 61000-6-1](https://www.dlsemc.com/iec-en-61000-6-1-electromagnetic-compatibility-emc-generic-standards-immunity-for-residential-commercial-and-light-industrial-environments/)
- [D.L.S. Electronic Systems - IEC 61000-6-2](https://www.dlsemc.com/iec-en-61000-6-2-generic-standards-immunity-for-industrial-environments/)
- [Keystone Compliance - IEC 61000-6-1 Testing](https://keystonecompliance.com/iec-61000-6-1/)
- [Keystone Compliance - IEC 61000-6-2 Testing](https://keystonecompliance.com/iec-61000-6-2/)
- [Keystone Compliance - EN 55032 Testing](https://keystonecompliance.com/en-55032-multi-media-emission-testing/)
- [Keystone Compliance - EN 55035 Testing](https://keystonecompliance.com/en-55035-multimedia-emc-testing/)
- [Academy of EMC - EMC Standards](https://www.academyofemc.com/emc-standards)
- [EMC Bayswater - EN 55032 & CISPR 32](https://www.emcbayswater.com.au/blog/emc-testing/commercial-emc-testing/en-55032-2012-multi-media-equipment/)
- [EMC Bayswater - EN 55035 & CISPR 35](https://www.emcbayswater.com.au/blog/certifications/ce-mark-emc-radio-testing/en55035-cispr35-multimedia-accredited-emc-lab/)
- [Element - EN 55032 and 55035](https://www.element.com/nucleus/2020/what-you-need-to-know-about-en-55032-and-55035-cispr-32-and-35)

### 🏥 แหล่งข้อมูลมาตรฐานทางการแพทย์
- [Johner Institute - IEC 60601-1-2](https://www.johner-institute.com/articles/product-development/and-more/iec-60601-1-2/)
- [Intertek - IEC 60601-1-2 Medical EMC Testing](https://www.intertek.com/medical/regulatory-requirements/emc-testing/)
- [Medical Design Briefs - EMC for Medical Devices](https://www.medicaldesignbriefs.com/component/content/article/mdb/pub/features/articles/33060)
- [Testups - IEC 60601-1-2 Medical EMC Standard](https://www.testups.com/iec-60601-1-2-medical-emc-standard/)
- [Sunfire Testing - IEC 60601-1-2 Testing Guide](https://www.sunfiretesting.com/IEC-60601-1-2-Testing-Guide-for-Medical-Device-EMC/)

### 🔋 แหล่งข้อมูลมาตรฐานแบตเตอรี่
- [Intertek - IEC 62133 Safety Testing](https://www.intertek.com/batteries/iec-62133/)
- [DNK Power - Battery IEC 62133](https://www.dnkpower.com/battery-iec-62133/)
- [Environmental Chambers - IEC 62133-2 Testing](https://www.envi-chambers.com/iec-62133-2-testing-for-lithium-systems/)
- [Benzo Energy - IEC 62133 Certification](https://www.benzoenergy.com/blog/post/li-ion-battery-test-report-iec-62133.html)
- [UL Solutions - Understanding Portable Battery Safety](https://www.ul.com/news/ul-62133-family-standards-batteries)
- [TÜV SÜD - Battery Transportation Safety](https://www.tuvsud.com/en/industries/mobility-and-automotive/automotive-and-oem/automotive-testing-solutions/battery-testing/battery-testing-according-to-un-38-3-iec-62133-iec-62619-and-other-standards)
- [UFine Battery - IEC 62133 Certification](https://www.ufinebattery.com/blog/what-is-the-iec62133-certification/)
- [LiPol Battery - IEC 62133-2:2017 Certification](https://www.lipolbattery.com/What's-IEC62133-2-2017-Certification-of-Lithium-ion-Battery.html)
- [Clever Compliance - International Battery Safety Standards](https://blog.clevercompliance.io/electrical-product-compliance/international-safety-standards-for-batteries/)

### 🎵 แหล่งข้อมูลมาตรฐาน IEC 62368-1
- [UL Solutions - IEC 62368-1 Testing and Certification](https://www.ul.com/services/iec-62368-1-testing-certification)
- [D.L.S. Electronic Systems - EN IEC 62368-1](https://www.dlsemc.com/iec-en-62368-1-audio-video-information-and-communication-technology-equipment-part-1-safety-requirements/)
- [Megalab Group - Beginner's Guide to IEC 62368-1](https://megalabinc.com/safety/a-beginners-guide-to-ul-csa-iec-62368-1-product-safety-standards-for-audio-video-and-ict-equipment/)
- [Online Standard - IEC 62368-1 Standards](https://onlinestandart.com/en/iec-62368-1-standards-in-audio-video-and-information-technology/)
- [LISUN - IEC 62368-1 Testing Solutions](https://www.lisungroup.com/standards/iec-62368-1-audio-video-information-and-communication-technology-equipment-part-1-safety-requirements.html)
- [C&T Solution - What is IEC 62368-1?](https://www.candtsolution.com/news_events-detail/what-is-iec-62368-1/)
- [Document Center - IEC 62368-1](https://www.document-center.com/standards/show/IEC-62368-1)
- [Intertek - IEC 62368-1 Certification Solutions](https://www.intertek.com/ict/iec-62368-1-certification/)

---

## 📋 ตารางสรุปมาตรฐานทั้งหมด

| มาตรฐาน | ประเภท | สภาพแวดล้อม | ความสำคัญ | หมายเหตุ |
|---|---|---|---|---|
| IEC 60601-1 | ความปลอดภัย | โรงพยาบาล | ★★★★★ | มาตรฐานหลักสำหรับอุปกรณ์ทางการแพทย์ |
| IEC 60601-1-2 | EMC | โรงพยาบาล | ★★★★★ | EMC เฉพาะสำหรับอุปกรณ์ทางการแพทย์ |
| IEC 62133-2 | ความปลอดภัย | ทั่วไป | ★★★★☆ | จำเป็นหากใช้แบตเตอรี่ลิเธียม |
| IEC 62368-1 | ความปลอดภัย | ทั่วไป | ★★★★☆ | สำหรับระบบควบคุมและสื่อสาร |
| IEC 61000-6-1 | EMC | ที่อยู่อาศัย/พาณิชย์ | ★★★☆☆ | หากใช้งานนอกโรงพยาบาล |
| IEC 61000-6-2 | EMC | อุตสาหกรรม | ★★☆☆☆ | หากใช้งานในสภาพแวดล้อมอุตสาหกรรม |
| CISPR 32 | EMC Emissions | ทั่วไป | ★★☆☆☆ | หากมีฟังก์ชันมัลติมีเดีย |
| CISPR 35 | EMC Immunity | ทั่วไป | ★★☆☆☆ | หากมีฟังก์ชันมัลติมีเดีย |

---

## 📞 การติดต่อและคำปรึกษา

สำหรับข้อมูลเพิ่มเติมหรือคำปรึกษาเกี่ยวกับการนำมาตรฐานเหล่านี้ไปใช้ในโครงการ กรุณาติดต่อผู้เชี่ยวชาญด้าน EMC และความปลอดภัยอุปกรณ์ทางการแพทย์ หรืออ้างอิงจากแหล่งข้อมูลที่ระบุไว้ในเอกสารนี้

**หมายเหตุ:** เอกสารนี้จัดทำขึ้นเพื่อเป็นแนวทางเบื้องต้น การนำไปใช้จริงควรได้รับคำปรึกษาจากผู้เชี่ยวชาญและศึกษามาตรฐานฉบับเต็มจากแหล่งที่เป็นทางการไฟฟ้าทางการแพทย์ - ส่วนที่ 1: ข้อกำหนดทั่วไปสำหรับความปลอดภัยพื้นฐานและประสิทธิภาพที่จำเป็น

**วัตถุประสงค์:** [เป็นมาตรฐานหลักสำหรับความปลอดภัยของอุปกรณ์ไฟฟ้าทางการแพทย์และระบบไฟฟ้าทางการแพทย์](https://en.wikipedia.org/wiki/IEC_60601)

**ขอบเขตการใช้งาน:**
- [อุปกรณ์ไฟฟ้าทางการแพทย์และระบบไฟฟ้าทางการแพทย์ (ME equipment และ ME systems)](https://webstore.iec.ch/en/publication/2594)
- [การปฏิบัติตามมาตรฐาน IEC 60601-1 เป็นข้อกำหนดสำหรับการขายอุปกรณ์ทางการแพทย์ในหลายประเทศ](https://en.wikipedia.org/wiki/IEC_60601)
- [มาตรฐานนี้ไม่รับประกันประสิทธิผลของอุปกรณ์ทางการแพทย์](https://en.wikipedia.org/wiki/IEC_60601)

**โครงสร้างมาตรฐาน:**
- **มาตรฐานหลัก (General Standard):** IEC 60601-1
- **มาตรฐานกลุ่ม (Collateral Standards):** IEC 60601-1-X (เช่น EMC, Usability, Alarms)
- **มาตรฐานเฉพาะ (Particular Standards):** IEC 60601-2-X (เช่น MRI, EEG, Ventilators)

---

### 📶 IEC 60601-1-2: ความเข้ากันได้ทางแม่เหล็กไฟฟ้าสำหรับอุปกรณ์ทางการแพทย์

- **ชื่อเต็ม (EN):** [Medical electrical equipment - Part 1-2: General requirements for basic safety and essential performance - Collateral Standard: Electromagnetic disturbances - Requirements and tests](https://webstore.iec.ch/en/publication/67554)
- **ชื่อไทย:** อุปกรณ์
