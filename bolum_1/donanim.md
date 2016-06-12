# Donanım

Bilgisayar donanımı çok sayıda elektronik parçanın birlikte çalışmasından oluşmaktadır. Gelin bu parçaların en önemli olanlarını birlikte tanıyalım.

## Kasa

## Anakart ([Motherboard](https://en.wikipedia.org/wiki/Motherboard))

![Anakart (Moxfyre, en.wikipedia, CC BY-SA 3.0)](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Acer_E360_Socket_939_motherboard_by_Foxconn.svg/440px-Acer_E360_Socket_939_motherboard_by_Foxconn.svg.png)

Anakart, bütün parçaların üzerine takıldığı, sistemdeki elektrik iletimi ve haberleşmeyi sağlayan iskelet ya da sinir sistemi olarak da görebileceğimiz bir parçadır. Anakart genellikle kasanın büyük bir bölümüne yayılmaktadır. Üzerinde, parçaların takılabileceği soket adı verilen bölmeler bulunmaktadır. Toplama bilgisayar alınması durumunda anakartın desteklediği teknolojilere ve soket türlerine uygun parçalar takılmasına dikkat edilmelidir.

## Sabit Disk

Sabit disk, bilgisayarın uzun vadeli hafızasıdır diyebiliriz. Bir insanın çocukluğunda yaşadıklarını her an aklına getirmemesine rağmen gerektiğinde yıllar sonra hatırlayabiliyor olması gibi sabit disk de verilerin uzun vadeli hafıza görevi görmektedir. Programların kurulduğu, dosyaların saklandığı yer sabit disktir. Farklı sabit disk teknolojileri mevcuttur:

### HDD ([Hard Disk Drive](https://en.wikipedia.org/wiki/Hard_disk_drive))

![Hard Disk Drive (by Evan-Amos, CC BY-SA 3.0)](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Laptop-hard-drive-exposed.jpg/220px-Laptop-hard-drive-exposed.jpg)

Plak benzeri manyetik bir diskin (platter) üzerinde okuyucu bir kafanın (head) diskin üzerindeki bitleri okuması prensibine dayanan disk türüdür. Diskin üzerinde içten dışarıya doğru iç içe halkalar bulunmaktadır. Bu halkalara silindir ([track/cylinder](https://en.wikipedia.org/wiki/Cylinder-head-sector)) denilmektedir. Her bir halkanın üzerine sırayla 10010101001... şeklinde bitler manyetik olarak kodlanır ve tekrar okunur. Diskin iç kısımlarındaki verileri okumak için okuyucu kafanın iç silindirlere doğru uzanması, halkanın bir noktasındaki veriyi okumak içinse diskin dönerek istenen noktanın kafanın altına gelmesinin beklenmesi gerekmektedir. 

![Silindir ve Sektör](https://upload.wikimedia.org/wikipedia/commons/0/02/Cylinder_Head_Sector.svg)

Alakalı ardışık verilerin bir silindir veya komşu silindirler üzerine ardışık olarak yazılması durumunda performanslı bir yazma ve okuma imkanı sağlar. Ama okunmak istenen veriler diskin rastgele noktalarında olduğunda kafanın kalkıp yer değiştirmesi gerektiğinden performans düşük olabilmektedir. Manyetik yapıları gereği silinen verileri kurtarmak bu tür disklerde daha kolay olmakla birlikte harici manyetik etkilere karşı daha hassastır. Çarpma ve sarsıntı gibi durumlardan etkilenebilirler.

Diskin dönme hızı ne kadar fazlaysa o kadar hızlı okuma ve yazma gerçekleşir. Bu hızın birimi dakikadaki tur sayısı - round per minute (rpm) ile tanımlanır. Günümüzde 5400, 7200 ve 10000 rpm hızlı 500 GB, 1 TB, 2 TB kapasiteli HDD'ler yaygındır. HDD'ler, günümüzde genellikle [SATA](https://en.wikipedia.org/wiki/Serial_ATA) arayüzü üzerinden anakarta bağlanmaktadır. 

### SSD (Solid-state Drive)

![SSD (by D-Kuru from Wikimedia Commons)](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Vertex_2_Solid_State_Drive_by_OCZ-top_oblique_PNr%C2%B00307.jpg/220px-Vertex_2_Solid_State_Drive_by_OCZ-top_oblique_PNr%C2%B00307.jpg)

Verilerin ardışık yazılmadığı, rastgele erişimin (random access) önemli olduğu noktalarda öne çıkan bir teknoloji ise Katı Hal Sürücüdür (SSD). HDD'leri pikapa benzetirken SSD'leri bal peteğine benzetebiliriz. SSD'lerde diskin herhangi bir noktasındaki veriyi okumak aynı zamanı almaktadır. Manyetik HDD'lerde yazma hızı ortalama 150 MB/s iken SSD'lerde bu 560 MB/s'dir. HDD'lere kıyasla düşük enerji ile çalışır, daha az ısınır, sessiz çalışır ve (adında disk yer almasına rağmen) hareketli mekanik aksam olmadığı için sarsıntılara karşı dayanıklıdır.

Dezavantaj olarak HDD'lere kıyasla daha küçük boyutlarda diskler üretilmektedir ve ortalama 4 kat daha pahalıya satılmaktadır.

### Flash

## Bellek (RAM)

![Bellek - Random Access Memory](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Memory_module_DDRAM_20-03-2006.jpg/440px-Memory_module_DDRAM_20-03-2006.jpg)


RAM (Random Access Memory) ise bir bilgisayarın açık olduğu esnada hafızasında tutması gerektiği bilgileri kaydedebileceği, sabit diskten çok daha hızlı ama düşük kapasiteli  hafıza kaynağıdır. Diskler 1024 GB olabilirken masaüstü bilgisayarların RAM'leri 4-8-16 GB civarındadır. Bilgisayar açıldığında işletim sisteminin gerekli dosyaları RAM'e yüklenir. Ardından açtığınız programlar kısa vadeli hafıza ihtiyacını RAM üzerinden sağlarlar. RAM büyüklüğü aslında aynı anda ne kadar çok program/tarayıcı sekmesi açabileceğinizin bir göstergesidir. Programlar, hafızayla işleri bittiğinde RAM'den bilgilerini silmelidirler.

RAM'ler ile SSD'ler benzer teknolojiye sahiptir. Bal peteği gibi düşündüğümüzde istenilen herhangi bir hücreye anında ulaşmak mümkündür.

## İşlemci (CPU)

![İşlemci: Intel CPU Core i7 2600K Sandy Bridge (Eric Gaba at en.wikipedia)](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/Intel_CPU_Core_i7_2600K_Sandy_Bridge_bottom.jpg/440px-Intel_CPU_Core_i7_2600K_Sandy_Bridge_bottom.jpg)

Bilgisayarın verileri işleyen, karar veren, programları adım adım çalıştıran parçasıdır. Gerekli verileri sabit diskten RAM'e aktarır ve RAM üzerindeki bilgiler üzerinde işlem yapar. Sonuçların tekrar diske yazılmasını sağlayabilir. 

Bir işlemcinin ne kadar hızlı bilgi işleyebileceği clock rate'i ile tanımlanır. Günümüz işlemcileri 2.0 GHz ile 3.8 GHz arasında hızlara sahiptir. İşlemcinin hızı arttıkça enerji tüketimi ve yaydığı ısı artmaktadır. Bu sebeple son yıllarda 3.8 GHz işlemci kullanmak yerine 2 tane 2.0 GHz hızlı işlemci çekirdeği (çift çekirdekli işlemci) kullanmak tercih sebebi olabilmektedir. Günümüzde 8 çekirdekli işlemciler yaygın hale gelmiştir.

Günümüzde en yayın işlemci üreticileri Intel ve AMD'dir. Yıllar önce 32 bit işlemciler yaygınken günümüzde 64 bit işlemciler standart hale gelmiştir. İşlemcinin 64 bit mimaride olması, işlemcinin işlem yaparken aynı anda 64 bellek gözüne birden bakabilmesine, yani daha büyük sayılarla hesap yapabilmesine imkan tanır. 32 bit işlemcide en fazla 2<sup>32</sup> sayısı önbellekte saklanabilirken 64 bit işlemcide en fazla 2<sup>64</sup> sayısı saklanabilir.

### Önbellek (Cache)

Sabit Diski evimizdeki kütüphane, RAM'i masaüstümüz olarak düşünürsek bir kitabı üzerinde çalışmak amacıyla kütüphanemizden alıp masaüstümüze koyup işlemci olan beynimiz tarafından işleme konulmasını sağlayabiliriz. Beynimizin aynı anda 5±2 öğeyi kısa süreli hafızasında tutabileceğini düşündüğümüzde işlemci de kısa süreli hafıza olarak Önbellek (Cache) denen 1-6 MB'lık hafıza bölmesini kullanır. Kitaptan okuduğumuz cümleler önbelleğe aktarılıp beynimiz tarafından işlenir diyebiliriz. 


## Grafik İşlemci (GPU)

![Grafik İşlemci - GPU (Berkut at en.wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/6600GT_GPU.jpg/440px-6600GT_GPU.jpg)

İlk zamanlar Ekran Kartı ismi verilen bu parça, zamanla matematiksel işlem yapma noktasında CPU'lardan daha yüksek hızlarda çalışabilen bir parça haline geldi. En yeni GPU'ların clock rate'i 2000 Mhz seviyelerine ulaşabilmektedir. Bununla birlikte bu hızla CPU'dan 10 kat fazla iş yapabilmektedirler.

GPU'ların ek olarak dahili bellekleri bulunmaktadır. Günümüzde 4 GB'a ulaşan bellek boyutlarına sahip olabilmektedirler. Bununla birlikte çoğu dizüstü bilgisayarda GPU, anakarta monte edilmiş haldedir ve RAM'in belleğini kullanır.

Masaüstü bilgisayarlarda kullanılabilecek yüksek hızlı ve yüksek bellekli bir GPU ile yapay zeka algoritmaları ve 3 boyutlu modelleme işlemleri hızlıca gerçekleştirilebilir.
