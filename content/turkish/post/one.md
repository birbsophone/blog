+++
date = '2025-04-14T22:19:47+03:00'
draft = true
title = 'Windows Üzerinde Ungoogled Chromium Nasıl İndirilir?'
description = 'Adım Adım.'
featured_image= "/images/chromium.jpg"
tags= 'nasıl yapılır'
+++

Hangi tarayıcıyı seçmeye karar verdiğine göre şimdi Google'sız Chromium'u indirebilirsin:

>1. <a href="/downloads/ungoogled-update.bat" download>ungoogled-update.bat'i</a> indir

>1,5. Tarayıcın indirmeyi engelleyebilir, çünkü indirdiğin dosya bilgisayarına bir komut yazdırır. "Yine de indir" düğmesine tıklayabilirsin.

>2. Dosyaya çift tıkla. 

>3. Eğer komut istemi izin isterse/soru sorarsa klavyeden "y" tuşuna bas.

Ve bu kadar. Windows gerisini halledecek. Bu komutu her güncelleme geldiğinde yürütmen lazım.

>"Komutun içinde ne yazıyor?" 
winget install --id=eloston.ungoogled-chromium -e yazıyor. Bu kodu direk UC'nin resmi github sitesinden aldım ( https://github.com/ungoogled-software/ungoogled-chromium-windows)

Dosyanın içinde ne olduğunu kontrol etmek istiyorsan:
> ungoogled-update.bat dosyasına sağ tıkla > "Not defterinde düzenle" üstüne tıkla.
Ve içeriklerini görebileceksin. 

## Ungoogled Chromium'u Nasıl Otomatik Olarak Güncelleyebilirim?

>1. Ungoogled-update.bat dosyasına shift + sağ tık (shift'e basılı tutarken mouse'un sağdaki tuşuna bas)

>2. "Kısayol oluştur"u bul ve üstüne tıkla.

>3. "ungoogled-update.bat - Kısayol" adlı bir dosya oluşması lazım.

>4. Aynı anda Windows + R tuşuna bas (windows logolu tuş ve klavyende R tuşuna bas).

>5. Boşluğa "shell:startup" yaz, klavyende enter'a bas

>6. "ungoogled-update.bat - Kısayol"u açılan dosyanın içine at.

Artık Windows'a her giriş yaptığında bu .bat komut dosyası güncellemeleri kontrol edecek. Giriş yaptığınızda otomatikmen kısa bir anlığına bir komut paneli açılabilir.
