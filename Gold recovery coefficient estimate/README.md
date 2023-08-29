# Предсказание коэфициента восстановления золота из руды.  

#*Задача* -   
#*Цель* - 

# Использованные инстументы  
## Анализ данных  
**pandas**  
**numpy**  
## Визуализация данных  
**matplotlib**  
**seaborn**  
**shap**  
## Прогнозирование, выбор модели  
sklearn.preprocessing.**StandardScaler**  
sklearn.model_selection.**GridSearchCV**  
sklearn.metrics.**mean_absolute_error**  

sklearn.ensemble.**RandomForestRegressor**  
sklearn.ensemble.**GradientBoostingRegressor**  
sklearn.linear_model.**LinearRegression**  
catboost.**CatBoostRegressor**  

# Общий вывод  
Обучены 4 модели.  
По результатам проверки на тестовой выборке лучше всего себя показала модель **RandomForestRegressor**(Средняя абсолютная ошибка температуры составила 6 градусов).  
Были выявлены наиболее значимые признаки, влияющие на конечную температуру.



