OUTDIR=../build

all: spy calibration
spy: spy.cpp
	g++ -std=gnu++11 -O3 -o $(OUTDIR)/$@ $<
calibration: calibration.c
	gcc -std=gnu11 -O3 -o $(OUTDIR)/$@ $<
