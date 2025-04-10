🎓 Smart Student ID Generator

💡 Project Idea
An app to generate smart student ID cards with photos, allergy info, QR codes, and more. Each card can be downloaded as an image and stored locally.

---

🧠 Thought Process

Form Design:
   - Collected all student data (Name, Roll No., Class, Division, Rack No., Bus Route, Allergies, Photo).
   - Used multiselect for allergies and dropdowns for Class and Bus Route.

2. Preview & Template:
   - Card updates live as user types.
   - Added two templates that can be switched with visible UI change.

3. QR Code Integration:
   - Used `qrcode.react` to create QR from student info.

4. Download & Save:
   - Used `html-to-image` and `file-saver` to save card as PNG.
   - Stored previous entries in `localStorage`.

5. Bonus Features:
   - List of old saved cards.
   - Delete cards individually.

---

🛠️ Tech Stack
- ReactJS
- HTML + CSS
- `qrcode.react`
- `html-to-image`
- `file-saver`
- LocalStorage

---
 🔗 Hosted on Replit
👉https://replit.com/@sharmaritika970/smart-student-id
