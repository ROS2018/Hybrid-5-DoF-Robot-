# Hybrid-5-DoF-Robot-

Hearing loss is a common chronic condition among older adults especially the sensorineural, which is caused by damage to the hair cells of the inner ear. Surgical doctors have little ability to reliably access the complex anatomy of the inner ear and thus are unable to cure it. The CochleRob project comes to handle this obstacle by introducing therapeutic SPMNs (Super Paramagnetic Nanoparticles) in the inner ear and control it using a magnetic actuator positioned around the patient’s head by the mean of a robotic platform.

In this context my work comes to develop a novel robotic platform and control it via a computer. We proceeded, at first, to study the effective specifications needed for the robotic platform (especially the work space, the required degrees of
freedom, and the compactness).

![alt text](https://github.com/ROS2018/Hybrid-5-DoF-Robot-/blob/main/Design5DOFRobot.png?raw=true)

Then, after analyzing the preliminary works done before in the project and discovering some other relevant medical mechanisms, we developed a novel robot
manipulator that fulfil all the required specifications showing the rational behind the choice of the mechanism together with its motorisation as well; Beside, The mechanism was portrayed and designed by the mean of SolidWorks.

In the next step, we established the different necessary models (Geometric, Kinematic, and Dynamic models) to demonstrate the system state model and control it as well. Hence, the last chapter was dedicated for tuning a control law, explaining the rational point behind the strategy that allowed us to introduce, in a straightforward manner, controllers like PI and Loop-shaping.

![alt text](https://user-images.githubusercontent.com/45684110/173240726-e20793f6-6904-46c2-b2c4-db221a365644.png)
)

As for simulation, the structure designed using Solidworks was exported to SimMechanics environment, then used to validate the different models and the tuned control law.

Finally, After printing the different mechanism organs, they were jointed together to make a prototype controlled via a computer using Labview software and Maxon controllers.

