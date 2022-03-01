# Учебные проекты Yandex.Practicum по специальности "Специалист по Data Science"

<code>[***1. Исследование предпочтений пользователей Yandex.Music***](https://github.com/Reijii-sar/yandexdc/blob/main/YandexMusic.ipynb)</code>  

**Цель исследования:** проверьте три гипотезы:  
- Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.  
- В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие. Так же и вечером пятницы преобладают разные жанры — в зависимости от города.  
- Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.  

**Библиотеки:** pandas

<code>[***2. Исследование объявлений о продаже квартир***](https://github.com/Reijii-sar/yandexdc/blob/main/real_estate.ipynb)</code>  

**Цель исследования:** изучить зависимость и определить следующие факторы:  
- зависимость следующих параметров: площадь, цена, число комнат, высота потолков  
- время продажи квартиры, определить что продажи идут быстро/медленно  
- зависит ли цена от площади, числа комнат и удаленности от центра, от того на каком этаже размещена квартира и даты размещения объявления
- изучить среднюю стоимость квадратного метра в 10 населенных пунктах с самым большим количеством объявлений  
- определить факторы влияющие на стоимость квартиры в центре (площадь, число комнат, высота потолков, этажность, удаленность от центра, дата размещения объявления), имеются ли различия с общей картиной  

**Библиотеки:** pandas, matplotlib, pymystem3, collections

<code>[***3. Исследование надёжности заёмщиков***](https://github.com/Reijii-sar/yandexdc/blob/main/bank.ipynb)</code>  

**Цель исследования:**  оценка следующих факторов для построения модели кредитного скоринга:  
- зависимость между количеством детей и возвратом кредита в срок  
- зависимость между семейным положением и возвратом кредита в срок  
- зависимость между уровнем дохода и возвратом кредита в срок  
- как разные цели кредита влияют на его возврат в срок  

**Библиотеки:** pandas, matplotlib, pymystem3

<code>[***4. Определение перспективного тарифа для телеком компании***](https://github.com/Reijii-sar/yandexdc/blob/main/megalain.ipynb)</code>

**Цель исследования:** необходимо поризвести следуюшие расчеты и проверить гипотезы:  
- необходимо для каждого пользователя посчитать: количество сделанных звонков и израсходованных минут разговора по месяцам, количество отправленных сообщений по месяцам;
объем израсходованного интернет-трафика по месяцам, помесячную выручку с каждого пользователя.
- сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц.  
- проверить гипотезы: 1. средняя выручка пользователей тарифов «Ультра» и «Смарт» различаются; 2. средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов.

**Библиотеки:** pandas, numpy, matplotlib, scipy

<code>[***5. Изучение закономерностей определяющих успешность игр***](https://github.com/Reijii-sar/yandexdc/blob/main/games.ipynb)</code>  

**Цель исследования:** необходимо выявить следующие закономерности и проверить гиппотезы:  
- посчитать суммарные продажи во всех регионах; сколько игр выпускалось в разные годы, важны ли данные за все периоды
- как менялись продажи по платформам, за какой характерный срок появляются новые и исчезают старые платформы
- какие платформы лидируют по продажам, растут или падают
- как влмяют на продажи внутри одной популярной платформы отзывы пользователей и критиков, как это соотносится с продажами на других платформах
- какое распределение игр по жанрам, выделяются ли жанры с высокими и низкими продажами
- портрет пользователя каждого региона (топ-5 платформ по полярности, топ-5 популярных жанров, влияние рейтинга ESRB на продажи в регионе)
- проверить гипотезы: 1.средние пользовательские рейтинги платформ Xbox One и PC одинаковые; 2. средние пользовательскте рейтинги жанров Action и Sports разные  

**Библиотеки:** pandas, numpy, matplotlib, seaborn, scipy

<code>[***6. Рекомендация тарифов***](https://github.com/Reijii-sar/yandexdc/blob/main/megalain2.ipynb)</code>  

**Цель исследования:** необходимо произвести следующие действия:
- постройть модель с максимально большим значением accuracy, с долей правильных ответов по крайней мере до 0.75
- исследовать качество разных моделей
- проверить модели на вменяемость

**Библиотеки:** pandas, sklearn

<code>[***7. Предсказание оттока клиентолв банка***](https://github.com/Reijii-sar/yandexdc/blob/main/bank2.ipynb)</code>  

**Цель исследования:** необходимо произвести следующие действия:
- необходимо спрогнозировать, уйдёт клиент из банка в ближайшее время или нет
- постройть модель с предельно большим значением F1-меры (минимальное значение 0.59)
- измериять AUC-ROC, сравнить её значение с F1-мерой.

**Библиотеки:** pandas, sklearn, matplotlib, warnings

<code>[***8. Выбор локации для скважины***](https://github.com/Reijii-sar/yandexdc/blob/main/oil.ipynb)</code>  

**Цель исследования:** необходимо произвести следующие действия:
- обучить и проверите модель для каждого региона
- расчитать средний запас предсказанного сырья и RMSE модели.
- рассчитать достаточный объём сырья для безубыточной разработки новой скважины. Сравнить полученный объём сырья со средним запасом в каждом регионе.
- рассчитайть прибыль для полученного объёма сырья; просчитать риски и прибыль для каждого региона.

**Библиотеки:** pandas, numpy, sklearn  

<code>[***9. Эффективность восстановления золота из руды***](https://github.com/Reijii-sar/yandexdc/blob/main/gold.ipynb)</code>  

**Цель исследования:** необходимо произвести следующие действия:
- проверить, что эффективность обогащения рассчитана правильно  
- посмотреть, как меняется концентрация металлов (Au, Ag, Pb) на различных этапах очистки. Сравнить распределения размеров гранул сырья
- исследовать суммарную концентрацию всех веществ на разных стадиях: в сырье, в черновом и финальном концентратах
- вычислить итоговую sMAPE.
- обучить разные модели предсказывающие коэффициент восстановления золота из золотосодержащей руды

**Библиотеки:** pandas, warnings, sklearn, seaborn, matplotlib, numpy  
