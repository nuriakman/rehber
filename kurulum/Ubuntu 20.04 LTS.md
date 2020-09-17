Ubuntu Kurulumu
  # Ubuntu İndirme ve Yazdırma
- https://ubuntu.com/download/desktop Adresinden ubuntu son LTS sürümünü indir(En son 20.04).
- Flash belleğe yazdırmak için https://rufus.ie/ adresinden rufus son surumunu indir(en son 3.1.1).
- Rufus kurduktan sonra önyükleme seçimini indirdiğin ubuntu .iso dosyasını seç.
- Gerisini varsayılan ayarda kullanarak başlat tuşuna bas(en üstte doğru flash bellek seçili olduğundan emin ol)
- yükleme gerekli bildirimi gelirse onayla ve diğer soruları da onayla.
  # Bilgisayarı Format İçin Yeniden Başlatma
- Windows 10da shift tuşuna basılı tutarak başlangıç menüsünden yeniden başlata bas.
- Gelen mavi ekrandan sorun gidere, gelişmiş seçeneklere ardından uefi donanım yazılımı ayarlarına tıkla.
- BIOS ekranından boot sekmesinde boot option #1 üzerinde enterlayarak usb sürücünü seç(Cihazdan cihaza farklılık gösterebilir usb sürücünüz en üstte olmalı).
- Save & Exit sekmesinden save changes and reset seç.
  # Temel Kurulum
- Bende OEM modda yükleme yapıyor. Sebebini bilmiyorum ama sorun olmaz sanırım.
- Temel seçimleri yap(dil, wifi vb.). 3. Parti yazılımları yükle faydası olabilir.
- Wifi şifreni hatırlamıyorsan [windows için şifre öğrenme](https://support.microsoft.com/tr-tr/help/4023501/windows-find-wireless-network-password)
- Temiz kurulum için erase disk and install ubuntuyu seç. Açılan pencerede use lvm seçeneğini seçtim ama işlevini tam bilmiyorum
- Oem olmasından dolayı ad ve username seçtirmiyor. Kurduktan sonra düzelir diye umuyorum.
- Kurulum biraz sürebilir.

   ## Özel Bir Sorun
```
- Çift işletim Sistemli(windows + linux)den geçiyordum ve açılışta boot seçme kısmını atlama olayını geçemedim. Bu yüzden kurulumu farklı ayarlarla baştan yapıyorum.
- İnstall kısmına kadar gelip erase disk yerine something else seçiyorum
- İşe yaramadı, yine biosa girip uefi hard disk drive bbs kısmını disabled yapıp yeniden başlatıyorum.
- Linux kısmında biçimlendirme yönetimini bilemediğim için windows 10 indirip usb ye yükleyip diskleri biçimlendiriyorum.
- Sanırım boot kısmında gelen seçenekte oem seçtiğim için oem yüklemye çalışmışım, ubuntuyu seçerek onu düzelttim.
```
  # Kurulumu Tamamlama
- Yükleme tamamlandıktan sonra yeniden başlat ve usb sürücüsünü çıkar. Bir terslik olmadıysa ubuntu yüklendi.
- Klavyeyi türkçe yapmak için sağ üstteki simgelere tıklayarak settingsi aç, Region & Language sekmesinden input sources bölümüne Turkish-Turkish dilini ekle ve mevcut olan english dilini sil.
