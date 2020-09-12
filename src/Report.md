# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10.09.2020 было проведено тестирование документации, тестирование установки, функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявленны дефекты:
* [Credit Card Number Validator не распознает 19-значные номера карт VISA, JCB, Discover.](https://github.com/Dmitrii4/Task-2-Credit-Card-Number-Validator/issues/1)
* [Credit Card Number Validator не распознает номера карт Diners Club - Carte Blanche.](https://github.com/Dmitrii4/Task-2-Credit-Card-Number-Validator/issues/2)
* [Credit Card Number Validator не распознает номера карт Diners Club Internation.](https://github.com/Dmitrii4/Task-2-Credit-Card-Number-Validator/issues/4)
* [Credit Card Number Validator не распознает номера карт American Express.](https://github.com/Dmitrii4/Task-2-Credit-Card-Number-Validator/issues/3)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* Руководство по установке IntelliJ IDEA

## В качестве тестовых данных использовались данные с этого [сайта](freeformatter.com):

* VISA:
4716649813947141
4539321175578329
4539814090534167929
* MasterCard:
2720990549290861
5372452463867855
5542216063519256
* American Express (AMEX):
371969655455050
373122472787614
340970133558893
* Discover:
6011176871078657
6011820503739596
6011577915703651623
* JCB:
3533572359381629
3540133200342459
3589450263033972504
* Diners Club - North America:
5457770868609574
5508418425558590
5594626055836251
* Diners Club - Carte Blanche:
30219073819278
30550318548631
30557842979489
* Diners Club - International:
36724362192448
36745594816397
36222608525083
* Maestro:
6761858089063322
6304077075648327
5038455680407112
* Visa Electron:
4026323100241569
4508562402440596
4844596292449310
* InstaPayment:
6387898324462347
6382724585505456
6379276073151785

**Тестирование производилось в следующем окружении:**
* Windows 7 x64
* IntelliJ IDEA 2020.2.1
* openjdk version "11.0.8" 2020-07-14 OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10) OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
