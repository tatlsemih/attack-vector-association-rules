# Veri

Orijinal veri: [CICIDS2017, Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html) (8 günlük trafik, yaklaşık 2.8 milyon akış).

Repoda sınıf başına sınırlı, tekrar üretilebilir bir örnek var (seed 42):

| Dosya | Satır | İçerik |
|---|---|---|
| `cicids2017_attack_vectors.csv` | 39.183 | BENIGN 15.000, her saldırı türü en fazla 2.500; 13 akış özelliği (hedef port, akış süresi, paket sayıları, bayt/sn, paket boyu, 6 TCP bayrağı, ilk pencere boyutu) + Day + Label |

Görev dokümanında örnek verilen Shadowserver CTI verisi yalnızca kayıtlı kurumlara açık olduğu için kamuya açık CICIDS2017 kullanıldı.
