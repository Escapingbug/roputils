CC := gcc
CFLAGS := -fno-stack-protector -no-pie

bof: bof.c

.PHONY: clean getoffset
clean:
	$(RM) bof

getoffset: bof
	python getoffset.py ./bof
