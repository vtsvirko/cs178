compile:
	gcc -o src/ServerCountThrees  src/ServerCountThrees.c src/readInt32BitLE.c
#run:
#	cd build; ./ServerCountThrees
test: 
	mkdir build
	cp  data/threesData.bin build
	cp src/ServerCountThrees build
	cd build; ./ServerCountThrees
clean:
	rm -rf build
