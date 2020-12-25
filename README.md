# SDT Code Review reposuna hoşgeldiniz. 

Buradaki ana amacımız ilgililerin, herhangi bir konuda ve dilde yazdığı kodları barındıran pull requestler
açarak konu hakkında tecrubeli reviewerlardan yardım alabilmelerini sağlamak için bir ortam oluşturmaktır.

İkinci amacımız ise insanların daha sonra geri dönebileceği zaman içerisinde büyüyen bir arşiv oluşturmak.

### Nasıl pull request atacağım ?

Burada bunu size adım adım anlatmaya çalışacağız. 

##### Sadece ilk seferinizde yapmanız gerekenler

- Bu yazıyı okuduğunuz yer olan reponun ana saydasında sağ üstte bulunan `fork` adlı butona tıklayın.
Boylece kendi github hesabınıza bu reponun bir kopyasını çıkarmış olacaksınız.
- Bundan sora kendi github hesabınıza gidip fork ettiğiniz reponun ana sayfasına girin.
- Burada sağ üstte yemyeşil bir buton olan `Code` adlı butona tıklayın. Burada kendi sayfanıza kopyalamış olduğunuz reponun urlini bulacaksınız.
- Buradan urli kopyaladıktan sonra command linei açın.
- İlk yapacağımız hareket forkladığınız repoyu bilgisayarınıza clonelamak olacak. Bunun için `git clone <repo-url>` komutunu çalıştırın.
- Bu repo içerisinde remote olarak otomatikman sizin forkladığınız repo ayarlı olacak. Simdi bunun yanına bir repo daha eklemek istiyoruz. Bu repo da projenin ana reposu. Bunun için  komutunu `git remote add upstream <ana-repo-url>` çalıştırın.
- Bunun sonrasında `git remote -v` komutunu çalıştırarak eklediğiniz remoteları görebilirsiniz. 
- Projenin ana dosyasından en son değişiklikleri kendi lokal reponuza çekmek için `git pull upstream main` komutunu kullanın.
- Böylelikle çalışma alanınız için sadece bir sefer yapılacak kurulumu tamamlamış bulunuyorsunuz.

##### Çalışma biçimi ve her pull request için yapılması gerkenler
- İlk ve öncelikli olarak bir branch oluşturmalısınız. Bunun için `git checkout -b review/<ad>_<soyad>` komutunu kullanın.
- Kullandığınız programlama dilinin dosyasının içinde bir dosya yaratın ve bu dosyayı `ad_soyad_tarih` şeklinde isimlendirin. Lütfen calışmanızı sadece bu dosya icinde tutun.
- Sonra ise çalışmaya baslayın ve lokal olarak bol bol commitlerinizi yapın. Daha hiçbir şey 
push etmenize gerek yok.
- İşiniz bitti ise ve review için hazırsanız branchinizi su komutu kullanarak `git push origin review/<ad>_<soyad>` forkladığınız repoya push edin.
- Simdi ise bu reponun web sayfasına giderek Compare & pull request butonuna tıklayın.
- Burada sizin için hazırladığımız şablonu doldurduktan sonra Create pull request adlı butona tıklayın.

Tebrikler!

