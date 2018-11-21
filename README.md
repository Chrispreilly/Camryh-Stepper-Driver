# Camryh-Stepper-Driver

 * loop() updates current steering angle from the car, and desired angle from Openpilot. 
 * Based on the difference it calculates how many steps to move to achieve the desired angle and requests to move there.
 * It continues to update at 200hz as both current angle and desired angle changes.
 * Also takes advantage of the enable pin on the A4988 to disable the stepper when not engaged.
 
 ToDo:  
 -Update README with more details  
 -Improve comments in Arduino code  
 -Draw circuit details  
 -Make OLDCAR Panda  
 
 
