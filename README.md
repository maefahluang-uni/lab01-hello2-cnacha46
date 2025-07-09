[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19915667)
# Computer Programming - Hello World

### ขั้นตอนที่ 1: เปิดไฟล์

1. ในหน้าเบราว์เซอร์ของโปรแกรม Codespace (Explorer view) ให้ไปที่โฟลเดอร์ `lab`
2. แก้ไขไฟล์ `Program.cs` ที่ `main` โดยเพิ่มโค้ดตามด้านล่าง

```c#
Console.WriteLine("Hello John");
```

### ขั้นตอนที่ 2: บันทึกไฟล์

* กด `ctrl` + `s` เพื่อบันทึกไฟล์

### ขั้นตอนที่ 3: ทดสอบโปรแกรม

คุณสามารถรันโปรแกรมได้ 2 วิธี

#### 3.1 รันผ่านทาง UI

* กดปุ่มรัน (สามเหลี่ยม) ที่มุมขวาบนของโปรแกรม (รูปภาพประกอบอาจจะแตกต่างกันไปขึ้นอยู่กับโปรแกรมที่ใช้)

![](/images/vscode-run.png)

#### 3.2 รันผ่านทาง Terminal

1. เปิด Terminal (กด `ctrl` + `shift` + `  บนแป้นพิมพ์ด้านซ้ายบน)
2. พิมพ์คำสั่งต่อไปนี้ใน Terminal

```
dotnet run --project lab/hello-program.csproj
```

**หลังจากทำแบบฝึกหัดเสร็จอย่าลืม Commit & Push (โปรดดูรายละเอียดการส่งงานที่ระบบ)**




