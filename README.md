Ardoino nano kullanılarak blink uygulaması.
İlk int komutu kullanarak D1 pinine bağlı olan ledi tanımlıyoruz. Daha sonra void setup komutu ile led pinini output yani çıkış pini olarak atadık. Void loop komutunda ise döngüye aldık. For komutu içinde i değişkeni oluşturup 0 olarak tanımladık. Daha sonra for döngüsü içinde i değişkenini 10 a kadar saydırdık. İ değişkeni her artışında ledi 1 saniye yakıp 1 saniye söndürdük. For döngüsü içinde 10 kere yapılmasını sağladı fakat i değerini değiştirip daha büyük yada daha küçük değer tanımlanabilir, aynı şekilde ledin açık ve kapalı kalma süreleri değiştirilebilir. Süre konusunda dikkat edilmesi gereken detay delay komutunun saniyenin binde biri hassasiyetinde çalıştığıdır. Yani 1000 yazıldığında 1 saniyeye karşılık gelmektedir.
#C++
