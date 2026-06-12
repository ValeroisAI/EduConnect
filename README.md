
```markdown
# Valerois EduConnect 🏫💬
!WARNING!
SOME FILES ARENT AVAIBLE RIGHT NOW. THIS REPO DOES NOT HAS HAVE ALL FILES!
**Valerois EduConnect** is a Firebase-based school communication platform that lets students and teachers talk **without sharing phone numbers**, submit complaints, and manage appointments – all under full principal oversight.

TCKN (Turkish Republic Identification Number) registration prevents troll accounts and ensures users are real individuals within the school ecosystem.

> 🔐 **Privacy-first:** No phone numbers are exposed. Conversations are logged and can be audited only by the principal.

---

## 🧩 Features

- 👥 **Role-based accounts**
  - Student
  - Teacher
  - Counselor / Vice Principal (created by principal)
  - Principal (super admin, sees all logs)

- 💬 **Anonymous chat**
  - Students ↔ teachers
  - No phone numbers exchanged
  - Principal can view all message logs

- 📢 **Complaint system**
  - Students send complaints to teachers / administration
  - Logged & viewable by principal

- 📅 **Appointment system**
  - Teachers or counselors propose time slots
  - Students request; accept / reject workflow
  - Full history for principal

- 🛡️ **TCKN registration**
  - Users register with their real Turkish ID number
  - Prevents duplicate and troll accounts
  - Principal verifies teacher/counselor accounts manually

- 🔍 **Principal dashboard**
  - See all messages, complaints, appointments
  - Create counselor / vice principal accounts
  - Full audit trail

---

## 🧰 Tech Stack

- **Firebase** (Auth, Realtime Database / Firestore, Storage)
- **State management:** Provider / Riverpod
- **Authentication:** Firebase Auth (email/password) + custom TCKN validation

## 🧪 Usage Flow

1. **Student** registers with TCKN + email/password (TCKN is validated for uniqueness)
2. **Teacher** registers similarly; account must be approved by the principal
3. **Principal** logs in and can:
   - Approve teachers
   - Create counselor / vice principal accounts
   - Browse all chats & complaints
   - Monitor appointments
4. **Chat**: Student searches for a teacher by name → opens a chat → teacher replies → both sides see only the name, no number
5. **Complaint**: Student fills a form → reaches designated recipients; log visible to principal
6. **Appointment**: Teacher creates available slots → student picks one → teacher accepts/rejects → both receive notification

---

## 🔐 TCKN & Anti-troll

- TCKN is validated against a basic algorithm (checksum) and checked for duplicates.
- This drastically reduces fake accounts because each real student/teacher can only register once.
- Further verification (school email, admin approval) can be enabled per school policy.

---


---

## 🛡️ License

This project is strictly protected:

```
Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International
+ Additional restrictions (no AI training, no commercial use)
```

See [LICENSE](./LICENSE) for full details.

- ❌ Commercial use **forbidden**
- ❌ Modification & redistribution **forbidden**
- ❌ AI/ML training **forbidden**
- ❌ Inclusion in any product or service **forbidden**

---

## 👤 Copyright

Copyright (c) 2026 **Berkay Şahin**  
Company: **Valerois**

---

**⭐ Star this repo if you find it useful!**
