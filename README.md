# Windows DOS Komutları
## Giriş ve Açıklama
Bu dosya, Windows işletim sistemi için kullanılan komutların açıklamalarını içerir.

## Komutlar


### ``dir``
* Açıklama: Altta öğreneceğiniz cd komutu ie girdiğiniz dosyanın içerisindeki bilgileri gösterir.

```DOS
dir [dizin]
```

![dir komutu](Pictures/dir.png)
### ``cd``
* Açıklama: cd ile olduğunuz dosya içerisinde hareket edebilir yada belirli bir dosyaya ullaşabilirsiniz. Bir önceki dosyaya dönmek için cd.. yazmanız yeterlidir.
```DOS
cd [dizin]
cd C:\Users\Admin\Desktop
cd..
```

![cd komutu](Pictures/cd.png)
### ``mkdir``
* Açıklama: Belirtilen konuma yeni bir dosya oluşturur. İsim vermek için sonuna vericeğiniz ismi yazmanız yeterlidir.
```DOS
mkdir [dizin]
```

![mkdir komutu](Pictures/mkdir.png)
### ``rmdir``
* Açıklama: Belirtilen konumdaki dosyaları siler. Mesela "yeni" adlı dosyayı silelim. 
```DOS
rmdir [dizin]
```

![rmdir komutu](Pictures/rmdir.png)
### ``copy``
* Açıklama: Belirtilen dosyayı belirtilen hedefe kopyalar. Resimde görüldüğü gibi "test" adlı dosyayı "destop" adlı dosyaya kopyaladık.
```DOS
copy [dosya] [hedef]
```

![copy komutu](Pictures/copy.png)
### ``del``
* Açıklama: Belirtilen dosyayı siler. Mesela "test" adlı dosyayı silelim.
```DOS
del [dosya]
```

![del komutu](Pictures/del.png)
### ``ren``
* Açıklama: Belirtilen dosyanın adını değiştirir. Mesela "test" adlı dosyanın adını "test1" olarak değiştirelim.
```DOS
ren [eski_ad] [yeni_ad]
```

![ren komutu](Pictures/ren.png)
### ``cls``
* Açıklama: Komut istemini temizler. Eğer komut isteminde bir şeyler yazdıysanız, bu komut ile ilk açılmış gibi görüntülenir.
```DOS
cls
```

![cls komutu](Pictures/cls.png)
### ``help``
* Açıklama: Bütün komutların açıklamalarını gösterir. 
```DOS
help
```

![help komutu](Pictures/help.png)
### ``exit``
* Açıklama: Komut istemini(CMD) kapatır.
```DOS
exit
```

![exit komutu](Pictures/exit.png)
### ``type``
* Açıklama: Belirtilen dosyanın içeriğini görüntüler. Mesela "test" adlı dosyanın içeriğini görüntüleyelim.
```DOS
type [dosya]
```

![type komutu](Pictures/type.png)
### ``move``
* Açıklama: Belirtilen dosyayı veya dizini başka bir konuma taşır. Mesela "test" adlı dosyayı "testfolder" adlı dosyaya taşıyalım.
```DOS
move [kaynak] [hedef]
```

![move komutu](Pictures/move.png)

### ``echo``
* Açıklama: Belirtilen metni ekrana yazdırır veya dosyaya yönlendirir.
```DOS
echo [metin] veya echo [metin] > [dosya]
```

* ![echo komutu](Pictures/echo.png)

### ``date``
* Açıklama: Sistem tarihini görüntüler veya değiştirir.
```DOS
date
```

![date komutu](Pictures/date.png)

### ``time``
* Açıklama: Sistem saatini görüntüler veya değiştirir.
```DOS
time
```

![time komutu](Pictures/time.png)

### ``ver``
* Açıklama: Windows sürüm bilgisini görüntüler.
```DOS
ver
```

![verkomutu](Pictures/ver.png)

### ``systeminfo``
* Açıklama: Sistem hakkında detaylı bilgi görüntüler.
```DOS
systeminfo
```

![systeminfo komutu](Pictures/systeminfo.png)

### ``tasklist``
* Açıklama: Çalışan işlemleri listeler.
```DOS
tasklist
```
 
![tasklist komutu](Pictures/tasklist.png)

### ``taskkill``
* Açıklama: Belirtilen işlemi sonlandırır.
```DOS
taskkill /PID [işlem_numarası] veya taskkill /IM [program_adı]
```

![taskkill komutu](Pictures/taskkill.png)

### ``ipconfig``
* Açıklama: Ağ adaptörlerinin IP yapılandırmasını görüntüler.
```DOS
ipconfig
```
 
![ipconfig komutu](Pictures/ipconfig.png)

### ``ping``
* Açıklama: Belirtilen adrese ağ bağlantısını test eder.
```DOS
ping [adres]
```
* ![ping komutu](Pictures/ping.png)

### ``netstat``
* Açıklama: Ağ bağlantılarını ve portları görüntüler.
```DOS
netstat
```

![netstat komutu](Pictures/netstat.png)

### ``tree``
* Açıklama: Dizin yapısını ağaç görünümünde gösterir.
```DOS
tree [dizin]
```
* ![tree komutu](Pictures/tree.png)

### ``attrib``
* Açıklama: Dosya özelliklerini görüntüler veya değiştirir.
```DOS
attrib [+/-] [``R|A|S|H] [dosya]
```

![attrib komutu](Pictures/attrib.png)

### ``fc``
* Açıklama: İki dosyayı karşılaştırır.
```DOS
fc [dosya1] [dosya2]
```

![fc komutu](Pictures/fc.png)

