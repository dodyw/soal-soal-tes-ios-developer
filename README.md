# Soal-soal tes untuk posisi iOS Developer
> Semoga bermanfaat, insyaAllah soal-soal berikut sudah mengcover hal-hal yg sering digunakan dalam development aplikasi iOS.

##Soal

1. Urutkan urutan method berikut berdasarkan app life cycle dari sebuah aplikasi iOS
  * viewWillAppear
  * viewDidLoad
  * didFinishLaunchingWithOptions 
  * viewDidUnload
  * viewWillDisappear
2. Apa perbedaan NSUrlConnection synchronous dg asynchronous. Yg mana yg biasa digunakan bersama dg progress hud?
3. Apa yg anda ketahui dari cocoapod? Jelaskan bagaimana menggunakannya.
4. Jelaskan mekanisme persistent storage dengan NSUserDefaults dan CoreData.
5. Jelaskan cara mendistribusikan aplikasi iOS dg Apple Store Distribution, AdHoc Distribution, dan In-House Distribution.
6. Ceritakan salah satu aplikasi iOS yg pernah anda selesaikan.

##Jawaban

1. Urutan sesuai dg app life cycle:
  1. didFinishLaunchingWithOptions
  2. viewDidLoad
  3. viewWillAppear
  4. viewWillDisappear
  5. viewDidUnload

2. NSUrlConnection synchronous akan berjalan di main-thread, sehingga mengakibatkan GUI tidak responsif. Sedangkan asynchronous akan membuat proses baru di thread baru sehingga tidak mengganggu main-thread dan GUI akan tetap responsif. Yg biasa digunakan bersama progress hud adalah synchronous.

3. Cocoapod adalah dependency manager yg digunakan oleh Objective-C. Cara menggunakannya adalah dengan membuat file `Podfile` yg berisi library yg akan digunakan. Selanjutnya masuk ke command-prompt untuk menjalankan `pod install`. Selanjutnya akan berbentuk file `workspace`. Untuk selanjutnya kita menggunakan selalu file workspace ini setiap kali membuka project.

4. NSUserDefaults akan menyimpan data secara permanent ke dalam aplikasi. NSUserDefaults bekerja secara key-value dan tidak membutuhkan database. Data dalam NSUserDefaults akan tersedia selama aplikasi tidak dihapus. Sedangkan CoreData adalah sebuah mekanisme yg digunakan untuk menyimpan data ke dalam database sqlite.

5. Apple Store Distribution: aplikasi didistribusikan ke Apple App Store. AdHoc Distribution: Aplikasi didistribusikan secara terbatas untuk beberapa device yg telah didaftarkan sebelumnya. In-House Distribution: Aplikasi didistribusikan secara bebas untuk semua device tanpa perlu diregistrasi sebelumnya, namun hanya boleh digunakan untuk internal perusahaan saja.

6. Jawaban bebas :)

