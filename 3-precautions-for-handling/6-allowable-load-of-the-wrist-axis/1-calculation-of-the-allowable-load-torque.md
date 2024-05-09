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
