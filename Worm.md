# Worm
- - -
**computer worm**

  A computer worm is a standalone malware computer program that replicates itself in order to spread to other computers.
  1. It often uses a computer network to spread itself, 
  relying on security failures on the target computer to access it. It will use this machine as a host to scan and infect other computers. When these new worm-invaded computers are controlled, 
  the worm will continue to scan and infect other computers using these computers as hosts, and this behaviour will continue.
  2. Computer worms use recursive methods to copy themselves without host programs and distribute themselves based on exploiting the advantages of exponential growth, thus controlling and infecting more and more computers in a short time.
  3. Worms almost always cause at least some harm to the network, even if only by consuming bandwidth, whereas viruses almost always corrupt or modify files on a targeted computer.

     <p align="center">
         <img src="img/Virusworm.jpg" />
      </p>
     
Many worms are designed only to spread, and do not attempt to change the systems they pass through. However, as the Morris worm and Mydoom showed, even these "payload-free" worms can cause major disruption by increasing network traffic and other unintended effects.

**Countermeasures**

Worms spread by exploiting vulnerabilities in operating systems. Vendors with security problems supply regular security updates (see "Patch Tuesday"), and if these are installed to a machine, then the majority of worms are unable to spread to it. If a vulnerability is disclosed before the security patch released by the vendor, a zero-day attack is possible.

Users need to be wary of opening unexpected email, and should not run attached files or programs, or visit web sites that are linked to such emails. However, as with the ILOVEYOU worm, and with the increased growth and efficiency of phishing attacks, it remains possible to trick the end-user into running malicious code.

Anti-virus and anti-spyware software are helpful, but must be kept up-to-date with new pattern files at least every few days. The use of a firewall is also recommended.

Users can minimize the threat posed by worms by keeping their computers' operating system and other software up to date, avoiding opening unrecognized or unexpected emails and running firewall and antivirus software.

Mitigation techniques include:

 + ACLs in routers and switches
 + Packet-filters
 + TCP Wrapper/ACL enabled network service daemons
 + EPP/EDR software
 + Nullroute

Infections can sometimes be detected by their behavior - typically scanning the Internet randomly, looking for vulnerable hosts to infect. In addition, machine learning techniques can be used to detect new worms, by analyzing the behavior of the suspected computer.

refer
> https://en.wikipedia.org/wiki/Computer_worm#cite_note-1

- - -

**Worm (เวิร์ม) หรือ หนอนคอมพิวเตอร์ คืออะไร?**

  หนอนคอมพิวเตอร์ หรือ หนอนอินเทอร์เน็ต (อังกฤษ: computer worm) หรือบางทีเรียกกันว่าเวิร์ม คือหน่วยย่อยลงมาจากมัลแวร์ (อังกฤษ:Malware)ปกติแล้ว หนอนคอมพิวเตอร์จะแพร่กระจายโดยไม่ผ่านการใช้งานของผู้ใช้ โดยมันจะคัดลอกและกระจายตัวมันเองข้ามเครือข่าย      เช่น  ระบบเครือข่ายหรืออินเทอร์เน็ตเป็นต้น หนอนคอมพิวเตอร์สามารถทำลายข้อมูลและแบนด์วิดท์สร้างความเสียหายให้กับคอมพิวเตอร์รวมไปถึงการทำให้คอมพิวเตอร์หยุดทำงานอีกด้วย
     <p align="center">
         <img src="img/worm.png" />
     </p>

  การโจมตีของมัลแวร์เวิร์มคือ จะคัดลอกตัวเองไปยังไดร์ฟเครื่อข่ายหรือไดร์ฟแบบถอดได้ เช่น USB Drive (ยู เอส บี ไดร์ฟ) โดยมัลแวร์ชนิดนี้สามารถกระทำการที่เป็นอันตรายต่างๆ เช่น ขโมยข้อมูลที่สำคัญ เปลี่ยนการตั้งค่าความปลอดภัยของเครื่องคอมพิวเตอร์ เพื่อส่งข้อมูลไปยัง     แฮกเกอร์ ทำให้เป็นอันตรายและมำให้เหยื่อไม่สามารถเข้าถึงไฟล์ของตัวเองได้

**ลักษณะการแพร่กระจายของเวิร์ม**

  มัลแวร์เวิร์ม สามารถแพร่กระจายผ่านไฟล์แนบอีเมลล์โปรแกรมส่งข้อความโต้ตอบแบบทันที โปรแกรมแชร์ไฟล์ ไซต์เครือข่าย ไดร์ฟแบบถอดได้ และช่องโหว่ของซอฟแวร์

**วิธีการป้องกันมัลแวร์เวิร์ม**

  สามารถป้องกันมัลแวร์เวิร์มได้ โดยการติดตั้งโปรแกรมสแกนไวรัส หรือ แอนตี้ไวรัสได้ 
  1. Windows Defender สำหรับ Windows 10 และ Windows 8.1
  2. Microsoft Safety Scanner สำหรับ Windows 7 และ Windows Vista
  3. นอกจากนี้ยังควรใช้การสแกนแบบเต็มรูปแบบ การสแกนแบบเต็มรูปแบบอาจจะทำให้พบมัลแวร์อื่นๆที่ซ่อนอยู่
  4. ปิดการใช้งานอัตโนมัติ
  5. ควรสแกนไดร์ฟแบบถอดได้เสมอ ก่อนการเปิดใช้งาน
  6. ไม่เปิดไฟล์ที่แนบมากับอีเมลที่ส่งมาจากผู้ที่ไม่รู้ว่าเป็นใคร
  7. ถึงแม้จะรู้ว่าผู้ส่งเป็นใคร ก็ไม่ควรเปิดไฟล์ที่แนบมาถ้าไม่แน่ใจว่าไฟล์ที่แนบมาเป็นอะไรกันแน่

อ้างอิง
> https://th.wikipedia.org/wiki/%E0%B8%AB%E0%B8%99%E0%B8%AD%E0%B8%99%E0%B8%84%E0%B8%AD%E0%B8%A1%E0%B8%9E%E0%B8%B4%E0%B8%A7%E0%B9%80%E0%B8%95%E0%B8%AD%E0%B8%A3%E0%B9%8C

> https://www.mindphp.com/%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%A1%E0%B8%B7%E0%B8%AD/73-%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%AD%E0%B8%B0%E0%B9%84%E0%B8%A3/4934-whatisworm.html
