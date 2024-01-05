all:
	cd 00_orientation && pandoc readme.md -o 00.pdf && cd ..
	cd 01_snowball_fight && pandoc readme.md -o 01.pdf && cd ..
	cd 02_linux_101 && pandoc readme.md -o 02.pdf && cd ..
	cd 03_azure_101 && pandoc readme.md -o 03.pdf && cd ..
	cd 04_hashcat && pandoc readme.md -o 04.pdf && cd ..
	cd 05_elf_hunt && pandoc readme.md -o 05.pdf && cd ..
	cd 06_certificate_sshenanigans && pandoc readme.md -o 06.pdf && cd ..

merge:
	pdftk 00_orientation/00.pdf 01_snowball_fight/01.pdf 02_linux_101/02.pdf 03_azure_101/03.pdf 04_hashcat/04.pdf 05_elf_hunt/05.pdf 06_certificate_sshenanigans/06.pdf cat output merged.pdf
