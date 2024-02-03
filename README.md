# River-Modelling
This is a project I completed in a course called Modelling in Applied Mathematics. We were given the task of modelling a river, In our case we chose to model a section of the Amazon River. We analysed the data of a river every 5 years from 2000 to 2020 using Google Earth Pro.
![294278452-564213f3-41e7-4354-8ac7-e32275583889](https://github.com/MatthewGall3/River-Modelling/assets/113800575/6311fb67-76ed-4caa-92ed-5ff261030733)
We then imported this data into excel and transferred to Python
![294279336-fc973146-3868-416a-9273-29a857a802d3](https://github.com/MatthewGall3/River-Modelling/assets/113800575/13d9c1c2-380e-47bd-9899-6ea085aeec38)
The basic premise of our model:
***
1-Move each point of the river out in the orthonormal direction of the point by an amount proportional to a constant times the square root of the width of the river at that point and the curvature at that point.
***
![294282093-62e1b3ca-45b5-4ed9-8032-0d6b3b07fd63](https://github.com/MatthewGall3/River-Modelling/assets/113800575/a54e7577-9398-463f-9255-a129fd8423f6)
***
2-To find this constant we used our previous data collected to see which constant caused our model to line up best with the data collected.
***
![294282406-88a09235-b2d4-498e-934a-d8bcdae880c2](https://github.com/MatthewGall3/River-Modelling/assets/113800575/29c34c4c-e800-41d8-b0ab-c6d6f01256a2)
![294282473-7d91a181-cdb4-4593-8308-1b00c626ee64](https://github.com/MatthewGall3/River-Modelling/assets/113800575/5e47c843-e4b9-45ec-a995-f60779895f1b)
***
3-We then made a python model for this river.
***
![294284244-d9efaa62-d458-45ff-b47e-78a57e50d21f](https://github.com/MatthewGall3/River-Modelling/assets/113800575/afad0a3b-4448-4a8a-9e01-ad9e7a4e5291)
![294283097-9ef08b07-4f31-4051-8745-86213fedcaa7](https://github.com/MatthewGall3/River-Modelling/assets/113800575/f3f97dbd-c71c-47d2-b0aa-195b999bf6e8)
![294283678-82dc4166-41f2-4098-acec-d5ed7819474c](https://github.com/MatthewGall3/River-Modelling/assets/113800575/94809733-25f2-4870-93f2-c7181a60bee4)
***
4-Then we made an animation of the river
***
![294285479-6ddcf23a-a35f-472c-a17e-9e0fb4e03c8e](https://github.com/MatthewGall3/River-Modelling/assets/113800575/80618a92-b1d2-4a0b-bfe2-213c55d6e303)


