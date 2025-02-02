## Итоговая проектная работа по Построению модели машинного обучения

## "Подготовка прототипа модели машинного обучения для эффективной работы промышленных предприятий"

### Описание проекта
Подготовка прототипа модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении данные с параметрами добычи и очистки. 
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

### Описание входных данных
Данные находятся в трёх файлах:
- gold_recovery_train_new.csv — обучающая выборка;
- gold_recovery_test_new.csv — тестовая выборка;
- gold_recovery_full_new.csv — исходные данные.

Технологический процесс
- Rougher feed — исходное сырье
- Rougher additions (или reagent additions) — флотационные реагенты: Xanthate, Sulphate, Depressant
- Xanthate — ксантогенат (промотер, или активатор флотации);
- Sulphate — сульфат (на данном производстве сульфид натрия);
- Depressant — депрессант (силикат натрия).
- Rougher process (англ. «грубый процесс») — флотация
- Rougher tails — отвальные хвосты
- Float banks — флотационная установка
- Cleaner process — очистка
- Rougher Au — черновой концентрат золота
- Final Au — финальный концентрат золота

Параметры этапов
- air amount — объём воздуха
- fluid levels — уровень жидкости
- feed size — размер гранул сырья
- feed rate — скорость подачи
- 
### Использованные библиотеки Python
- pandas
- sklearn.model_selection - train_test_split
- matplotlib - pyplot
- sklearn.linear_model - LinearRegression
- sklearn.model_selection - cross_val_score
- sklearn.tree - DecisionTreeRegressor
- sklearn.ensemble - RandomForestRegressor
- sklearn.model_selection - GridSearchCV
- sklearn.metrics - make_scorer
- sklearn.dummy - DummyRegressor
- sklearn.metrics - mean_absolute_error
- warnings
- seaborn
- numpy