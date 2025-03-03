# Description of files in repository
VIQRC Team 84K - The Slayinators Github Repository

* **MotorSpeedExperiment.iqblocks** - Blocks code to log odometry information for drivetrain motor velocities and headings from brain intertial. The data is logged to a file on the SD card that is inserted into the brain. The file names will automatically change and include a counter and the speed.

* **kp_experiment_odometry.iqblocks** - Blocks code (with Python sprinked using Switch blocks) for collecting odometry data during robot runs to find a good value for KP. Results and analysis are documented in our engineering notebook for the VEX IQ Rapid Relay season.

* **driver_mode_code.iqblocks** - Blocks code for driver skills and teamwork matches.

* **motor_speed_data** - Contains files which have the odometry data from running the **MotorSpeedExperiment.iqblocks** code at different motor speeds.

* **front_kp_data** - Contains files which have the odometry data from executing the **kp_experiment_odometry.iqblocks** code with different values for kp. The robot is moving forward for these tests.

* **back_kp_data** - Contains files which have the odometry data from executing the **kp_experiment_odometry.iqblocks** code with different values for kp. In our Robot, the brain is positioned at the back of the Robot. We did this to ensure that the positioning of the brain does not affect the KP value when the robot is moving backwards instead of forwards. 

* **project plans** - contains Gantt charts created using https://www.onlinegantt.com/ that describe our project plan for the season.

* **Robot Data Analysis** - Google Sheets that has all the charts from sensor data. https://docs.google.com/spreadsheets/d/17uxgtx0vI1p23lCWfUO68CUN96lxko14br0P3NBp0Uk/edit?gid=299427813#gid=299427813
