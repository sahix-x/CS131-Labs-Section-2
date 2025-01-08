Q1: What version of your Jetson nano’s system?
-- The version 4.6.1 -b110 which we got from looking at the system settings.

Q2: What is the effect of different power modes(MAXN, 5W)?
- MAXN mode is the highelest level of performance for the JEtson Nano as it comsumes more power (10W) and is ideal for programs/applications with heavy workloads such as image processing.
- 5W mode is the Nanos more conservative level as it uses less energy and can only run relatively "light weight" tasks such as simple data processsing. As a result, the Nano can not make full
  use of its cores, can reduce clock speed, and is slower with computuations at this level. However, this means that the Nano will run at a cooler and can run longer depending on the applications.

Q3: What challenges did you face during the setup and how did you overcome them?
--Some challenges we faced was setting up the Jetson Nano since previous users didn't include the password for the Nano so it was difficult to use. 
  We solved this issue by requesting other boards and eventually resetting the nano. Another issue was following the instructions since some steps 
  of the lab manual were not necessary, we solved this by asking questions.

Q4: Can you think of a real-world problem that could be solved using the Jetson Nano? Describe how you would design and implement a solution
-- One use for the Jetson Nano is training ML models. One real world-example is creating an automous vehicle that can navigate through a course full of obstacles such as traffic cones. It is
   feasible to use  Jetson Nanos to train ML models that can detect obstacles on a track so that vehicle can recognize obstacles, adjust its positioning, and avoid crashing. 

