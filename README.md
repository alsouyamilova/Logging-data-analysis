# Анализ каротажных данных

Данные от заказчика часто приходят в неструктурированном или частично
структурированном виде. Поэтому первым шагом в работе с данными является их тщательный
анализ. Данный проект заключается в обработке открытого датасета Volve, содержащего реальные данные, собранные при разработке и эксплуатации одноименного месторождения.
Данные предоставлены платформой Changellenge в рамках виртуальной IT-стажировки "Аналитик данных".

**Описание задачи**

Помочь компании разобраться с данными, получаемыми из скважин при
бурении и проведении геофизических исследований, чтобы извлечь как можно
больше информации о строении разрабатываемого месторождения. В качестве
младшего аналитика данных необходимо провести разведочный анализ данных и
дать свои рекомендации.

**План работы для проведения EDA**
+ Пройти по всем папкам в архиве и ознакомиться с их содержимым.
+ Собрать Pandas DataFrame
+ Оценить полноту данных через долю отсутствующих значений по каждому каналу сбора
информации и скважине
+ Предложить мероприятия по работе с пропущенными значениями
+ Почистить выбросы
+ Визуализировать каротажные данные

Из всего многообразия материалов в папках используются только файлы каротажей с
расширениями DLIS, LAS, LIS, LTI.<br>
Код проекта представлен в файле *EDA logging data.ipynb*
