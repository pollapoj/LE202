# ESP 01 Microcontroller

1 Digital

-สัญญาณดิจิทัลรับสัญญาณตัวเลข 0vเป็น0 

-สัญญาณดิจิทัลตั้งแต่0vถึง5v นับเป็น1

-ข้อมูลจะรับข้อมูลด้วยเลขฐาน2หรือเลขฐาน16

2 Voltage
-แรงดันไฟฟ้ากระแสตรง

-แรงดันไฟฟ้ากระแสสลับ

3 Computer

-มีการพัฒนามายาวนานกว่า60ปีโดยจะเน้นไปการทำให้มีขนาดที่เล็กลง ความจุและการประมวผลที่มากขึ้น

4 Internet

-เป็นสิ่งที่คอยเชื่อมต่อคนทั้งโลกเอาไว้โดยมีทั้งแบบมีสายและไม่มีสาย

5 Program lang

-ภาษาของคอมพิวเตอร์

6 Platform IO

- Microcontroller มีผู้ผลิตมหาศาลทำให้แต่ละคนเลือกใช้ภาษาที่แตกต่างกัน

- IO เป็นมาตรฐานในการพัฒนาซอต์ฟแวร์ที่สามารถเขียนบนMicrocontroller

- มีบอร์ดมากกว่า900แบบที่สามารถนำไปใช้เพื่อต่อยอดจากสิ่งที่เป็นอยู่ได้

IO set

- Download Program git

- Command promt ->Folder ->gitclone https://github.com/choompol-boonmee/ioset1.git

- Run github code

#Experiment

ex1 

- MicrocontrollerESP01 มีเสาอากาศ wifiและต้องต่อสายUSB ไปยังserial port เพื่อเขียนโปรแกรม

- มีโปรแกรมที่ใช้ภภาษาซีด้วยกัน9แบบ
 
- upload programเข้าไปยังmicrocontroller
 
- pio device monitorในการให้โปรแกรมแสดงผลลัพธ์ พบว่าcountเป็น0และเพิ่มที่ละ1 สามารถresetได้
 
ex2

- ใช้USB serial port และ set up wifiให้พร้อมและมีloop
 
- เมื่อมีwifi = access point อะไรบ้าง
 
- pio device monitor หา wifi
 
relay

- programที่ติดตั้งไปทำให้microcontrollerสามารถส่งสัญญาณผ่านport0ไปยังหลอดไฟ ทำให้หลอดไฟกระพริบ
 
- microcontrollerต่อกับrelayเพื่อเป็นswitchในการเปิดปิดอุปกรณ์ ในทุกๆวินาที
 
- เสียงโลหะเป็นตัวนำไฟฟ้า เป็นswitchได้
 
ex4

- ทดลองส่งสัญญาณinputเข้าไปในmicrocontroller
 
- สัญญาณinputที่port0เป็นตัวควบคุม
 
- ใช้pio device monitorเพื่อทดลองการทำงาน
 
- ทดลองต่อcencerแสง มีresisterในวงจรโดยต่อสายขาหนึ่งเข้ากับground
 
- cencerเจอแสงอ่านเป็น0ไฟจะติด
 
- cencerไม่เจอแสงอ่านเป็น1ไฟจะไม่ติด
 
wifi

- program ต้องต่อwifiเพราะฉะนั้นต้องใส่ชื่อSSIDและpassword
 
- upload program -> microcontroller
 
- เช็คการทำงานของprogramด้วยbrownser
 
- จะทำงานเมื่อเจอserverจะแสดงข้อความ "Hello cnt:"
 
wifi AP

- เป็นการสร้างaccess pointของตัวเอง
 
- ต้องกำหนดIP address
 
- เปิดserverทีport80และเตรียมserverไว้1ตัว
 
- ใช้คำสั่งpio device monitorในการสร้างwifi(สามารถเชื่อมต่อจากอุปกรณ์electronicชิ้นใดก็ได้)
 
