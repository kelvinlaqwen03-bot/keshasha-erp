# KESHASHA ERP — Phase 0 (Netlify + Firebase)

Multi-company foundation. Deploy kama ANDO Worksheet.

## Setup (mara ya kwanza)

### 1. Firebase
1. https://console.firebase.google.com → Create project `keshasha-erp`
2. Add Web app
3. Copy `firebaseConfig`
4. Firestore → Create database → **Test mode** → Publish rules:

```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write: if true;
    }
  }
}
```

### 2. Paste config
Fungua `index.html`, tafuta:

```js
const firebaseConfig = {
  apiKey: "PASTE_YOUR_API_KEY",
  ...
};
```

Badilisha na config yako.

### 3. Netlify
1. Drag folder hii (au zip extract) → Netlify Deploy manually  
2. Open site URL  
3. **First setup** → weka email + password → Super Admin  
4. Login → Create companies, branches, employees, users

## Features Phase 0
- Super Admin + multi-company
- Branches
- Employees (search by name)
- Users + passwords
- Projects / Dimensions
- Document numbering series
- Dense tabular UI (SAP/Excel style)

## Baadaye
Tunapohitaji SQL Query Manager → **Supabase / PostgreSQL**.

## Collections Firestore
- companies, branches, employees, users, dimensions, doc_series
