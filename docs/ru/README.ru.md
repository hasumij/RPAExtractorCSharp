# Solicen.RPAExtractorCSharp

[**Englsih**](/README.md) | [**Русский**](./docs/ru/README.ru.md)

Сделано с ❤️ для **всех** переводчиков и разработчиков переводов.

Это скрипт/инструмент для извлечения файлов из архива формата **RPA** с помощью движка визуальных новинок [`Ren'Py`](https://www.renpy.org). В отличие от своих предшественников в качестве [unRPA](https://github.com/Lattyware/unrpa), он написан на чистом C# *(CSharp)* без использования частей Python в единной строке кода.

## Использование:
* Загрузите исходный код. И скопируйте/вставьте файлы `.cs` из папки `/src` в свой проект. 
    И используйте это в своем проекте, коде или программе с помощью:
    ```csharp
    using Solicen.RenPy
    Archive.ExtractArchive("path_to_RPA");
    ```
*  Или [загрузите]() программу командной строки для извлечения файлов из **RPA** архивов.

## Ваш вклад:
* Вы можете создать свой собственный форк этого проекта и внести свой вклад в его развитие.
* Вы также можете внести свой вклад через вкладки [`Issues`]() и [`Pull Request`](), предложив свои изменения кода. И дальнейшее развитие проекта. 

## Будущее проекта:
Исходное состояние кода и проекта включало добавление файлов в архивы `RPA`, а также создание архива `RPA` на основе файлов, чтобы исключить использование `unRPA` в проектах CSharp. 

Однако первоначальные разработчики: [Денис Солисен](https://github.com/DenisSolicen) и [SAn4Es-TV](https://github.com/SAn4Es-TV) не нашли хорошего решения для того, чтобы упаковать архивы обратно, поскольку для этого потребовалось бы использовать части кода на Python, что полностью противоречит первоначальной идее проекта.

## Все права защищены нами за Вами 
Вы можете использовать этот проект/сценарий в любом месте, где захотите, с указанием авторства ([Денис Солисен](https://github.com/DenisSolicen) и [SAn4Es-TV](https://github.com/SAn4Es-TV)) в соответствии с лицензией MIT. Вы также можете свободно изменять этот проект, создавать форки и взаимодействовать с исходным кодом любым способом, чтобы продолжить и улучшить проект после нас.

---
Мы выражаем нашу огромную благодарность автору `unRPA` за открытый исходный код, на основе которого был создан этот проект на языке CSharp.