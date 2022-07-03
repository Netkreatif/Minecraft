Selamlar!

Minecraft sunucusu olanların sürekli cmd açıp uğraşması yerine sizlere .bat dosyası oluşturup sunucunuzu 2 saniyede açmanın kodunu sizlerle paylaşıyorum;
```bat
java -Xms1024M -Xmx1024M -Dfile.encoding=UTF-8 -jar spigot.jar -o true
```

Sonundaki spigot.jar'ı kendi kulladığınız jarla değiştirebilirsiniz.  (waterfall.jar vb.)

1. -Xms1024M sunucunun minimum ram ayarını belirtir. MB cinsinden yazmak için M, GB cinsinden yazmak için G harfi yazılır.
2. -Xmx1024M yazısı ise sunucunun maksimum ram ayarını belirtir. MB cinsinden yazmak için M, GB cinsinden yazmak için G harfi yazılır.


> Bu sistemi paylaşan `Ranxe#2053`'ye teşekkür ederiz.
