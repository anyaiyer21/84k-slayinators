# Description of files in repository
VIQRC Team 84K - The Slayinators Github Repository

* **MotorSpeedExperiment.iqblocks** - Blocks code to log odometry information for drivetrain motor velocities and headings from brain intertial. The data is logged to a file on the SD card that is inserted into the brain. The file names will automatically change and include a counter and the speed. 

* **motor_speed_data** - Contains files which have the odometry data from running the **MotorSpeedExperiment.iqblocks** code at different motor speeds.

* **front_kp_data** - Contains files which have the odometry data from executing the **kp_experiment_odometry.iqblocks** code with different values for kp. The robot is moving forward for these tests.

* **back_kp_data** - Contains files which have the odometry data from executing the **kp_experiment_odometry.iqblocks** code with different values for kp. In our Robot, the brain is positioned at the back of the Robot. We did this to ensure that the positioning of the brain does not affect the KP value when the robot is moving backwards instead of forwards. 
