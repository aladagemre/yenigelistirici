# git

## Git Nedir?

[Git](https://git-scm.com/) büyük ve küçük projeler için uygun bir dağıtık
sürüm takip sistemidir. Peki sürüm takibi ne demektir.

Sürüm takibi uygulamanızı geliştirirken dosyalarınızın değişikliklerini ve
değişikliklerin kimler tarafından yapıldığını takip edebilmek için
kullanabileceğiniz bir araçtır. Tabiki sadece bununla sınırlı değildir.
Kullanımın alanlarını daha iyi anlamak için birkaç senaryo üzerinden konuşalım.

Bir projenizde çok sayıda dosyanız ve bu dosyalar üzerinde bir çok geliştirme
yapıyorsunuz. Bu geliştirmeleri takip etmek ve duruma göre bazılarını yayınlayıp
bazılarını sadece test sürümü olarak yayınlamak istiyorsunuz. Bu gibi durumda
projeniz aslında 2 dal olarak ilerliyor. Birisi yayınladığınız kısımlarını
içeriyor diğeri ise beta testleri için açtınız kısımları. Bu senaryonun yönetimi
için sürüm yönetim araçlarını kullanabilirsiniz.

Diğer taraftan yapılan geliştirmelerin kimin tarafından ve ne zaman yapıldığını
da yine sürüm yönetim araçları ile kontrol edebilirsiniz. Bir geliştirmeyi
yayınladınız ancak müşterileriniz ya da kullanıcılarınız memnun kalmadı, bu
durumda da sürüm yönetim sistemini kullanarak bu geliştirmeyi geri alabilirsiniz.

Git ise sürüm takip sistemlerinden birisidir. Bunun dışında başka sürüm takip
araçları da mevcuttur:

 * [Mercurial](https://www.mercurial-scm.org/)
 * [CVS - Concurrent Versions System](http://www.nongnu.org/cvs/)
 * [Subversion](https://subversion.apache.org/)
 * [BitKeeper - Scalable Version Control](http://www.bitkeeper.org/)


Basit olarak bu şekilde. Bunun dışında bir çok senaryo için bu araçları
kullanabiliriz. Daha fazla bilgi almak için aşağıdaki bağlantıları
kullanabilirsiniz:

 * [https://git-scm.com/](https://git-scm.com/)
 * [https://tr.wikipedia.org/wiki/Git_(yaz%C4%B1l%C4%B1m)]("https://tr.wikipedia.org/wiki/Git_(yaz%C4%B1l%C4%B1m)")
 * [https://help.github.com/](https://help.github.com/)


## Git Kavramları

Dosyalar repository (repo) denilen depolarda saklanır. **git init** diyerek bulunduğunuz klasörde yerel bir repo oluşturabilirsiniz. Yerel reponuzun **Remote Repo** denilen uzakta ilişkili bir reposu olabilir. Bu genellikle github tarzı sistemlerin size sunduğu repolardır. Dosyalar ekledikçe veya dosyalarda değişiklik yaptıkça **git add dosyaadi** diyerek dosyaları **Stage**'e yani gönderilecekler sahnesine yerleştirebilirsiniz. **git commit** diyerek sahnedeki dosyaları göndermek üzere işaretleyebilir (zarf içine yerleştirebilir), **git push** diyerek de gönderilmek üzere commitlenen, yani zarflanan değişiklikleri **Remote Repo**ya gönderebilirsiniz.

## Git Repoları

Git dağıtık bir sistem olduğu için merkezi bir repository/repo (depo) kavramı gerekmemekle birlikte [Github](https://github.com), [Bitbucket](https://bitbucket.org), [Gitlab](https://about.gitlab.com/) gibi firmaların sunduğu depoları referans merkez repo olarak kullanabilirsiniz. Böylelikle kodlarınızı geliştirdikçe bu firmaların sunucularına son hallerini yollayabilirsiniz. Eğer ileride çok gizli projeler yapacak olup başka bir firmanın sunucularına kod yollamak istemezseniz Gitlab'ın Community Edition sürümünü kendi sunucularınıza kurup çalıştırabilirsiniz.

Açık Kaynak camiasında github oldukça yaygın bir kullanıma sahiptir. Ancak gizli repolar için ücret gerektirmektedir. Bitbucket ve Gitlab ise başkalarından gizlemek istediğiniz projeler için ücretsiz gizli repo desteği vermektedir.

## Nasıl Kullanırım?

Çoğu geliştirici komut satırından git komudunu kullanarak sürüm takibi yapar. Bununla birlikte [SourceTree](https://www.sourcetreeapp.com/) gibi bu işi arayüz üzerinden yapma imkanı sağlayan yazılımlar mevcuttur.

## Nasıl Öğrenirim?

* [Web arayüzünden kullanım için](https://guides.github.com/activities/hello-world/)
* [Komut satırından kullanım için](https://try.github.io/levels/1/challenges/1)
* [Arman Kara, Git ve Github Kullanımı](http://www.dr.com.tr/Kitap/Git-ve-GitHub-Kullanimi/Arman-Kara/Egitim-Basvuru/Bilgisayar/urunno=0000000699363)

