OUTDIR=../build

all: measure
	
measure: measure.cpp
	g++ -g -std=c++11 -lm -O3 -o $(OUTDIR)/$@ $<

clean:
	rm -f $(OUTDIR)/measure
