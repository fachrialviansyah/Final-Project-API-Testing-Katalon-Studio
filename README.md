# Final Project API Automation Testing at AffterOffice
#### Source API Server: https://goofy-saguaro-aa5.notion.site/Katalon-Mock-API-28df0a2b8f4d80599e92e4173a6f2b9e

### 📌 Step Kriteria Penilaian
1. Test Object
- Test object harus mewakili 4 endpoint yang ada berdasarkan API documentation
- Setiap test object harus memiliki verifikasi schema
- Setiap test object harus memiliki validasi status code
- Point tambahan jika bisa menggunakan profile / environtment variable
2. Test Cases
- Minimal terdapat 4 test cases untuk mewakili setiap endpoint yang ada dalam API Documentation
- Point tambahan jika ada lebih dari 4 test cases
- Point tambahan jika ada test cases chain request atau user CRUD
3. Test Suite
- Minimal terdapat 1 test suite
4. Test Suite Collection
- Minimal terdapat 1 test collection
5. Integrasikan Dengan GITHUB Repository
- Tugas di integrasikan/upload ke GITHUB repository
- Pastikan memiliki minimal 2 branch (Master & Development)
- Pastikan minimal memiliki 1 commit
- Pastikan username dan email sesuai dengan nama anda

Mentor: <a href="https://www.linkedin.com/in/ubaidillah-amir-1083505a/">Ubaidillah Amir</a>

---

### 📁 Struktur File Katalon Studio
    ├── Profile
    │   └── default
    ├── Test Cases                                        # Berfungsi untuk menyimpan, mengelola, dan menjalankan skenario pengujian.
    │   ├── 01 Get Users All
    │   ├── 02 Get User By ID
    │   ├── 03 Post User
    │   ├── 04 Post Username Duplicate
    │   ├── 05 Patch User
    │   ├── 06 Delete User
    │   └── 07 Verify CRUD User
    ├── Object Repository                                 # Untuk menyimpan dan mengelola elemen UI (button, textbox, link, dll) yang digunakan dalam test case
    │   └── Mock API
    │   │   ├── 01 GET Users ALL
    │   │   ├── 02 GET User By ID
    │   │   ├── 03 POST User
    │   │   ├── 04 POST Username Duplicate
    │   │   ├── 05 PATCH User
    │   │   └── 06 DELETE User
    ├── Test Suites                                      # Untuk mengelompokkan dan menjalankan beberapa test case sekaligus
    │   └── Mock API
    │   │   ├── 01 Test Users All
    │   │   ├── 02 Test Users Endpoints
    │   │   ├── 03 Test Users CRUD
    │   │   └── 04 Test users Collections                # Untuk menjalankan beberapa Test Suite secara bersamaan
    ├── Data Files
    ├── Checkpoints
    ├── Keywords
    ├── Test Listeners
    ├── Report                                           # Untuk menyimpan hasil pengujian Test Suite atau Test Suite Collection
    │   └── 20251024_161438
    │   │   └── Mock API
    │   │   │   ├── 01 Test Users All
    │   │   │   ├── 02 Test Users Endpoints
    │   │   │   ├── 03 Test Users CRUD
    │   │   │   └── 04 Test Users Collection
    ├── Include
    ├── Images                                            # Optional
    │   ├── TestCollection.png
    │   ├── TestUserEndpoints.png
    │   ├── TestUsersAll.png
    │   └── TestUsersCRUD.png
    ├── Plugins
    ├── Resource                                          # Optional
    │   ├── DeleteUser.txt
    │   ├── GetUserAll.txt
    │   ├── GetUserByID.txt
    │   ├── PatchUser.txt
    │   ├── PostUser.txt
    │   └── TestUsersCRUD.png
    └── README.md

---

### :zap: Hasil Report Test Users All
<img width="1338" height="754" alt="image" src="https://github.com/user-attachments/assets/a6167194-0adf-44f8-b99b-3d3c3df80af6" />

### :zap: Hasil Report Test User Endpoints
<img width="1356" height="711" alt="image" src="https://github.com/user-attachments/assets/45db2292-fbd5-483a-bbd7-dbd2558de1af" />

### :zap: Hasil Report Test Users CRUD (Create, Read, Update, Delete)
<img width="1353" height="548" alt="image" src="https://github.com/user-attachments/assets/1ee7161c-713f-4af0-8c5a-dd970510d6cd" />

### :zap: Hasil Report Test Collection
<img width="1317" height="632" alt="image" src="https://github.com/user-attachments/assets/84b4e21c-f462-44dd-bad0-0445ee407147" />





