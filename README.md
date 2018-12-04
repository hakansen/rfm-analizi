# Python ile RFM Analizi

RFM analizi, pazarlama çalışmalarınıza cevap vermesini beklediğiniz hedef müşteri kitlenizi belirlemek için kullanılan popüler bir analiz yöntemidir.

Bu analiz yönteminde müşterinin geçmiş alışveriş alışkanlıklarının yanı sıra, yaptıkları alışveriş sayısına ve bu alışverişlerin harcama miktarına bağlı olarak müşterilerin muhtemel satın alma eğilimlerinin belirlenmesi amaçlanır.

https://productphilosophy.com/rfm-analizi-nedir-ve-nasil-yapilir/

## Kullanım:

```bash
$ python rfm-analizi.py -i ornek-siparis-verisi.csv -o rfm-segmentleri.csv -d "2018-10-30"
```

- Satın alım geçmişini içeren dosya (-i ornek-siparis-verisi.csv)
- RFM çıktısının kaydedileceği dosya (-o rfm-segmentleri.csv)
- Analizin baz alınacağı son işlem tarihi (-d “YYYY-mm-dd”).