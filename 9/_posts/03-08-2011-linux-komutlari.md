---
layout: post
title: Gerekli Linux Komutları
---
# cd
Change Directory kelimelerinin ilk harfleri. Dos da oldugu gibi dizin degistirmeye yariyor. Misal cd /mnt dersiniz oraya gecersiniz.

# mount
Dosya sistemlerini mount etmeye yariyor. Misal # mount /dev/hda1 /mnt dediginizde hda1 partition i mnt dizinine mount edilir.

# umount
Mount ettiginiz dosya sistemini un mount eder.

# cp
Copy/Paste komutu. Örnek; # cp dosyaismi /home/tux derseniz o dosya belirttigimiz dizine yani /home/tux a kopyalanır.

# mv
Move. Dosyalari taşımak için kullanilir. Bu sefer kopyalamak yerine direk oraya taşırsınız. Örnek cp ile ayni.

# mkdir
Make Directory. Dizin oluşturmaya yarar. Örnek; # mkdir /home/tux/yenidizin derseniz. tux altinda yenidizin diye bir klasör oluşur.

# rm
Remove. Dosya yada dizin silmek için. Örnek # rm dosya1 dediginide dosya1 silinir.

# ls
List. Dos daki dir komutu ile ayni işlevde. İçinde bulundugunuz dizinin içerigini gösterir.

# pwd
print name of working directory. İçinde bulundugunuz dizini gösterir.

# df
Disk kullanimi hakkinda bilgi verir. Ne kadar kullanimda, ne kadar bos yer var gibi.

# free
Ne kadar RAM ve swap kullandiginizi gösterir.

# locate
Dosya yada dizinin yerini belirlemekte kullanılır. Örnek; # locate dosyaismi

# updatedb
locate komutunun kullandigi database i günceller.

# chmod
Dosya yada dizinin izinlerini değiştirmek için kullanilir. Örnek # chmod 755 dosya2 derseniz dosya2 nin izinleri 755 olur.

# head
Bir text dosyasinin ilk satirlarini görmenizi saglar. Kac satir görmek istediginizide belirtebilirsiniz. Örnek head -10 dosya3.txt derseniz dosya3.txt nin ilk 10 satirini gösterir.

# tail
Head den farkli olarak txt nin son satirlarini gösterir.

# man
Herhangi bir komut ile ilgili manual’i yani kullanim klavuzunu gösterir. Örnek; # man tail

# clear
Konsol ekranini temizler..

# top
Kullanimda olan programlari listeler, ne kadar memory kullandiklarini yazar, islemci istatistiklerini gösterir vb.

# ps
Process Status. PID ( Process ID ) leri ile birlikte kullanimda olan programlari listeler. #ps -au derseniz all users-bütün kullanicilar için process leri verir.

# su
Super User. konsolda root haklariyla oturum acmanizi saglar.

# passwd
Şifre değiştirmek için kullanilir. root iseniz ve baska bir kullanicinin şifresini değiştirecekseniz #passwd kullaniciadi seklinde kullanmalisiniz.

# whoami
Kullanici isminizi görüntüler.

# date
Tarihi ve saati gösterir.

# reboot
Sistemi yeniden baslatir.

# lsmod
Yüklü olan kernel modüllerini gösterir.

# tar -zxvf dosyaismi.tar.gz
.tar.gz yada .tgz uzantili sıkıştırılmış dosyaları (tarball) açmanızı saglar. Örnek; # tar -zxvf dosya4.tar.gz

# tar -xvf dosyaismi.tar
.tar uzantili tarball lari acmanizi saglar.

# gunzip dosyaismi.gz
.gz veya .z uzantili sıkıştırılmış dosyalari acmanizi saglar.

# shutdown
Sistemi kapatir. Lakin parametre girmeniz gerekir. -h halt anlamina gelir sistem kapanir. -r reboot anlamina gelir.Sistemi o anda kapatmak için # shutdown -h now yazmaniz yeterli.


