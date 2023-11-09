# Introduction

### İletişimimizde kayıplar olmaması adına bu içeriğin bazı kısımlarını Türkçe yazıyorum.


Bu taskı kusursuz bir code-base yaratmaktansa kusursuz bir problem çözmek üzere ele aldım.

Aşağıda problemi parçalarına ayırarak tanımlarını zenginleştirdim. Bu sayede problemi daha iyi anlayarak olabilecek en uygun çözümleri üretmeye çalıştım.

Task detaylarında tanımladığınız ve çözülmesini istediğiniz problem için efektif çözümler bulup bulmadığımı merak ediyorum. Bu konuda feedback vermeniz beni fazlasıyla mutlu edecektir.



## The problem to be solved
Iceberg Estates isimli bir emlakçının yöneticisi; çalışanlarının hangi evi, ne
zaman ve hangi müşterisine göstereceğinin kayıtlarını tutmakta zorluk yaşıyor.
Çalışanlarını daha efektif kullanmak isteyen şirket yöneticisi, özellikle randevulara
gidiş geliş süreçlerinin ne uzunlukta olduğunu, çalışanların randevu için ayırdıkları
vakitleri ve tüm bu randevuları kendi arasında çakışma olmadan kontrol edebilmek
istiyor.

1. Problem Kimin? Emlakçı Yöneticisi
2. Kimler Kullanacak? Emlakçı yöneticisi ve çalışanları
3. Zorluk Yaşadığı Şey: Hangi çalışanın, hangi evi, hangi müşterisine, ne zaman göstereceğinin kayıtlarını doğru şekilde tutamıyor.
4. Ne istiyor?
   1) Randevulara ne kadar zaman harcandığını görmek
   2) Çalışanların randevu için ayırdıkları vakitleri görmek
   3) Randevuların birbiri ile çakışmamasını sağlamak

## The Solutions

#### Yönetici
- Yönetici sisteme giriş yaparak ihtiyacı olan tüm bilgilere erişebilmeli

#### Hangi Çalışan
- Çalışanlar kendi hesapları ile giriş yapabilmeli
- Randevularını oluşturabilmeli ve detaylarını görebilmeli

#### Hangi evi
- Evler listelenmeli
- Evlerin hangi çalışan ile hangi müşteriye ne zaman gösterildiği görünmeli

#### Hangi müşterisine
- Müşteriler listelenmeli
- Müşterilerin hangi eve, hangi çalışan ile ne zaman baktığı görünmeli

### Randevulara ne kadar zaman harcanıyor
- Tüm randevulara ayrılan toplam zaman görünmeli
- Gün, hafta, ay bazında görünebilir

### Çalışanların randevu için harcadıkları zaman
- Her bir çalışanın randevular için harcadığı zaman görünmeli


## Additional Problems

### UI & UX
Task detaylarında uygulamanın nasıl olacağı ile ilgili bir yönerge var fakat tasarım olmadığı için neredeyse her şey benim yorumuma açık.

Emlakçı yöneticisinin ve çalışanlarının genelde kullandığı uygulamaları araştırarak fikir sahibi olmaya çalışacağım.

Kullanıcıların zorluk çekmeden kolayca kullanabilecekleri bir uygulama olması için alışkanlıklarına uygun bir UX deneyimi yaratmaya çalışcağım.

### Airtable
Kaynak olarak kullanmam istenilen airtable tablosu belirtilen problemi çözmek için yetersiz. Bu nedenle kendim farklı bir kaynak kullanacağım.


## Requirements
#### Node.js Version
18.18.1
#### VueJs Version
3.3.4




## Clone & Open Repo

```sh
git clone git@github.com:barisbabacanoglu/appointment-task.git
cd appointment-task
```


## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```
