练习三、分析bootloader进入保护模式的过程  

请分析bootloader是如何完成从实模式进入保护模式的。了解如何从实模式切换到保护模式，需要了解：  
1.为何开启A20，以及如何开启A20?  
2.如何初始化GDT表?  
3.如何使能和进入保护模式?  

答：  
1.打开/moocos/uocre_lab/labcodes/lab1/boot目录下的bootasm.S和asm.h文件，并分析其中的代码。  
2.