# Manipulator Maintenance Manual - YS080 / YS100A / HH050 / HH030L / HH050T

{% hint style="warning" %}
The information provided in this manual is the property of Hyundai Robotics.

The manual may not be copied, in part or in full, nor redistributed without a prior written consent from Hyundai Robotics. It may not be provided to any third party nor used for any other purposes.


The manual may be changed without prior notification.



**Copyright ⓒ 2023 by Hyundai Robotics**
{% endhint %}

# 1. Safety
# 1.1. Introduction

The main purpose of this chapter is to describe the safety precautions for users and operators who repair and manipulate the industrial robot. 

This manual describes safety precautions for robot manipulator and controller, in complies with the safety regulation of EU Machinery Directive 98/37/EC(2006/42/EC) and US OSHA. And the robot manipulator and controller is manufactured to comply with the safety standards EN ISO 10218-1:2011 and ANSI/NFPA 79:2021. 

Every operator, who installs, replaces, adjusts, manipulates, maintains, and repairs, must read thoroughly and fully understand the manipulation and maintenance manual, in particular, the special attention must be paid to the WARNING symbol, the most important marking related to the safety.

Installation, replacement, adjustment, manipulation, maintenance, and repair of robot system must be performed by the personnel who was duly trained for these purposes, following the indicated operating procedure.

This company is planning and carrying out the relevant training such as maintenance, repair, and manipulation for the above operations, so robot users make sure that robot operators should get the relevant training. And make sure that the robot handling work should be carried out only by the operators who completed this training course. 

Hyundai Robotics user of industrial robot has responsibility to observe the safety regulation related to robot adopted in corresponding countries and responsibility to design, install and operate safety equipment well in order to protect workers who work at robot system.

In high-risk areas concerning robot systems in which robots, tools, and accessories operate, there must be a method of protection to stop the workers or objects from entering the area according to ANSI/NFPA 79:2021.



![](../_assets/말머리이미지.png )  <font size = 3> **Applicable areas** </font><br>

It is applied to the industrial robot used by installing on the surface of wall or plane (axes addable). It is also appropriate for controlling operation in the dotted section or consecutive section.

Major application is 

*	Spot welding
*	Arc welding
*	Cutting
*	Handling
*	Assembly
*	Application such as Sealing
*	Palletizing
*	Grinding

For the other use than the above emergency application, make a contact with our company to consult on the robot use and possible applications. 


![](../_assets/말머리이미지.png )  <font size = 3> **Disable environment** </font><br>

Our robot must not be used in a highly explosive environment and the areas contaminated by oil, flammable materials or chemical materials. (Prohibited to be installed and manipulated.) 

# 1.2. Relevant Safety Regulations


The robot is designed as per ISO 10218-1:2011 safety standards for industrial robots, and furthermore in comply with ANSI/NFPA 79:2021 regulations. 

# 1.3. Safety Training

All the personnel who intend to teach, operate or inspect the robot must be trained in an approved robotic operation and safety training course before start-up. The safety training course includes the following details:

*	Purpose and functions of safety devices
*	Safety procedure to handle the robot
*	Performance of robot or the robot system and possible hazards
*	Tasks associated with any specific robot applications 
*	Safety concepts, etc. 

# 1.4. Safety Related Nameplate 
# 1.4.1. Safety Marking 

For the purpose of effective safety instructions, the following safety symbols are used in this manual. 



<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-osmi{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-bav5{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:middle}
</style>
<table class="tg">
<caption>Table 1-1 Safety marking</caption>
<thead>
  <tr>
    <th class="tg-osmi" colspan="2">Symbols</th>
    <th class="tg-bav5">Descriptions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Warning</td>
    <td class="tg-nrix"><img src="../../_assets/주의표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">Indicate a highly dangerous situation, meaning that operating or handling in a wrong manner could result in death or serious injury to personnel, or damage to equipment. Attention should be paid to the operation and handling.</td>
  </tr>
  <tr>
    <td class="tg-nrix">Mandatory</td>
    <td class="tg-nrix"><img src="../../_assets/강제표시.png" width = 100 height = 100>  </td></td>
    <td class="tg-0lax">Indicate the compulsory measures that should be taken</td>
  </tr>
  <tr>
    <td class="tg-nrix">Prohibited</td>
    <td class="tg-nrix"><img src="../../_assets/금지표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">Indicate the prohibited actions and/or operations that should not be performed.</td>
  </tr>
</tbody>
</table># 1.4.2. Safety Nameplate

Identification plates, warning label and safety symbols are attached to the robot and to the inside and outside of control panel. The designation labels and cable Mark for wire harness between the robot and control panel, and the cables inside/outside of control panel are provided. 

All of these plates, labels, symbols and marks constitute safety-relevant parts of the robot and the control panel. They must remain attached to the robot manipulator and control panel at their clearly visible positions all the time for the safety and their full performance. 

The painted markings on the floor and signs indicating dangerous zones must be clearly distinguished in form, color, and style from other markings on the machine near the robot system or inside the plant facilities where the robot system is installed. 

<blockquote>
<table border="0">
<thead>
  <tr>
    <td> 
    <div align="center">
     <img src="../../_assets/금지표시.png" width = 60 height = 60> 
    </div>
    </td>
    <td colspan="4">       
      It is forbidden to remove, cover, or paint over by way of spoiling the clearly visible identification plates, warning labels, safety symbols, designation labels and cable marks.
    </td>
  </tr>
</thead>
</table>  
</blockquote># 1.5. Definition of Safety Functions

![](../_assets/말머리이미지.png )<font size = 3> **Emergency Stop Functions – IEC 204-1,10,7** </font><br>
There is one emergency stop button on the controller and teach pendant respectively. If necessary, additional emergency buttons can be connected to the robot's safety chain circuit. The emergency stop function, which overrides all other robot controls, can bring the current operation to a halt by cutting off the power supply to the motors of individual axes. This function will also shut down the power supply to other dangerous functions, which are controlled by the robot, to prevent them from being used

![](../_assets/말머리이미지.png )<font size = 3> **Safety Stop Function - EN ISO 10218-1:2011** </font><br>
A safety stop circuit needs to be configured, and, through this circuit, each robot should be connected with the safeguards and interlocks. The robot should have a number of electrical input signals which can be used to connect external safety devices, such as safety gates, safety pads, and safety lamps. These signals allow the robot's safety functions to be activated by all equipment, including peripheral equipment and the robot itself. 

![](../_assets/말머리이미지.png )<font size = 3> **Speed Limitation Function - EN ISO 10218-1:2011** </font><br>
In a manual mode, the maximum speed of the robot is limited to 250 mm per second.
The speed limitation applies not only to the TCP(Tool Center Point), but to all parts of manual mode robot. The speed of equipment mounted on the robot should be possibly monitored. 

![](../_assets/말머리이미지.png )<font size = 3> **Restricting working Envelope - ANSI/NFPA 79:2021** </font><br>
Operation area of each axis is restricted by soft limit and hardware limit. Axis 1, 2, and 3 can also be restricted by means of mechanical stopper.

![](../_assets/말머리이미지.png )<font size = 3> **Operation Mode Selection - ANSI/NFPA 79:2021** </font><br>
The robot can be operated either in the manual mode or auto mode. In the manual mode, the robot can be operated only by using the teach pendant.# 1.6. Installation# 1.6.1. Safety Fence

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4">Install safety fence against the possible collision between the robot and workers, so that no worker may approach the robot.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>


Install safety fence against the possible collision between the robot and workers, so that no worker may approach the robot. When operators or other personnel enter the robot's working envelope by accident, it may cause an accident. Install the safety fence to stop the robot when one, who intends to replace for TIP DRESSING or TIP changing replacement, or to inspect welding equipment, opens the fence gate and approaches the equipment during operation.

![](../../_assets/그림_1.1_권장펜스크기와_출입구크기.png)

Figure 1.1 Recommended size for safety net and entrance gate (slot type entrance gate)


![](../../_assets/그림_1.2_권장펜스크기와_출입구크기.png)

Figure 1.2 Recommended size for safety net and entrance gate (square type entrance gate)

<ol style="list-style-type:decimal" start="1">
<li>Enough space for safety net should be secured by covering robot operating area so as that workers would not have difficulty in teaching work or repairing work, and the safety net should have solid structure in order that it would not move easily and man cannot enter over easily.
</li><br>
    <li>
Safety net should be installed by static type in principle, and should not have hazardous parts such as prominence and depression or keen part, etc.
</li><br>
    <li>
Install the safety fence with an entrance gate, and register the safety plug at the gate so that it does not open unless pulling the plug out. Wiring should be carried out in a way that the robot should be in the operation ready OFF status as well as in the motor OFF status when the safety plug is pulled out or safety net is open.
</li><br>
    <li>
In order to operate the robot with the safety plug pulled out, wiring should be carried out in a way that will allow the playback to take place at a low speed.
</li><br>
    <li>
The emergency stop button should be installed at a place where it can be pushed quickly by the operator. 
</li><br>
    <li>
If no safety net is to be installed, devices such as photoelectric switches, and mat switches, should be installed, instead of the safety plug, to cover the overall area within the robot’s operation range in a way that the robot can be stopped automatically when a person enters the robot’s operation range.
</li><br>
    <li>
Operation area of robot (hazardous area) should be distinguished by the method like painting on floor. 
</li>
</ol>
# 1.6.2. Placement of Robot & Peripheral Equipment

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4">Please make sure that robot and peripheral equipment should be arranged by following method.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
<li>(1)	In case of connecting primary power of controller or peripheral devices, please work after checking whether supply power has been deleted. There is a possible danger of electric shock because the high voltage such as 220V and 440V is used as its primary power. 
</li><br>
    <li>
Post a sign [No enter during operation] up the safety fence gate, and inform the operators of its purport. 
</li><br>
    <li>
Arrange such devices as controller, interlock panel, and other manipulation panels to be handled outside of the safety fence. 
</li><br>
    <li>
When installing operation stand, install the emergency stop button on the stand. Make sure that stopping in an emergency situation can be initiated from any place from which the robot is operated.
</li><br>
    <li>
Make sure that the robot manipulator and the wiring and piping of controller, interlock panel, and timer should not be placed in the way of operator's working range so that they would not be directly stepped on by FORK　and LIFT. Otherwise, the operator may suffer electrocution or the wire may suffer disconnection. 
</li><br>
    <li>
Place the controller, interlock panel, and handling stand within the sight of robotic performance. It may cause a major accident to operate the robot while the robot is malfunctioning in an area where the robot’s activity can not be observed, or while the operator is working on it.
</li><br>
    <li>
Restrict the robot's working envelope by using the soft limits and the mechanical stopper if the necessary working envelope is narrower than the robot’s workable envelope. When the robot is to move beyond the restricted envelop due to abnormal operation, such as the robot being handled in a wrong way, the robot will be stopped automatically in advance thanks to the function that restricts the workable envelop.
</li><br>
    <li>
During the welding work, spatter could fall down to workers or the workers could be injured by burning, or fire could break out. Install such devices as a glare shield or a cover in the full sight of robot's working envelope.
</li><br>
    <li>
Make sure that the device indicating the robot's running condition, whether automatic or manual mode, can be noticeable even from a slightly distant location. In the case of automatic start-up, a buzzer or a warning lamp will be useful.
</li><br>
    <li>
Make sure that there is no projecting part in the robot's peripheral equipment. Cover it, if necessary. It usually could cause an accident if the operator comes in touch with it. And it may cause a major accident when the operator tumbles while being astonished at the sudden movement of the robot.
</li><br>
    <li>
Don't make the system designed to allow the workers to carry the Work in and out using their hands through the safety fence. It could be a cause of accident associated with compressing or amputating. 
</li>
</ol>



![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_원통형.png)
(Cylinder type)
![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_빔형.png)
(Beam type)

Figure 1.3 Arrangement of LCD robot peripheral devices and workers


![](../../_assets/그림_1.4_산업로봇주변장치와_작업자의배치.png)

Figure 1.4 Arrangement of general robot peripheral devices and workers# 1.6.3. Installing the Robot

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4">Please install the robot in accordance with following method surely</td>
        </tr>
    </thead>
</table>  
</blockquote><br>

Install the robot as per the planning and layout which has been previously reviewed and studied for its optimized performance and functionality. In case of poor conditions for robot installation, the serious problems can take place, including error of relative position between robot and workpiece during operation, bad performance quality of robot caused by vibration, shortening lifetime, and cause of serious accidents. Thus, pay attention to the following precautions when installing the robot.

<br><br>

![](../../_assets/말머리이미지.png )<font size = 3> **General Safety Precautions** </font><br>


<ol style="list-style-type:decimal" start="1">
<li>
Design and install the robot system properly in compliance with laws, regulations, and safety requirements enable in the country where the robot system is installed. 
</li><br>
    <li>
All the workers for the robot system must have the complete knowledge on the information specified in the application and supplementary manual, and proficiently operate and handle the industrial robot. 
</li><br>
    <li>
Installation workers of robot must follow the safety instructions and apply them to the installation when they face any safety problems.
</li><br>
    <li>
System provider must ensure that all the circuits utilizing safety functions perfectly perform in a safe way.
</li><br>
    <li>
Install main power supply to be disconnected from outside of the robot’s working envelope. 
</li><br>
    <li>
System provider must ensure that all the circuits utilizing emergency stop function perfectly perform in a safe way.
</li><br>
    <li>
or the immediate emergency stop, install emergency stop button within the accessible distance for the operator.
</li><br>      
</ol>

<br>

![](../../_assets/말머리이미지.png )<font size = 3> **Technical Safety Precautions** </font><br>

<ol style="list-style-type:decimal" start="1">
<li>
Eliminate any interference with peripheral equipment considering the dimension and working envelope. 
</li><br>
    <li>
Avoid such place for installing which is directly exposed to the sun, extremely humid, contaminated by oil or chemicals, and containing a large amount of metal powder and explosive gas.
</li><br>
    <li>
Install at the ambient temperature ranged 0~45℃. 
</li><br>
    <li>
Secure sufficient space for the easier disassembly and maintenance.
</li><br>
    <li>
Install safety fence with a gate, and prohibit any person from entering the robot's working envelope.
</li><br>
    <li>
Remove any obstacles out of the robot’s working envelope.
</li><br>
    <li>
Take a special measure, considering thermodynamics of controller, if the robot is installed near the heating elements or places exposed directly to the sun.
</li><br>
    <li>
Take a special measure if the robot is installed in a place of abundant dust such as metal powder in the air.
</li><br>
    <li>
Install the robot not to transmit welding electric current. In other word, insulate SPOT GUN with/from the robot’s wrist.
</li><br>
    <li>
Grounding is very critical in preventing electric shock and malfunction caused by noise, and thus install as following instructions. 
            <ol style="list-style-type:lower-roman" start="1">
                <li>
tall an exclusive grounding terminal using class 3 or higher. (For the input voltage of 400V of higher, use special class 3 or higher.) 
</li>
<li>
Connect grounding line into the grounding bus-bar inside of the control panel. 
</li>
<li>
In case of direct grounding on the floor by anchoring, two-point grounding both by robot manipulator and by controller can produce a “ground loop” and contrariwise cause abnormal operation. In this case, connect the grounding line to the base of robot manipulator and disconnect the second grounding point to the controller. If the robot vibrates even after stopping, double-check the grounding status because the possible main causes could be an incomplete grounding or “ground loop”.
</li>
<li>
In the use of internal transgun(GUN), there is a possible danger of dropping because the primary power cable is directly connected to the spot gun. In this case, directly connect the grounding line to the base of robot manipulator in order to prevent any electric shock and protect the control panel, but do not connect it to the controller.
</li>
</ol>
</li><br>   
</ol># 1.6.4. Space for Robot Installation

Install robot after securing sufficient space for maintaining the robot manipulator, controller, and other peripheral equipment. to install the main body and controller, please secure the above mentioned installation area. Install controller outside of the safety fence in order to monitor the robot manipulator and to operate in a safe way.
When installing, be sure to make it easier to perform the maintenance when opening the Controller door. Secure the available space. The specifications of the controller can change according to the type of the controller. (For more details, please refer to the “Maintenance manual”.)

# 1.7. Safety Operation for Robot Handling


Follow the safety instructions to prevent any accidents. Don't modify nor ignore safety devices or circuits at any time, and be careful of electric shock.

All the normal operations in an automatic mode must be performed outside of the safety fence. Check the robot's working envelope if anyone is inside before operating. 
# 1.7.1. Safety Precautions for Robot Handling

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            <div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety is very important for the test operation of the robot.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
		<li>
Do not handle the robot other than such personnel as operators handling the robot and other possible operators and supervisors who were designated as whom duly trained in an approved robotic training course and become familiar enough with the proper operation of the safety and robotic functions. 
</li><br>
    <li>
Be sure to wear helmets, goggles, and safety shoes. 
</li><br>
    <li>
Perform the work in pairs. One person must be ready to press the emergency stop button in an emergency while the other must perform his work quickly but carefully within the robot’s working envelope. Always check the escape route before working. 
</li><br>
    <li>
Make sure that there is no one in the working envelope when the power source is on. 
</li><br>
    <li>
Operations such as teaching must be performed outside of the robot's working envelope. However, if the operation is performed within the working envelope after stopping the robot, enter the envelope with safety plug or key switch for converting to automatic mode. Make sure that other operators do not change it into automatic mode by accident. Also, pay close attention to the specific direction of robotic movement in case of abnormal operation and malfunction. 
</li><br>
    <li>
Supervisors should follow the instructions below. 
<ol style="list-style-type:lower-roman" start="1">
    <li>
Be located at a place where you could take an entire view of robot, and commit yourself to monitoring.
</li>
<li>
Press the emergency stop button immediately when abnormality is found. 
</li>
    <li>
Anyone is forbidden to be near the operating area other than those who are engaged in the operation.
</li>
</ol>
<li>
In a manual mode, the speed of teaching is limited to 250mm/sec. 
</li><br>
    <li>
In teaching, post a sign [Under Teaching]. 
</li><br>
    <li>
Operators must pull the safety plug out, and enter the safety fence with the plug. 
</li><br>
    <li>
Do not use any devices causing noise in and around the teaching area. 
</li><br>
    <li>
Handle the teach pendant button, while checking the teaching point with your naked eyes, and do not handle it just relying on your sense. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">It is a repairing part to be prepared for when you buy many sets. 
</li><br>
    <li>
In teaching, check and examine carefully under your feet. In particular, in high teaching for more than 2M, secure a safe zone on which you may step before teaching. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">Instructions for any abnormal operations. 
<ol style="list-style-type:lower-roman" start="1">
    <li> Press immediately the emergency stop button when any abnormal operations are found. 
</li><br>
    <li>
Be sure to check if the relevant equipment is stopped when checking the abnormality in an emergency stop. 
</li><br>
    <li>
In case that the robot stops automatically due to power failure, investigate possible causes and take actions after confirming that the robot completely stops. 
</li><br>
    <li>
In case of malfunction of emergency stop devices, immediately disconnect the main power and investigate possible causes to take necessary actions. 
</li><br>
    <li>
Investigation of the failure must be conducted only by a designated person. For the re-operation after emergency stop, operators must clarify the cause of failure and take necessary actions, and then operate the robot again following the proper procedure. 
</li></ol>
    <li>
Write out the operating rules proper to working details and installing location regarding the operation and handling method for the robot, and the necessary actions for robot's any failure. In addition, it is recommended to operate the robot in accordance with the operating rules. 
</li><br>
    <li>
Instructions when the robot stops 
Make sure not to approach the robot even when it seems to be stopped. Most accidents occur from a sudden movement of robot which seemed to be stopped when one approaches it. The conditions that the robot stops are as follows.
        </li><br> 
            <style type="text/css">
                .tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
                .tg caption{caption-side: top;text-align: left;}
                .tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg .tg-osmi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
                .tg .tg-bb96{background-color:#ccf1bc;color:#000000;text-align:center;vertical-align:middle}
                .tg .tg-nrix{text-align:center;vertical-align:middle}
            </style>
            <table class="tg">
                <caption>Table 1-2 State of Robot Stop</caption> 
                <thead>
                <tr>
                    <th class="tg-osmi">No.</th>
                    <th class="tg-osmi">State of Robot</th>
                    <th class="tg-osmi">Drive Power</th>
                    <th class="tg-osmi">Access</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td class="tg-bb96">1</td>
                    <td class="tg-nrix">Pause (Minor failure, Pause switch)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">2</td>
                    <td class="tg-nrix">Emergency stop (Major failure, Emergency stop switch, Safety gate)</td>
                    <td class="tg-nrix">OFF</td>
                    <td class="tg-nrix">O</td>
                </tr>
                <tr>
                    <td class="tg-bb96">3</td>
                    <td class="tg-nrix">Input signal standby of peripheral equipment (START INTERLOCK)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">4</td>
                    <td class="tg-nrix">Playback Completion</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">5</td>
                    <td class="tg-nrix">Standby</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                </tbody>
            </table><br>
            Even in the accessible state of robot, be watchful against any possible sudden movement of robot. Make sure to avoid approaching the robot without precautions for emergency under all circumstances.<br><br>            
</ol>

<ol style="list-style-position: outside; list-style-type:square;" start="1">
    <li>
        <b>
        During temporary halt, the entrance countermeasure same as entrance of teaching work should be considered at the case (nozzle contact, welded part detected, arc error, and so on) of opening entrance gate for simple management against error.
        </b>
    </li>
</ol><br>

<ol style="list-style-type:decimal" start="17">
    <li>
        Clean up any split oil, tools, and impurities in the safety fence after completing robotic operation. Accidents such as conduction may occur in the working envelope contaminated by oil, or scattered tools on its floor. Make a habit of organizing and cleaning things up. 
    </li>
</ol># 1.7.2. Safety Precautions for Operating Test 

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety on robot operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



In case of operating test, errors in design or teaching and inferiority in manufacturing are possibly seen in the entire system such as teaching program, jig, and sequence. Thus, be more careful and safe in case of operating test. Accidents may occur by these combined causes. 

<ol style="list-style-type:decimal" start="1">
		<li>
            Before handling, check the stop buttons and signal functions to stop the robot such as emergency stop button or stop button. And then, check the abnormality - detective movements. Above all, it is the most critical to check all the stop signals. It would be the most important to stop the robot when any possible accidents are predicted. 
        </li><br>		
		<li>
            In case of operating test, start the robot at low speed(approximately 20%~30%) in the variable speed function, and repeat it more than one cycle to check the movements. If any errors are found, immediately correct them. After then, increase in speed (50% → 75% → 100%) gradually, and repeat more than one cycle respectively to check the movements. Operating at high speed from the very beginning may cause a serious accident. 
        </li><br>	
		<li>
           In case of operating test, it is hard to predict what problems would happen. Do not enter the safety fence during operating test. Unexpected accidents are likely to occur because of its low reliability. 
        </li><br>	          
</ol>
# 1.7.3. Safety Precautions for Automatic Operation

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety on robot automatic operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
hile posting a sign [Do Not Enter During Operation] up the safety fence gate, ask the operators not to enter during operation. If the robot stops, you may enter the safety fence under your full understanding of the situation. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
Be sure to check if any operators are inside of the safety fence when starting the automatic operation. Operating without checking the presence of operators may cause a personal injury. 
</li><br>
    <li>
Before starting the automatic operation, check and confirm that the program number, step number, mode, and starting selection are in the possible state for automatic operation. If starting with the other programs or steps selected, the robot could move in an unpredicted way, and lead to an accident. 
</li><br>
    <li>
Before starting the automatic operation, check if the robot is properly located to get started. Check whether the program number or step number is identical with the location of robot. Even if it's all identical, accidents are still possible to occur due to an abnormal movement when the robot is differently located. 
</li><br>
    <li>
Be prepared to immediately press the emergency stop button when starting the automatic operation. Immediately press the emergency stop button in case of robot's unexpected movements or emergency. 
</li><br>
    <li>
Be sure to detect any abnormalities by checking the route, condition, or sound of robot movement. Sometimes the robot may be abnormally operated including a sudden break down. However, it will show a certain indication before the break down. Understand the robot's normal condition well in order to catch the symptom in advance. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
When any abnormality is detected from the robot, immediately stop and take proper actions on it. Using the robot before any proper actions taken may cause an interruption of produce as well as serious failure leading to a very serious personal injury. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
When checking the robot’s movement after the proper actions taken for the abnormality, do not operate the robot with operators inside of the safety fence. Unexpected accidents are possibly to occur because its low reliability may cause another abnormality. 
    </li><br>	 
</ol>
# 1.8. Safety Precautions for Access to Safety Fence

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
               Please observe following countermeasures because safety on robot automatic operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>

The robot is very heavy and strong, even at low speeds. When entering the safety fence, one must observe the relevant safety regulations of its pertinent country.

The operators always must be aware of the unexpected movements of robot. Robots are able to move fast shortly after being stopped. The operators should know that the robot is able to move in a different route, without any notice, by means of external signals. Thus, when trying to stop the robot during teaching or operating test, one should be able to stop the robot with a teach pendant or control panel.

When entering the working envelope through the safety gate, you must take the teach pendant with yourself so that other people can not operate the robot. Make sure to post up the control panel a sign indicating the state of robot handling. 

People must understand the followings when they are to enter the robot’s working envelope


<ol style="list-style-type:decimal" start="1">
		<li>
Do not enter the working envelope other than teaching person. 
</li><br>
    <li>
Operation set-up mode of controller must be a manual mode in the control panel. 
</li><br>
    <li>
Always wear the approved working suite.(Do not wear a loose clothes as you please) 
</li><br>
    <li>
Do not wear gloves when handling controller. 
</li><br>
    <li>
Do not leave innerwear such as underwear, shirts, or necktie out of the working suite. 
</li><br>
    <li>
Do not wear personal accessories such as big earrings, rings, or necklaces. 
</li><br>
    <li>
Make sure to wear safety shoes, helmet, and goggles and if necessary, wear other self-protective outfit such as safety gloves. 
</li><br>
    <li>
Make sure that the emergency stop circuit is working correctly and in its proper function, turns MOTOR OFF when pressing the emergency stop button in the control panel and teach pendant before handling the robot. 
</li><br>
    <li>
Make your posture face-to-face with the robot manipulator when performing your work. 
</li><br>
    <li>
Follow the predetermined working procedure.
</li><br>
    <li>
Be prepared for emergency exit or safe place considering that the robot may unexpectedly rush at you.
</li><br>	
</ol># 1.9. Safety Precautions for Maintenance and Repair # 1.9.1. Safety Precautions for Controller Maintenance and Repair

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>   
            <td colspan="4"> 
                Please observe following safety countermeasures on repair and check for robot controller.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Maintenance and repair of the robot must be performed by the personnel who was duly trained in the special maintenance training course and has a good knowledge of maintenance. 
</li><br>
    <li>
Perform your work following the maintenance procedures for controller. 
</li><br>
    <li>
Perform your maintenance and repair in a safe way by securing emergency exit or safe place. 
</li><br>
    <li>
Before the daily maintenance, repair, or changing parts, be sure to power down. In addition, post a warning sign [Do Not Input Power] up the primary power so that other operators may not input power by accident. 
</li><br>
    <li>
When changing parts, be sure to use the specified ones. 
</li><br>
    <li>
When you open the door of controller, you should turn off power, and please start working after 3 minutes. 
</li><br>
    <li>
If sufficient illuminance is not secured when you perform maintenance and inspection inside the controller, you should use external lights.
</li><br>
    <li>
Please do not touch heat radiating plate of servo AMP and recovery resistance because they are very hot. 
</li><br>
    <li>
After completing maintenance, be sure to close the door completely after checking if tools or other things are still remained in the controller.
</li><br>	
</ol># 1.9.2. Safety Precautions for Robot System & Manipulator Maintenance

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following safety countermeasures on repair and check for robot controller.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Refer to the safety precautions for Controller maintenance and repair. 
</li><br>
    <li>
Perform your maintenance and repair for the robot system and manipulator, following the indicated procedures. 
</li><br>
    <li>
Be sure to disconnect the primary power of controller. Post the warning sign [Do not input power] up the primary power to prevent other workers from connecting the power. 
</li><br>
    <li>
Make sure that the Arm is fixed and immovable before maintenance and repair since dropping or moving of the robot's Arm may cause a danger during maintenance and repair. (Refer to the 『Robot manipulator maintenance manual』.)
</li><br>	 
</ol># 1.9.3. Necessary Actions after Maintenance and Repair

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please install the robot in accordance with following method surely.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Check if the cables or parts of controller are properly connected. 
</li><br>
    <li>
After maintenance is completed, carefully check that no tools are left around or inside of the controller and manipulator. Make sure that the door is firmly closed. 
</li><br>
    <li>
Do not turn on the power if any problems or critical failures are detected. 
</li><br>
    <li>
Be sure that there is no one within the working envelope, and that you are in a safe place before turning on the power. 
</li><br>
    <li>
Turn on the main circuit breaker on the control panel. 
</li><br>
    <li>
Check the current position and status of robot. 
</li><br>
    <li>
Operate the manipulator at low speed. 
</li><br>	 
</ol># 1.10. Safety Functions
# 1.10.1. Operating a Safety Circuit

![](../../_assets/그림_1.5_안전체인_구성도_.png)


Figure 1.5 Configuration for safety chain

<br>

The robot's safety system is based on a two-channel safety circuit that is continuously monitored. If an error is detected, the power supply to the motors is disconnected and the motor brake is applied. To return the robot to MOTOR ON mode, the switches of two-channel circuit must be connected. If one of the two-channel circuit switches shorts, the contactor of motor will be disconnected leading to the application of brake, and finally the robot will be stopped. Furthermore, when safety circuit is disconnected, the interrupting call will be sent automatically to the controller to find out the possible reason for the interruption. 

The safety control circuit of operation is based on dual safety electric circuit in which the controller and MOTOR ON mode are operated interactively. In order to be in MOTOR ON mode, the safety circuit consisted of several switches must be all connected. MOTOR ON mode indicates that drive power is supplied to the motors. If one of the contactors is disconnected, the robot will always return to MOTOR OFF mode.

MOTOR OFF mode indicates that drive power is removed from the robot's motors and the brakes are applied. The status of the switches is displayed on the teach pendant. (Refer to the I/O monitoring screen of "SERVICE" menu, 『Operation manual』.)

<font size = 3><b>Safety circuit</b></font>

The emergency stop buttons on the controller panel and on the teach pendant and external emergency stop buttons are included in the safety circuit of operation. Users may install the safety devices (safety plug, safety stop device for safe place) which are operated in the AUTO mode. In a manual mode, the signals of these safety devices are ignored. You can connect the general safety stop devices that is active in all operating modes. No one can enter the working envelope in an automatic operation mode due to the unconditional operation of the safety devices (door, safety mat, safety plug etc.). These signals are also generated in a manual mode, but the controller will keep the robot operating while ignoring the robot's teaching. In this case, maximum speed of robot is restricted to 250mm/s. Thus, the purpose of this safety stop function is to secure the safe area around the manipulator while one approaches the robot for maintenance and teaching. 

When the robot is stopped with the limit switch, change the robot’s position by operating it with the pendant key at the constant setting mode. (Constant setting mode refers to the state of entry into the menu『[F2]: System』 menu)


<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                The safety circuits must never be by-passed, modified or changed in any way.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br># 1.10.2. Emergency stop

An emergency stop should be activated when people or equipment is located at the dangerous area. The emergency stop buttons are located both on the control panel and on the teach pendant. 
All safety control devices such as emergency stop buttons on the control panel must be located outside the working envelope and easily accessible at any time.


![](../../_assets/말머리이미지.png)<font size = 3> **Status of Emergency stop** </font><br>

When the button is pressed, the robot will operate as follows. 
Robot stops immediately in any cases.

<ol style="list-style-type:square" start="1">
		<li>
            Disconnect the servo system power.
        </li>		
		<li>
            Motor brake is activated.
        </li>	  
        <li>
        	Motor brake is activated.
        </li>
</ol>


For the emergency stop, the following two methods can operated simultaneously.

<ol style="list-style-type:decimal" start="1">
<li>
Emergency stop for control panel and teach pendant (Basic)<br><br>
Above the control and teach pendant console.
        </li><br>
		<li>
Emergency stop of external system<br><br>
External emergency stop device (button etc.) can be connected to the safety electric circuit in accordance with applied standard for the emergency stop circuit.
(Please refer to system board in “basic configuration of controller”) At this time, the emergency stop must be connected to be “Normal On” and it must be check for proper operation during test run.
</li><br>
</ol>


![](../../_assets/그림_1.6_시스템보드_터미널블록_TBEM를_통한_외부비상정지스위치의연결.png)

Figure 1.6 Connection with external emergency halt switch through system board terminal block TBEM# 1.10.3. Operating Speed

To teach the robot, the operating mode switch must be in a MANUAL mode. Then the maximum speed of robot is limited to 250mm/s. # 1.10.4. Connecting the Safety Devices

External safety devices such as light beams, light curtains, safety plug, and safety mats which can be adapted by the system builder execute interlocking the controller by way of connecting with safety circuit within the controller. These devices are used for safety device during execution of normal program in an automatic mode. 
# 1.10.5. Restricting the working Envelope

When the robot is not necessary to reach certain area for specific applications, working envelope of the robot can be limited to secure the sufficient safety working area. This will reduce the damage or loss in case of robot's collision with external safety devices such as safety fence, etc. The movement of axes 1, 2, and 3 of HR, HX, HS and HA can be limited by means of mechanical stopper or electrical limit switches. In this case, the corresponding software limitation parameters must be also changed. If necessary, movement of wrist 3 axes can be restricted, too. Limitation of working envelope for all the axes could be carried out by the user. The robot is delivered to customer as the status of full working envelope setting. 

<style type="text/css">
    .block {background-color:#f8f8be}
</style>
<blockquote class="block">
    <ol style="list-style-type:disc" start="1">
        <br>
		<li>
            <font size = 3><b>Manual mode: Maximum speed is 250mm/s. </b></font><br>
            In a manual mode, by means of worker’s selection, workers may enter the safeguard area. 
        </li><br>
		<li>
            <font size = 3><b>Auto mode : The robot can be operated via remote controller.</b></font><br>
            All safety devices such as safety door, safety mats, etc. are activated.<p>
            No one may enter the safety device area of robot.
           </li><br>
    </ol>
</blockquote># 1.10.6. Monitoring Function

<ol style="list-style-type:decimal" start="1">
		<li>
Motor monitoring function<p>
Motors are protected against overload by means of onboard sensors. 
    </li>	<br>
		<li>
Voltage Monitoring Function<p>
For the protection of, the servo amp module turns off the power switch when the voltage is too low or too high. 
</li>	  
</ol># 1.11. Safety Related to End Effectors

# 1.11.1. Gripper

<ol style="list-style-type:decimal" start="1">
		<li>
      When a gripper is used to grip a workpiece, there should be safety precautions for unexpected dropping of the loaded workpiece. 
    </li>	<br>
		<li>
      When any end effectors or devices are installed on the robot arm, use the required size and piece of bolt, and securely fasten as per the required torque using torque wrench. Do not use the bolt which has rust or dirt on its surface. 
    </li><br>
    <li>
      End effector must be designed and manufactured not to exceed the maximum allowable load at the wrist of robot. Even though power or air supply stops, the gripped workpiece must not be dropped from the gripper. In order to remove any risks and problems which may cause personal injury and/or physical damage, the sharp edge and projecting part of end effector must be made dull and smooth. 
    </li><br>
</ol># 1.11.2. Tool / Workpiece


<ol style="list-style-type:decimal" start="1">
    <li>
      It must be possible to replace tools such as milling cutters in a safe manner. Make sure that safety devices are working correctly until the cutters stop rotating. 
    </li>	<br>
    <li>
      Tool must be designed to keep in gripping workpiece securely even though a power failure or a control failure takes place. It must be possible to release workpiece from the gripper in a manual mode. 
    </li><br>
</ol># 1.11.3. Pneumatic and Hydraulic Systems

<ol style="list-style-type:decimal" start="1">
    <li>
      The special safety regulations will apply to pneumatic and hydraulic systems. 
    </li>	<br>
    <li>
      Since residual energy of pneumatic and hydraulic systems can be still remaining even after the robot stops, particular care and attention must be paid by users. Internal pressure of equipment must be removed whenever starting the repair work for pneumatic and hydraulic systems.  
    </li><br>
</ol># 1.12. Liabilities 

The robot system has been built in accordance with the latest technical standards and approved safety rules. Nevertheless, the serious accidents such as death or personal injury still may take place due to the collision between the robot system and peripheral equipment.

The robot system must be used by operator who has a full technical knowledge on its designated use and also pay his close attention to the possible dangers and risks involved in its operation. The use of robot system is subject to compliance with these operating instructions and the operation and maintenance manual supplied together with the robot system. The safety related functions of robot system must not be used for any purposes other than safety.

When you use the robot system for any other or additional purposes than its designated usage, you must review whether it is enable in accordance with design criteria. The manufacturers cannot take any responsibility for any damage or loss which resulted from such misuse or improper use. The users shall have the full responsibility for the risks caused by such misuse or improper use. When you use and operate the robot system for its designated use, you must have a good command of all the information contained at these operating instructions as well as the maintenance manual. 

The robot system may not be put into operation until it is ensured that the functional machine or plant into which the robot system has been integrated conforms to the specifications of the EU Machinery Directive 98/37/EC(2006/42/EC) and US OSHA. 

The following harmonized standards in particular were taken into account with regard to the safety of the robot system.



<ol style="list-style-type:square" start="1">
    <li>
ANSI/RIA R15.06-1999 
Industrial Robots and Robot Systems - Safety Requirements 
</li><br>
    <li>
ANSI/RIA/ISO 10218-1-2007 
Robots for Industrial Environment - Safety Requirements - Part 1 - Robot 
ISO 11161:2007 
</li><br>
    <li>
Safety of machinery - Integrated manufacturing systems - Basic requirements 
EN ISO 13849-1:2008
</li><br>
    <li>
Safety of machinery - Safety-related parts of control systems - Part 1: General principles for design (ISO 13849-1:2006) 
</li><br>
    <li>
EN 60204-1:2006 
Safety of machinery - Electrical equipment of machines - Part 1: General requirements (IEC 60204-1:2005 (Modified)) 
</li><br>
    <li>
EN ISO 10218-1:2006 
Robots for industrial environments - Safety requirements - Part 1: Robot (ISO 10218-1:2006) 
</li><br>
</ol>


Users must take the full responsibility for any accident caused by their negligence or non-observance of these instructions. The manufacturer will not take any liabilities and responsibilities for any damages or losses caused by the misuse or malfunction of such equipment which is not included in the contract between manufacturer and user and provided by user, or such equipment which is installed around the robot system arbitrarily by the user. User must take the full liabilities and responsibilities for any risks and damages caused by such equipment.


# 2. Specifications
# 2.1. Robot Machinery Part

![](../_assets/그림_2.1_로봇기구부형식.png)

Figure 2.1 Robot Machinery Part# 2.2. Location of Robot Identification Plate

The model name, serial number, and manufacturing date of robot are written down in the name plate. 

The name plate is located at the lower part of the main body (left or right) as shown below.




![](../_assets/그림_2.2_로봇명판부착위치.png)

Figure 2.2 The location of identification plate
# 2.3. Basic Specifications


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-bgl2{background-color:#f8f8be;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-tfzl{background-color:#ccf1bc;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-foot{border-width:0}
</style>
<table class="tg">
<caption>Table 2-1 Basic Specifications for Models: [YS080/YS100A]</caption>  
<thead>
  <tr>
    <th class="tg-bgl2" colspan="4">Item</th>
    <th class="tg-bgl2" colspan="2">Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-bgl2" colspan="4">Robot Model</td>
    <td class="tg-bgl2">YS080</td>
    <td class="tg-bgl2">YS100A</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Construction</td>
    <td class="tg-c3ow" colspan="2">Degree of freedom</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Degree of freedom</td>
    <td class="tg-c3ow" colspan="2">6</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Drive system</td>
    <td class="tg-c3ow" colspan="2">AC servo system</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max. Working envelope</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow" colspan="2">±3.142 rad (±180°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow">-1.134 ~ +2.967 rad (-65°~ +170°)</td>
    <td class="tg-c3ow">-1.134 ~ +3.142 rad (-65°~ +180°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow">-1.396 ~ +3.141 rad (-80°~ +180°)</td>
    <td class="tg-c3ow">-1.396 ~ +3.142 rad (-80°~ +180°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow" colspan="2">±6.284 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow" colspan="2">±2.182 rad (±125°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow" colspan="2">±6.284 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max. Speed</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow">2.967 rad/s (170°/s)</td>
    <td class="tg-c3ow">2.618 rad/s (150°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow">2.444 rad/s (140°/s)</td>
    <td class="tg-c3ow">2.094 rad/s (120°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow">2.793 rad/s (160°/s)</td>
    <td class="tg-c3ow">2.443 rad/s (140°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">4.015 rad/s (230°/s)</td>
    <td class="tg-c3ow">3.491 rad/s (200°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">4.015 rad/s (230°/s)</td>
    <td class="tg-c3ow">3.491 rad/s (200°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">6.109 rad/s (350°/s)</td>
    <td class="tg-c3ow">5.236 rad/s (300°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Load Capacity</td>
    <td class="tg-c3ow">784 N (80 kg)</td>
    <td class="tg-c3ow">980 N (100 kg)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="2" rowspan="3">Wrist Torque</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">400 N·m (40.8 kgf·m)</td>
    <td class="tg-c3ow">490 N·m (50.0 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">400 N·m (40.8 kgf·m)</td>
    <td class="tg-c3ow">490 N·m (50.0 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">200 N·m (20.4 kgf·m)</td>
    <td class="tg-c3ow">245 N·m (25.0 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Accuracy of position repeatability [Note 1]</td>
    <td class="tg-c3ow" colspan="2">±0.1 mm </td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Ambient Temperature</td>
    <td class="tg-c3ow" colspan="2">0~45℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Relative humidity</td>
    <td class="tg-c3ow" colspan="2">20 ~ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Robot's Weight</td>
    <td class="tg-c3ow" colspan="2">645 kg</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Vibration</td>
    <td class="tg-c3ow" colspan="2">0.5G or less</td>
</tbody>
</table>

 <b>[Note 1] Conforms to ISO 9283.</b>

<br>

 <style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-bgl2{background-color:#f8f8be;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-tfzl{background-color:#ccf1bc;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-foot{border-width:0}
</style>
<table class="tg">
<caption>Table 2 2 Basic Specifications for Models: [HH050/HH030L]</caption>  
<thead>
  <tr>
    <th class="tg-bgl2" colspan="4">Item</th>
    <th class="tg-bgl2" colspan="2">Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-bgl2" colspan="4">Robot Model</td>
    <td class="tg-bgl2">HH050</td>
    <td class="tg-bgl2">HH030L</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Construction</td>
    <td class="tg-c3ow" colspan="2">Articulated</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Degree of freedom</td>
    <td class="tg-c3ow" colspan="2">6</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Drive system</td>
    <td class="tg-c3ow" colspan="2">AC servo system</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max. Working envelope</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow" colspan="2">±3.142 rad (±180°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow" colspan="2">-1.134 ~ +2.967 rad (-65°~ +170°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow" colspan="2">-1.396 ~ +3.141 rad (-80°~ +180°)</td>
  
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow" colspan="2">±6.284 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow" colspan="2">±2.182 rad (±125°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow" colspan="2">±6.284 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max. Speed</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
    <td class="tg-c3ow">2.618 rad/s (150°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
    <td class="tg-c3ow">2.444 rad/s (140°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
    <td class="tg-c3ow">2.618 rad/s (150°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">4.363 rad/s (250°/s)</td>
    <td class="tg-c3ow">4.363 rad/s (250°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">4.363 rad/s (250°/s)</td>
    <td class="tg-c3ow">4.363 rad/s (250°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">6.109 rad/s (350°/s)</td>
    <td class="tg-c3ow">6.109 rad/s (350°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Load Capacity</td>
    <td class="tg-c3ow">490 N (50 kg)</td>
    <td class="tg-c3ow">294 N (30 kg)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="2" rowspan="3">Wrist Torque</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">216 N·m (22.0 kgf·m)</td>
    <td class="tg-c3ow">200 N·m (20.4 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">216 N·m (22.0 kgf·m)</td>
    <td class="tg-c3ow">200 N·m (20.4 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">147 N·m (15.0 kgf·m)</td>
    <td class="tg-c3ow">100 N·m (10.2 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Accuracy of position repeatability[Note 1]</td>
    <td class="tg-c3ow" colspan="2">±0.1 mm </td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Ambient Temperature</td>
    <td class="tg-c3ow" colspan="2">0~45℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Relative humidity</td>
    <td class="tg-c3ow" colspan="2">20 ~ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Robot's Weight</td>
    <td class="tg-c3ow">645 kg</td>
    <td class="tg-c3ow">650 kg</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Vibration</td>
    <td class="tg-c3ow" colspan="2">0.5G or less</td>
</tbody>
</table>

 <b>[Note 1] Conforms to ISO 9283.</b>

 <br>

 <style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-bgl2{background-color:#f8f8be;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-tfzl{background-color:#ccf1bc;border-color:inherit;color:#000000; font-weight:bold;
text-align:center;vertical-align:middle}
.tg .tg-foot{border-width:0}
</style>
<table class="tg">
<caption>Table 2-3 Basic Specifications for Models: [HH050T]</caption>  
<thead>
  <tr>
    <th class="tg-bgl2" colspan="4">Item</th>
    <th class="tg-bgl2">Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-bgl2" colspan="4">Robot Model</td>
    <td class="tg-bgl2">HH050T</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Construction</td>
    <td class="tg-c3ow">Articulated</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Degree of freedom</td>
    <td class="tg-c3ow">5</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Drive system</td>
    <td class="tg-c3ow">AC servo system</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max. Working envelope</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow">±3.142 rad (±180°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow">-1.134 ~ +2.967 rad (-65°~ +170°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow">-1.396 ~ +3.141 rad (-80°~ +180°)</td>
  
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">-</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">±2.182 rad (±125°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">±6.284 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="6">Max.Speed</td>
    <td class="tg-tfzl" rowspan="3">Arm</td>
    <td class="tg-tfzl">S</td>
    <td class="tg-tfzl">Swivel</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">H</td>
    <td class="tg-tfzl">For/Backward</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">V</td>
    <td class="tg-tfzl">Up/downward</td>
    <td class="tg-c3ow">3.054 rad/s (175°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" rowspan="3">Wrist</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">-</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">4.363 rad/s (250°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">6.109 rad/s (350°/s)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Load Capacity</td>
    <td class="tg-c3ow">490 N (50 kg)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="2" rowspan="3">Wrist Torque</td>
    <td class="tg-tfzl">R2</td>
    <td class="tg-tfzl">Rotation 2</td>
    <td class="tg-c3ow">-</td>
  </tr>
  <tr>
    <td class="tg-tfzl">B</td>
    <td class="tg-tfzl">Bending</td>
    <td class="tg-c3ow">216 N·m (22.0 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl">R1</td>
    <td class="tg-tfzl">Rotation 1</td>
    <td class="tg-c3ow">147 N·m (15.0 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Accuracy of position repeatability[NOTE 1]</td>
    <td class="tg-c3ow">±0.15 mm</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Ambient Temperature</td>
    <td class="tg-c3ow">0~45℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Relative humidity</td>
    <td class="tg-c3ow">20 ~ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Robot's Weight</td>
    <td class="tg-c3ow">635 kg</td>
  </tr>
  <tr>
    <td class="tg-tfzl" colspan="4">Vibration</td>
    <td class="tg-c3ow" colspan="2">0.5G or less</td>
</tbody>
</table>

 <b>[Note 1] Conforms to ISO 9283.</b># 2.4. Robot Dimension and Working Envelope
# 2.4.1. For Hi5


![](../../_assets/그림_2.3_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.3 Robot Dimension and Working Envelope: [YS080/YS100A/HH050]

![](../../_assets/그림_2.4_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.4 Robot Dimension and Working Envelope: [HH030L]# 2.4.2. For Hi5a

![](../../_assets/그림_2.5_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.5 Robot Dimension and Working Envelope [YS080-11/YS100A-11/HH050-11]

![](../../_assets/그림_2.6_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.6 Robot Dimension and Working Envelope [HH030L-11]

![](../../_assets/그림_2.7_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.7 Robot Dimension and Working Envelope [HH050T-11]# 2.5. Axis Identification



Table 2-4 Axis Motion

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jx5t{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-dq1w{background-color:#CCF1BC;color:#212529;text-align:center;vertical-align:top}
.tg .tg-ew0z{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jx5t">Axis Name</th>
    <th class="tg-jx5t">Operation</th>
    <th class="tg-jx5t" colspan="2">Teach Pendant Button</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-dq1w">S</td>
    <td class="tg-ew0z">Arm Swivel</td>
    <td class="tg-ew0z">LFT(S+)</td>
    <td class="tg-ew0z">RHT(S-)</td>
  </tr>
  <tr>
    <td class="tg-dq1w">H</td>
    <td class="tg-ew0z">Arm Forward and Backward</td>
    <td class="tg-ew0z">BWD(H+)</td>
    <td class="tg-ew0z">FWD(H-)</td>
  </tr>
  <tr>
    <td class="tg-dq1w">V</td>
    <td class="tg-ew0z">Arm Upward and Downward</td>
    <td class="tg-ew0z">UP(V+)</td>
    <td class="tg-ew0z">DOWN(V-)</td>
  </tr>
  <tr>
    <td class="tg-dq1w">R2</td>
    <td class="tg-ew0z">Wrist Rotation 2</td>
    <td class="tg-ew0z">Rx+(R2+)</td>
    <td class="tg-ew0z">Rx-(R2-)</td>
  </tr>
  <tr>
    <td class="tg-dq1w">B</td>
    <td class="tg-ew0z">Wrist Bend</td>
    <td class="tg-ew0z">Ry+(B+)</td>
    <td class="tg-ew0z">Ry-(B-)</td>
  </tr>
  <tr>
    <td class="tg-dq1w">R1</td>
    <td class="tg-ew0z">Wrist Rotation 1</td>
    <td class="tg-ew0z">Rz+(R1+)</td>
    <td class="tg-ew0z">Rz-(R1-)</td>
  </tr>
</tbody>
</table>
<br><br>

![](../_assets/그림_2.8_본체_외관_및_동작_축.png)

Figure 2.8 Robot Dimension and Axis [YS080/YS100A/HH050/HH030L] - [HH050T] R2 axis excluded# 2.6. Details of Wrist Axis Attachment Surface


When attaching the operating tool to the mechanical interface of robot's wrist flange, fasten it with a bolt at P.C.D. 100.

![](../_assets/그림_2.9_손목축_취부면_상세도.png)

Figure 2.9 Details of Wrist Axis Attachment Surface : [YS080/YS100A/HH050/HH030L/HH050T]
# 2.7. Details of ARM Frame Attachment Surface

The upper parts of the arm frame and arm pipe of the robots are attached using a tap designed to attach peripheral devices.

Within the area marked with ▦, peripheral devices (valves, etc.) shall be attached. 


<b>[Attention]</b>

Peripheral devices shall be attached either on the upper part of the arm frame or the upper part of the arm pipe. When attaching, be sure to the center position of gravity should be located within the range marked as ▦.

*	Max weight on the ARM PIPE : 15kg

![](../_assets/그림_2.10_ARMFRAME_상부_부착부상세도.png)

Figure 2.10 Details of Upper ARM FRAME Attachment Surface: [YS080/YS100A/HH050/HH050T]


![](../_assets/그림_2.11_ARMFRAME_상부_부착부상세도.png)

Figure 2.11 Details of Upper ARM FRAME Attachment Surface: [HH030L]# 2.8. Application Wiring and Inspection Wiring Diagram


There are air unit and connector to connect the additional equipment to the robot manipulator.
Application connectors are indicated as follows.

[Note] Max air pressure of air connection: 5bar (5.1 kgf/cm2, 72.5 psi)
# 2.8.1. For Hi5


![](../../_assets/그림_2.12_어플리케이션용_배선_및_배관도.png)

Figure 2.12 Application Wiring and Inspection Wiring Diagram: [YS080/YS100A/HH050/HH030L]

![](../../_assets/그림_2.13_어플리케이션_커넥터_상세.png)

Figure 2.13 Details of Application Connector: [YS080/YS100A/HH050/HH030L]# 2.8.2. For Hi5a

![](../../_assets/그림_2.14_어플리케이션용_배선_및_배관도.png)

Figure 2.14 Application Wiring and Inspection Wiring Diagram: [YS080-11/YS100A-11/HH050-11/HH030L-11/HH050T-11]

![](../../_assets/그림_2.15_어플리케이션_커넥터_상세.png)

Figure 2.15 Details of Application Connector: [YS080-11/YS100A-11/HH050-11/HH030L-11/HH050T-11]# 2.9. Restricting the Working Envelope

When installing the robot, take into account that the working envelope can be adjusted freely within the entire working envelope. 

Limiting the motion range is useful when: 

*	During robot operation
*	When the robot is likely to collide with another device
*	When the length of the application cables or hose pipes are limited

There are three methods to use to limit the motion range of the robot as follows:

*	Software limit (applied to the entire axis)
*	Limit switch (1-3 axis: optional application)
*	Mechanical stopper (1-3 axes)



<img src="../../_assets/작은주의표시.png"><b>[Warning]</b><br>
The mechanical stopper is a physical device. The robot should not exceed the area occupied by the mechanical stopper. The mechanical stopper of a 1-3 axis is fixed. The mechanical stopper with a 4-6 axis is applied only within the software limits.

Once the mechanical stopper is collided with, its strength cannot be guaranteed. Therefore, please ensure it is replaced after impact.
# 2.9.1. Axis 1(Axis S)

By adding one more mechanical stopper, the working envelope of the 1st axis can be limited. (by 30˚).
If the 1st STOPPER　BLOCK and STOPPER are deformed due to a great impact, they must be replaced.


# 3. Instructions



# 3.1. Robot Component Name

The following [Figure 3.1] show and name each component of the robot.


![](../_assets/그림_3.1_본체_각_부위_명칭.png)

Figure 3.1 Name of Robot Components
# 3.2. Location of Safety Nameplate

In order to prevent any accidents, safety marking plates such as [Figure 3.2] are attached to the robot. Do not remove or replace it unnecessarily. 


![](../_assets/그림_3.2.1_안전명판위치1.png)

[OLD]   

![](../_assets/그림_3.2.1_안전명판위치2.png)

[NEW]   

![](../_assets/그림_3.2.1_안전명판위치3.png)

[OLD]   

![](../_assets/그림_3.2.1_안전명판위치4.png)

[NEW]   

Figure 3.2 Location of Safety Nameplate
# 3.3. How to Transport
# 3.3.1. Using Crane


![](../../_assets/그림_3.3_운반방법_크레인이용.png)

Figure 3.3 How to Transport: Using crane [YS080/YS100A/HH050/HH030L/HH050T]

<br>

The following lifting instructions are valid for a "naked" robot. If additional equipment is put on the robot, the center of gravity may change and make lifting dangerous.

![](../../_assets/작은주의표시.png)
*	Never walk under the robot.
*	Pose the robot as shown in the Figure.
*	Install a 4-M24 eye bolt to the base body.
*	Connect a wire rope to the eye bolts.
*	Attach the protective hose (50㎝) to prevent the damage to the main body of the robot.
*	Keep the safety regulations during Lifting process.
*	Weight of manipulator : 645kg(YS080/YS100A/HH050), 650kg(HH030L), 635kg(HH050T)
*	Minimum crane capacity: 2 tons
# 3.3.2. Forklift use

A forklift can be used to carry the main body of the robot.

For safety reasons, please pay attention to the following procedures:

*	With reference to the pictures provided, use the standard position of each model.
*	Fix the robot onto a pallet and insert the forklift fork into the pallet to carry it. The pallet should be strong enough to withstand the weight.
*	Carry at a slow speed.
*	Follow all safety regulations.


![](../../_assets/작은주의표시.png) <b>Cautions</b>

*	Do not lean against the robot while carrying it.
*	Make sure the robot does not collide with the floor while loading and unloading.
*	Pay attention to the relevant safety rules while using the forklift truck.





![](../../_assets/그림_3.4_운반방법_지게차이용.png)


Figure 3.4 How to Transport: Using forklift [YS080/YS100A/HH050/HH030L/HH050T]# 3.4. Storage of the robot

To store the robot for non-use, position it as shown in [Figure 3.4].

![](../_assets/작은주의표시.png) <b>[Caution]</b>

If not placed as instructed, the robot may fall. For long-term storage, take extra care to ensure that it does not fall. # 3.5. How to Install

![](../../_assets/작은주의표시.png)
<b>NOTE:</b>

Before starting to unpack and install the robot, read the safety regulations and other instructions very carefully. 

![](../../_assets/작은주의표시.png)
<b>Warning:</b>

The installation shall be made by qualified installation personnel and should conform to all national and local codes. 

When unpacking the robot, check if it has been damaged during transporting or unpacking. In addition, strictly keep the following installation instructions because installation method and foundation are very important to maintain a good robot performance. 

# 3.5.1. Operating Conditions

<ol style="list-style-type:decimal" start="1">
    <li>
Ambient temperature should range from 0℃ to 45℃.
  </li><br>
    <li>
Ambient humidity should range from 20% to 85% RH, without dew condensation.
  </li><br>
    <li>
Less dust, oil, or moisture.
  </li><br>
    <li>
No flammable, corrosive liquid or GAS. 
  </li><br>
    <li>
No impact and shacking. 
  </li><br>
    <li>
No electrical noise generator near the robot.
  </li><br>
    <li>
If the robot is not immediately installed, keep it in a dry area at an ambient temperature between -15℃∼ and 40℃. 
</li>
</ol>

# 3.5.2. Installation the Robot Manipulator

The base floor to install the robot should be constructed with concrete with a thickness of 300mm or more so that the hardness minimizes dynamic effect to the robot. Repair bumps and cracks on the concrete surface of the floor during installation, and fix the mounting place with M20 Chemical Anchor. And if the thickness of the concrete floor is less than 300mm, it requires an independent base construction that must be reviewed beforehand. 
Locate the robot unit on the mounting plate and tightly assemble 8 M20 bolts.

*	Bolt: M20*70 (Hardness level: 12.9) 
*	Flat washer: T = 4mm or above, internal diameter (ID) = 24, hardness of HrC 35
*	Assembly torque: 530±20Nm
 

 





# 3.5.3. Accuracy of Installation Surface

The degree of flatness for the four attachment plate surfaces should satisfy the specification. Use a shim, if necessary. The rest of the surface must be flat within ±2mm.


* <b>Cautions</b>

①	The flatness of mounting plate must be within 1.0 mm.

②	Make four plane figures of a sealed plate of 1.0 mm (±0.5 mm) or less.



![](../../_assets/그림_3.5_로봇_설치면_정도.png  )

Figure 3.5 Accuracy of Installation surface
# 3.5.4. Dimension of Installation Surface


Fix the swivel base for robot's installation. 

Refer to [Figure 3.6] for the dimension.





![](../../_assets/그림_3.6_로봇_설치면_치수.png  )

Figure 3.6 Dimension of Robot Installation: [YS080/YS100A/HH050/HH030L/HH050T]# 3.5.5. Robot Cable Connection

![](../../_assets/그림_3.7_로봇cable연결.png  )

Figure 3.7 Robot Cable Connection


The robot will be connected to the controller with power cables and a signal cable. Connect the cables to the connectors on the rear of the robot base. Connect the ground wire as well.
For the connection of pneumatic pressure cables and option cables, refer to “2.8 Application Wiring and Inspection Wiring Diagram”.


<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 45 height = 40>
    </div>
    </td> 
    <td colspan="4">Make sure to turn OFF the power of the controller before connecting the cables</td>
  </tr>
</thead>
</table>  
</blockquote>
# 3.5.6. Emergency Stop Time & Distance


The following items are the response time and distance for an emergency stop during the max speed operation of each axis (S, H, and V) with the standard load.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-lput{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Robot Model</th>
    <th class="tg-yhpm"></th>
    <th class="tg-yhpm">S Axis</th>
    <th class="tg-yhpm">H Axis</th>
    <th class="tg-yhpm">V Axis</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-lput" rowspan="2">YS080</td>
    <td class="tg-nrix">Maximum moving distance [mm]</td>
    <td class="tg-nrix">1,096</td>
    <td class="tg-nrix">1,444</td>
    <td class="tg-nrix">1,036</td>
  </tr>
  <tr>
    <td class="tg-nrix">Maximum time [s]</td>
    <td class="tg-nrix">0.48</td>
    <td class="tg-nrix">0.72</td>
    <td class="tg-nrix">0.59</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">YS100A</td>
    <td class="tg-nrix">Maximum moving distance [mm]</td>
    <td class="tg-nrix">1,114</td>
    <td class="tg-nrix">975</td>
    <td class="tg-nrix">970</td>
  </tr>
  <tr>
    <td class="tg-nrix">Maximum time [s]</td>
    <td class="tg-nrix">0.53</td>
    <td class="tg-nrix">0.57</td>
    <td class="tg-nrix">0.62</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">HH050<br>HH050T</td>
    <td class="tg-nrix">Maximum moving distance [mm]</td>
    <td class="tg-nrix">1,107</td>
    <td class="tg-nrix">1,634</td>
    <td class="tg-nrix">931</td>
  </tr>
  <tr>
    <td class="tg-nrix">Maximum time [s]</td>
    <td class="tg-nrix">0.45</td>
    <td class="tg-nrix">0.66</td>
    <td class="tg-nrix">0.47</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">HH030L</td>
    <td class="tg-nrix">Maximum moving distance [mm]</td>
    <td class="tg-nrix">1,138</td>
    <td class="tg-nrix">1,634</td>
    <td class="tg-nrix">1,020</td>
  </tr>
  <tr>
    <td class="tg-nrix">Maximum time [s]</td>
    <td class="tg-nrix">0.44</td>
    <td class="tg-nrix">0.70</td>
    <td class="tg-nrix">0.48</td>
  </tr>
</tbody>
</table>


# 3.6. Allowable Load of Wrist Axis



# 3.6.1. Permitted load torque estimation

The load, which will be applied to the mechanical interface of robot's wrist axis, is restricted by allowable weight, allowable load torque and allowable moment of inertia. The direction of coordinate system used to calculate the load torque and inertia moment is the same with the direction of robot base coordinate system.


*	Step 1

    Calculate the location of the weight center from the B axis rotation center (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: Location of weight center in X axis

    L<sub>y</sub>: Location of weight center in Y axis

    L<sub>z</sub>: Location of weight center in Z axis



*	Step 2

    Check the location from the center of B and R1 axis to the weight center based on the torque map.

    ![](../../_assets/3.6.1_수식1.png)

    L<sub>B</sub> : Length from B axis rotation center to weight center

    L<sub>R1</sub> : Length from R1 axis rotation center to weight center



*	Step 3

    Calculate the load torque from the calculated distance.

    ![](../../_assets/3.6.1_수식2.png)


*	Step 4

    Check if the load torque calculated in the step 3 is the same with or smaller than the limit value, on the basis of allowed load torque table.

 
* Note : If the load mass is similar to the mass on the torque curve below, the torque can be alternatively validated by checking if the distance calculated in the step 2 is distributed in the torque curve, instead of the step 3 and 4. If it is in the torque curve, the calculated load torque is smaller than the allowed load torque but if it is out of the torque curve, the calculated load torque is bigger than the allowed load torque.


![](../../_assets/그림_3.8_손목축_토크_선도.png  )

Figure 3.8 Wrist Axis Torque Mapping: [YS080]

![](../../_assets/그림_3.9_손목축_토크_선도.png  )

Figure 3.9 Wrist Axis Torque Mapping: [YS100A]

![](../../_assets/그림_3.10_손목축_토크_선도.png  )

Figure 3.10 Wrist Axis Torque Mapping: [HH050/HH050T]

![](../../_assets/그림_3.11_손목축_토크_선도.png  )

Figure 3.11 Wrist Axis Torque Mapping: [HH030L]

<br></br>

![](../../_assets/작은주의표시.png) <b>Allowable Load Torque</b>

Table 3-2 Allowable Load Torque
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">Robot Model</th>
    <th class="tg-zegx" colspan="3">Allowable Load Torque</th>
  </tr>
  <tr>
    <th class="tg-zegx">R2 Axis Rotation</th>
    <th class="tg-zegx">B Axis Rotation</th>
    <th class="tg-zegx">R1 Axis Rotation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">YS080</td>
    <td class="tg-nrix" colspan="2">Less than 400 N·m(40.8 kgf·m)</td>
    <td class="tg-nrix">200 N·m(20.4 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-nrix">YS100A</td>
    <td class="tg-nrix" colspan="2">Less than 490 N·m(50.0 kgf·m)</td>
    <td class="tg-nrix">245 N·m(25.0 kgf·m)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH050</td>
    <td class="tg-nrix" colspan="2">Less than 216 N·m(22.0 kgf·m)</td>
    <td class="tg-nrix">Less than 147 N·m(15.0 kgf·m)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH030L</td>
    <td class="tg-nrix" colspan="2">Less than 200 N·m(20.4 kgf·m)</td>
    <td class="tg-nrix">Less than 100 N·m(10.2 kgf·m)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH050T</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">Less than 216 N·m(22.0 kgf·m)</td>
    <td class="tg-nrix">Less than 147 N·m(15.0 kgf·m)</td>
  </tr>
</tbody>
</table>
# 3.6.2. Permitted inertia moment estimation

Loads must be kept below maximum conditions shown in [Figure 3.8] ~ [Figure 3.11]. 

*	Step 1

    Calculate the inertia moment value of the load at each wrist axis center (Ja4, Ja5, Ja6)(J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - Inertia moment from R2 axis rotation center

    J<sub>a5</sub> - Inertia moment from B axis rotation center

    J<sub>a6</sub> - Inertia moment from R1 axis rotation center

*	Step 2

    Check if the inertia moment is under the thread according to the permissible inertia moment table.



![](../../_assets/그림_3.12_손목축_부하조건.png)

Figure 3.12 Wrist Axis Load Condition: [YS080/YS100A/HH050/HH030L/HH050T]

<br>

![](../../_assets/작은주의표시.png) <b>Allowable Moment of Inertia</b>

Table 3-3 Allowable Moment of Inertia

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">Robot Model</th>
    <th class="tg-zegx" colspan="3">Allowable Moment of Inertia</th>
  </tr>
  <tr>
    <th class="tg-zegx">R2 Axis Rotation</th>
    <th class="tg-zegx">B Axis Rotation</th>
    <th class="tg-zegx">R1 Axis Rotation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">YS080</td>
    <td class="tg-nrix" colspan="2">30 kg·m²(3.06 kgf·m·s²)</td>
    <td class="tg-nrix">20 kg·m²(2.04 kgf·m·s²)</td>
  </tr>
  <tr>
    <td class="tg-nrix">YS100A</td>
    <td class="tg-nrix" colspan="2">40 kg·m²(4.08 kgf·m·s²)</td>
    <td class="tg-nrix">25 kg·m²(2.55 kgf·m·s²)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH050</td>
    <td class="tg-nrix" colspan="2">30 kg·m²(2.04 kgf·m·s²)</td>
    <td class="tg-nrix">15 kg·m²(1.53 kgf·m·s²)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH030L</td>
    <td class="tg-nrix" colspan="2">15 kg·m²(1.53 kgf·m·s²)</td>
    <td class="tg-nrix">10 kg·m²(1.02 kgf·m·s²)</td>
  </tr>
    <tr>
    <td class="tg-nrix">HH050T</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">30 kg·m²(2.04 kgf·m·s²)</td>
    <td class="tg-nrix">15 kg·m²(1.53 kgf·m·s²)</td>
  </tr>
</tbody>
</table># 3.6.3. Example of permitted torque and inertia moment calculation (HS180 Case)

(1)	Case #1 Simple 2-D model

![](../../_assets/그림_3.14_2차원_부하_모델.png)

Figure 3.13 2-D load model



M - Load weight

J<sub>xx</sub> - Inertia moment in X direction from weight center of load

J<sub>yy</sub> - Inertia moment in Y direction from weight center of load

J<sub>zz</sub> - Inertia moment in Z direction from weight center of load

J<sub>a4</sub> - Inertia moment from R2 axis rotation center

J<sub>a5</sub> - Inertia moment from B axis rotation center

J<sub>a6</sub> - Inertia moment from R1 axis rotation center


 
<br></br>
☞ Load condition: Stainless steel with length and width of 260mm and thickness of 260mm (Mass 138.15kg)

① 	Weight limitation

Load weight: 138.15 ≤180 kg


   <br>

② Permitted torque limit 

Location of B axis weight center L<sub>X</sub> = 350mm, L<sub>Y</sub> = 0mm, L<sub>Z</sub> = -60mm

The distance from the axis B and R1 to the center of gravity can be calculated as follows.

![](../../_assets/3.6.3_수식1.png)


<br>

③	Permitted inertia moment limit

Inertia moment of load from the weight center  J<sub>xx</sub>= 1.56kgm², J<sub>yy</sub>= 1.56 kgm², J<sub>zz</sub>= 1.56 kgm²


![](../../_assets/3.6.3_수식2.png)


<br>
  
④	Conclusion

It is safe because the weight, torque and inertia moment all satisfy the limited condition.

<br></br>

(2)	Case #2 Complicated 3-D model

![](../../_assets/그림_3.15_3차원_부하_모델_2D_형상.png)

Figure 3.14 3-D load model 2-D shape

<br></br>

Aluminum block shape combination

(σ=0.0027 g/mm<sup>3</sup> : 176.3 kg)

m1 (60×300×300)	 14.6kg

m2 (480×440×220)	125.4kg

m3 (280×300×160)	 36.3kg

<br>

mi - Weight of i block load

L<sub>xi</sub> - Weight center location in X axis direction of “i” block 

L<sub>yi</sub> - Weight center location in Y axis direction of “i” block 

L<sub>zi</sub> - Weight center location in Z axis direction of “i” block 

<br>

①	Weight limitation

부하 중량: 176.3 ≤180 kg

<br>

②	Permitted torque limit

You can calculate the weight center location for the total load from the B axis rotation center as follows.

![](../../_assets/3.6.3_수식3.png)


<br>


he weight center location for the total load from the B axis rotation center
L<sub>x</sub> = 520.85mm, L<sub>y</sub> = 0mm, L<sub>z</sub>= -238.47mm

<br>

![](../../_assets/3.6.3_수식4.png)

<br>

x1 y1 z1 – x, y and z direction length of block m1

x2 y2 z2 – x, y and z direction length of block m2

x3 y3 z3 – x, y and z direction length of block m3

<br>

L<sub>X1</sub>, L<sub>Y1</sub>, L<sub>Z1</sub> - Weight center location of block m1 from B axis rotation center

L<sub>X2</sub>, L<sub>Y2</sub>, L<sub>Z2</sub> - Weight center location of block m2 from B axis rotation center

L<sub>X3</sub>, L<sub>Y3</sub>, L<sub>Z3</sub> - Weight center location of block m3 from B axis rotation center

<br>

J<sub>xx1</sub>, J<sub>yy1</sub>, J<sub>zz1</sub> – Inertia moment by x, y and z axis from the weight center of block m1

J<sub>xx2</sub>, J<sub>yy2</sub>, J<sub>zz2</sub> – Inertia moment by x, y and z axis from the weight center of block m2

J<sub>xx3</sub>, J<sub>yy3</sub>, J<sub>zz3</sub> – Inertia moment by x, y and z axis from the weight center of block m3


![](../../_assets/그림_3.16_3차원_부하_모델_3D_형상.png)

Figure 3.15 3-D load model 3-D shape

<br>

③	Permitted inertia moment limit

Table 3-4 Inertia moment from weight center by block
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1e26{background-color:#f8f8be;color:#000000; font-weight:bold;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">Block weight(kg)</th>
    <th class="tg-1e26">Weight center(L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>)</th>
    <th class="tg-1e26">J<sub>xx</sub></th>
    <th class="tg-1e26">J<sub>yy</sub></th>
    <th class="tg-1e26">J<sub>zz</sub></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-amwm">m<sub>1</sub>(14.6)</td>
    <td class="tg-baqh">(0.25, 0, 0)</td>
    <td class="tg-baqh">0.219 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>2</sub>(125.4)</td>
    <td class="tg-baqh">(0.48, 0, -0.26)</td>
    <td class="tg-baqh">2.530 kgm²</td>
    <td class="tg-baqh">2.915 kgm²</td>
    <td class="tg-baqh">4.433 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>3</sub>(36.3)</td>
    <td class="tg-baqh">(0.89, 0, -0.26)</td>
    <td class="tg-baqh">0.350 kgm²</td>
    <td class="tg-baqh">0.314 kgm²</td>
    <td class="tg-baqh">0.509 kgm²</td>
  </tr>
</tbody>
</table>

<br>

![](../../_assets/3.6.3_수식5.png)

<br>

④	Conclusion

It is safe because the weight, torque and inertia moment all satisfy the limited condition.

# 4. Inspection

This chapter describes regular inspection, disassembly, and adjustment necessary to maintain the performance of the robot for a long time.# 4.1. Inspection Schedule

Inspection is positively necessary to continue and maintain the high performance of robot for long-term operation.
There are daily inspection and regular inspection. [Table 4-1] shows basic periods for regular inspections, so inspectors should make an inspection according to the indicated periods.  
And overhaul every 35,000 operating hours.  

The inspection periods have been reviewed for SPOT Welding. In case of high precision work such as handling, it is recommended to inspect at the half intervals of that period as shown in [Table 4-1].
If you have difficulty in understanding the inspection and adjustment methods, please contact the Hyundai Robotics A/S Center (Customer Support).


<br>
Table 4-1 Inspection Schedule
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000; font-weight:bold;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Daily inspection</th>
    <th class="tg-wa1i">Daily</th>
    <th class="tg-nrix">MANIPULATOR, MOTOR, REDUCER</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jafi" rowspan="3">Regular Inspection</td>
    <td class="tg-wa1i">3months</td>
    <td class="tg-nrix">WIRING, BOLTS, REDUCER</td>
  </tr>
  <tr>
    <td class="tg-wa1i">1 year</td>
    <td class="tg-nrix">LIMIT SWITCH / DOG, BRAKE</td>
  </tr>
</tbody>
</table># 4.2. Inspection Item and Period

Table 4-2 Inspection Items and Periods

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi" rowspan="2">No</th>
    <th class="tg-jafi" colspan="3">Inspection Intervals</th>
    <th class="tg-jafi" rowspan="2">Inspection Items</th>
    <th class="tg-jafi" rowspan="2">Inspection method</th>
    <th class="tg-jafi" rowspan="2">Standards</th>
    <th class="tg-jafi" rowspan="2">Remark</th>
  </tr>
  <tr>
    <th class="tg-jafi">Daily</th>
    <th class="tg-jafi">3months</th>
    <th class="tg-jafi">1year</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i" colspan="8">Robot Manipulator and Axes common</td>
  </tr>
  <tr>
    <td class="tg-wa1i">1</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Cleaning</td>
    <td class="tg-nrix">Examine dirt and dust with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">2</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Inspection wiring</td>
    <td class="tg-nrix">· Examine any cable damages<br>
· Examine cable fixing bracket tightening, paint marking with naked eyes<br>
· Examine any cable cover damages with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">3</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Main bolts</td>
    <td class="tg-nrix">Examine paint marking with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">4</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">Limit Switch/ Dog</td>
    <td class="tg-nrix">Check the ON-OFF function of limit switch</td>
    <td class="tg-nrix">Check if the emergency stop lamp is on when the limit switch is ON.</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">5</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Motor</td>
    <td class="tg-nrix">Check the abnormal heating<br>Check the abnormal sound</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">6</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">Brake</td>
    <td class="tg-nrix">Check the ON/OFF operation of brake release switch
Note) Turn the switch off in a second because the ARM of working axis may be dropped when the brake release switch is on</td>
    <td class="tg-nrix">When the brake release switch is OFF, ARM of End Effect will not be dropped.</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i" colspan="8">Axis S, H, V</td>
  </tr>
  <tr>
    <td class="tg-wa1i">7</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Reducer</td>
    <td class="tg-nrix">Check the abnormal sound<br>Check the shaking(vibrating)</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
<tr>
    <td class="tg-wa1i" colspan="8">Axis R2, B, R1</td>
  </tr>
  <tr>
    <td class="tg-wa1i">8</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Reducer</td>
    <td class="tg-nrix">Check the abnormal sound<br>Check the shaking(vibrating)
</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">9</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">End Effect tightening bolts</td>
    <td class="tg-nrix">Examine paint marking with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">10</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Diversion</td>
    <td class="tg-nrix">There is any diversion by rotating each axis to the right and reverse direction</td>
    <td class="tg-nrix">Should not feel diversion by touch</td>
    <td class="tg-nrix"></td>
  </tr>
</tbody>
</table>


<br>

*	If the robot is utilized in adverse condition(such as spot welding, grinding, etc.), perform the inspection more frequently to ensure proper reliability of the robot system
*	Inspect all visible cabling, and replace them if damaged.
*	Check the mechanical bumper devices for deformation and damage. If the bumper or Dog is bent, replace it immediately.
*	Check the tightening torque of main bolts as shown in [Figure 4.1] ~ [Figure 4.2].
*	Check the abnormal noise in an automatic or teaching mode in order to ensure the condition of power transmission (such as motor, reducer, etc).
 

 


# 4.3. Inspection of Main External Bolts


The recommended bolt torque is shown in [Figure 4.1] ~ [Figure 4.2].
Apply the appropriate torque, where required, using the torque wrench and place the paint marking where the check-up is completed.

Table 4-3 Inspection part for main bolts

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-t1e1{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-1e26{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">Inspection parts</th>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">Inspection parts</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-t1e1">1</td>
    <td class="tg-baqh">H-axis reducer seal bolt</td>
    <td class="tg-t1e1">6</td>
    <td class="tg-baqh">ARM PIPE seal bolt</td>
  </tr>
  <tr>
    <td class="tg-t1e1">2</td>
    <td class="tg-baqh">H-axis motor seal bolt</td>
    <td class="tg-t1e1">7</td>
    <td class="tg-baqh">R2-axis reducer seal bolt</td>
  </tr>
  <tr>
    <td class="tg-t1e1">3</td>
    <td class="tg-baqh">V-axis reducer seal bolt</td>
    <td class="tg-t1e1">8</td>
    <td class="tg-baqh">Wrist assembly seal bolt</td>
  </tr>
  <tr>
    <td class="tg-t1e1">4</td>
    <td class="tg-baqh">V-axis motor seal bolt</td>
    <td class="tg-t1e1">9</td>
    <td class="tg-baqh">B-axis reducer seal bolt</td>
  </tr>
  <tr>
    <td class="tg-t1e1">5</td>
    <td class="tg-baqh">Upper plate of balance spring seal bolt</td>
    <td class="tg-t1e1">10</td>
    <td class="tg-baqh">R1-axis reducer seal bolt</td>
  </tr>
  </tr>
</tbody>
</table>

![](../_assets/그림_4.1_주요_볼트_점검_부위.png)

Figure 4.1 Inspection Part for Main Bolts [YS080/YS100A/HH050/HH030L/HH050T]# 5. Maintenance
# 5.1. Grease replacement & Injecting grease after replacing the reducer

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 40 height = 40>
    </div>  
    </td>
    <td colspan="4">If the grease is not properly injected, the internal pressure in the injection part may suddenly increase, causing the oil seal damage, oil leakage, and abnormal operation. Abnormal sound may be generated when replacing the current grease with new grease of a different specification, so make sure that different types of grease should not be mixed together. Therefore, you must observe the following items when injecting grease.</td>
  </tr>
</thead>
</table>  
</blockquote>

<ol style="list-style-type:decimal" start="1">
		<li>
Make sure to wear safety glasses before injecting grease and inspection
  </li><br>
    <li>
Before starting to grease, remove the plug from the grease outlet
  </li><br>
    <li>
When loosening a plug, grease and the plug could be discharged. Block the outlet with a thick cloth to prevent injuries caused by discharged grease or plug, and keep a distance away for safety. (Do not look into the grease outlet.)
  </li><br>
    <li>
Whenever possible, avoid using a compressed-air pump, powered by the factory air supply. If the use of a compressed-air pump is unavoidable, restrict the greasing pressure less than 1.5bar(1.5kgf/cm2)
  </li><br>
    <li>
Use grease only of the specified type. If not, may damage the reducer or lead to other problems
  </li><br>
    <li>
After injecting it, remove the residual pressure from each axis and tighten the plugs according to the given procedure.
<p>

  <style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow">Axis</th>
    <th class="tg-c3ow">Operation angle (1 Axis /2 Axis /3 Axis)</th>
    <th class="tg-c3ow">Operation speed</th>
    <th class="tg-c3ow">Operation time</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">1 Axis ~ 3 Axis</td>
    <td class="tg-c3ow">80°/90°/70° or more</td>
    <td class="tg-c3ow">50 %</td>
    <td class="tg-c3ow">Least 20 min</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4 Axis ~ 6 Axis</td>
    <td class="tg-c3ow">60°/120°/60° or more</td>
    <td class="tg-c3ow">100 %</td>
    <td class="tg-c3ow">Least 20 min</td>
  </tr>
    <tr>
    <td class="tg-c3ow">Arm Frame Gear Box</td>
    <td class="tg-c3ow">60°/120°/60° or more</td>
    <td class="tg-c3ow">100 %</td>
    <td class="tg-c3ow">Least 20 min</td>
  </tr>
</tbody>
</table>
        </li><br>
        <li>
After greasing, confirm that no grease is leaking from the grease outlet and that the grease bath is not pressurized, then re-attach the plug in the grease outlet.
    </li><br>
    <li>
To prevent accidents caused by slipping, completely remove any excess grease from the floor or robot.
    </li><br>
    <li>
When an ambient temperature is more than 35℃, be sure to shorten the period of replenishment in half.
    </li><br>
    <li>
When replacing grease, replace the specified amount and inject new grease as much as the amount of the discharged grease.
    </li><br>
    <li>
If an abnormal sound is generated from the reducer part during operation after replenishment or replacement of grease, at low temperature, at low speed, or after long-term non-operation, you need to operate the robot while checking the state of the abnormal sound for one or two days. Abnormal sound caused by grease will disappear.
    </li><br>
    <li>
If the grease with a different specification is injected into the reducer part that has been greased already, an abnormal sound may occur. Therefore, do not mix these different types of grease.
    </li><br>
    <li>
An abnormal sound may occur even if the existing grease is replaced with the new grease of the same designated specification as the existing grease.
    </li><br>
    <li>
Replacing the grease is not for completely removing the existing grease. A significant amount of existing grease will remain.
</li><br>	
</ol>

<br>
■ Periodic Replacement

-	S-axis Reducer, Arm Frame Gear Box : 24,000 hours
-	Other Reducers : 12,000 hours

 <br>

If there is still noise in the reducer even after using specified grease, check the state closely for 1-2 days during operation. Generally, the noise will go away.
(The noise will go away if you run the axis at a high speed for 5-10 minutes).
- It can be checked if the abnormal sound will disappear even when the concerned axis is operated at high speed for about 5 to 10 minutes or more.
- When the old grease is discharged as much as possible (about 90% or more) and replaced with new grease, the abnormal grease sound can be minimized. (When the grease is discharged while the axis is rotating at low speed, the grease discharge time can be shortened.)


An abnormal sound usually occur in the following cases:
-	During operation after replacement of grease/reducer
-	During operation after a long-term non-operation
-	During operation at low speed
-	During operation at low temperature 
-	When using unspecified grease 
-	Mixing grease of different specifications
 


<br><br>

■ Rate of the grease injection amount based on VIGO GREASE

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">VIGO GREASE RE0</th>
    <th class="tg-c3ow">RV GREASE LB00</th>
    <th class="tg-c3ow">REMARKS</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Specific gravity (25°C)</td>
    <td class="tg-c3ow">0.9g/㎤</td>
    <td class="tg-c3ow">0.87g/㎤</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Rate of the grease injection amount</td>
    <td class="tg-c3ow">100%</td>
    <td class="tg-c3ow">96.7%</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody>
</table>

- VIGO GREASE RE0 → RV GREASE LB00	


<br><br>
	
■ Rate of the grease injection amount based on EUREKA

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow"></th>
    <th class="tg-c3ow">EUREKA 114 No.0</th>
    <th class="tg-c3ow">RV GREASE LB00</th>
    <th class="tg-c3ow">REMARKS</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">Specific gravity (25°C)</td>
    <td class="tg-c3ow">0.84g/㎤</td>
    <td class="tg-c3ow">0.87g/㎤</td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">Rate of the grease injection amount</td>
    <td class="tg-c3ow">100%</td>
    <td class="tg-c3ow">103.60%</td>
    <td class="tg-c3ow"></td>
  </tr>
</tbody>
</table>

- EUREKA 114 No.0 → RV GREASE LB00		
- Please avoid using EUREKA grease. When the use of EUREKA grease is necessary, please contact us.
# 5.1.1. S-Axis Reducer



![](../../_assets/그림_5.1_1축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">If grease is added without removing the outlet plug, the grease will go inside the motor and may damage it. It is absolutely necessary to remove the plug.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>	Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type  : VIGO GREASE RE0
-	Amount of grease  : 2,755cc(2.480g)
 <p>

-	Grease type  : RV GREASE LB00
-	Amount of grease  : 2,755cc(2,397g)
                                                            
</li><br>
 <li>
The grease replacement is complete when new grease appears in the outlet port. The new grease can be distinguished from the old one by color.
</li><br>
 <li>Move the S-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
 <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
 <li>Remove the grease nipple of the inlet and the plug of the air vent, and assemble the inlet plug and air vent set.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer.
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple A-PT1/4.
</li><br>
 <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
 <li>Remove the plug G1/4 of the grease outlet.
</li><br>
 <li>Inject the grease into the grease inlet using a grease gun.
</li><br>
 <li>The grease replacement is complete when new grease appears in the outlet port.
</li><br>
 <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
 <li>Remove the grease nipple of the inlet and the plug of the air vent, and assemble the inlet plug and air vent set.

<p>

-	Grease type  : VIGO GREASE RE0
-	Amount of grease  : 3,444cc(3.100g)
 <p>

-	Grease type  : RV GREASE LB00
-	Amount of grease  : 3,444cc(2,996g)
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection
<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease
</li><br>
 <li>Operate it within a range without surrounding and interference under the following conditions

①	Operation angle : 80° or more

②	Operation speed : 50%

③	Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
 <li>Wipe the outlet port with a cloth and attach the plug
</li>
</ol>
 
# 5.1.2. H-Axis Reducer




![](../../_assets/그림_5.2_h축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">If grease is added without removing the outlet plug, it cause damage to the seal of reducer and grease will go inside the motor and may damage it. It is absolutely necessary to remove the plug.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare the grease nipple A-PT1/4, and then set the H-axis arm perpendicularly.
(H:90°-Floor Type, H:0°-Shelf Type )
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type  : VIGO GREASE RE0
-	Amount of grease  : 1,689cc (1.520g)
 <p>

-	Grease type  : RV GREASE LB00
-	Amount of grease  : 1,689cc(1,469g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port. The new grease can be distinguished from the old one by color.
</li><br>
    <li>Move the H-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer.
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare the grease nipple A-PT1/4, and then set the H-axis arm perpendicularly.
(H:90°-Floor Type, H:0°-Shelf Type ) 
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type  : VIGO GREASE RE0
-	Amount of grease  : 2,111cc(1.900g)
 <p>

-	Grease type  : RV GREASE LB00
-	Amount of grease  : 2,111cc(1,837g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection.
<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease.
</li><br>
    <li>Operate it within a range without surrounding and interference under the following conditions.

①	Operation angle: 90° or more

②	Operation speed: 50%

③	Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
    <li>Wipe the outlet port with a cloth and attach the plug.
</li>
</ol>
 
# 5.1.3. V-Axis Reducer

![](../../_assets/그림_5.3_v축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">If grease is added without removing the outlet plug, it cause damage to the seal of reducer and grease will go inside the motor and may damage it. It is absolutely necessary to remove the plug.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple A-PT1/4 and then make the R2-Axis 0°degree.
(V:0°-Floor Type, V:-90°-Shelf Type)
 </li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
 </li><br>
    <li>Remove the plug G1/4 of the grease outlet.
 </li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 889cc (800g)
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 889cc(773g)
 </li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
The new grease can be distinguished from the old one by color.
</li><br>
    <li>Move the H-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare the grease nipple A-PT1/4, and then set the V-axis arm horizontally.
(V:0°-Floor Type, V:-90°-Shelf Type)
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 1,111cc (1.000g)
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 1,111cc(967g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection
<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease.
</li><br>
    <li>Operate it within a range without surrounding and interference under the following conditions.

①	Operation angle: 70° or more

②	Operation speed: 50%

③	Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
    <li>Wipe the outlet port with a cloth and attach the plug.
</li>
</ol>
 
# 5.1.4. R2-Axis Reducer (HH050T - Grease not injected into R2 axis)

![](../../_assets/그림_5.4_r2축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Do not inject excessive grease. The excessive grease would cause an abnormal operation.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple A-PT1/8 and then make the R2-Axis 0°degree.
</li><br>
    <li>Remove the plug R1/8 of the grease inlet, and fasten the grease nipple A-PT1/8.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 586cc(528g)
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 586cc(510g)
</li><br>
<li>
The grease replacement is complete when new grease appears in the outlet port.
The new grease can be distinguished from the old one by color.
</li><br>
<li>Move the R2-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
<li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
<li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple A-PT1/8 and then make the R2-Axis 0°degree.
</li><br>
<li>Remove the plug R1/8 of the grease inlet, and fasten the grease nipple A-PT1/8.
</li><br>
<li>Remove the grease outlet plug.
</li><br>
<li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 733cc (660g)
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 733cc(638g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection


<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease.
</li><br>
    <li>Operate it within a range without surrounding and interference under the following conditions.

①	Operation angle: 60° or more

②	Operation speed: 100%

③	Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
    <li>Wipe the outlet port with a cloth and attach the plug.
</li>
</ol>
 
# 5.1.5. B-Axis Reducer

![](../../_assets/그림_5.5_b축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Do not inject excessive grease. The excessive grease would cause an abnormal operation.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple (A-PT1/4) and then make the R2, B-Axis 0°degree.
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 205cc (184g) 
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 205cc(178g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port. 
The new grease can be distinguished from the old one by color.
</li><br>
    <li>Move the R2-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple (A-PT1/4) and then make the R2, B and R1-Axis 0°degree.
</li><br>
    <li>Remove the plug G1/4 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the plug G1/4 of the grease outlet.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 256cc (230g) 
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 256cc(223g)
</li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection
<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease.
</li><br>
    <li>Operate it within a range without surrounding and interference under the following conditions.

①	Operation angle: 60° or more

②	Operation speed: 100%

③	Operation time: Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
    <li>Wipe the outlet port with a cloth and attach the plug.
</li>
</ol>
 

# 5.1.6. R1-Axis Reducer

![](../../_assets/그림_5.6_r1축_감속기_그리스_주입_배출구.png  )

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Do not inject excessive grease. The excessive grease would cause an abnormal operation.</td>
  </tr>
</thead>
</table>  
</blockquote>

<br>




■	Grease Replacement

<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple (A-PT1/4) and then make the R2, B and R1-Axis 0°degree.
 </li><br>
    <li>Remove the plug TR6X6 of the grease inlet, and fasten the grease nipple A-PT1/4.
 </li><br>
    <li>Remove the plug G1/4 of the grease outlet.
 </li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 240cc (216g)  
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 240cc(209g) 
  </li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port. 
The new grease can be distinguished from the old one by color.
</li><br>
    <li>	Move the R2-Axis for a few minutes to eject the old grease and then add grease until the new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>



<br>

■	Injecting grease after replacing the reducer
<ol style="list-style-type:decimal" start="1">
    <li>
Prepare a grease nipple (A-PT1/4) and then make the R2, B and R1-Axis 0°degree.
</li><br>
    <li>Remove the plug TR6x6 of the grease inlet, and fasten the grease nipple A-PT1/4.
</li><br>
    <li>Remove the grease outlet plug.
</li><br>
    <li>Inject the grease into the grease inlet using a grease gun.

<p>

-	Grease type : VIGO GREASE RE0
-	Amount of grease : 300cc (270g)  
 <p>

-	Grease type : RV GREASE LB00
-	Amount of grease : 300cc(261g) 
  </li><br>
    <li>
The grease replacement is complete when new grease appears in the outlet port.
</li><br>
    <li>Discharge excessively fueled grease and residual pressure. (Refer to the discharge procedure below.)
</li><br>
    <li>Remove the grease nipple of the inlet and assemble the inlet plug.
</li>
</ol>

<br>

■	Procedure in discharging excessively fueled grease and residual pressure after grease replacement and injection
<ol style="list-style-type:decimal" start="1">
    <li>Attach a grease receiver or a hose to the grease outlet to prevent contamination from discharged grease.
</li><br>
    <li>Operate it within a range without surrounding and interference under the following conditions.

①	Operation angle: 60° or more

②	Operation speed: 100%

③	Operation time: 1.5 hours or more

④	Work so that the injected amount and the discharged amount are the same. If the discharged amount is less, the residual amount needs to be discharged through the inlet.
</li><br>
    <li>Wipe the outlet port with a cloth and attach the plug.
 </li>
</ol>
 # 5.1.7. Arm Frame - Gear Box

![](../../_assets/그림_5.7_arm_frame_기어박스.png  )


■	Grease Replenishment

<ol style="list-style-type:decimal" start="1">
    <li>
Remove the grease outlet plug.
    </li><br>
    <li>
Inject the grease into the grease inlet using a grease gun.
<p>

-	Grease type : GADUS S2 V46 2
-	Amount of grease : 30cc 
  </li><br>
    <li>
Reinstall the grease plugs with seal tape.
</li>
</ol>
# 5.2. Battery Replacement

The position data of each axis is preserved by the backup batteries. The batteries need to be replaced every two years. To replace batteries observe the following procedure.



<ol style="list-style-type:decimal" start="1">
    <li>
With the power of the control in on condition, press the emergency stop button.
<p>
<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Replacing the batteries with the power supply turned off causes all current position data to be lost. Therefore, zeroing will be required again.</td>
  </tr>
</thead>
</table>  
</blockquote>
    </li><br>
    <li>
Separate the cover of the battery location by each axis.
    </li><br>
    <li>
Remove the old battery.
    </li><br>
    <li>
Insert the new battery. Pay attention to the direction.
<p>

-	Battery Spec. : ER6V-T1 (AA) 3.6V<br>
-	Manufacturer  : TOSHIBA

</li><br>
<li>
Install the cover to its original location.
</li>
</ol>


![](../../_assets/그림_5.1_배터리_교환_위치.png)

Figure 5.1 Location of Battery Replacement



<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
    <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">
-	Do not dispose the batteries. Dispose of the battery with industrial waste according to the laws and other rules in the country where the controller is installed.<p>
-	Do not recharge the batteries, otherwise batteries may result in exploding or overheating.<p>
-	Do not use any batteries other than the recommended one. <p>
-	Change the batteries only with the specified one. <p>
-	Do not short positive and negative terminals of battery. <p>
-	Do not expose batteries to high temperature or flame

</td>
  </tr>
</thead>
</table>  
</blockquote>
# 5.2.1. Instructions for Battery Storage

<ol style="list-style-type:decimal" start="1">
    <li>
Do not keep the batteries at a high temperature and humidity. Keep it in the well-ventilating place without dew condensation. 
    </li><br>
    <li>
Keep it in a normal temperature, at relatively constant temperature(20±15℃) and at relative humidity of less than 70%. 
    </li><br>
    <li>
Check the battery storage every six months, and manage them with first-in-first-out.
</li>
</ol>
# 5.3. Internal Wiring

Replacement cycle of internal wiring depends on follows.

-	Continuous operation
-	Operating speed
-	Atmosphere/environment

Inspect on a regular basis, every three months and check any damage on the cables or cable protect spring. If any damage, replace it. 

Replace the cable every 16,000 operating hours regardless of working condition.



<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td> 
    <td colspan="4">
-	As all the wires are flexible type, do not use any wires other than specified one.<p>
-	Wiring replacement must be done by unit. <p>
-	Do not use any Cable, protective spring, and Hose that have external damage as they may cause future problems. <p>
-	When purchasing robot cables, make inquiry of our service office about wiring type.<p>
-	Specify the length of wiring for connecting the robot with the controller.
</td>
  </tr>
</thead>
</table>  
</blockquote>


# 6. Troubleshooting



# 6.1. Troubleshooting Procedure 

If a failure occurs during robot's operation, but it does not stem from the controller, it must be caused by damage on machine parts. The way to troubleshoot as quick and easy as possible should be to diagnose the problem. In addition, it is necessary to determine which parts cause the problem.

<ol style="list-style-type:decimal" start="1">
	<li>Step 1: Which axis occurs the problem?

First of all, check which axis causes the malfunction. In case that it is hard to detect the problem, check the following possible mechanical defaults,

*	Is there any parts making noise?
*	Is there any parts generating an overheating?
*	Is there any parts have a play or backlash? 
</li><br>
    <li>
Step 2: Which parts have been damaged?

If the abnormal axes are determined, investigate which parts cause trouble. There could be many causes for one phenomenon. Refer to [Table 6-1] for the cause and phenomenon of the trouble.
</li><br>
    <li>
Step 3: Dealing with malfunction parts

If the malfunction parts are confirmed, conduct relevant repair procedure based on the chapter 6.3 Diagnostics and Resolutions for Major Parts Failure. Contact our service office if you have any difficulties in dealing with problems. 
</li>
</ol> 

# 6.2. Trouble Symptoms and Possible Causes

As shown in [Table 6-1], there may be many parts as the cause of one phenomenon. 
Refer to next page to determine which part is malfunction.


<br>
Table 6-1 Trouble phenomenon and cause

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Defect parts/<br>Trouble phenomenon</th>
    <th class="tg-jafi">Reducer</th>
    <th class="tg-jafi">Brake</th>
    <th class="tg-jafi">Motor</th>
    <th class="tg-jafi">Encoder</th>
    <th class="tg-jafi">Backlash</th>
    <th class="tg-jafi">Grease</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">Overload         [Note 1]</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">Displacement</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Abnormal sound occurrence</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-wa1i">O<br>[Note 5]</td>
  </tr>
  <tr>
    <td class="tg-wa1i">Noise in operation [Note 2]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-wa1i"></td>
  </tr>
    <tr>
    <td class="tg-wa1i">Staggering at stop [Note 3]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-wa1i"></td>
  </tr>
    <tr>
    <td class="tg-wa1i">Irregular twitching [Note 4]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-wa1i"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Abnormal deviation</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Free fall of an axis</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Overheating</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
  </tr>
  <tr>
    <td class="tg-wa1i">Incorrect action and out of control movement</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
</tbody>
</table>

<br>

[Note 1] Overload ----------------- Phenomenon occurring when a load exceeds the rated motor load.<br>
In specific, thermal relay of circuit protector is tripped.<br>
[Note 2] Noise in operation ----- Phenomenon which occurs vibration on operation.<br>
[Note 3] Staggering at stop ----- Phenomenon which gives oscillating motion when the robot stops<br>
[Note 4] Irregular twitching ----- Phenomenon which gives sporadic twitching when the robot is not in motion.<br>
[Note 5] If there is noise from the greased part of reducer at reduced-speed operation, check the state closely for 1-2 days during operation. Generally, the noise will go away.<br>
(The noise will go away if you run the axis at a high speed for 5-10 minutes).

<br>

The noise may be caused by following reasons.
1.	Operation after greasing or replacing the reducer
2.	Operation after long-term storage
3.	Operation at a low speed
4.	Operation at a low temperature


# 6.3. Diagnostics and Resolutions for Major Parts Failure# 6.3.1. Reducer

Vibration and abnormal sound will be occurred when a reducer is damaged. In this case, it causes overload and abnormal deviation disturbing normal operation. Sometimes overheating may result. The robot may also become completely immovable, or a position offset error may occur.

<img src="../../_assets/작은주의표시.png"> <b>[Main Axes (S, H, V)]</b>

When turning [ON][OFF] the brake release switch of axis H and axis V, be sure to take necessary precautions to prevent the ARM from dropping, and then switch the brake release [ON][OFF].

*	Diagnostics

    ①	Apply force to the 1st and the 2nd arms to investigate whether the bearings have any gap.<br>
    (When a chain block is to be used, maintain the 1st and the 2nd arms in their positions and check whether the bearings have any gap while not applying any load on the reducer.)<br>
    ②	Check if peripheral equipment has been contacted with the robot before the abnormality.


*	Resolution

    Replace the reducer. A chain block is needed to lift and hang the robot ARM. Contact our service office for any difficulties



<img src="../../_assets/작은주의표시.png"> <b>[Wrist Axes (R2, B, R1)]</b>

When turning [ON][OFF] the brake release switch, be sure to take necessary precautions to prevent the ARM from dropping, and then switch the brake release [ON][OFF].

*	Diagnostics

    ①	Check out any vibration, abnormal sound, or overheating of the reducer when the robot is in operation.<br>
    ②	Check out any play in the reducer by shaking the End Effector (such as spot gun and hand devices, etc.) back and forth.<br> 
    ③	Turn motor off, with the brake release switch [ON], and check that the axis can be rotated by hand. If not, the reducer is in bad condition.<br> 
    Check if peripheral equipment has been contacted with the robot before the abnormality.
    (Damage may occur to the reducer due to the contacting impact)

*	Resolution

    ①	Replace the reducer.<br>
    ②	Replace the entire wrist section.<br>
    (The replacement of entire wrist should be a quick and reliable resolution as it takes time and necessary equipment for reducer replacement)

 



# 6.3.2. Brake

In case of brakes failure, each axis possibly drops with the motors [OFF]. Or, in reverse, brakes possibly operate even with the motors [ON]. The latter causes overload and noise.

![](../../_assets/작은주의표시.png) When intending to operate the entire robot without the motors [ON], operate it with the brake release switch [ON]. Before turning the switch [ON], take necessary precautions to prevent the ARM from dropping as the robot ARM will drop by gravity.





*	Diagnostics

    Check if the brake can be heard in operation, by turning the brake release switch [ON] [OFF] alternately with the motors [OFF]. If not heard, the brake cable may be broken. (When operating the brake release switch [ON] [OFF], be careful of ARM dropping. The brake release switch is located on the panel in the controller cabinet door.)

*	Resolution

    If cables turn out to be good condition, replace the motor.





# 6.3.3. Motor


Motor failure causes abnormal operation of robot such as staggering at stop, irregular twitching and noise in operation. Besides, It may cause overheating and abnormal sound. 

Check the reducer and fulcrum bearing as well in order to determine which part causes the abnormality. It is because that similar phenomenon is observed when the reducer is damaged.

*	Diagnostics

    Check for overheating and abnormal sound.

*	Resolution

    Replace the motor.



# 6.3.4. Encoder


Position offset, malfunction, and out of control movement as well as staggering at stop, irregular twitching may occur when the Encoder is in bad condition. This case has nothing to do with such phenomena as mechanical abnormal sound, overheating, and vibration.

*	Diagnostics

    ①	Check for any encoder data failure.<br>
    ②	Use reference pins and blocks to check the positional data is correct at pin position.<br>
    ③	Check for any irregular variations in the encoder data when moving each robot axis.<br> 
    ④	Replace the servo amp board(BD542) to check errors. 
 
*	Resolution 

    ①	If cabling turns out to be in good condition without any damage, replace the encoder.<br>
    ②	If there is no error after replacing the servo amp board(BD542), replace the servo amp board.
 

# 6.4. Motor Replacement 


![](../../_assets/작은주의표시.png) <b>Warning</b>

This robot has a brake installed on the motor to maintain the position of the arm and when the motor is disassembled, the arm will fall. To prevent this, hang the arm with the crane or insert a fixating pin to keep the 1st and 2nd arms fixed.

When touching the motor immediately after the robot stops, check the temperature of the motor. The weights of the motor and reducer are as follows. When transporting the motor, be careful.



<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Axis</th>
    <th class="tg-jafi">S</th>
    <th class="tg-jafi">H</th>
    <th class="tg-jafi">V</th>
    <th class="tg-jafi">R2</th>
    <th class="tg-jafi">B</th>
    <th class="tg-jafi">R1</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Weight(kg)</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">8.2</td>
    <td class="tg-nrix">8.2</td>
    <td class="tg-nrix">8.2</td>
  </tr>
  <tr>
    <td class="tg-nrix">Weight(kg)<br>HH050T
</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">27.2</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">8.2</td>
    <td class="tg-nrix">8.2</td>
  </tr>
</tbody>
</table>

![](../../_assets/작은주의표시.png) <b>Warning</b>

In this work, there is a part performed with the motor [ON]. Therefore, perform the work in pairs. An observer must always be ready to activate an emergency stop. The other performs the work quickly and carefully. An escape route should be determined before starting work.
 
# 6.4.1. Necessary Tools and Parts

Table 6-2 Necessary Tools
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3xd{background-color:#f8f8be;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-uzvj{border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3xd">Tool Name</th>
    <th class="tg-c3xd">Axis Name</th>
    <th class="tg-c3xd">Part No.(Model)</th>
    <th class="tg-c3xd">Remark</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-uzvj" rowspan="2">Torque wrench<br>(Prepared by user)</td>
    <td class="tg-9wq8">S, H, V</td>
    <td class="tg-9wq8">M12 Torque wrench(Lock type)</td>
    <td class="tg-9wq8" rowspan="2">Use torque wrench and<br>extension on the market</td>
  </tr>
  <tr>
    <td class="tg-9wq8">R2, B, R1</td>
    <td class="tg-9wq8">M8 Torque wrench (Lock type)<br>M5 Torque wrench (Lock type)</td>
  </tr>
</tbody>
</table>

<br></br>

Table 6-3 Necessary Parts
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3xd{background-color:#f8f8be;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-uzvj{border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3xd">Part Name</th>
    <th class="tg-c3xd">Axis Name</th>
    <th class="tg-c3xd">Use or not</th>
    <th class="tg-c3xd">Part No.(Model)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-uzvj" rowspan="2">Dropping preventive bolt (Optional)</td>
    <td class="tg-9wq8">Axis H, V</td>
    <td class="tg-9wq8">O</td>
    <td class="tg-9wq8">M20×250(Standard)</td>
  </tr>
  <tr>
    <td class="tg-9wq8">Wrist (R2, B, R1)</td>
    <td class="tg-9wq8">-</td>
    <td class="tg-9wq8">-</td>
  </tr>
</tbody>
</table>


(When overhauling the robot, a leveling bulb can be used to focus on the precise starting point. To focus on the precise starting point, please contact us.)
 
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



# 6.4.2.1. Motor for main axis (Hi5)


![](../../../_assets/그림_6.2_s축모터.png)

Figure 6.2 Axis S motor assembly

<br>

![](../../../_assets/작은주의표시.png) <b>Caution</b>

If the entire upper arm is not completely attached to the mechanical stopper in a gravitational direction when replacing the motor of the V-axis, the upper arm may rotate when the motor is being dismantled.

<br>



![](../../../_assets/그림_6.3_h_v축모터.png)

Figure 6.3 Axis H&V Motor Assembly


# 6.4.2.2. Motor for main axis (Hi5a)


![](../../../_assets/그림_6.4_s축모터.png)

Figure 6.4 Axis S motor assembly


<br>


![](../../../_assets/그림_6.5_h축모터.png)

Figure 6.5 Axis H motor assembly

<br>


![](../../../_assets/그림_6.6_v축모터.png)

Figure 6.6 Axis V motor assembly# 6.4.2.3. Motor for wrist axis (Hi5/Hi5a)


![](../../../_assets/그림_6.7_손목축모터.png)

Figure 6.7 Wrist Axis Motor Assembly - R2 axis motor excluded (HH050T)
# 6.5. Encoder Zero Setting 

It is necessary to reset the origin when encoder data has been corrupted due to some problems and when the motor is replaced.

A scale or V-groove is used to determine the standard posture position for each axis of the robot. When the motor is replaced by the user, set the encoder using the scale or V-groove to have each axis at its original point.




![](../../_assets/작은주의표시.png) <b>Warning</b>

In this work, there is a part performing in the state of motor [ON]. Therefore, this work must be performed in pairs. One must always be ready to activate an emergency stop. The other must perform the work quickly but carefully. 
An escape route should be determined before starting work.
# 6.5.1. Zero Setting

<ol style="list-style-type:decimal" start="1">
<li>
Set the controller to teaching mode and set the robot to standby [ON] condition.
If the robot cannot be set to standby [ON] condition due to issues, use the brake cancel switch to set the reference location of the robot.
    </li><br>
    <li>
Move each axis to the basic posture to align it with the scale or V-groove.
    </li><br>
    <li>
Reset the Encoder. Refer to 『6.5.2 Encoder Reset』for the method of encoder reset.
    </li><br>
    <li>
Correct the encoder. Refer to 『Controller Operation Manual』.
    </li><br>
    <li>
Confirm that there is no problem in robot motion.
</li>
</ol>
<br>

![](../../_assets/그림_6.8_원점설정방법.png)

Figure 6.8 Method of Zero Setting [YS080/YS100A/HH050/HH030L] - [HH050T - R2 axis excluded]# 6.5.2. Encoder Reset

<ol style="list-style-type:decimal" start="1">
    <li>Turn off the motor.
    </li><br>
    <li>
Open the serial encoder reset window. (『[F2]: System』 → 『5: Initialize』 → 『4: Serial encoder reset』)

<br><br>

![](../../_assets/그림_6.4_시리얼_엔코더_리셋.png)
 

</li><br>
    <li>
Use keys like [↓], [↑], [SHIFT] + [←][→] to move to a desirable axis, then press the [Execute] key.
</li><br>
    <li>After the encoder is reset, please make sure the controller power is turned on.
</li>
</ol>
# 6.5.3. Encoder offset and Selection


*	It is necessary to compensate encoder data for the basic position of each axis.
*	Refer to 『Encoder offset』in the Controller Manual for details.


<b>[Encoder offset Screen]</b>

![](../../_assets/그림_6.5_엔코더_보정.png)



<ol style="list-style-type:decimal" start="1">
    <li>
Select the axis, move the axis to a standard position using the [Axis operation] key, and press the 『[F1]: Apply』key. 
    </li><br>
    <li>
Place the robot’s entire axis as the standard position using the [Axis operation] key and press the 『[F2]: Apply all』 key to carry out encoder offset correction for the entire axis.
    </li><br>
    <li>
To save the set data, press the 『[F7]: Complete』 key. The [ESC] key will prevent the changes being saved.
</li>
</ol>

<table>
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4"><b>Warning</b><br>
    In case of encoder DATA compensation after replacing motor, check if the motor power is on with the power 『ON』.</td>
  </tr>
</thead>
</table>  


# 7. Recommended Spare Parts

The recommended spare parts for robot are as follows. Please check robot serial number and manufacturing date when purchasing, and contact our service office.

<b>[Category]</b>

A : Regular maintenance parts(what is replaced regularly)

B : Essential spare parts (what is of high frequency)

C : Essential component parts

D : Machine parts

<br></br>
Table 7-1 Spare Parts List I
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Category</th>
    <th class="tg-jafi">Robot Applied</th>
    <th class="tg-jafi">PLATE No.</th>
    <th class="tg-jafi">Product Name and Specification</th>
    <th class="tg-jafi">Quantity</th>
    <th class="tg-jafi">Remark</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R7900004400<br>R7900004402</td>
    <td class="tg-nrix">VIGO GREASE RE0 1CAN=16KG<br>RV GREASE LB00 1CAN=16KG</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R7900054780</td>
    <td class="tg-nrix">GADUS GREASE(1CAN=15KG)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R1001-6202-0P2</td>
    <td class="tg-nrix">Encoder Battery</td>
    <td class="tg-nrix">6</td>
    <td class="tg-nrix">Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P01<br>R3123-7112-P01<br>R3120-7112-P01</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">S, H and V-axis Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P01<br>R3123-7312-P01<br>R3120-7312-P01</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">3</td>
    <td class="tg-nrix">R2, B and R1-axis Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH050T</td>
    <td class="tg-nrix">R3123-7312-P01<br>R3120-7312-P01</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">B and R1-axis Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P02<br>R3123-7112-P02<br>R3120-7112-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">S-Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3123-7212-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">H-Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P03<br>R3120-7212-P03</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">H-Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P03<br>R3123-7212-P03<br>R3120-7212-P03</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">V-Axis</td>
  </tr>
 <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P02<br>R3123-7312-P02<br>R3120-7312-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R2-Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7412-P01<br>R3123-7412-P01<br>R3120-7412-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">B-Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7412-P02<br>R3123-7412-P02<br>R3120-7412-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1 -Axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7412-001<br>R3123-7412-001<br>R3120-7412-001</td>
    <td class="tg-nrix">WRIST ASSY</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">WRIST ASSY</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-112<br>R3123-7112-112<br>R3120-7112-112</td>
    <td class="tg-nrix">INPUT GEAR(S)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For S-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3123-7212-112</td>
    <td class="tg-nrix">INPUT GEAR(H)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For H-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-112<br>R3120-7212-112</td>
    <td class="tg-nrix">INPUT GEAR(H)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For H-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-111<br>R3123-7212-111<br>R3120-7212-111</td>
    <td class="tg-nrix">INPUT GEAR(V)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For V-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-136<br>R3123-7312-136<br>R3120-7312-136</td>
    <td class="tg-nrix">R2 SPUR GEAR(INPUT)</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For R2-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-138<br>R3123-7312-138<br>R3120-7312-138</td>
    <td class="tg-nrix">R1 AND B SPUR GEAR(INPUT)</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">For B/R1-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P03<br>R3123-7112-P03<br>R3120-7112-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">For S-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P04<br>R3123-7112-P04<br>R3120-7112-P04</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For S-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P08<br>R3123-7112-P08<br>R3120-7112-P08</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For S-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P06<br>R3123-7112-P06<br>R3120-7112-P06</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For S-axis reducer<br>(BASE BODY)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7112-P13<br>R3123-7112-P13<br>R3120-7112-P13</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For S-axis reducer<br>(LOWER FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P04<br>R3123-7212-P04<br>R3120-7212-P04</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">For H/V-axis INPUT GEAR</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P06<br>R3123-7212-P06<br>R3120-7212-P06</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">H/For V-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P07<br>R3123-7212-P07<br>R3120-7212-P07</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For H-axis reducer<br>(LOWER FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P11<br>R3123-7212-P11<br>R3120-7212-P11</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For H-axis reducer<br>(UPPER FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P10<br>R3123-7212-P10<br>R3120-7212-P10</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For V-axis reducer<br>(UPPER FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7212-P05<br>R3123-7212-P05<br>R3120-7212-P05</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For V-axis reducer<br>(ARM FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P04<br>R3123-7312-P04<br>R3120-7312-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For R2-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P17<br>R3123-7312-P17<br>R3120-7312-P17</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">3</td>
    <td class="tg-nrix">For R2, B and R1-axis Motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P14<br>R3123-7312-P14<br>R3120-7312-P14</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For R2-axis reducer<br>(ARM PIPE)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7312-P15<br>R3123-7312-P15<br>R3120-7312-P15</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For R2-axis reducer<br>(WRIST BODY)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7412-P24<br>R3123-7412-P24<br>R3120-7412-P24</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">For B-axis reducer</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050/HH050T<br>YS080/YS100A</td>
    <td class="tg-nrix">R3135-7412-P23<br>R3123-7412-P23<br>R3120-7412-P23</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">For R1-axis reducer</td>
  </tr>
</tbody>
</table>

<br>
Table 7-2 Spare Parts List II
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Category</th>
    <th class="tg-jafi">Robot Applied</th>
    <th class="tg-jafi">PLATE No.</th>
    <th class="tg-jafi">Product Name and Specification</th>
    <th class="tg-jafi">Quantity</th>
    <th class="tg-jafi">Remark</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P17<br>R3123-7412-P17<br>R3120-7412-P17</td>
    <td class="tg-nrix">TAPER BEARING</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">R1-Axis B/G(1)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P12,P18<br>R3123-7412-P12,P18<br>R3120-7412-P12,P18</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1-Axis(B/G) SPLINE SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P07<br>R3123-7312-P07<br>R3120-7312-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">ARM FRAME – R1-Axis SHAFT/<br>R2-Axis SHAFT-B-Axis SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P10<br>R3123-7312-P10<br>R3120-7312-P10</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">B-Axis SHAFT– R1-Axis SHAFT<br>(GEAR BOX/B SPUR GEAR)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P05<br>R3123-7312-P05<br>R3120-7312-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">B-Axis SHAFT – R1-Axis SHAFT<br>(CENTER)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P06<br>R3123-7312-P06<br>R3120-7312-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">B-Axis SHAFT – R1-Axis SHAFT<br>(WRIST BODY)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P14<br>R3123-7412-P14<br>R3120-7412-P14</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1-Axis SPLINE SHAFT(B/G)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P13,P19<br>R3123-7412-P13,P19<br>R3120-7412-P13,P19</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">B-Axis GEAR SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P08<br>R3123-7312-P08<br>R3120-7312-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R2-Axis SHAFT-B-Axis SHAFT<br>(GEAR BOX/R2 SPUR GEAR)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P09<br>R3123-7312-P09<br>R3120-7312-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">ARM PIPE-R2-AxisSHAFT<br>(ARM FRAME)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P03<br>R3123-7312-P03<br>R3120-7312-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">ARM PIPE-R2-Axis SHAFT<br>(R2-Axis reducer)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P16<br>R3123-7412-P16<br>R3120-7412-P16</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1-Axis MAIN BRG SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P11<br>R3123-7312-P11<br>R3120-7312-P11</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">B-Axis SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P12<br>R3123-7312-P12<br>R3120-7312-P12</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R2-Axis SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P13<br>R3123-7312-P13<br>R3120-7312-P13</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">ARM PIPE</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P21<br>R3123-7412-P21<br>R3120-7412-P21</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1-Axis MAIN BRG SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7112-P05<br>R3123-7112-P05<br>R3120-7112-P05</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">S-Axis CABLE HOLLOW</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7312-P16<br>R3123-7312-P16<br>R3120-7312-P16</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">ARM PIPE-ARM FRAME</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7412-P22<br>R3123-7412-P22<br>R3120-7412-P22</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">R1-Axis MAIN BRG SHAFT</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R3135-7112-P07<br>R3123-7112-P07<br>R3120-7112-P07</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">S-Axis CABLE HOLLOW</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R1001-6202-P1a</td>
    <td class="tg-nrix">LIMIT SWITCH</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix">Option (S-Axis)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH030L<br>HH050<br>YS080</td>
    <td class="tg-nrix">R1001-6202-P1b</td>
    <td class="tg-nrix">LIMIT SWITCH</td>
    <td class="tg-nrix">2</td>
    <td class="tg-nrix">Option (H/V-Axis)</td>
  </tr>
</tbody>
</table># 8. Decommissioning
# 8.1. Material for each robot part

The robot is made up of several materials as shown in [Table 8-1]. Some of them should be properly arranged and sealed up to eliminate any bad influence on the human body or environment.
<br>

Table 8-1 Materials of each part
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Parts</th>
    <th class="tg-jafi">Materials</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Battery</td>
    <td class="tg-nrix">NiCad or Lithium</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wiring, Motor</td>
    <td class="tg-nrix">Copper</td>
  </tr>
  <tr>
    <td class="tg-nrix">Base body, Lower Frame, Upper Frame etc.</td>
    <td class="tg-nrix">Cast Iron</td>
  </tr>
  <tr>
    <td class="tg-nrix">Brakes, Motors</td>
    <td class="tg-nrix">Samarium Cobalt(or Neodymium)</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wiring, Connectors</td>
    <td class="tg-nrix">Plastic / Rubber</td>
  </tr>
  <tr>
    <td class="tg-nrix">Reducers, Bearings</td>
    <td class="tg-nrix">Oil / Grease</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wrist cover etc.</td>
    <td class="tg-nrix">Aluminum alloy cast</td>
  </tr>
</tbody>
</table># 9. Internal Wiring Diagram



Internal wiring is shown in a connection diagram per unit, and thus utilizes it to inspect and replace the wiring.


![](../_assets/그림_10.1_본체_부품_배치.png)

Figure 9.1 Manipulator Configuration



![](../_assets/기내배선도_1.png)
![](../_assets/기내배선도_2.png)
![](../_assets/기내배선도_3.png)
![](../_assets/기내배선도_4.png)
![](../_assets/기내배선도_5.png)
![](../_assets/기내배선도_6.png)
![](../_assets/기내배선도_7.png)
![](../_assets/기내배선도_8.png) 



