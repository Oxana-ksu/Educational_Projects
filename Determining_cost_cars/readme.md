# Determining_cost_cars

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.

**Заказчику важны:**

- качество предсказания;
- скорость предсказания;
- время обучения.

**Библиотеки, использованные для выполнения проекта:**
- pandas;
- matplotlib;
- lightgbm.

**Вывод:** 
 Проанализировав показатели выбранных моделей, я пришла к выводу, что моделью с допустимым качеством и самой быстрой скоростью лбучения и предсказания, является модель DecisionTreeRegressor, но rsme RandomForestRegressor было в 2 раза ниже, это значительная разница и поэтому в качестве лучшей модели я выбрала случайный лес. Проверка на тестовых данных дала хороший результат

