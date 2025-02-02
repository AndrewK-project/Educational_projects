## Проектная работа по Основам машинного обучения

## "Рекоммендации тарифов оператора мобильной связи «Мегалайн»"

### Описание проекта
В нашем распоряжении данные о поведении клиентов, которые уже перешли на рекоммендуемые тарифы. Построим модель для задачи классификации, которая сама выберет подходящий тариф для будущих клиентов мобильного оператора. Построим модель с максимально большим значением accuracy (точность) и доведем долю правильных ответов по крайней мере до 0.75. Проверим accuracy на тестовой выборке самостоятельно.

### Описание входных данных
- 'сalls' — количество звонков,
- 'minutes' — суммарная длительность звонков в минутах,
- 'messages' — количество sms-сообщений,
- 'mb_used' — израсходованный интернет-трафик в Мб,
- 'is_ultra' — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

### Использованные библиотеки Python
- pandas
- sklearn.tree - DecisionTreeRegressor
- sklearn.tree - DecisionTreeClassifier
- sklearn.ensemble - RandomForestClassifier
- sklearn.model_selection - train_test_split
- sklearn.metrics - mean_squared_error
- sklearn.ensemble - RandomForestRegressor
- sklearn.linear_model - LinearRegression
- sklearn.linear_model - LogisticRegression
- sklearn.metrics - accuracy_score