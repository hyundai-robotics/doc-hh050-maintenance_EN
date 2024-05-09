# 6.4.2. How to Replace Motor


![](../../../_assets/작은주의표시.png) <b>Warning</b>

Because a brake for maintaining the posture of the arm is embedded in the motor of the robot, the arm will fall if the motor is separated. Thus, to prevent falling, there must be safety measures such as hanging the arm using a crane and then inserting fixing bolts to fix arm 1 and arm 2.

<br>

<ol style="list-style-type:decimal" start="1">
    <li>
Put the controller into TEACH mode and select motors [ON]. When the motors [On] state cannot be obtained, check the respective ARM is firmly fixed while supporting it to prevent dropping. And then begin at step No.4.
</li><br>
    <li>The axis requiring motor replacement takes basic posture. 
</li><br>
    <li>In case of main axes(S, H, V): Refer to [Figure 6.1] and [Figure 6.2]. 
Insert a supporting bolt to prevent ARM dropping.
In case of wrist axes (R2, B, R1): Set the origin by using SCALES.
</li><br>
    <li>Turn the main power [OFF] with the controller power [OFF].
</li><br>
    <li>Disconnect the connector from the motor.
</li><br>
    <li>Remove attachment bolts of motor and pull the motor out of robot. When removing motors of axis H or V, be sure not to damage the lip of oil seal due to the gear attached to the axis of motor.
</li><br>
    <li>Detach the gear from the motor shaft. 
Be careful to avoid excessive impact to the motor.
</li><br>
    <li>Assemble the gear after lightly applying grease to the shaft.
The bolt used to attach the gear to the shaft should be cleaned and removed of grease before using. Apply Loctite 243 to the screw part of the bolt, and then tighten it using a torque wrench in a regular torque. , Besides, slowly tighten the bolt in a symmetrical order.
</li><br>
    <li>Assemble the motor on the robot after applying a small amount of grease to the lip of oil seal and applying a moderate amount of grease to the teeth of gear. When assembly the main axis motor, be sure not to damage the lip of oil seal.
</li><br>
    <li>Connect the connector to the motor.
</li><br>
    <li>When replacing the axis H or V, replenish the grease as the amount as it lost.
</li><br>
    <li>Reset the encoder of the axis whose motor is replaced.
<p>

![](../../../_assets/작은주의표시.png) <b>Warning</b>

Before encoder correction, check motor connections, with motors [ON], while pressing the Enable switch for 2~3 seconds.
</li><br>
    <li>Perform the encoder calibration about the axis whose motor is replaced. Refer to the chapter [Encoder Calibration] in the controller operating manual.
</li><br>
    <li>Remove M20 bolt, a supporting bolt for preventing possible dropping of axis H.
</li><br>
    <li>Confirm that there is no error in robot's motion.
</li>
</ol>


![](../../../_assets/그림_6.1_arm축_고정용_볼트_삽입_위치.png)

Figure 6.1 Insertion position of Arm 1 (H axis) and Arm 2 (V axis) fixing bolt



