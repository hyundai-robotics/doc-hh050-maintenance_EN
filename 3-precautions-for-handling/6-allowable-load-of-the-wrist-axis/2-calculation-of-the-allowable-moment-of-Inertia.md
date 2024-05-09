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
</table>