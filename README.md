# operatingsystem-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [OperatingSystem Assignment 3 Solved](https://www.ankitcodinghub.com/product/operatingsystem-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91421&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;OperatingSystem Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
1 Linux Scheduler

The first exercise requires you to change the Linux kernel scheduler in the fol- lowing ways. For any process, there should be a system call to reduce (and NOT increase) the chances that the process would be selected for being dispatched. More specifically, let us assume that a certain process is chosen by the sched- uler. The system call must pass on information, the additional delay (in msec) (that has been accepted from the userland) to the scheduler such that anytime the said process is chosen by the scheduler, it adjusts the vruntime of the said process so as to delay its selection.

For every process with the same nice value, you must log the timestamps corresponding to when each process is selected and dispatched to run. It must reflect the additional delay specified by the user. You may need to have a fresh look at how vruntime is calculated. This would help you in figuring out how vruntime could be adjusted to reflect the additionally requested latency.

What to submit/rubric.

<ol>
<li>Fully functional and modified kernel diff which can be patched to a stock kernel and used (preferably 5.10 upwards). The diff should correspond to the code that must include the system call implementation and the changes to the scheduler functions. Additionaly, you would also require a test program to test the system call and show the functionality (by print- ing timeslices given to the program each time scheduled). [35 points]. Full compilation and correct functionality demonstrated using the test program (35 points). Patched kernel compiles successfully but meets only a few functionality requirements (25 points). Patched kernel doesn’t com- pile or compiles but doesn’t boot up. But the functionality and changes presented seem valid and correct, though cannot be validated (12.5 points). The patched kernel doesn’t compile or compiles but doesn’t boot but the functionality doesn’t seem correct, let alone be validated (0 points).</li>
<li>A readme describing the logic of the programs with relevant description of the data structures used, including description of the kernel data struc-
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
tures and source files modified (which ones were modified, how and why) [7.5 points].

2 Unix domain sockets IPC (flow-controlled)

The goal of this second exercise is to develop a better understanding of the Linux interprocess communication mechanisms. This would require you to write two programs P1 and P2. The first program P1 needs to generate an array of 50 random strings (of characters) of fixed length each. P1 then sends a group of five consecutive elements of the array of strings to P2 along with the ID’s of the strings, where the ID is the index of the array corresponding to the string. The second program P2 needs to accept the received strings, and send back the highest ID received back to P1 to acknowledge the strings received. The program P2 simply prints the ID’s and the strings on the console. On receiving the acknowledged packet, P1 sends the next five strings, with the string elements starting from the successor of the acknowledged ID.

The above mechanism needs to be implemented using three different tech- niques: (i) Unix domain sockets, (ii) FIFOs, and (iii) message passing queues. Please note that you may NOT make assumptions about the reliability of the in- terprocess communication mechanism, unless they are guaranteed by the mech- anism itself.

What to submit/rubric.

<ol>
<li>Three variants of the program P1 (one each for communicating using Unix domain sockets, FIFOs and message passing queues respective) [20 points]. Full compilation and correct functionality of all the programs (20 points). Program compiles successfully but doesn’t meet all the function- ality requirements (15 points). Program doesn’t compile, even if program logic seems apparently correct (0 points).</li>
<li>Three variants of the program P2 (one each for communicating using Unix domain sockets, FIFOs and message passing queues respective) [20 points]. Full compilation and correct functionality of all the programs (20 points). Program compiles successfully but doesn’t meet all the function- ality requirements (15 points). Program doesn’t compile, even if program logic seems apparently correct (0 points).</li>
<li>A single Makefile to build each program [5 points].</li>
<li>A readme describing the logic of the programs with relevant description
of the data structures used [5 points].

2
</li>
</ol>
</div>
</div>
</div>
