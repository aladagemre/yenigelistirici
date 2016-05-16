# Crystal

Crystal programlama dili, Ruby'nin statik tipli derlenen hali diyebiliriz. Hemen hemen aynı sözdizimini ve API'yi kullanmakla birlikte Ruby'den çok daha performanslı sonuç vermektedir. Manastech firması tarafından aktif şekilde geliştirilmekte olup kararlı 1.0 sürümünün 2017 yılında çıkması beklenmektedir. 

## Kullanan Şirketler

Manastech, Protel, Bulutfon, rainforestqa, lab2023

## Önde olduğu noktalar

* Derlenebilir  ve statik tipli bir dil olmasına rağmen tip belirtmek şart değil. Yapabildiği ölçüde kendisi tahmin ediyor.
* Performansı çok yüksek. Hem hızlı, hem az kaynak tüketiyor. Günde [10 milyon talep karşılayıp sadece 185MB RAM ve %30 CPU tüketen uygulama](https://groups.google.com/forum/#!msg/crystal-lang/fXTAMilSo_Q/lMxM46mACgAJ) buna en güzel örnek. Bununla birlikte Node.JS'in %38.5 CPU ve 900MB ile karşıladığı [10.000 WebSocket bağlantısını %1.85 CPU ve 11MB RAM ile karşılayan Kemal](https://gist.github.com/sdogruyol/bdd400a6eac13e26228e) buna gösterilebilecek örneklerden.
* Açık seçik sözdizimi, okuması ve yazması kolay.
* Öğrenmesi kolay.
* C kodlarını kullanmak mümkün
* LLVM ile optimizasyon yapılabiliyor.

## Geride kaldığı noktalar

* Henüz kararlı değil, çeşitli hatalarla karşılaşılabiliyor.
* Dilin kuralları çok hızlı değişiyor, sürümler arasında uyumsuzluk olabiliyor.
* Her konuda paket mevcut değil.

## Öğrenme Kaynakları

Dili öğrenmeye [Tutorial](http://crystal-lang.org/docs/) sayfasından başlayabilirsiniz. Henüz tüm özellikleri yansıtmıyor ama başlangıç açısından iyi. Takıldığınız, eksik gördüğünüz noktalar olursa [API Belgelendirmesi](http://crystal-lang.org/api/) çok işinize yarayacaktır. Aşkın Gedik'in geliştirdiği [Örneklerle Crystal](https://github.com/askn/crystal-by-example) sayfası da somut örnek görme açısından güzel. Harici modüllerin kod içi belgelendirmelerine [DocCrystal](http://docrystal.org) adresinden ulaşılabiliyor.

## Takip Edilesi Kaynaklar

* Crystal Weekly: haftalık olarak Crystal'le ilgili haberleri ve yeni Crystal paketlerini e-posta ile iletir.

## Yardım Kaynakları
* [Crystal-TR slack kanalı](https://crystal-tr.slack.com/)
* Crystal-lang IRC kanalı: irc.freenode.org - #crystal-lang
* [Github Sayfası](https://github.com/crystal-lang/crystal)