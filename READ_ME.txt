1.Keep the Project jar at "Output" directory.

2.Generate the files (Data, Rules, Segment) as mentioned in project description.
NOTE:generate data files at specific directory.
ex: java -jar DataGen.jar Data ./Data

3.Run project jar as follow:
scala jarName.jar "path of rules file" "path of segment file" "path of data files directory"
NOTE: you can run command with jar name if your cmd at the same directory of jar otherwise you should give the full path of jar.
ex:
E:\ITI\Scala\Day3\ScalaProjectFinal\target\scala-2.12>scala scalaprojectfinal_2.12-0.1.jar "E:\\ITI\\Scala\\Day3\scala_project_final\\RULES.csv" "E:\\ITI\\Scala\\Day3\scala_project_final\\SEGMENT.csv" "E:\\ITI\\Scala\\Day3\\scala_project_final\\Data"