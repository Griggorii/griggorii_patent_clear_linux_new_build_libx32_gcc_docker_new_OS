# griggorii_patent_clear_linux_new_build_libx32_gcc_docker_new_OS
griggorii , patent , clear , linux , new , build , libx32 , gcc , docker , new , nano os api , klibc-wBFLvVtxy4xJqEadIBJMa78iJz8 , klibc-xcgdUApi-P9SoPhW_fi5gXfvWpw , arch.conf , заготовки для новых операционных систем что бы пересобрать весь мусор и уменьшить размер iso образов , типа дампа который отделяет мусор естественно библиотеки apt.so и другие надо будет добавить.

Download rootfs variant: https://github.com/Griggorii/griggorii_patent_clear_linux_new_build_libx32_gcc_docker_new_OS/releases/tag/rootfs 

Кто будет делать операционную систему из моих исходников в initrd.img-4.4.0-116 не забудьте удалить resume из /conf/conf.d по скольку это старый алиас на не существующий uuid раздела которого нет. Там где архитектура заворачивает ссылками в /usr/local типа bin lib lib64 libx32 sbin для разработчиков то эта архитектура уменьшит заключительный размер образа filesystem.squashfs в casper который позднее окажется в iso имейте ввиду с потолка не беру только точные мои эксперементы и наблюдения за которые в другой стране бы скорее всего заплатили. Т.е если вы берете initrd.img-4.4.0-116-generic-patent_griggorii_OS100%_fast_directx.tar.gz то в процессе надо сделать всю архитектуру как в других initrd которые вы можете распаковать и посмотреть в initrd.img-5.6.0-1020 или в initrd.img-5.9.0-1-rt-amd64.tar.gz опять же directx9 и выше работали очень быстро только в 4.4.0-116. 

Griggorii@gmail.com только настоящие технологии bitcoin support real technology new fix 1Fps612daCcb7vYN2bFDRoDuUnrjJESDmk
