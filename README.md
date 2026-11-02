# My AI Gemini / Antigravity Skills

คลังรวบรวม Global Skills สำหรับ Antigravity / Gemini

## วิธีซิงก์ไปใช้ที่เครื่องใหม่ (How to sync on a new machine)

### 1. ไปที่โฟลเดอร์ Config
```powershell
cd "$HOME\.gemini\config"
```

### 2. Clone Repository นี้ลงมา
```powershell
git clone https://github.com/IMONTE23/my-ai-gemini-skills.git skills
```

### 3. การอัปเดตเมื่อมี Skill ใหม่
* **เครื่องที่มีการแก้ไข/เพิ่ม Skill:**
  ```powershell
  cd "$HOME\.gemini\config\skills"
  git add .
  git commit -m "update skills"
  git push
  ```
* **เครื่องอื่น ๆ ที่ต้องการดึงข้อมูลล่าสุด:**
  ```powershell
  cd "$HOME\.gemini\config\skills"
  git pull
  ```
