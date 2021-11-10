<p># fwbotlocal<br />Farmers World Bot Anchor<br />######################################</p>
<h2>การทำงานเบื้องต้น</h2>
<p style="padding-left: 40px;">ระบบจะลิสอุปกรณ์ทั้งหมดในไอดี (เฉพาะ tools ในเวอชั่นนี้) จากนั้นจะทำงานจากไอเทมที่เวลาเหลือน้อยที่สุดหากยังไม่ถึงเวลา จะแจ้งสถานะในการเคลมครั้งต่อไปไว้</p>
<p style="padding-left: 40px;">ปล.ควรเปิดปิดบอทวันละ 1 ครั้งเพื่อการทำงานเต็มประสิทธิภาพ</p>
<h2>วิธีใช้</h2>
<ol>
<li>ใส่ wallet และ privatekey ในไฟล์ accounts.json แล้วบันทึก</li>
<li>ตั้งค่าต่างในไฟล์ settings.json ดังนี้
<ul>
<li>"REPAIR_IF_DURABILITY_LOWER": 50, //จะซ่อมอุปกรณ์ เมื่อค่าน้อยกว่าหรือเท่ากับค่าที่กำหนด&nbsp;</li>
<li>"RECOVER_IF_ENERGY_LOWER": 40, //จะเติมพลังงาน เมื่อค่าน้อยกว่าหรือเท่ากับค่าที่กำหนด&nbsp;</li>
<li>"LOWEST_ENERGY": 275, //จะเติมพลังงาน เมื่อค่าน้อยกว่าค่าที่กำหนด</li>
<li>"MINIMUM_FEE": 5, //ถอน token เมื่อมีค่า fee ตามที่กำหนด</li>
<li>"MINIMUN_WITHDRAW": 300, //จำนวนขั้นต่ำที่ถอน</li>
<li>"FOOD": false, // ตั้งค่าถอน food / true = ถอน,false = ไม่ถอน</li>
<li>"WOOD": true, // ตั้งค่าถอน wood / true = ถอน,false = ไม่ถอน</li>
<li>"GOLD": false // ตั้งค่าถอน gold / true = ถอน,false = ไม่ถอน</li>
</ul>
</li>
<li>แตกไฟล์ web.zip จะเจอไฟล์ web.exe ให้นำไปไว้ในโฟเดอร์เดียวกับ settings.json และ accounts.json</li>
<li>รัน web.exe เพื่อทำงาน</li>
</ol>
<h2>เงื่อนไขการใช้งาน</h2>
<p style="padding-left: 40px;">การหา privatekey ได้มาจาก ตอนสร้าง wallet wax ใน anchor ควรเก็บรักษาให้ดีและไม่ให้ใคร</p>
<p style="padding-left: 40px;">ตัวโปรแกรมไม่มีการเก็บข้อมูลต่างๆแต่อย่างใด สามารถใช้งานได้ฟรี หากไม่สบายใจ ปล่อยผ่านได้</p>
<p>######################################</p>
