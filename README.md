# log.sh
just for select the .log files
for i in `ls *.gjf`
do result=$(grep "Normal termination" $i)
