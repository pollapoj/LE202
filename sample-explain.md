#Ex1

-ตัวโปรแกรมจะเริ่มตัวประกาศตัวแปรตัวเลขcnt โดยเริ่มต้นที่1

-loop เพิ่มทีละ1

-delay300ms

#Ex2

-ตัวโปรแกรมจะเริ่มตัวการประกาศตัวแปรตัวเลขcnt

-reset wifiให้พร้อมทำงานโดยมีdelay100ms

-loop scanหาwifi

-ถ้าหากหาไม่เจอจะขึ้นข้อความNO NETWORK FOUND

-ถ้าหาเจอจะแสดงผลและให้เราสามารถเลือกใช้wifi

#Ex3

-ตัวโปรแกรมจะเริ่มตัวการประกาศตัวแปรตัวเลขcnt

-setup กำหนดหน้าที่ของขาสัญญาณ(pin mode)ให้port 0เป็นoutput

-loopจะยังคงทำงานหากเป็นไปตามเงื่อนไข cnt%2

-หากcntเป็นเลขคู่จะแสดงผลONและจะเปิด

-หากcntเป็นเลขคี่จะแสดงผลOFFและจะปิด

-โดยทีี่แต่ละครั้งจะมีdelay500ms

#EX4

-set port 0 = inputและ port 2 = output

-ทำloopให้อ่านข้อมูลจากport0แล้วแสดงผล

-หากเป็น1จะให้lowไปที่port2ไฟจะดับ

-หากเป็น0จะให้highไปที่port2ไฟจะเปิด

#Ex5

-เริ่มต้นด้วยการใส่ชื่อSSID และPASSWORD

-select server

-เริ่มทำการรับสัญญาณ มีdelay500ms

-แสดงผลIP ADDRESS

-หากเชื่อมต่อไม่สำเร็จจะแสดงข้อความ" Path Not Found"

-หากเชื่อมต่อสำเร็จจะแสดงข้อความ" Hello cnt:(cntจะบวก1)

-HTTP server started

#Ex6

-เริ่มต้นด้วยการใส่ชื่อSSID และ PASSWORD

-ตั้งค่าIP address local,gateway,subnet

-หากเชื่อมต่อได้จะแสดงข้อความ " Hello cnt"
