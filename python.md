## Python

Python programlama dili, ilk sürümü 1994 yılında çıkan, şu anda 2.7 ve 3.5 sürümleri olan dinamik tipli, yorumlanan bir programlama dilidir. Yıllardır Python 2.X kullanılmakta olup, dilin yeniden tasarlanmış hali olan Python 3, geriye dönük uyumsuzluklar barındırmaktadır. Yani Python 3 dili ile yazılan bir kod Python 2 yorumlayıcısında, Python 2 ile yazılan bir kod da Python 3 yorumlayıcısında çalışmayabilir. Yeni geliştiricilere Python 3 tavsiye edilmekle birlikte kullanacağınız paketlerin Python 3 tarafından desteklendiğini kontrol etmekte fayda vardır.

### Kullanan Şirketler

Youtube, Dropbox, Google, NASA

### Önde olduğu noktalar

#### Kolay ve Pratik
Öğrenmesi en kolay dillerin başında gelir. İngilizce yazar gibi kod yazabilirsiniz. Pratiktir, esnektir. Gereksiz yere kod yazdırmaz. Çok daha az satır kodla çok kısa zamanda büyük işler yapabilirsiniz. Prototip çıkarmak için birebirdir. Etkileşimli Kabuk (interactive shell) ile hızlıca denemeler yapabilirsiniz.

#### Yaygın

Dünyadaki en yaygın ve kabul gören programlama dillerindendir. Hemen her konuda kullanışlı paketleri mevcuttur. Web geliştirmede ve startuplar tarafından yaygın olarak kullanılmaktadır.

#### Bilim Dili

Numpy, Scipy gibi bilimsel kütüphaneler, C ile yazılıp Python'a entegre edilmiştir. Bu da Python'u bilimsel camiada tercih sebebi kılmaktadır.

### Geride kaldığı noktalar

Eşzamanlı (concurrent) işlemler yapmanız gerektiğinde Global Interpreter Lock (GIL) denilen kilit, aynı anda iki threadin çalışmasına engel olur, bu da performans kayıplarına sebep olur.

Dinamik tipli ve yorumlanan bir dil olması, çok miktarda Encapsulation içermesi derlenen statik dillere göre performans kayıplarına sebep olabilmektedir. Eğer saniyede binlerce talep karşılayacak web sunucusu yazıyorsanız bir noktadan sonra Python ile zorluk çekebilirsiniz. Bu durumlarda [SWIG](http://www.swig.org/tutorial.html) benzeri araçlarla C binding'i yazarak performans artışı sağlayabilirsiniz.


### Öğrenme Kaynakları
* [Python Kursu](https://www.youtube.com/playlist?list=PLoGyh79qJtNLN-bfc1JBbMIf4nVJvLs8O)
* [İstihza](http://www.istihza.com/)
* [A Byte of Python](http://www.swaroopch.com/notes/python/)
* [Python 2 Official Tutorial](https://docs.python.org/2/tutorial/)
* [Python 3 Official Tutorial](https://docs.python.org/3/tutorial/)
* [Python Guide](http://docs.python-guide.org/en/latest/intro/learning/)

### Takip Edilesi Kaynaklar

* [Python Weekly](http://www.pythonweekly.com/): haftalık olarak Python'la ilgili haberleri ve yeni python paketlerini e-posta olarak iletir.

### Yardım Kaynakları

* [Python Istanbul e-posta grubu](https://groups.google.com/forum/#!forum/python-istanbul)

### Topluluklar
* Python Istanbul

### Araçlar

#### Pip

Python programlama dili, birçok kullanışlı paketi içerisinde barındırmaktadır. Bununla birlikte harici (3. taraf) modülleri kurmak için geliştirilen **pip** adında bir aracı vardır. Python 2.7.9 ve 3.4 sürümleriyle hazır olarak gelmektedir. Pip, öntanımlı olarak istediğiniz paketi sistem çapında, tüm kullanıcıların kullanabileceği şekilde kurar:

```bash
$ sudo pip install flask
```
Bu komudun ardından Python kodlarınızda flask kütüphanesini kullanabilirsiniz.
    
```python
#!/usr/bin/python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
```    

#### Virtualenv

Farklı projelerde aynı kütüphanenin farklı sürümlerine ihtiyaç duyabilirsiniz. pip ile sistem çapında (global) paket kurmanız durumunda farklı sürümleri barındırma imkanınız olmaz. Bunu çözmek için ise **virtualenv** adlı araç geliştirilmiştir. Virtualenv ile proje bazlı paket kurulumu yapabilirsiniz.

```bash
$ virtualenv --distribute venv
$ . venv/bin/activate
(venv)$ 
(venv)$ pip install flask
```

Öncelikle bulunduğumuz klasör altında venv adında bir depo klasörü oluşturuyoruz. venv/bin altında python yorumlayıcısı, venv/lib altında ise kuracağınız Python paketleri yer alacaktır. Bu sayede sistem çapında kurulma gerek kalmayacaktır.

**Örnek proje kurulumu**

Elinize ulaşan bir proje içerisinde requirements.txt gibi bir dosya varsa içindeki tüm bağımlılıkları **-r** parametresiyle kurabilirsiniz. Örnek olarak Flask kütüphanesiyle yazılmış basit bir web sunucu projesini indirip, bağımlılıklarını kurup çalıştıralım:

```bash
$ git clone https://github.com/waitingkuo/flask-sample
$ cd flask-sample
$ virtualenv --distribute venv
$ . venv/bin/activate
(venv)$ pip install -r requirements.txt
(venv)$ python app.py
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
```    


### IDEler
#### PyCharm
Piyasadaki en yetenekli IDE diyebiliriz. Açık kaynaklı topluluk sürümü birçok işinizi görecektir. Python 3.5 ile gelen opsiyonel tip tanımını kullanarak [otomatik tamamlama ve statik kontrol](http://blog.jetbrains.com/pycharm/2015/11/python-3-5-type-hinting-in-pycharm-5/) da yapmaktadır.

#### Atom

Hızlıca kod yazıp sonuç almak istediğinizde, otomatik tamamlamaya ihtiyaç duymadığınızda oldukça etkilidir. Kod yorumlamayı konsoldan gerçekleştirebilirsiniz.

#### Eclipse PyDev

Eclipse'in Python eklentisidir. Eclipse'e alışık olanlar buradan devam edebilir.

### Hata Ayıklama

pydb

