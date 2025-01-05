"# TempControl" 

go build -ldflags="-H windowsgui" -o rt06server.ex_ 
flutter build windows --release   



scp lkt@192.168.56.22:/home/lkt/work/rt06/BUILD/K64F/GCC_ARM/rt06.bin d:/RT06adv/ 
scp *.* -r lkt@192.168.56.22:/home/lkt/work/rt06/src/ 

ssh klt@192.168.56.22
