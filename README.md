![image](https://github.com/AlexanderSchelokov/coursework_network_engineer/assets/121572590/367131f1-2ebb-4e8f-b6f5-48234e7c75c9)

Тестирование
ПК сегмента производственного отдела, гостевого Wi-Fi и имеют доступ в сеть интернет.
![image](https://github.com/AlexanderSchelokov/coursework_network_engineer/assets/121572590/85681cdf-e556-4d4e-bf57-e1ce9395bbb3)
![image](https://github.com/AlexanderSchelokov/coursework_network_engineer/assets/121572590/4d3c8331-5776-47e4-9849-1ce05c7c22ef)

ПК на производстве имеет доступ в интернет и выходит в него через ISP3 (дополнительно приложить вывод traceroute).
![image](https://github.com/AlexanderSchelokov/coursework_network_engineer/assets/121572590/3a18e187-f123-436a-ba08-001770907351)

ПК на производстве имеет доступ к принтерам центрального офиса и сети производства центрального офиса, однако не имеют доступа к сегменту бухгалтерии.

ПК в сегменте гостевого Wi-Fi не имеет доступа к сегменту производственного отдела.
ПК в сегменте бухгалтерии имеют доступ к принтерам.
ПК производственного отдела не может взаимодействовать с ПК из отдела продаж, ИТ отдела и бухгалтерии.
ПК, подключенное в сегмент периферийных устройств, не имеет доступа в интернет.
Провести тестирование используемых механизмов обеспечения отказоустойчивости. Для каждого из следующих пунктов снять трассировки из точки А в точку Б до начала теста и после отключения одного из элементов сети.

Точка А – ПК в бухгалтерии, точка Б – интернет (3.0.0.2). Отключение ISP1, проверка, что центральный офис перешел на ISP2.
Точка А – ПК в производственном отделе, точка Б – пользователь на производстве. Отключение ISP1, проверка, что связь между офисом и производством не прервалась.
Точка А – ПК в отделе продаж, точка Б – интернет (3.0.0.2). Полное отключение маршрутизатора, к которому подключен ISP1, проверка того, что центральный офис перешел на второй маршрутизатор.
Точка А – ПК в производственном отделе, точка Б – пользователь на производстве. Полное отключение маршрутизатора, к которому подключен ISP1, проверка того, что связь до производства перешла на второй маршрутизатор.
Точка А – ПК в бухгалтерии, точка Б – интернет (3.0.0.2). Отключение устройства, на котором расположены адреса шлюзов по умолчанию для внутренних сетей в центральном офисе. Проверка того, что адрес шлюза стал доступен через резервное устройство.
Точка А – ПК в бухгалтерии, точка Б – интернет (3.0.0.2). Поочередное отключение каждого из линков, подключенных к коммутатору доступа, где расположена точка А. Проверка того, что выход из строя одного из линков не нарушает связность.
ПРИМЕЧАНИЕ. В связи с особенностью эмулятора Packet Tracer, часто бывает так, что для того, чтобы тест заработал, нужно перезагрузить устройства.

