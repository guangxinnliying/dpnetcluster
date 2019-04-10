# dpnetcluster
Implementation of the Algorithm of constructing a protein-based disease network by searching for disease groups in each similarity interval. The algorithm is implemented by several procedures. The database and procedures are in the download files.
Installation instructions are below.
step 1.Create a database in MySQL with the name of "diseaseproteindb". 
step 2.Download "diseaseproteindb.sql" and all the procedure files to your computor.
step 3.Use "source" command to import diseaseproteindb.sql to database "diseaseproteindb".
step 4.Create all procedures using the code in everey procedure files.
Note: the clustering result has been written to tables "alldiseasecluster" and "clusterprotein". If you want to cluster disease again, please run procedure "sectionclusterall".
