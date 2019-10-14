export ARCH=arm
export CROSS_COMPILE=arm-linux-gnueabi-
KDIR := /home/gp/guru/projects/V4/source_codes/linux-at91/


obj-m+=hello.o

all:
	make -C $(KDIR) M=$(PWD) modules
#	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) modules
clean:
	make -C $(KDIR) M=$(PWD) clean
#	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) clean
 