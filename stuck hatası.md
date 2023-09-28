## Stucks hatası düzeltmek için
[BURADAN](https://alchemy.com/?r=DUwMTk1NDc3NzY0M) Alchemy sitesine kayıt oluyoruz. 

![Ekran görüntüsü 2023-09-28 224140](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/2ef95c2b-eda5-4cd8-83b3-9b0292d82061)

* Create APP yazıyoruz.

![Ekran görüntüsü 2023-09-28 224231](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/a377aef7-98a7-46b9-9f26-3398b4d6f093)

* Burada ETH> ETH Mainnet seçiyoruz. Herhangi bir isim verebilirsiniz.

![Ekran görüntüsü 2023-09-28 224340](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/cf038def-ac7e-4a56-a046-44feb1cb4bb7)

Buradan API KEY basarak size özel olan RPC adresine ulaşabilirsiniz.

![Ekran görüntüsü 2023-09-28 224429](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/074b582c-cd6f-4246-bab4-dbeca258d472)

buradaki https ile başlayan RPC adresini kopyalıyoruz.

## VPS sunucusunda yapılacak adımlar.

* winSCP yada mobaxtermm ile sunucumuzdaki dosyalara ulaşıyoruz.
![Ekran görüntüsü 2023-09-28 224625](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/6fa7b53a-1509-4925-8da3-27ace5037d78)

nodeismin/src/processor.ts dosyasını ister bilgisayarınıza indirin. ister içinde düzenleyin.

![Ekran görüntüsü 2023-09-28 224821](https://github.com/CoinHuntersTR/Subsquid/assets/111747226/28a9bec1-c8d5-4536-811f-ac4c06d8475b)

* buradaki chain bölümünde yazan RPC silip alchemy üzerinden aldığınız RPC ekliyoruz.

* Sonrasında bu dosyayı kayıt edip sunucu içinde olanla değiştiriyoruz.

Yukarıdaki adımları tamamladıysak. Aşağıdaki kodu terminale yazıp enter basıyoruz. Sizden bir yada iki kere soru soracak y yazıp enter etmeniz yeterli olacaktır.

```
sqd deploy --org nodeismin ./nodeismin
```
*nodeismin yazan yere subsquid kurarken yazdığın ismi ekliyorsun
