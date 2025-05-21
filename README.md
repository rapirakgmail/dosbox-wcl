# wcl-env
# รายละเอียด
    - ชุุดโปรแกรมที่ใช้ในการสร้าง (build) โปรแกรมในชุดฝึกหัด
    - โปรแกรมรองรับเฉพาะระบบปฎิบัติการ DOS 16 bit หรือ DOXBOX
    
# แฟ้ม
    - DPRJ  : เตรียมสำหรับเก็บ source file 
               - การ complie โปรแกรม ".c" ให้เป็น ".exe" ใช้ c.bat
                  เช่น c wcloader  ผลลัพทธ์  wcloader.exe 
              - การ complie โปรแกรม ".c" ให้เป็น ".com" ใช้ b.bat
                  เช่น  b app2   ผลลัพทธ์  app2.com
    - tools : utility programs
    - WATCOM: Watcom C/C++ ที่พร้อมใช้งาน
    - AUTOEXEC.BAT : ไฟล์ "BAT" ทำหน้าที่ set path โดยให้สั่ง run เป็นลำดับแรก
      
 5. NOTE :
     1. exe2bin โปรแกรมที่ทำหน้าที่แปลง ".EXE" ให้เป็น ".COM"
     2. คู่มือการใช้ Watcom C/C++ https://open-watcom.github.io/open-watcom-v2-wikidocs/ctools.pdf
  
