**Alur Kerja Pembuatan Aplikasi by Programming Zaman Now**

#Tahapan 1 Business Requirement Document > Yang buat orang operasional, business atau product
-	Aplikasi apa yg mau kita buat?
-	Fiturnya apa aja? 
-	Berapa lama timeline pembuatannya? Bulan 1 apa, bulan 2 apa? MVP nya apa?
-	Alurnya bagaimana? Business Flownya bagaimana? Harus detail!
-	Di awal diperjelas BRD nya dengan tim riset, produk dan bisnis

#Tahapan 2 UI/UX 
-	Tim UI/UX membuat
-	Semua hasilnya diberikan ke tim teknologi
-	Diskusi sama orang Front Engineer dan Quality Assurance

#Tahapan 3 Technical Design
-	Dari Alurnya dan UI/UX nya kita butuh berapa aplikasi
-	Buat Deployment Diagram > Aplikasi, Database, Koneksinya dengan apa? API, message broker
-	Buat ERD (Tabelnya seperti apa)

#Tahapan 4 Architectur Review/Technical Architect > Memastikan bahwa technical design yg dibuat atau nanti aplikasi yg kita develop itu baik secara architectur review
-	Technical Designnya akan di review
-	Infrastruktur Architect (Spec Server butuh berapa)
-	Security Architect (MD5 atau Berrupt)
-	Development/Back End Architect  (Tidak semua erd nya harus normal)
-	Front End Architect

#Tahapan 5 API Specification > Kesepakatan untuk membuat API seperti apa
-	Buat Product > GET/API/products/id
-	Buat Banners > GET/API/banners
-	Harus bareng” menyepakati antara Front End sama Back End. 
-	Bagaimana cara buat API Spec > Diliat aja dari UI/UX
-	Tahapan yang perlu diperhatikan !!! Tidak boleh diganti setelah disepakati

#Tahapan 6 Development (BackEnd, FrontEnd, QualityAssurance)
-	BE akan bikin API nya
-	FE akan bikin tampilan sesuai API nya
-	QA buat QA otomation based on API 
-	Kelebihan klo udh dibuat API SPEC nya, antara BE, FE dan QA jalan bareng

#Tahapan 7 Non Production Deployment > tergantung perusahaannya
-	Developmen, QA, Staging, Sandbox
-	Buat CI/CD
-	Apakah yg kita lakukan selama ini sudah beneran kita kerjakan sesuai dgn janji API Spec atau tidak

#Tahapan 8 Testing > Environment yg bukan production
-	End to end test 
-	Performance Test
-	Security Test

#Tahapan 9 Production Deployment
-	Strategi Deployment > AB Test
-	Ketika melakukan deployment baru, harus dilakuin QA Otomation

#Tahapan 10 Maintenance/Improvement
-	Improvement > tinggal balik lagi ke awal
-	Maintenance > Buat monitoring cth berapa jumlah datanya ? total traffic? Respon time?

- SELESAI -
