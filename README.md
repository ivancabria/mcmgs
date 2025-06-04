The file mcmgs-source.tar.gz contains the source files and the makefile file of the code mcmgs.
To obtain the files run 'tar zxvf mcmgs-source.tar.gz'. After running this command, there will be a directory names mcmgs/source.
The source files and the makefile file are inside that directory. To compile the code, create the directory bin/mcmgs and then 
run 'make' or 'make -s' in the directory mcmgs/source

The file inputandoutputfiles.tar.gz contains two examples of input-output files for the code mcmgs.
To obtain the files run 'tar zxvf inputandoutputfiles.tar.gz'. After running this command, there will be four files:

example-onemillion-roomtemperature.input

example-onemillion-roomtemperature.out

nu-2100-muvt-10000000-1-0.5-298.15-1.0-periodic-111-percen20.0-srk-fh.input

nu-2100-muvt-10000000-1-0.5-298.15-1.0-periodic-111-percen20.0-srk-fh.out

To run an example, make:

$HOME/bin/mcmgs < example-onemillion-roomtemperature.input > example-onemillion-roomtemperature.out-new
