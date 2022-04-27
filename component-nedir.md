# Component Nedir?

React, component mimarisiyle çalışır. Peki nedir bu component. Aslında katman gibi düşünebilirsiniz. Sitenizin component hiyerarşinizi siz tasarlıyorsunuz. Ancak genel kullanım olarak bir inceleyelim.

İlk olarak sizlere özet olarak anlatımını yapacağım. Merak etmeyin çok kolay bir şekilde anlayacaksınız 😊

Kısaca özetlersek olursam, web sitenizde farklı sayfalarda kullanmak istediğiniz bir bileşeni, component mimarisine sokmalısınız. Anlamadım dediğinizi duyar gibiyim. Peki o halde örnekle size anlatayım.

Şimdi facebook’a girelim. Hesabımıza giriş yaptık. Bizi ilk olarak bir anasayfa karşılıyor. En üst kısımda menü var. Menüyü facebook her sayfada kullanıyor. Bu yüzden menü.js diye bir component açıyoruz. Bu js dosyasına menü kodlarımızı yazıyoruz. Ve artık componentimiz hazır. Bunu istediğimiz her sayfada istediğimiz her yerde kullanabiliriz. 😊

React’ın ana componenti app.js dir. Kurulumu yapanlar görecektir. Menüyü app.js ye component olarak koyduğumuz zaman app.js her zaman çalıştığı için menü de her sayfada olacaktır.

Peki ben hem menüye hem de footer’a bir arama çubuğu koymak istiyorum diyelim. Peki bunu nereye koyacağız? Şöyle ki aramacubugu.js diye bir dosya açıp kodlarımızı yazıyoruz. Daha sonra nereye koymak isterseniz oraya koyabilirsiniz.

Ana componentimiz app.js. İçine menü.js koyduk. Artık menü her sayfada görünecek. Arama çubuğunu ise menü componentinin içine koymamız gerek. Daha sonra baktınız kötü oldu. Tek satırı silerek çubuğu kaldırabiliyorsunuz. İşte React’ın kolaylığı da burada 😊

Bu anlattıklarımı component hiyerarşisini gösteren bir görselle pekiştirmek istiyorum.

![](https://miro.medium.com/max/700/0\*zDtCYbJRYFdB0E\_l.png)

Resimde gördüğünüz gibi, en üstte ana component APP var. Daha sonra Menümüz geliyor ve altında arama çubuğu var. Bu şekilde sınıflandırabiliyoruz. Peki şimdi aklınıza şu soru gelmiş olabilir. E abi biz buttonun içinde arama çubuğu kullanmak istesek nasıl olacak? İşte burada state management devreye giriyor. State konusunda anlatacağım.

\
