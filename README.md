Şöyle ki uygulamanızda güvenliği sağlamanın farklı yolları var eğer genel olarak güvenlik sağlamak istiyorsanız saldırganların araçlarından korunmak istiyorsanız
kullanılan bir yöntem var bu yönteme "obfuscation" deniyor ve flutter bu yöntemi bizim yerimize otomatik olarak uyguluyor ama bunu uygulamamızı build ederken belirtmemiz gerek örnek olarak: 
obfuscation olmadan derleme: flutter build apk -release dosya_adı
obfuscation ile derleme: flutter build apk -- obfuscation -- split-debug-info=./proje_adı/debug detayına internetten bakabilirsiniz ben burada apk için örnek verdim
ve bilmemiz gereken önemli diğer güvenlik durumu da ssl sabitleme detaylarını sonradan yazıyı güncellediğimde ekleyebilirim
Diğer Yöntemler:
Eğer bir login sayfası yapıyorsanız hacker a bazı bilgileri vermemeniz gerekir ne gibi bilgiler?
Login sayfasına bağlı bilgiler mesela kişi telefon numarası şifresi ile kayıt oluyorsa ve siz doğrulama yaparsanız örnek olarak
telefon numarası var ama şifresi yanlış gibi bilgileri sunarsanız hacker bunu sorgulayabilir birinin telefon numarasının olup olmamasını arayabilir ve buradan yola çıkıp şifresini bile bulabilir eğer ki bilgili bir hacker ise şifreyi bulması çok zor olmaz
Uygulamanızda güvenlik olarak vpn varmı yani sahte konum ondan sonra sayfayı bölmüş mü cihaz root mu gibi kontroller yapabilirsiniz bunun için pub.dev de paketler var paketleri de yazıyı güncellersem eklerim kalın sağlıcakla :)...
