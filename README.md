# River-Modelling
This is a project I completed in a course called Modelling in Applied Mathematics. We were given the task of modelling a river, In our case we chose to model a section of the Amazon River. We analysed the data of a river every 5 years from 2000 to 2020 using Google Earth Pro.
![294278452-564213f3-41e7-4354-8ac7-e32275583889](https://github.com/MatthewGall3/River-Modelling/assets/113800575/6311fb67-76ed-4caa-92ed-5ff261030733)
We then imported this data into excel and transferred to Python
![294279336-fc973146-3868-416a-9273-29a857a802d3](https://github.com/MatthewGall3/River-Modelling/assets/113800575/13d9c1c2-380e-47bd-9899-6ea085aeec38)
The basic premise of our model:
***
1-Move each point of the river out in the orthonormal direction of the point by an amount proportional to a constant times the square root of the width of the river at that point and the curvature at that point
