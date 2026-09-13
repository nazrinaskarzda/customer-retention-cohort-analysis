# Müştəri saxlanması üzrə kohort analizi

Bu layihədə müştərilər ilk alış etdikləri aya görə kohortlara bölünüb və sonrakı aylardakı alış aktivlikləri təhlil edilib. Məqsəd müştəri itkisinin əsas dövrlərini müəyyənləşdirmək, kohortlar arasındakı fərqləri müqayisə etmək və saxlanma göstəricisini yaxşılaşdırmaq üçün tədbirlər hazırlamaqdır.

## Analizin məqsədi

- Aylıq müştəri saxlanma göstəricisini hesablamaq
- Kohortların nəticələrini müqayisə etmək
- Müştəri itkisinin ən yüksək olduğu dövrləri müəyyənləşdirmək
- Nəticələrə əsaslanan saxlanma strategiyası hazırlamaq

## Metodologiya

Müştərilər ilk alış etdikləri aya görə qruplaşdırılıb və hər kohortun sonrakı aylardakı aktivliyi izlənib.

**Saxlanma faizi = Aktiv müştərilərin sayı / Kohortun ilkin müştəri sayı × 100**

Analiz aşağıdakı mərhələlər üzrə aparılıb:

1. Alış məlumatlarının təmizlənməsi və yoxlanılması
2. Müştərilərin ilk alış ayına görə kohortlara bölünməsi
3. Aylıq saxlanma faizlərinin hesablanması
4. Kohortların müqayisəsi və nəticələrin vizuallaşdırılması

## Əsas nəticələr

| Göstərici | Nəticə |
| --- | ---: |
| Birinci ay üzrə saxlanma | 81% |
| Birinci ay üzrə müştəri itkisi | 19% |
| Üçüncü ay üzrə saxlanma | 62% |
| Altıncı ay üzrə saxlanma | 42% |
| On ikinci ay üzrə saxlanma | 25% |
| Müştərinin orta ömürboyu dəyəri (CLV) | 650 AZN |

## Kohortların müqayisəsi

| Kohort | On ikinci ay üzrə saxlanma | Nəticə |
| --- | ---: | --- |
| Oktyabr 2023 | 32% | Ən yüksək göstərici |
| Yanvar 2023 | 20% | Ən aşağı göstərici |

Kohortlar arasındakı 12 faiz bəndlik fərq müştəri keyfiyyəti, cəlbetmə kanalı və kampaniyaların təsirinin ayrıca araşdırılmalı olduğunu göstərir.

## Analitik nəticələr

### İlk ay kritik dövrdür

Müştərilərin 19%-i ilk aydan sonra aktivliyini dayandırıb. Bu nəticə ilkin müştəri təcrübəsinin və məhsulun dəyərinin ilk həftələrdə aydın göstərilməsinin vacibliyini vurğulayır.

### Uzunmüddətli saxlanma zəifləyir

Saxlanma göstəricisi birinci ayda 81%, üçüncü ayda 62%, altıncı ayda 42%, on ikinci ayda isə 25% təşkil edir. Bu azalma müştəri münasibətlərinin davamlı saxlanılmasında boşluqlar olduğunu göstərir.

### Kohortlar arasında nəzərəçarpan fərq var

Oktyabr 2023 kohortunun nəticəsi Yanvar 2023 kohortundan 12 faiz bəndi yüksəkdir. Fərqin səbəbini müəyyənləşdirmək üçün həmin dövrlərdəki kampaniyalar, cəlbetmə kanalları və müştəri profilləri müqayisə edilməlidir.

### Yenidən aktivləşmə potensialı mövcuddur

Bəzi dövrlərdə mövsümi kampaniyalardan sonra aktivlik artıb. Bu müşahidə uyğun vaxtda göndərilən fərdiləşdirilmiş təkliflərin passiv müştərilərin geri qaytarılmasına kömək edə biləcəyini göstərir.

## Tövsiyələr

- İlk ay üçün qarşılama və məhsulla tanışlıq prosesini təkmilləşdirmək
- Aktivliyi azalan müştərilər üçün fərdiləşdirilmiş yenidən aktivləşdirmə kampaniyaları hazırlamaq
- Ən yaxşı nəticə göstərən kohortun cəlbetmə kanallarını və müştəri profilini təhlil etmək
- Təkrar alışları artırmaq üçün loyallıq mexanizmlərini sınaqdan keçirmək
- Müştəri itkisi riskini erkən müəyyənləşdirmək üçün davranış göstəricilərini izləmək

## İzlənəcək göstəricilər

- Birinci, üçüncü, altıncı və on ikinci ay üzrə saxlanma faizi
- Müştəri itkisi faizi
- Təkrar alış faizi
- Yenidən aktivləşmə faizi
- Müştərinin ömürboyu dəyəri (CLV)

## İstifadə olunan alətlər

- **Excel** - məlumatların hazırlanması və ilkin hesablamalar
- **SQL** - alış məlumatlarının çıxarılması və strukturlaşdırılması
- **Python / pandas** - məlumatların yoxlanılması və təhlili
- **Tableau** - kohort istilik xəritəsinin və interaktiv vizuallaşdırmanın hazırlanması

> Bu layihə tədris və portfel məqsədilə hazırlanmış konseptual analizdir.

## Cohort heatmap

![Customer Retention Cohort Analysis](Cohort_Retention_Heatmap.png)

## Fayl

[Tableau workbook-u yüklə](customer-retention-cohort-analysis.twbx)

## Bacarıqlar

`Cohort Analysis` · `Customer Retention` · `Tableau` · `Data Visualization`
