# BAU Bright FS-2310-13 Frontend 1. Proje
     Trendyol
* Site navinasyonu bilgilendirmesi:
    * Ana Sayfaya dönmek için sol üstteki "Trendyol" logosundan
    * Ürün listesine ulaşmak için navbardaki (Kadın, Erkek, Anne & Çocuk ...) herhangi bir linken veya "Süper Alışveriş Günleri" yazan kartlandan birine tıklayarak
    * Ürün Linki için Ana Sayfa'nın alt kısımlarında bulunan sliderdaki ürünlerden birine (Ana Sayfadaki sliderda gösterilen ürün parfüm olmasına rağmen ben ürün sayfasını bir ayakkabı ürün sayfası olarak tasarladığım için parfüm yerine ayakkabı ürün linkine çıkıyor.) veya Ürün Listesi'ndeki (product_list.html) herhangi bir ürünün üstüne tıklandığında
    * Sepet Bölümüne ise sadece sticky header kısmında sağ üstteki "Sepet" kısmına tıklayarak ulaşabilirsiniz.
    * Belirttiğim linkler harici hatırladığım kadarıyla etkisiz link (#) olması lazım ama Ana Sayfa (/) linki olarak unuttuktum olabilir, şimdiden özür diliyorum.
* Ürün Listesi (product_list.html) deki soldaki listenin en dışındaki kalan scroll barın çalışmama nedenini çözdüm; display:flex verdiğim için scroll bar çalışmıyormuş, o komut satırını sildiğimde direkt olarak düzeldi. :)
* Ürün sayfasında (product.html) ürünün büyük görselinin olduğu kısımda kısıtlı vaktim kaldığı için ufak bir screenshot hilesine başvurdum lütfen mazur görün :) main / product-content / #product-image id'li görsel. Onun dışında screenshot alarak kolaya kaçtığım başka bir yer yok. 
* Bazen bir sayfanın css'inde kullandığım classları başka sayfalarda da kullandım o yüzden sayfaları oluşturduğum sıraya göre birbirlerine css dosyaları bağlı. Sayfaları oluşturma sıram:
    * Ana Sayfa(index.html) / Ürün Listesi(product_list.html) / Ürün Sayfası(product.html) / Sepet(shopping_cart.html)
