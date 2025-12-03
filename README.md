# faq


Запуск программы только с правами администратора C++ 
https://learn.microsoft.com/en-us/cpp/build/reference/manifestuac-embeds-uac-information-in-manifest?redirectedfrom=MSDN&view=msvc-170

Отключение нумерации списков Word
https://office-guru.ru/word/kak-otklyuchit-avtomaticheskoe-sozdanie-numerovannyh-spiskov-v-word-2013-82.html

Настройки json файлов vscode
https://code.visualstudio.com/docs/editor/variables-reference

Настройка принтера
https://printerp.ru/info/kak-ustanovit-printer-bez-diska.html

Mingw64
https://osdn.net/projects/sfnet_mingw-w64/releases/

Проблема с gcc
https://stackoverflow.com/questions/62600341/how-to-tell-gcc-to-not-align-function-parameters-on-the-stack

Тестирование утечек памяти
https://ru.m.wikipedia.org/wiki/Valgrind

Работа с git for vscode
https://codelab.pro/kak-podklyuchit-github-k-visual-studio-code/
https://codelab.pro/video/kak-podklyuchit-github-k-visual-studio-code/

Работа с git bash
https://www.youtube.com/watch?v=zZBiln_2FhM&ab_channel=%D0%92%D0%BB%D0%B0%D0%B4%D0%B8%D0%BB%D0%B5%D0%BD%D0%9C%D0%B8%D0%BD%D0%B8%D0%BD

Откат к commit'ам
https://www.youtube.com/watch?v=NMh4u5tyDC4&ab_channel=ITDoctor

Переназначение клавиш 
https://github.com/microsoft/PowerToys/releases/tag/v0.74.1

Установка TEX for VScode 
https://www.youtube.com/watch?v=4lyHIQl4VM8&t=1s&ab_channel=FedericoTartarini

Переопределение приложений контекстного меню(открыть с помощью)
https://it-tehnik.ru/windows10/ispolzovanie/redaktirovat-kontekstnoe-menyu.html

Открыть с помощью Android Studio
https://stackoverflow.com/questions/61036255/open-folder-as-android-studio-project

Как изменить цвет шрифта в Obsidian 
https://talk.macpowerusers.com/t/modifying-fonts-in-obsidian-themes/22151

VScode для всех пользователей 
https://stackoverflow.com/questions/52677564/install-vscode-for-all-users

Мои темы VScode
https://vscodethemes.com/e/lkytal.flatui/flatui-dark?language=javascript
https://vscodethemes.com/e/avzcp4.vuewave/vuewave?language=javascript

Активация Windows
```cpp
system("slmgr /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99");
system("slmgr /skms kms8.msguides.com");
system("slmgr /ato");
```

WinDirStat, чтобы определить очаг загрязнения 

Развертывание офиса
https://learn.microsoft.com/en-us/deployoffice/ltsc2021/deploy
https://www.microsoft.com/en-us/download/details.aspx?id=49117

Скачать 365
https://www.microsoft.com/en-us/download/details.aspx?id=49117

Активация Office 2021
https://vk.com/video-168585760_456239180
это файл `.cmd` 
```c
@echo off
title Aktivator Microsoft Office 2021&cls&(if exist "%ProgramFiles%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles%\Microsoft Office\Office16")&(if exist "%ProgramFiles(x86)%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles(x86)%\Microsoft Office\Office16")&(for /f %%x in ('dir /b ..\root\Licenses16\ProPlus2021VL_KMS*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%%x" >nul)&echo Office naiden, aktivatsija...&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo ospp.vbs /setprt:1688 >nul&cscript //nologo ospp.vbs /unpkey:6F7TH >nul&set i=1&cscript //nologo ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH >nul||goto notsupported
:skms
if %i% GTR 10 goto busy
if %i% EQU 1 set KMS=104.244.78.23
if %i% EQU 2 set KMS=kms8.MSGuides.com
if %i% EQU 3 set KMS=s9.us.to
if %i% GTR 3 goto ato
cscript //nologo ospp.vbs /sethst:%KMS% >nul
:ato
cscript //nologo ospp.vbs /act | find /i "successful" && (echo Office yspeshno aktivirovan! Nazhmi lubyu klavishu, chtobi viiti. Bydy rad vashemy otzivy! S uvageniem Bakharev) || (echo Ne udalos soedinitsa s serverom. Fail tochno zapyshen ot imeni administratora? Soedinjaus s drygim serverom...& set /a i+=1 & goto skms)
goto halt
:notsupported
echo Office ne naiden. On tochno ystanovlen? Versija tochno 2021? Napishite ob etom v teme.&goto halt
:busy
echo Fail tochno zapyshen ot imeni administratora?????? Napishite v teme, esli problema ne v etom.
:halt
pause >nul
```

Удалить элемент из автозагрузки
https://ichip.ru/sovety/ekspluataciya/kak-udalit-programmu-iz-avtozagruzki-windows-10-ili-dobavit-v-nee-704372


Linux rice - типо интерфейс для линукса 

MacOS ISO
https://shaadlife.com/download-macos-ventura-iso-file/

Библиотеки Kotlin
https://github.com/JetBrains/kotlin/blob/master/libraries/stdlib/src/kotlin/collections/Collections.kt

Собрать свой moodle / мудл
https://hub.docker.com/r/bitnami/moodle

Приложение не установлено 
https://startandroid.ru/ru/uroki/vse-uroki-spiskom/223-urok-124-chto-takoe-package-dlja-prilozhenija.html

Красивые стрелочки
https://tproger.ru/experts/plugins-for-ide

Restart activity  Перезагрузить приложение
https://gist.github.com/easterapps/7127ce0749cfce2edf083e55b6eecec5

Реклама в приложениях / Убрать рекламу в приложениях 
https://androidinsider.ru/polezno-znat/kak-ubrat-reklamu-v-prilozheniyah-na-android-3-luchshih-sposoba.html/amp

Release APK / Релиз 
https://www.youtube.com/watch?v=WPScAR_UPDE&ab_channel=BoostMyTool

ICO / иконка для Android / mipmap
https://www.youtube.com/watch?v=skRXfroPhGg&ab_channel=%D0%91%D1%83%D0%BB%D0%B0%D1%85%D0%A1%D0%B5%D1%80%D0%B3%D0%B5%D0%B9
png 512\*512 

Крутая камера для Windows 
https://www.youtube.com/watch?v=gde7-EF9Msg

Latex in VScode 
https://dsc.sgu.ru/helpful/latex/
еще может помочь https://mathjiajia.github.io/vscode-and-latex/

KSP ksp 
https://developer.android.com/build/migrate-to-ksp#kts

SQL
https://gist.github.com/sagarnayak/3e49055f47d1403c5f365b4dfedcba96


TextField textfield изменить цвет курсора и выделения 
https://stackoverflow.com/questions/76479701/android-jetpack-compose-cannot-change-basictextfield-cursor-thumb-color

TimePicker 
[Jetpack Compose Time Picker (Material 3) (jetpackcomposeworld.com)](https://jetpackcomposeworld.com/jetpack-compose-time-picker-material-3/)


Перейти на определенную строку
Windows: `Ctrl + G`


Скопировать путь 
https://www.reddit.com/r/gnome/comments/wcvph1/easiest_way_to_copy_a_filepath_in_nautilus/


VSCode перенос строк 
alt+Z 
[Как включить перенос слов в Visual Studio Code? - Stack Overflow на русском](https://ru.stackoverflow.com/questions/1505697/%D0%9A%D0%B0%D0%BA-%D0%B2%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%8C-%D0%BF%D0%B5%D1%80%D0%B5%D0%BD%D0%BE%D1%81-%D1%81%D0%BB%D0%BE%D0%B2-%D0%B2-visual-studio-code#:~:text=%D0%9F%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8%2C%20%D0%B8%D0%BB%D0%B8%20%D1%80%D0%B0%D0%B7%D1%80%D1%8B%D0%B2%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8,%D1%8D%D1%82%D0%BE%20%D0%BE%D1%81%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%BB%D1%8F%D0%B5%D1%82%D1%81%D1%8F%20%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D1%88%D0%B5%D0%B9%20%D0%B2%D0%B2%D0%BE%D0%B4%D0%B0%20Enter.)

Скачать видео с ютуба 
[Y2meta.app Converter Button for Google Chrome](https://y2meta.app/help/y2meta-converter-button-for-google-chrome)

Как поменять поисковую систему Edge 
https://yandex.ru/video/preview/8451099760366721741

Конфигурация .vscode     Linux&Windows
Linux
https://code.visualstudio.com/docs/cpp/config-linux
Windows
https://code.visualstudio.com/docs/cpp/config-mingw

Монтирование флешек 
https://losst.pro/formatirovanie-fleshki-v-linux


Чтобы при открытии Android Studio не открывались ранее открытые проекты, вы можете изменить настройки среды разработки. Вот как это сделать:
1. Откройте Android Studio.
2. Перейдите в меню `File` -> `Settings` (или `Android Studio` -> `Preferences` для macOS).
3. В открывшемся окне перейдите в раздел `Appearance & Behavior` -> `System Settings`.
4. Снимите галочку с пункта `Reopen last project on startup`.


paplay 
https://www.baeldung.com/linux/pc-speaker-beep-in-linux


отключить горячий углы 
```bash 
gsettings set org.gnome.desktop.interface enable-hot-corners false
```

**Исключение файлов во время отладки с помощью gdb:**
- Добавьте следующий раздел в файл `launch.json` в параметр `setupCommands`:
    ```json
    "setupCommands": [
        {
            "description": "Skip library files",
            "text": "-interpreter-exec console \"skip -gfi **/bits/*.h\""
        }
    ]
    ```

Линукс спящий режим 
https://fostips.com/automatic-suspend-idle-time-less-15-min-ubuntu-fedora-debian/


Dev containers runs wsl during starting vscode
Dev contaienrs запускает wsl при старте vscode
Отключить
![alt text](image.png)
