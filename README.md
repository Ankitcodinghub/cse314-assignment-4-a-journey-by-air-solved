# cse314-assignment-4-a-journey-by-air-solved
**TO GET THIS SOLUTION VISIT:** [CSE314 Assignment 4-A journey by Air Solved](https://www.ankitcodinghub.com/product/operating-systems-ipc-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96978&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE314 Assignment 4-A journey by Air Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
A journey by Air

Many students of CSE, BUET are travelling to Cox’s bazar by air to attend the NSysS conference. On arriving at the airport, each passenger performs self check-in at a kiosk which issues a boarding pass. There are M kiosks available. A passenger needs to wait in a line if a kiosk is not available.

Next, each passenger needs to pass through the security check and boarding gate to get on the flight. However, VIP passengers are allowed to skip the security check. They use a VIP channel to reach the boarding gate. Any number of passengers can walk simultaneously through the VIP channel.

Security Check: There are N belts. Each belt has a separate waiting line. After receiving the boarding pass from the kiosk a passenger can join any of the waiting lines. Each belt can serve P passengers at a time.

Boarding: There is only one line to board on the airplane. At the boarding gate, an officer checks the boarding pass one at a time. Passengers need to wait in a line for their turn. Some passengers are not very careful. They have lost their boarding passes. When a passenger fails to show the boarding pass at the gate, s/he is sent back to a special kiosk using the VIP channel which is used only by the returned passengers. The special kiosk can serve one passenger at a time. After getting the boarding pass, s/he walks through the VIP channel to come back to the boarding gate and waits in line for his/her turn.

VIP Channel: The VIP channel is basically a moving walkway, which runs usually in the direction from the kiosk to the boarding gate. Let’s call this direction Left-Right. It is also used to send back a returned passenger from the boarding gate to a special kiosk. Let’s call this direction Right-Left.

Any number of passengers can walk simultaneously through this channel in either direction. Since it is a moving walkway, it can be used in one direction at a time. The direction is manually changed by a staff member. The staff gives priority to the Left-Right direction and changes the direction only if there is no passenger who is ready to use the channel in Left-Right direction. If there is any passenger waiting on the Left side while the walkway is being used in the Right-Left direction, the staff only waits for the passengers to finish their walk who are already on the walkway. No new passenger on the Right side is allowed to enter the walkway.

Implementation Guideline:

<ul>
<li>● &nbsp;Each passenger should be given an unique ID. Some passengers can be assigned VIP status at random at the beginning.</li>
<li>● &nbsp;The timing of the operations should be implemented using sleep. The relative time for each operation is given.</li>
<li>● &nbsp;There MUST NOT be any busy waiting anywhere in the implementation</li>
<li>● &nbsp;Generate passengers using Poisson distribution</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Operation Name

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Relative Time Unit

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Self check-in at a kiosk

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
w

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Security check

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Boarding at the gate

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
y

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Walking on VIP channel in either direction

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
z

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;Select passengers randomly during the boarding operation to lose the boarding pass.</li>
<li>● &nbsp;Print every move of a passenger in detail (with timing info). Samples are given just toshow the output format.</li>
<li>● &nbsp;Input/Outpu:
<ul>
<li>○ &nbsp;You will take input from a file and give output in an output file</li>
<li>○ &nbsp;The format of the input file is:MNPwxyz
Where M = Number of kiosk

N = Number of belts for security check

P = Number of passengers each belt can serve w, x, y, z = relative time units for the operations
</li>
</ul>
</li>
<li>● &nbsp;Sample Output format:
<ul>
<li>○ &nbsp;Passenger 1 has started waiting in kiosk 1 at 2</li>
<li>○ &nbsp;Passenger 2 (VIP) has started waiting in kiosk 2 at 4</li>
<li>○ &nbsp;Passenger 1 has got his boarding pass at 8</li>
<li>○ &nbsp;Passenger 1 has started waiting for security check in belt 2 at 14</li>
<li>○ &nbsp;Passenger 1 has crossed the security check at 20</li>
<li>○ &nbsp;Passenger 1 has boarded the plane at 28</li>
<li>○ &nbsp;Passenger 2 (VIP) has arrived at VIP channel at time 16</li>
<li>○ &nbsp;Passenger 2 (VIP) has crossed the VIP channel at time 22</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
</div>
