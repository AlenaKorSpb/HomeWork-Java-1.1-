# Отчёт о тестировании 
Проверка инструкци по установке приложения OpenJDK 11 и её совместимость с Java 11


## Краткое описание 
Приложение легко устанавливается,совместимо с Java 11, но работает не так,как описано в документации (не корректно отвечает по валидным и невалидным ключам)

10.08.2020 - 12.08.2020 было проведено функциональное тестирование приложения OpenJDK 11

На тестирование затрачено: 8 часов

В результате тестирования выявлены следующие дефекты:
* https://github.com/AlenaKorSpb/HomeWork-Java-1.1-/issues/1
* https://github.com/AlenaKorSpb/HomeWork-Java-1.1-/issues/2

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* TestCase 
* Bag-report
* Отчет о тестировании

В качестве тестовых данных использовались данные приложения KeyValidator:
###  Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180


###  Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* 6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1


### Тестирование производилось в следующем окружении:

* Устройство: DESKTOP-MUBS610
* Браузер: Chrome (Windows 10)
