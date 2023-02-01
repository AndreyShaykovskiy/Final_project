# Final_project
####    Представьте, что вы работаете в компании, которая разрабатывает мобильные игры. К вам пришел менеджер с рядом задач по исследованию нескольких аспектов мобильного приложения:
 1) В первую очередь, его интересует показатель retention. Напишите функцию для его подсчета.
 2) Помимо этого, в компании провели A/B тестирование наборов акционных предложений. На основе имеющихся данных определите, какой набор можно считать лучшим и на основе каких метрик стоит принять правильное решение.
 3) Предложите метрики для оценки результатов последнего прошедшего тематического события в игре.


Написав функцию для расчета retencion получаю данный heatmap:
![2023-02-01_23-52-44](https://user-images.githubusercontent.com/122619433/216161312-311c001a-2310-4e0e-8f10-e2a860f85051.png)

### Задание 2
Имеются результаты A/B теста, в котором двум группам пользователей предлагались различные наборы акционных предложений. Известно, что ARPU в тестовой группе выше на 5%, чем в контрольной. При этом в контрольной группе 1928 игроков из 202103 оказались платящими, а в тестовой – 1805 из 202667.

Какой набор предложений можно считать лучшим? Какие метрики стоит проанализировать для принятия правильного решения и как?

посмотрим на распределение чеков в тестовой группе а и b
![2023-02-01_23-58-41](https://user-images.githubusercontent.com/122619433/216161966-4f7a2540-d5db-4011-9b22-6691c468676d.png)
![2023-02-01_23-59-17](https://user-images.githubusercontent.com/122619433/216162102-91cbf1ad-625a-496a-a43a-4e5f09fdd44c.png)

