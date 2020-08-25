# Udacity-MapMyWorld

<p>
   The project uses Occupancy Grid Mapping algorithm to map the surfaces. The robot uses a Continuous Bag of Words model to determine the important features of the images. 
   The images are obtained using a depth camera. The rtabmapping package of ROS is enables the robot to estimate the map of its environment. The algorithm generates the map based 
   on the loop closures. The robot is moved through turtle bot teleop twist keyboard in the environment made in Gazebo. Here the robot has made three loop closures to map 
   the environment.
 </p>
 
 
 <h2> The snippet of rtabmap-databaseViewer</h2>
 
 <p> The yellow circles represents the features. The pink circles will mention loop closures. </P>
 
 <img src="/Ross.JPG" alt="Image"/>
 
 <h2> The snippet of Environment </h2>
 
 <img src="/Ross1.JPG" alt="Env"/>
 
 <h2> The snippet of 3D map generated </h2>
 
 <p> The rtabmap-databaseViewer DB file is exported into ply format  which is displayed using MeshLab. </p>
 
 <img src="/Ross2.JPG" alt="GeneratedEnv" />
