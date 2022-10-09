# hackathon-season2

## How to use

```
cd hackathon-season2

make convert_xml_to_csv (**แปลงไฟล์ xml เป็น csv ชื่อ dev_club.csv กับ dev_mountain.csv**)

make create_table (**สร้าง database และ table**)

make clean_table (**ลบ data ออกจาก table**)

make csv_to_db (**import dev_club.csv to database**)

make generate_json (**สร้างไฟล์ dev_club.json**)

make generate_csv_by_nationality (**สร้างไฟล์ csv แยกตาม nationality**)
```

## เลข Status จะมีตามนี้ครับ
- 1 = Active
- 2 = Resigned
- 3 = Retired
- ถ้าเป็นเลขอื่นๆจะถือว่าเป็น anomaly information(**ข้อมูลที่ไม่ถูกต้อง**)

## กฎระเบียบ

- ห้ามใช้ library สำหรับการทำ transformation จาก XML ไปเป็น CSV
- สามารถใช้ Driver ของตัวภาษานั้นๆ เพื่อต่อ SQLlite ได้
- ไม่อนุญาตให้ใช้ Tool สำเร็จรูป

## เกณฑ์การให้คะแนน

- โค๊ดทำงานถูกต้อง
- Performance
  - Memory usage
  - Runtime benchmark 
- Code อ่านง่าย
- ส่งเร็ว
- Creative ตอนทำ Data visualization 
- ผลลัพธ์จาก SQLlite ต้องได้เป็น **JSON** format

**ตัวอย่าง Data visualization**

[dev-mountain-visualization](https://dev-moutain-dataviz.netlify.app/)


## ตัวอย่างการสร้าง PR
ทีม Dev mountain
สมาชิก
- [annibuliful](https://github.com/annibuliful)
- [lordbenz](https://github.com/lordbenz)

Repo: [hackathon](https://github.com/devmountaintechfest/hackathon-season2)
