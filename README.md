# Türkçe Wordlist

Doğal dil işleme (NLP) ve makine öğrenmesi projelerinde kullanılmak üzere oluşturulmuş 2.510.327 (2.5 milyon) kelimeden oluşan Türkçe kelime listesi. 

Veriseti 48 MB büyüklüğünde sıkıştırıldığında da 14.6 MB büyüklüğündedir. 

Türkçe metin işleme ve dil modelleme gibi alanlarda verilerin encoding katmanında kullanılabilir.

Özellikler
----------

*   **Kaynak Veriseti:**  
    Kelimeler, Vikipedi üzerinde yer alan yaklaşık 500 bin makalenin metin kısmı işlenerek elde edilmiştir.
    
*   **Kelime Formatı:**
    
    *   Tüm kelimeler küçük harflerden oluşmaktadır.
    *   Türkçe harfler ve ayrım işaretleri dışında başka bir karakter bulunmamaktadır.
    *   Kullanılan karakter listesi:  
        "abcçdefgğhıijklmnoöprsştuüvyz'’\‘´"\

*   **Uzunluk Sınırı:**
    
    *   Kelimelerin maksimum uzunluğu 30 karakter ile sınırlandırılmıştır.
*   **Türkçe Skorlar (FastText):**
    *   Sözcüklerin **FastText** ile çıkarılmış Türkçe skorlarını içeren bir versiyonu bulunmaktadır. Bu versiyona, diger_versiyonlar kısmından ulaşabilirsiniz.
*   **Dosya Formatı:**
    *   Dosya büyüklüğü 48 MB. Sıkıştırılmış dosya büyüklüğü 14.6 MB dır.
    *   Kelime listesi, UTF-8 formatında oluşturulmuş olup, csv formatında id ve kelime her satır bir kelime olacak şekilde düzenlenmiştir.
