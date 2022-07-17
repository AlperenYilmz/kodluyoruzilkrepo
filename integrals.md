<h2>Calculating the Center of a Mass Using Integrals<h2/>
  As we all know, we as software developers, will end up using math at some point in our practise, and the most used math tool is undoubtly, integrals.
  At this blog post, we will be looking at one of its uses, calculating the center of mass for 2D and 3D objects in space.
  
<h3>Calculating the Center of Mass of 2D Objects<h3/>
  The center of mass can also be called as the center of gravity if the object is in a uniform gravitational field.
  If the object has uniform mass density, the center of mass is the geometric center of the object, which we know as the centroid.
  Figure below shows a point P as the center of mass of a lamina. The lamina is perfectly balanced about its center of mass on a wedge.
  
  ![alt text](https://github.com/AlperenYilmz/kodluyoruzilkrepo/blob/main/CNX_Calc_Figure_15_06_001.jpg?raw=true)
  
  To find the coordinates of the center of mass P(x,y) of the lamina, we need to find the moment Mx of the lamina about the x-axis and the moment My 
  about the y-axis. We also need to find the mass m of the lamina. Therefore,

  x = My/m  and y = Mx/m

  If we allow a constant density function, then x = My/m and y = Mx/m give the centroid of the lamina.
