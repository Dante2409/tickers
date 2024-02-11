# Анализ динамики акций выбранных компаний

### Обзор проекта
Проект посвящён анализу динамики акций выбранных компаний (GAZP, NVDA, SBER, TSLA, YNDX) за последние три года. Целью проекта является изучение ценовых трендов, объемов торгов и индикаторов технического анализа, таких как скользящие средние и индикатор относительной силы (RSI), для оценки инвестиционного потенциала и принятия обоснованных торговых решений.

### Источник данных
Данные были загружены с сайта finam.ru, с параметрами: Интервал - 3 года, периодичность - 1 день.

### Методология
- Загрузка данных: Собраны и объединены в единый датафрейм данные по акциям пяти тикеров за указанный период времени.
- Предобработка данных: Выполнена стандартизация заголовков, преобразование типов данных, обработка пропусков.
- Анализ данных: Построены графики динамики цен закрытия, рассчитаны и визуализированы скользящие средние (SMA и EMA) и индикатор RSI. Исследованы дни с максимальными изменениями цен и объемы торгов.
- Функции для анализа: Разработаны и реализованы функции для генерации графиков цен с скользящими средними и индикатором RSI.

### Результаты
1. Выявлены тренды изменения цен на акции избранных компаний.
2. Определены дни с максимальными колебаниями цен.
3. Рассчитаны и проанализированы скользящие средние и индикатор RSI для оценки текущего состояния акций (перекупленность/перепроданность).
4. Проведен анализ объемов торгов, выявлены аномалии и важные периоды активности инвесторов.

### Использованные инструменты
- Язык программирования: Python
- Библиотеки: Pandas для обработки и анализа данных, Matplotlib и Seaborn для визуализации данных.

### Заключение
Проект демонстрирует применение базовых и продвинутых методик анализа финансовых данных для исследования акций. Результаты анализа могут быть использованы для принятия решений в сфере инвестирования и торговли на фондовом рынке.
