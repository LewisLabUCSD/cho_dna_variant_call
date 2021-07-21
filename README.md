## Method to run these pipelines.
#### Paired end files should end with _1.fq.gz, _2.fq.gz or _1.fastq.gz,_2.fastq.fz. Single end files should end with _1.fq.gz
1. define all parameters in the corresponding parameter file in parameters folder.
2. In bash terminal, run the following command:
	* nohup python pipeline.py parameter.yaml > log.txt &
	Or if you are running in screen, try the following command:
	* python pipeline.py parameter.yaml 2>&1 | tee log.txt
3. Press enter

