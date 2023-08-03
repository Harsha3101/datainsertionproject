1.Project Title: 

Data Insertion Project, where we will populate data on daily basis and write to Hive

2.Project Description:

In this Project, we are considering SQLSERVER DataBase as Major Source and we connect to SQLSERVER and read the tables which are in AdventuresDWH22, here we are assuming that AdventuresDWH22 as OLTP and writing into Hive and assuming that Hive is our OLAP
Finally we will create Delta Tables on top of data present in Hive storage

To achieve the goal of our project we followed this project structure as follows 
ProjectName/
  com/
     Achyutas/
         data/
          insertion/
                 src/
                  main/
                    python/
                       configs/
                       pipeline/
                       logs/
                       resources/
                 Test/

Here every thing under one single pacakge i.e., com.Achyutas.data.insertion (package Name)

