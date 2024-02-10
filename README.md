# AES256-ENCODE-AND-DECODE

TR: Bu kod, güvenli dosya şifreleme ve çözme işlemlerini kolayca gerçekleştirmenizi sağlayan bir Python uygulamasını içerir.  uygulamanın özellikleri:

Gelişmiş Arayüz: Tkinter kütüphanesi kullanılarak oluşturulan bir GUI ile kullanıcı dostu bir deneyim sunar. Kullanıcılar dosya seçme, şifreleme modu seçme, anahtar ve IV (Başlatma Vektörü) üretme gibi işlevleri basit bir arayüz üzerinden kolayca gerçekleştirebilirler.

Güçlü Şifreleme: Dosya şifreleme ve çözme işlemleri AES (Advanced Encryption Standard) algoritması kullanılarak gerçekleştirilir. Bu, yüksek güvenlik seviyesi sağlar ve hassas verilerin korunmasını sağlar.

Esnek Şifreleme Modları: ECB, CBC, CTR ve CFB gibi çeşitli şifreleme modları arasından seçim yapabilirsiniz. Her bir mod farklı güvenlik seviyeleri ve kullanım senaryoları sunar, böylece ihtiyacınıza uygun olanı seçebilirsiniz.

Çoklu İş Parçacığı Desteği: Şifreleme ve çözme işlemleri çoklu iş parçacığı (thread) kullanılarak gerçekleştirilir. Bu, arayüzün donmasını önler ve kullanıcıların işlem sırasında etkileşimde bulunmasını sağlar.

Çoklu Dil Desteği: Kullanıcı arayüzü, İngilizce, Türkçe ve Rusça gibi farklı dillerde sunulabilir. Bu sayede, kullanıcılar tercih ettikleri dili seçerek uygulamayı daha iyi anlayabilirler.

Bu uygulamanın kullanılabilmesi için Python diline ve kriptografi temellerine aşina olmanız yeterlidir. Ayrıca, tkinter, Crypto (pycryptodome) ve threading gibi kütüphanelerin yüklü olması gerekmektedir. Bu uygulama, hassas verilerin güvenli bir şekilde şifrelenmesi ve saklanması gereken durumlarda kullanıcılar için ideal bir çözümdür.
