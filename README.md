# OLTA PCB CNC Laser

<p align="center">
 <img width="700px" src="src/Перед.jpg" alt="qr"/>
</p>

<p align="center">
 <img width="700px" src="src/Зад.jpg" alt="qr"/>
</p>

Проект можно описать следующей структурой:
1. [Кинематика](https://github.com/ufrs12/OLTA-PCB-CNC-Laser/tree/main/Cinematics)  
   -- Станина  
   -- Верхняя ось (X)  
   -- Нижняя ось (Y)  
2. Электроника  
   -- Модуль контроллера ESP32  
   -- Шильд модуля контроллера  
   -- CNC Shield V4  
   -- Два драйвера шаговых двигателей  
   -- Четыре щелевых оптопары 
3. Софт  
   -- Прошивка FluidNC (Hardware)  
   -- Конфигурационный файл FluidNC (Hardware)  
   -- Сендер (Software)  
   -- CAM  (Software)
4. [Лазерный модуль](https://github.com/ufrs12/OLTA-PCB-CNC-Laser/tree/main/Laser)
5. Тестовые и настроечные G-коды.

Характеристики:
- Габариты (Г/Ш/В)) - 200/200/200 мм.
- Рабочее поле - 50/100 мм (Потенциально можно увеличить до 100/100 мм, заменив нижнюю ось)
- Ускорение по X - 1000 мм в минуту за секунду
