# Final Project API Automation Testing at AffterOffice
### Source API Server: https://goofy-saguaro-aa5.notion.site/Katalon-Mock-API-28df0a2b8f4d80599e92e4173a6f2b9e

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

---

### 📁 Struktur File Katalon Studio
    │── src 
    │   └── test
    │       ├── java
    │       │   ├── helper                                               # File Pendukung Lainnya
    │       │   │   ├── JSONSchemadata
    │       │   │   │   └── profile_user.json                        
    │       │   │   ├── Endpoint.java
    │       │   │   ├── Models.java
    │       │   │   └── Utility.java
    │       │   ├── pages                                                # Page Object Models (POM)
    │       │   │   ├── api
    │       │   │   │   └── ApiPage.java                        
    │       │   │   └── web
    │       │   │   │   ├── AboutUs.java                        
    │       │   │   │   ├── Cart.java                        
    │       │   │   │   ├── Contact.java                                          
    │       │   ├── stepdef                                               # Step Definitions API & WEB
    │       │   │   ├── api
    │       │   │   │   └── ApiStep.java                        
    │       │   │   ├── web
    │       │   │   │   └── WebStep.java                        
    │       │   │   └── Hooks.java
    │       │   ├── steprun                                               # Step Running API & WEB Test
    │       │   │   ├── APITestRun
    │       │   │   │   └── ApiTest.java                        
    │       │   │   └── WebTestRun
    │       │   │   │   └── WebTest.java                        
    │       └── resources
    │           └── api.feature                                         # Feature Files API (Behavior-Driven Development - BDD)
    │           └── web.feature                                         # Feature Files WEB (Behavior-Driven Development - BDD)
    ├── .gitignore                                                      # File untuk mengecualikan file tertentu dari git
    ├── build.gradle                                                    # File konfigurasi Gradle
    ├── gradlew                                                         # Wrapper untuk Gradle (Linux/Mac)
    ├── gradlew.bat                                                     # Wrapper untuk Gradle (Windows)
    ├── config.properties                                               # File konfigurasi proyek
    └── README.md                                                       # Dokumentasi proyek


### :zap: Hasil Report Test Users All
<img width="1338" height="754" alt="image" src="https://github.com/user-attachments/assets/a6167194-0adf-44f8-b99b-3d3c3df80af6" />

### :zap: Hasil Report Test User Endpoints
<img width="1356" height="711" alt="image" src="https://github.com/user-attachments/assets/45db2292-fbd5-483a-bbd7-dbd2558de1af" />

### :zap: Hasil Report Test Users CRUD (Create, Read, Update, Delete)
<img width="1353" height="548" alt="image" src="https://github.com/user-attachments/assets/1ee7161c-713f-4af0-8c5a-dd970510d6cd" />

### :zap: Hasil Report Test Collection
<img width="1317" height="632" alt="image" src="https://github.com/user-attachments/assets/84b4e21c-f462-44dd-bad0-0445ee407147" />





