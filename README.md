# Автоматический анализ мнений о кофейнях

Предлагаются выводы об уровне удовлетворенности клиентов, основанные на анализе тональности отзывов, визуализациях количественных переменных, анализе мнений и машинном обучении. Информация может быть полезна владельцам и менеджерам заведений.

**Цель проекта** — количественно оценить уровень удовлетворенности клиентов и выявить области для улучшения в бизнесе.

Отзывы, оценки и даты публикации извлечены из Yandex maps, предобработка текстовых и других данных осуществлена стандартными методами.

Анализ тональности проводится с использованием методов обработки естественного языка (NLP). Я использовала предобученные модели, такие как RoBERTa, для анализа тональности отзывов. Модели классифицируют тональность каждого отзыва как положительную, отрицательную или нейтральную и выводят соответствующие оценки вероятности данного класса.

Проект включает визуализации для анализа количественных и текстовых переменных. Составлены облака слов, рассчитаны и проанализированы такие метрики, как SOV (Share of Voice) и NPS (Net Promoter Score), чтобы оценить лояльность и удовлетворенность клиентов.

В проекте также применяются методы Opinion Mining для консолидации информации из множества отзывов. Идентифицируются аспекты, которые клиенты учитывают при выборе кофейни, и анализируется общая тональность для каждого аспекта.

Кроме того, в качестве альтернативного метода демонстрируются возможности машинного обучения, в частности логистической регрессии, для прогнозирования тональности на основе текста. 
Модель обучается на предобработанных парах отзыв-рейтинг: показатель точности для задачи бинарной классификации более 85%.

## Выводы, основанные на анализе тональностей отзывов и метриках SOV и NPS

### **Star Hit**:
Star Hit демонстрирует впечатляющие результаты с высокой удовлетворенностью клиентов. Основные преимущества включают:

— Создание **уютной атмосферы** и предложение вкусных блюд.

— Доступная ценовая политика при высоком качестве привлекает клиентов и способствует лояльности.

Однако, есть несколько моментов для улучшения:

— Конкретные блюда: В отрицательных отзывах упоминаются вафли и чизкейк. Необходимо проанализировать эти аспекты и понять, что можно улучшить в этих блюдах, чтобы повысить удовлетворенность клиентов.

### **Surf**:
Surf привлекает клиентов следующими аспектами:

— Предложение **широкого выбора блюд** и уютная **атмосфера**.

— Дворик и удобное расположение - одни из наиболее привлекательных особенностей для клиентов заведения.

Вместе с тем, есть несколько моментов, которые требуют внимания владельцев:

— Ценовая политика: Отзывы указывают на **сравнительно высокие цены**, что может быть фактором, влияющим на лояльность клиентов. Необходимо найти баланс между ценами и качеством, чтобы обеспечить доступность для более широкой аудитории.

— Обслуживание и качество: Медленное обслуживание и **несоответствие качества некоторых блюд цене** - проблемы, которые время от времени указывают в отзывах

### **Prime**:
Клиентов особенно привлекают **доступные цены** и **блюда национальной кухни**. 

Анализ также выявил несколько проблем, которые могут влиять на удовлетворенность клиентов.

— Упоминания о кассире и размерах порций в отрицательных отзывах указывают на необходимость обеспечить более точное соответствие ожиданиям клиентов.

— Проблемы с качеством продуктов требуют немедленного внимания: свежесть и качество

