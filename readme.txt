SnowflakeGrowth Cell-DEVS Model



The zip file includes following files:

Snow1.ma	the definition of the cellular model "Snow"(background level=0.3;constant=0.001)
Snow2.ma	the definition of the cellular model "Snow"(background level=0.4;constant=0.01)
Snow3.ma	the definition of the cellular model "Snow"(background level=0.5;constant=0.0035)

Snow1.bat	the simulation script for "Snow1.ma"
Snow2.bat	the simulation script for "Snow2.ma"
Snow3.bat	the simulation script for "Snow3.ma"

Snow1draw.bat	the drawlog script for "Snow1.ma"
Snow2draw.bat	the drawlog script for "Snow2.ma"
Snow3draw.bat	the drawlog script for "Snow3.ma"

Snow.pal	the palette file for visualizing the simulation result in CD++ modeler
Snow.val	the initial value for the celluar model "Snow"


Note:  All of these three model base on the cell space =(30x30)=900.
In order to get the different result, it need change the three parameters
(space size, constant and background level). If we want get the perfect image,for instance,
space size =(400,400), constant = 0.001, background level = 0.35, the simulation will take long time, it will mainly influenced by the the 
increase of the cell space size.
See the assignment report for more details.  

