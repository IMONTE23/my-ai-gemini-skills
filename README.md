# My AI Gemini / Antigravity Skills

คลังรวบรวม Global Skills สำหรับ Antigravity / Gemini (รวมทั้งหมด 81 Skills + Superpowers)

## วิธีซิงก์ไปใช้ที่เครื่องใหม่ (How to sync on a new machine)

### 1. เข้าไปยังโฟลเดอร์ Config ของ Antigravity/Gemini

* **macOS / Linux:**
  ```bash
  cd ~/.gemini/config
  ```
* **Windows (PowerShell):**
  ```powershell
  cd "$HOME\.gemini\config"
  ```

### 2. Clone Repository นี้ลงมาเป็นโฟลเดอร์ skills

* **macOS / Linux / Windows:**
  ```bash
  git clone https://github.com/IMONTE23/my-ai-gemini-skills.git skills
  ```

---

## การอัปเดตเมื่อมี Skill ใหม่ / แก้ไข Skill

### เมื่อสร้างหรือแก้ไข Skill ในเครื่องปัจจุบัน (Push ไป GitHub)
```bash
cd ~/.gemini/config/skills      # (Windows: cd "$HOME\.gemini\config\skills")
git add .
git commit -m "Update skills"
git push
```

### เมื่อต้องการดึง Skill ล่าสุดมาใช้อีกเครื่อง (Pull จาก GitHub)
```bash
cd ~/.gemini/config/skills      # (Windows: cd "$HOME\.gemini\config\skills")
git pull
```
