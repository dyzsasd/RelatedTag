RelatedTag

Finding relationship among the tags

This project is developped with java 1.7 and tested with hadoop 2.4 yarn. It reads the file test_mapreduce and outputs the relationship among the tags.

The output file is "part-r-00000" which can be found under the root directory of the project. You can also generated a new output by launching the command:
yarn jar reltag.jar ReleatedTag [Input file or directory] [Output directory]. 
The reltag.jar can be found also under the root directory of project. Input file and Output directory are the path of HDFS and the Output directory should not exist before launching the program.

The output file can be found under the output directory.


