# ปัญหาที่พบส่วนตัวของหูฟัง Sony INZONE H9

## ปัญหาเกิดจากการใช้ **USB Dongle** ไม่ได้ต่อผ่าน Bluetooth ##
สาเหตุที่ต้องใช้ USB Dongle เพราะเมื่อเชื่อมต่อกับ Windows จะให้เสียงที่ดีกว่า Bluetooth และสามารถใช้งานฟีเจอร์ของหูฟังได้เต็มที่

### สาเหตุที่มั่นใจว่าเป็นที่ตัวหูฟัง ###
1. Laptop ที่ใช้งานหูฟัง Sony INZONE H9 เคยใช้งานหูฟังยี่ห้ออื่นที่มีฟังชั่นแยกเสียง 2 channels (Game และ Chat) มาก่อน และไม่เคยเจอปัญหาใดๆจากหูฟังยี่ห้ออื่น
2. หลังจากพบปัญหาและส่งเคลมรอบแรก ได้ทำการลง Windows 11 Pro ใหม่เรียบร้อยแล้ว จึงไม่น่าเกิดจากตัว Laptop เองได้
3. นำไปใช้กับ Laptop เครื่องอื่นที่มี ก็พบปัญหานี้เช่นกัน

### รายละเอียดของปัญหาอย่างละเอียด ###
เมื่อเสียงจาก channel Game กับ channel Chat ถูกเล่นไปพร้อมกันต่อเนื่องเป็นเวลาระยะนึง เมื่อหยุดทำการใช้เสียงจาก channel ใด (เช่นปิดเกม จะเป็นการหยุดใช้งาน channel Game หรือออกจากโปรแกรมพูดคุย จะเป็นการหยุดใช้งาน channel Chat) เสียงจากอีก channel จะหายตามไปด้วย (ซึ่งในความเป็นจริงไม่ควรจะหายตามไป) สามารถดูวิดีโอประกอบตัวอย่างได้ที่นี่ [วิดีโอแสดงปัญหา](https://drive.google.com/drive/folders/1J_uBY9oWRBFfN_tPscV0-sK3ND4qDldh?usp=drive_link)

### วิธีทำให้เกิดปัญหานี้เท่าที่นึกได้ ###
1. ทำการใช้ 2 channels พร้อมกันด้วยวิธีใดๆก็ได้
- เช่นเปิด Youtube ใน Web Browser และทำการตั้งค่าให้ Web Browser ที่ใช้ให้เสียงออกทาง channel Game)
- จากนั้นเปิด Discord แล้วตั้งค่าให้เสียงออกทาง channel Chat จากนั้นให้คนอื่นพร้อมกันกับเราเข้ามาในห้อง Discord เดียวกัน
- หรืออีกวิธีคือ ใช้ Web Browser อีกตัวเปิด Youtube เหมือนกัน แต่ตั้งค่าให้ Web Browser ตัวนี้ให้เสียงออกทาง channel Chat
2. ทำการเปิดไปเรื่อยๆ เป็นเวลาระยะนึง แล้วทำการลอง pause Video หรือ ออกจาก Discord แล้วรอซักพัก (จนกว่า Windows จะหยุดใช้ channel นั้น ประมาณ 5-10 วินาที)
3. หลังจากทำขั้นตอนที่ 2 หากเกิดปัญหา จะพบว่าเสียงจากอีก channel ที่เปิดไว้จะหายตามไปด้วย แต่หากยังไม่พบ ให้ทำต่อไปเรื่อยๆ เพราะปัญหานี้ไม่ได้เกิดขึ้นทุกครั้งที่ทำแบบนี้เช่นกัน

# Personal Issue Encountered with Sony INZONE H9 Headphone

## Issue Arises from **USB Dongle**, Not Connected via Bluetooth ##
The necessity for using a USB dongle arises from its ability to provide superior audio quality compared to Bluetooth when connected to Windows. Additionally, it enables the full utilization of the headphone's features.

### Reasons for confidence that it is the headphone's problem ###
1. The laptop used with Sony INZONE H9 headphones previously used headphones from other brands with separate 2-channel sound functions (Game and Chat) without any issues.
2. After encountering the problem and filing the first warranty claim, a fresh installation of Windows 11 Pro was installed, eliminating the likelihood of the issue originating from the laptop itself.
3. The issue persists when used with other laptops as well.

### Detailed Description of the Problem ###
When sound from both the Game and Chat channels is played simultaneously for a certain period, upon stopping the use of either channel (e.g., closing the game, which stops the use of the Game channel, or exiting the chatting program, which stops the use of the Chat channel), the sound from the other channel disappears (which should not happen in reality). A demonstration video of the issue can be viewed [here](https://drive.google.com/drive/folders/1J_uBY9oWRBFfN_tPscV0-sK3ND4qDldh?usp=drive_link).

### Ways to Replicate the Issue ###
1. Simultaneously use both channels by any means:
- For instance, open YouTube in a web browser and set the web browser to output sound through the Game channel.
- Then, open Discord and set the sound output to the Chat channel. Afterwards, have others join the same Discord room.
- Alternatively, use another web browser to open YouTube similarly but set this web browser to output sound through the Chat channel.
2. Keep them open for a while and then try pausing the video or exiting Discord and wait for a while (until Windows stops using that channel, approximately 5-10 seconds).
3. After performing step 2, if the issue occurs, the sound from the other open channel will disappear as well. If the issue is not encountered, continue to repeat the process, as the problem does not occur every time.
