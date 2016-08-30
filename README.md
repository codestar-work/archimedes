# Archimedes
Archimedes เป็นระบบแปลง Position จาก Latitude, Longitude
เป็นชื่อหมู่บ้าน ตำบล อำเภอ จังหวัด ซึ่ง Service นี้เปิดบริการฟรี

# ตัวอย่าง request
```
https://euclid.info?latitude=123.456789&longitude=12.345678
```

# ตัวอย่าง response
```
{
	"หมู่บ้าน":    "...",
	"ตำบล":     "...",
	"อำเภอ":    "...",
	"จังหวัด":    "...",
	"village":  "...",
	"district": "...",
	"city":     "...",
	"province": "..."
}
```

