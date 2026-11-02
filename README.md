# ZzaxAi — ตัวติดตั้ง

ที่เก็บนี้มีไว้แจกไฟล์ติดตั้งของ **ZzaxAi** เท่านั้น ไม่มีซอร์สโค้ด

ดาวน์โหลดรุ่นล่าสุดได้ที่ [zzaxai.com](https://zzaxai.com/#download) หรือที่หน้า [Releases](../../releases/latest)

| ไฟล์ | ใช้กับ |
|---|---|
| `ZzaxAi-Setup-Windows.exe` | Windows 10 / 11 (64 บิต) |
| `ZzaxAi-macOS-AppleSilicon.dmg` | แมคชิป Apple (M1 ขึ้นไป) |
| `ZzaxAi-macOS-Intel.dmg` | แมคชิป Intel |

ใช้ฟรี ไม่ต้องสมัครสมาชิก ไม่มีรุ่นเสียเงิน

## เปิดครั้งแรกบนแมค

แอปยังไม่ได้เซ็นชื่อนักพัฒนา macOS จึงกั้นไว้ ตอนเปิดครั้งแรกจะขึ้นกล่องว่า

> **“ZzaxAi” เสียหายและเปิดไม่ได้ คุณควรย้ายรายการไปยังถังขยะ**
> (เครื่องภาษาอังกฤษ: *“ZzaxAi” is damaged and can’t be opened.*)

**ไม่ใช่ไฟล์เสียครับ** กล่องนี้มีสองปุ่ม — **กด “ยกเลิก” อย่ากด “ย้ายไปยังถังขยะ”**
ถ้ากดถังขยะแอปจะหายต้องโหลดใหม่

จากนั้นลากแอปเข้า Applications แล้วเปิด Terminal วางคำสั่งนี้หนึ่งครั้ง

```
xattr -dr com.apple.quarantine /Applications/ZzaxAi.app
```

เปิดแอปได้ตามปกติ ทำครั้งเดียวพอ

## ติดปัญหา

อีเมล zzaxstudio@gmail.com · LINE @zabver

© ZZAX Studio
