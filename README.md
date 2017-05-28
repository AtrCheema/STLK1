# STLK1
STLK1 program from USGS has been modified to include more than 1000 data elements and optimization of parameters
The program execution file 'stlk1 modified' is modification of STLK1 program. 
STLK1 is groundwater surface water interaction model available from USGS. 
This modified version takes input data just as original STLK1 with the addition that it takes observed heads which are used for optimization purpose. 
As a test run, input data is given in file 'ii.txt'. Upon running of execution file 'stlk1 modifiled.exe' the user is asked to give file containing input data. For test run type 'ii.txt' which is attached with this software here. 
After that user is asked to give name of file which contains initial input data. You can give any name. 
After that user is asked to give another name for plot file. Just press enter to carry out execution. 
Once execution is completed, you have two outpu files named 'initialres.txt' and 'optres.txt' plut two numerical values on screen. The file 'initialres.txt' contains results for calculated heads with initially supplied aquifer parameters. The file 'optres.txt' contains heads which are calculated after optimization of aquifer parameters. The optimized aquifer parameters are hydraulic conductivity and specific storage. The two numerical values which appear on screen are the values of optimized hydraulic conductivity and specific storage. 
The result of hypothetical flood wave are can be seen in file 'hypothetical data.png'. 
The optimization for real field data can be seen in file 'real data.png'. 
The file 'real data.xlsx' shows the results in the form of excel tables. 
