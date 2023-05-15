# Pacemaker - Александр Шевцов
![image](https://github.com/aztecprod/Pacemaker/assets/25949605/41eb7e93-673b-4c10-80e1-30c1c575eeba)
Pacemaker - это менеджер ресурсов кластера , функциями которого являются:
1)	Обнаружение и восстановление сбоев на уровне узлов и сервисов;
2)	Независимость от подсистемы хранения: общий диск не требуется;
3)	Независимость от типов ресурсов: все, что может быть заскриптовано, может быть кластеризовано;
4)	Поддержка STONITH
5)	Автоматическая репликация конфига на все узлы кластера;
6)	Поддержка расширенных типов ресурсов: клонов (запущен на множестве узлов) и с дополнительными состояниями (master/slave и т.п.);

![image](https://github.com/aztecprod/Pacemaker/assets/25949605/7fce498d-1f5e-4ca2-897c-8662055526ec)

Corosync - программный продукт, позволяющий реализовать кластер
серверов. Его основное назначение — знать и передавать состояние всех участников кластера.
Функции:
● отслеживание состояния приложений;
● оповещение приложений о смене активной ноды кластера;
● отправка одинаковых сообщений процессам на всех узлах
кластера;
● предоставление доступа к базе данных с конфигурацией и
статистикой, а также отправка уведомлений о ее изменениях.
![image](https://github.com/aztecprod/Pacemaker/assets/25949605/a91fbf8e-1b38-4607-8bbb-0aa61445a611)
![image](https://github.com/aztecprod/Pacemaker/assets/25949605/cf297319-ea85-4cc0-8e77-be5e1ddb2e77)
![image](https://github.com/aztecprod/Pacemaker/assets/25949605/50e12c16-a73a-4900-8be6-3f5d02b5751c)
