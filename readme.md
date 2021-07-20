# Отчёт о тестировании IntelliJ IDEA
## Краткое описание

#### 19.07.21 - 20.07.21 было проведено тестирование установки и санитарное тестирование приложения IntelliJ IDEA.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* https://github.com/SvetlanaKS/HWJava1/issues/1#issue-948477144
* https://github.com/SvetlanaKS/HWJava1/issues/2#issue-948490538


## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:
* Баг-репорты
* Отчет о тестировании


В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:

VISA:
* 4485414038086079 Result is OK
* 4539146343341973 Result is OK
* 4539625049648685639 Result is FAIL

MasterCard:
* 2720991705002611 Result is OK
* 5567499044173233 Result is OK

Discover:
* 6011321412455630 Result is OK
* 6011989581778105 Result is OK
* 6011067803549177879 Result is FAIL

## Тестирование производилось в следующем окружении:
* Windows 10 Pro версия 21H1 64-разрядная операционная система,процессор x64
* Java version "11.0.11" 2021-04-20
