### Builder

Строитель - пошаговое создание продуктов или конфигурация сложных объектов.

Признаки применения паттерна: Строителя можно узнать в классе, который имеет один создающий метод и несколько методов настройки создаваемого продукта. Обычно, методы настройки вызывают для удобства цепочкой (например, someBuilder->setValueA(1)->setValueB(2)->create()) если нет директора который делает все нужные действия. Директор нужен не всегда. См. пример без директора