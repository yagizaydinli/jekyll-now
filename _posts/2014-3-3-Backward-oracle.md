---
layout: post
title: Backward Oracle Dizgi eşleme algoritması
---

Bu yazıda Backward Oracle dizgi eşleme algoritmasını anlatmaya çalıştım. Anlattığım örnek klasik DNA dizilim örneği üzerinden olacak. Herhangi bir metin üzerinde arama yapmak baya uzun sürüyor.
[ Lecroq'un linki](http://www-igm.univ-mlv.fr/~lecroq/string/bom.html) 

Arama yapacağımız dizilim: G C A T C G C A G A G A G T A T A C A G T A C G
Arayacağımız dizilim: G C A G A G A G

Arayacağımız dizilim üzerinde bir ön işlem yapmamız gerekiyor. Bu ön işlemde dizilimin sonlarına ulaşmamız gerekiyor.


![_config.yml]({{ site.baseurl }}/images/b1.jpg)

Başlangıcımız ve bitişimiz G karakteri ile olduğu için 0,7 ve 8 iki çerçeveli olarak belirtilmiş. Başlangıcımız 8 oluyor. 8den 7ye gidip bitme durumundan dolayı 7de iki çerçeveli olarak belirtiliyor.
Daha sonra sona ulaşma durumlarının hepsi düşünülerek aşağıdaki şekil oluşturulmuş.

![_config.yml]({{ site.baseurl }}/images/bom.png)


