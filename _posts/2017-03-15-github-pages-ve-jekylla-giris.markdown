---
title: Github Pages ve Jekyll'a giriş
date: 2017-03-15 18:31:00 +03:00
categories:
- jekyll
author: Ali Aşkın
---

Bilindiği üzere artık pages hizmeti sayesinde github üzerinden basit statik siteler kurulabiliyor. Ücretsiz şekilde sitenizi ayağa kaldırabiliyorsunuz. Ayrıca projenizin sitesini de bu şekilde sunabilmenize olanak sağlıyor. Peki bunu nasıl yapacağız? Jekyll bu yollardan biri ve en popüleri. Haricindekileri buradan görebilirsiniz.
Şahsen kendime not, hexo bir ara denenecek. Çok güzel duruyor.

[https://www.staticgen.com/](https://www.staticgen.com/)

Jekyll bir static site generator'u. Yani kaba tabirle siz elinizdeki malzemeleri veriyorsunuz,onları runtime'da pişirip statik sayfalar oluşturup sitenizi kuruyor. Basit ve kolay mı? Belki kolay ama kesinlikle daha karmaşık olabiliyor.

Öncelikle [https://pages.github.com/](https://pages.github.com/) adresindeki yönergeleri izleyip github projemizi oluşturduktan sonra [https://jekyllrb.com/](https://jekyllrb.com/) adresindeki basit yolla siteyi lokalimizde kurduktan sonra bu proje sayfasına commit'leyip ayağa kaldırabiliriz. Ancak bu siteye daha bir çok yararlı eklenti eklenmiş halini kullandım ben. Bazı üzerinde kafa patlatılmış şeyleri yeniden keşfetme yerine deneme sürüşünde anlama taraftarıyım. Yine de farketmez. İki yoldan da gidebilirsiniz. Benim yolumdan giderseniz [https://github.com/barryclark/jekyll-now](https://github.com/barryclark/jekyll-now) adresindeki versiyonu fork edip onun üzerinde çalışabilirsiniz. Bu versiyonun da ufak tefek eksikleri var. Onları da üzerinde çalışırken çözebilirsiniz. Sistemi de daha iyi anlarsınız böylece. Ayrıca yine jekyll sitesindeki yönergeleri takip edip siteyi önce bir lokalinizde çalıştırıp kurcalamanız tavsiyemdir.

Burada _config.yml dosyamız olayın özünü oluşturuyor. Buradaki ayarları site genelinde yapıyoruz. Site hakkında genelgeçer şeyler burada. Zaten biraz inceleyince amacını daha iyi anlarsınız.

Siteyi github'a atıp az çok ayağa kaldırıyoruz. Peki şimdi aklımızdaki soruları tek tek cevaplandırmaya çalışayım. 

Nasıl post yani yazı göndereceğiz? _Posts dosyası yazılarımızın durduğu dosyadır. Buraya ya github üzerinden ya da benim gibi online bir Cms yani içerik yönetim sistemi kullanarak yazı ekleyebilirsiniz. Ben siteleaf kullanıyorum. Gayet güzel.

Peki Jekyll Jekyll diyorsun da nasıl işliyor bu hacı? Jekyll'ın bir ana dizini var. Bu dizinde dikkatimizi çeken şey alt tireler. Bu dosyalar runtime'da oluşturulmaz. Bu bir köşede dursun. Başka bir yazımızda detaylı bir şekilde değiniriz. Jekyll'ı lokalinizde çalıştırıp kurcalarsanız runtime'ında _site diye bir klasör oluşturur. İşte sizin bütün siteniz bu dosyadan ibaret aslında. Diğer klasördeki _ içermeyen dosyaları alıp çeşitli işlemler sonrası bu _site dosyasında sitenizi kuruyor bu hayreti mucip. 

Şimdilik sitemizi kurup ilk postları kastığımıza göre yazımızı da bitirebiliriz :) Siteniz şimdiden hayırlı olsun. Jekyll ile daha çok haşır neşir olacağız.Merak etmeyin.

Yazı biterken çalan: Alice Cooper-School's Out
