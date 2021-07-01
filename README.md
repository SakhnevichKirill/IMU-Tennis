# IMU_Tennis

Архив с исходниками:
https://drive.google.com/drive/folders/1BADNmSdx3Lb0_9ldPejyhtXjDI3W7DY5?usp=sharing

Ключевые файлы архива:
IMU_Tennis_BT_PC\Assets\_Scripts\BluetoothController.cs - скрипт на c# отвечающий за обработку данных в unity

IMU-Arduino\serialBT\serialBT.ino - скетч для прошивки arduino

markupGUI.py - графическое приложение для разметки полученных данных

csvController.py - графики показывающие результаты интегрирования ускорения

anamalies.py - проверка на аномалии в данных полученных через bluetooth

IMU_Tennis_BT_PCTest_25_06 - данные получены по bluetooth, содержат запись движения "крученый удар справа"

IMU_Tennis_BT_PCTest_01_07 - данные получены по bluetooth, содержат последовательную запись движения "крученый удар справа", "плоский удар справа", "крученый удар справа"

UnityTestWire1 - данные получены по проводу, содержат информацию о скорости и позиции на каждой итерации при послежовательном переходе от состояния покоя к резкому движению

Также приложены скрины построенных графиков по данным из UnityTestWire1