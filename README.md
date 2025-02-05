### Markdown Kılavuz<a name="TOP"></a>
===================

- - - -  
# Başlık 1 #

    Biçimlendirme:  # Başlık 1 #

    -VEYA-

    Biçimlendirme:  ============= (Başlık 1 metninin altına)

## Başlık 2 ##

    Biçimlendirme:  ## Başlık 2 ##

    -VEYA-

    Biçimlendirme: --------------- (Başlık 2 metninin altına)

### Başlık 3 ###

    Biçimlendirme:  ### Başlık 3 ###

#### Başlık 4 ####

    Biçimlendirme:  #### Başlık 4 ####


Genel metin

    Biçimlendirme:  Genel metin

_Vurgulanmış metin_

    Biçimlendirme:  _Vurgulanmış metin_ veya *Vurgulanmış metin*

~~Üstü çizili metin~~

    Biçimlendirme:  ~~Üstü çizili metin~~

__Kalın metin__

    Biçimlendirme:  __Kalın metin__ veya **Kalın metin**

___Kalın ve vurgulanmış metin___

    Biçimlendirme:  ___Kalın ve vurgulanmış metin___ veya ***Kalın ve vurgulanmış metin***

[Adlandırılmış Bağlantı](http://www.google.com/ "Adlandırılmış bağlantı başlığı") ve http://www.google.com/ veya <http://example.com/>

    Biçimlendirme:  [Adlandırılmış Bağlantı](http://www.google.com/ "Adlandırılmış bağlantı başlığı") ve http://www.google.com/ veya <http://example.com/>

[başlık-1](#başlık-1 "başlık-1'e git")
    
    Biçimlendirme: [başlık-1](#başlık-1 "başlık-1'e git")

Tablo, aşağıdaki gibi:

İlk Başlık  | İkinci Başlık
------------- | -------------
İçerik Hücresi  | İçerik Hücresi
İçerik Hücresi  | İçerik Hücresi


Bir hücreye `|` eklemek:

İlk Başlık  | İkinci Başlık
------------- | -------------
İçerik Hücresi  | İçerik Hücresi
İçerik Hücresi  | \|


Sola, sağa ve ortaya hizalanmış tablo:

Sola Hizalanmış Başlık | Sağa Hizalanmış Başlık | Ortaya Hizalanmış Başlık
| :--- | ---: | :---:
İçerik Hücresi  | İçerik Hücresi | İçerik Hücresi
İçerik Hücresi  | İçerik Hücresi | İçerik Hücresi


`code()`

    Biçimlendirme:  `code()`

```javascript
    var ornekKod = 
    {
        "veri": {
            "aramaPlatformu": 1,
            "sorgu": "Kasabian+Test+Transmission",
            "bulunanÖğe": {
                "isim": "Test Transmission",
                "sanatçı": "Kasabian",
                "albüm": "Kasabian",
                "resim": null,
                "bağlantı": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
Biçimlendirme: ```javascript
         ```
 Biçimlendirme: * Madde işaretli liste
              * İç içe madde işareti
                  * Alt iç içe madde işareti vb.
          * Madde işaretli liste öğesi 2

-VEYA-

 Biçimlendirme: - Madde işaretli liste
              - İç içe madde işareti
                  - Alt iç içe madde işareti vb.
          - Madde işaretli liste öğesi 2 
 Biçimlendirme: 1. Numaralandırılmış liste
              1. İç içe numaralandırılmış liste
              2. Numaralı liste öğesi
          2. Numaralı liste öğesi
 Biçimlendirme: - [ ] Tamamlanmamış görev
          - [x] Tamamlanmış görev Biçimlendirme: - [ ] Tamamlanmamış görev
              - [ ] Alt görev

Biçimlendirme:  > Alıntı
          >> İç içe alıntı
Biçimlendirme:  - - - -
Biçimlendirme: ![resim açıklaması](http://via.placeholder.com/200x150 "Başlık isteğe bağlıdır")
Biçimlendirme: <details>
           <summary>Başlık 1</summary>
           <p>İçerik 1 İçerik 1 İçerik 1 İçerik 1 İçerik 1</p>
         </details>
<h3>HTML</h3>
<p> Buraya bazı HTML kodları gelir </p>
Biçimlendirme: [buraya metin gelir](#bölüm_adı)
          bölüm_başlığı<a name="bölüm_adı"></a>    
Biçimlendirme: <kbd>⌘F</kbd>
Kısayol tuşu listesi:
Tuş	Sembol
Seçenek	⌥
Kontrol	⌃
Komut	⌘
Shift	⇧
Caps Lock	⇪
Sekme	⇥
Escape	⎋
Güç	⌽
Enter	↩
Sil	⌫
Yukarı	↑
Aşağı	↓
Sol	←
Sağ	→

Emoji:

:exclamation: Metni vurgulamak için emoji simgelerini kullanın. :+1: Emoji kodlarını emoji-cheat-sheet.com adresinden bulun.

Biçimlendirme: Kod iki nokta işareti arasına yazılır :EMOJIKODU:
