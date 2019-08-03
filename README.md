# Test1 RxJava ABBYY

Пусть требуется отобразить уровень заряда батареи и статус зарядки пользователю. Необходимо реализовать кастомный реактивный поток данных, который сперва эмитит текущее состояние батареи, а затем эмитит новые состояния при изменении уровня заряда или при подключении/отключении зарядного устройства.
Референсы: BroadcastReceiver, BatteryManager, sticky intent, Observable#create.
Плюсом будет создание универсального решения для работы с broadcast сообщениями в реактивном стиле.
