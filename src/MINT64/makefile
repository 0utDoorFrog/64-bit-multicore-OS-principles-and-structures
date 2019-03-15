all: BootLoader Disk.img

BootLoader:
	@echo
	@echo ================ Build Boot Loader =====================
	@echo
	
	make -C 00.BootLoader
	
	@echo
	@echo ================ Build Complete =====================
	@echo
	
	cp 00.BootLoader/BootLoader.bin Disk.img
	
	@echo
	@echo ================ All Build Complete ===================
	@echo
	
Clean:
	make -C 00.BootLoader clean
	rm -f Disk.img