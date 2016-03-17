
all:
	mkdir -p output

	idss-seriation.py --debug 0 --graphs 0 --spatialbootstrapN 100 --spatialsignificance=1  --continuity 1 --frequency 0 --bootstrapCI=1 --bootstrapSignificance=0.95  --inputfile ./woodland-trimmed.txt --outputdirectory output --xyfile=./WoodlandXY.txt


clean:
	rm -rf output
