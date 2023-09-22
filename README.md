# SELINUX
___
<b>Цель задания</b>
<p>Диагностировать проблемы и модифицировать политики SELinux для корректной работы приложений, если это требуется</p>

___

<b>Описание задания</b>
1. Запустить nginx на нестандартном порту 3-мя разными способами:
    * переключатели setsebool;
    * добавление нестандартного порта в имеющийся тип;
    * формирование и установка модуля SELinux.
2. Обеспечить работоспособность приложения при включенном selinux.
    * развернуть приложенный стенд https://github.com/mbfx/otus-linux-adm/tree/master/selinux_dns_problems;
    * выяснить причину неработоспособности механизма обновления зоны (см. README);
    * предложить решение (или решения) для данной проблемы;
    * выбрать одно из решений для реализации, предварительно обосновав выбор;
    * реализовать выбранное решение и продемонстрировать его работоспособность

1.1 Переключатели setsebool
![img_1](https://github.com/Arkady1996/selinux/blob/main/images/1.1.png)
![img_2](https://github.com/Arkady1996/selinux/blob/main/images/1.2.png)
![img_3](https://github.com/Arkady1996/selinux/blob/main/images/1.3.png)
![img_4](https://github.com/Arkady1996/selinux/blob/main/images/1.4.png)

1.2 Добавление нестандартного порта в имеющийся тип
![img_5](https://github.com/Arkady1996/selinux/blob/main/images/2.1.png))
![img_6](https://github.com/Arkady1996/selinux/blob/main/images/2.2.png)

1.3 формирование и установка модуля SELinux
![img_7](https://github.com/Arkady1996/selinux/blob/main/images/3.1.png)
![img_8](https://github.com/Arkady1996/selinux/blob/main/images/3.2.png)

2.1 Обеспечить работоспособность приложения при включенном selinux
![img_9](https://github.com/Arkady1996/selinux/blob/main/images/4.1.png)
![img_10](https://github.com/Arkady1996/selinux/blob/main/images/4.2.png)
![img_11](https://github.com/Arkady1996/selinux/blob/main/images/4.3.png)
![img_12](https://github.com/Arkady1996/selinux/blob/main/images/4.4.png)
