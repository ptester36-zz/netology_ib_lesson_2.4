# **Задача №1**

## **Вопрос №1**:

Сколько уровней безопасности предусмотрено?

**Ответ**:

Всего уровней безопасности шесть

## **Вопрос №2**:

Как вы думаете, зачем и исходя из чего выполнено разбиение на эти уровни?

**Ответ**:

Разбиение выполнено на уровни как рубежи защиты, и предназначены для предотвращения НСД злоумышленником. Если злоумышленник пройдет один уровень, его может задержать второй и так далее (Цель задержать или недопустить).

## **Вопрос №3**:

Опишите, какие меры безопасности предпринимаются и предположите для каких сценариев (это должно быть явно видно из принимаемых мер)

**Ответ**:

* На первом уровне: Это вывески, ограждения - указывает на границы собственности

* На втором уровне: Это входные ворота, видеонаблюдение, круглосуточное патрулирование и не только - все это необходимо для контроля территории от несанкционированного проникновения.

* На третьем уровне: Доступ в здание по RFID картам, сотрудник СБ вручную проверяет владельца карты, аутентификация радужной оболочки глаза, и не только - все это необходимо для проверки доступа конкретного субьекта в здание, является ли держатель карты сотрудником имеющим доступ или же это злоумышленник.

* На четвертом уровне: Операционный центр безопасности - это мозг системы безопасности. Здесь происходит контроль дверей, камер, считывателей карт RFID (значков), сканирование радужной оболочки глаза. Сотрудники работающие на данном периметре безопасности должны улавливать что то необычное, то что может быть пропущено уровнями 1,2 и 3.

* На пятом уровне: Этаж Дата - Центра. Доступ максимально ограничен, и открыт только по мере необходимости техникам и инженерам для проведения работ. В Дата - Центре находится оборудование для хранения данных клиентов в зашифрованном виде. Такое сильное ограничение обусловленно тем, что компания защищает конфиденциальность и безопасность данных своих клиентов, для компании это наивысший приоритет. 

* На шестом уровне: Диски стираются и уничтожаются, когда их ресурс был отработан и они заменяются на новые. Доступ ограничен настолько, что только один техник, который назначен в комнату может находится там, а диски передаются через двухсторонник шкаф. Такие ограничения обусловлены тем, что на дисках хранится информация которая не должна быть скопирована/восстановлена, а диски не должны быть повторно использованы или похищены, поэтому они проходят через машину дробления.

P.S.

Так же Google Cloud есть еще две программы тестирования средств защиты: Первая система направлена на тестирования периметра площадки дата - центра извне. Вторая система направлена на тестирование протоколов безопасности изнутри.

При выходе с этажа ЦОД каждый сотрудник проходит полное обнаружение на металл, через рамочный металлодетектор. 