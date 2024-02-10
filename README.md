# AES256-ENCODE-AND-DECODE

EN: 


TR:Bu Python uygulaması, dosya şifreleme ve çözme işlemlerini gerçekleştirmek için geliştirilmiş bir arayüz sunar. Tkinter kütüphanesi kullanılarak oluşturulan grafiksel kullanıcı arayüzü (GUI) sayesinde, kullanıcılar dosya seçme, şifreleme modu seçme, anahtar ve başlatma vektörü oluşturma gibi işlemleri basit bir şekilde gerçekleştirebilirler.

Uygulamanın ana özellikleri şunlardır:

Gelişmiş Arayüz: Tkinter kütüphanesi kullanılarak oluşturulan arayüz, kullanıcıların işlemleri kolayca gerçekleştirebilmelerini sağlar. Arayüz, dosya seçme düğmesi, şifreleme modu seçici, anahtar ve başlatma vektörü oluşturma düğmesi gibi bileşenlerden oluşur.

Güçlü Şifreleme: Dosya şifreleme ve çözme işlemleri, AES (Advanced Encryption Standard) algoritması kullanılarak gerçekleştirilir. AES, endüstri standardı olarak kabul edilen güçlü bir şifreleme algoritmasıdır ve hassas verilerin güvenliğini sağlar.

Esnek Şifreleme Modları: Uygulama, ECB (Electronic Codebook), CBC (Cipher Block Chaining), CTR (Counter) ve CFB (Cipher Feedback) gibi farklı şifreleme modlarını destekler. Her mod farklı güvenlik seviyeleri ve kullanım senaryoları sunar, böylece kullanıcılar ihtiyaçlarına göre uygun modu seçebilirler.

Çoklu İş Parçacığı Desteği: Şifreleme ve çözme işlemleri, çoklu iş parçacığı (thread) kullanılarak gerçekleştirilir. Bu sayede, uzun süren işlemler arka planda gerçekleştirilir ve kullanıcı arayüzü donmaz, böylece kullanıcılar diğer işlemleri yapabilirler.

Çoklu Dil Desteği: Kullanıcı arayüzü, İngilizce, Türkçe ve Rusça gibi farklı dillerde sunulabilir. Kullanıcılar tercih ettikleri dili seçerek uygulamayı daha iyi anlayabilir ve kullanabilirler.

Bu uygulamanın kullanılabilmesi için Python diline ve temel kriptografi kavramlarına aşina olmanız gerekmektedir. Ayrıca, tkinter, Crypto (pycryptodome) ve threading gibi ilgili kütüphanelerin yüklü olması gerekmektedir. Bu uygulama, hassas verilerin güvenli bir şekilde şifrelenmesi ve saklanması gereken durumlarda kullanıcılar için ideal bir çözümdür.
