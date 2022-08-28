# Raspberry-Pico-MicroPython-Nokia5110
Коды на MicroPython для Raspberry Pico
Содержит таблицу знаков для англйского и русского языков размер шрифта 8х13
Функции инициализации SPI, знакогенератор передающий данные на дисплей Nokia5110.
Оснван на  https://github.com/mcauser/micropython-pcd8544 автора  mcauser за что ему большое спасибо.

Подключение: Испозьзуется SPI0
Nokia5110: 	RST --> GP2  
						CE  --> GP5
						DC  --> GP4
						CE  --> GP5
						DIN --> GP7
						CIK --> GP6
						VCC --> 3.3V
						BL(Light) --> GP3
						GND --> GND
