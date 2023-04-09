
**SpaceXApp**

SpaceXApp - это приложение, которое предоставляет информацию о космических ракетах компании SpaceX и список запусков.
  
&nbsp; 
**Содержание**

-   Требования
-   Установка
-   Как использовать
-   Тестирование
-   Архитектура
-   Дополнительная информация


**Требования**

-   Xcode версия 11.0 или новее
-   iOS версия 13.0 или новее
-   Swift версия 5.0 или новее
-   Kingfisher - для работы с изображениями ([https://github.com/onevcat/Kingfisher](https://github.com/onevcat/Kingfisher))


**Установка**

1.  Склонируйте репозиторий:
git clone https://github.com/yourusername/SpaceXApp.git

1.  Откройте файл SpaceXApp.xcworkspace или SpaceXApp.xcodeproj в Xcode.
2.  Убедитесь, что выбрана правильная схема сборки (Build Scheme) и устройство.
3.  Запустите приложение на симуляторе или реальном устройстве.


**Как использовать**

Приложение состоит из трёх экранов:

1.  Ракета: на этом экране отображается информация о ракетах компании SpaceX.
2.  Запуски: на этом экране представлен список запусков космических ракет SpaceX.
3.  Настройки: на этом экране пользователь может настроить предпочтения приложения.


**Тестирование**

Для запуска unit-тестов выполните следующие шаги:

1.  В Xcode выберите схему сборки SpaceXAppTests.
2.  Запустите тесты, нажав Cmd+U или выбрав в меню Product > Test.


**Архитектура**

Приложение использует архитектуру MVP (Model-View-Presenter), что облегчает тестирование и обеспечивает чистую разделение между UI и бизнес-логикой.


**Дополнительная информация**

Это приложение является тестовым заданием компании Контур, 2022г. 
