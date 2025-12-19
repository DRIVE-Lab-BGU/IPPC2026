<p style="font-size:30px;text-align:center;line-height:100%"><b>Welcome to the International Planning <span class="competition-highlight">Competition</span> 2026: Probabilistic and Reinforcement Learning Track</b></p>


The International Probabilistic Planning Competition is organized in the context of the International Conference on Planning and Scheduling (ICAPS). It empirically evaluates state-of-the-art planning and Learning systems on a number of benchmark problems. The goals of the IPC are to promote research, highlight challenges in the planning community and provide new and interesting problems as benchmarks for future research.

Since 2004, probabilistic tracks have been part of the IPC under different names (as the International Probabilistic Planning competition or as part of the uncertainty tracks). After 2004, 2006, 2008, 2011, 2014, 2018, and 2023 the 8th IPPC will be held in 2026 and conclude together with ICAPS, in July 2026, in Dublin (Ireland). This time it is organized by Ayal Taitler, Yuval Aroosh and Palash Chatterjee.


## Calls
Please forward the following calls to all interested parties:
- [Call for Domains and Participation](/call_email.md)

<div style="width:100%;text-align:center;">
  <a href="images/IPPC2026_Graphical_Call_V2.jpg">
    <img src="images/IPPC2026_Graphical_Call_V2.jpg" height="246" width="190" />
  </a>
</div>

We invite interested competitors to join the competition discussion:

   [ippc2023-rddl@googlegroups.com](https://groups.google.com/g/ippc2023-rddl)

## Preliminary Schedule


| Event                                         | Date              |
|:----------------------------------------------|:------------------|
| Call for domains and praticipants             | December, 2025    |
| Domain submission deadline                    | February 13, 2026 |
| Final domains announcement                    | March 6, 2026     |
| Competitors registration deadline             | March 20, 2026    |
| Dry-run                                       | April 19, 2026    |
| Planner abstract dubmission                   | May 1, 2026       |
| Contest run                                   | June 1-4, 2023    |
| Final planner abstract dubmission             | June 12, 2023     |
| Results announced                             | July 1, 2023     |



## Setup

This year's competition follow the previous iteration and will be using the generic pyRDDLGym - an autogeneration tool for gym environments from RDDL textual description.

<img src="images/RDDLGym.jpg" alt="RDDLGym diagram">

More information about the infrastructure, how to use it and how to add user defined domains can be found the following short guide

- [Infrastructure guide](/infrastructure.md)

pyRDDLGym also comes with a set of auxiliary utils and baseline methods:

- [Tools and Baselines](/planning.md)


## Domains

We provide a sample of RDDL domains here and include an updating list of the Competition Domains further below. We encourange the community to contribute user defined domains, or ideas you think the community should be aware of. While not all will be included in this competition, it will help enrich the the problem database, the suitable and mature enough suggestions will be included in the competition.


<div class="image123" style="center">
  <div style="float:left;margin-right:5px;">
        <a href="wildfire.html">
        <img src="images/wildfire_image.gif" height="190" width="190"  />
        <p style="text-align:center;">Fire Fighting (from tutorial)</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="rover.html">
        <img src="images/Rover_image2.gif" height="190" width="190"  />
        <p style="text-align:center;">Mars Rovers Science Mission</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="recsim.html">
        <img class="middle-img" src="images/recsys_loop.gif" height="190" width="190" />
        <p style="text-align:center;">Recommendation Systems</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="powergen.html">
        <img src="images/power_gen.gif" height="190" width="190" />
        <p style="text-align:center;">Power Unit Commitment</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="uav.html">
        <img src="images/drones.gif" height="190" width="190" />
        <p style="text-align:center;">UAV</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="elevator.html">
        <img src="images/elevator2.gif" height="190" width="190" />
        <p style="text-align:center;">Elevator Control</p>
        </a>
    </div>
</div>


<br clear="left">

In addition to the original domain, we have recreated some of the classical control domains in RDDL. Illustrating how easy it is to generate domains in pyRDDLSim:

<div class="image123" style="center">
    <div style="float:left;margin-right:5px;">
        <a href="cartpole.html">
        <img src="images/cart_pole.gif" height="190" width="190"  />
        <p style="text-align:center;">Cart Pole</p>
        </a>
    </div>
    <div style="float:left;margin-right:5px;">
        <a href="mountaincar.html">
        <img class="middle-img" src="images/mountain_car.gif" height="190" width="190" />
        <p style="text-align:center;">Mountain Car</p>
        </a>
    </div>
  <div style="float:left;margin-right:5px;">
        <a href="racecar.html">
        <img class="middle-img" src="images/racecar.gif" height="190" width="190" />
        <p style="text-align:center;">Race Car</p>
        </a>
    </div>
</div>

<br clear="left">

Note, that there are additional domains out there from past competitions (IPPC 2011, IPPC 2014), which can be also be used with pyRDDLSim:
- [IPPC 2011 domains](https://github.com/ssanner/rddlsim/tree/master/files/final_comp/rddl): This repository contains 8 domains: Elevators, Cross Traffic (Frogger), Game of Life, Navigation, Reconnaissance, Skill Teaching, SysAdmin, Traffic. 
- [IPPC 2014 domains](https://github.com/ssanner/rddlsim/tree/master/files/final_comp_2014/rddl): This repository contains some of IPPC 2011 domains, with additional 4 new domains: Tamarisk (Invasive Species), Wildfire (Firefighting), Academic Advising, Triangle Tireword.

Past competitions were entirely discrete; the focus of this year’s competition is on continuous and mixed discrete-continuous problems. However, everybody are welcome to take advantage of their existance. All previous competition domains are avilavble through the [rddlrepository](https://github.com/ataitler/rddlrepository) package/git.



## Registration

Information will be release soon.


<!---Please register at the following link:

- [Registration form](https://forms.gle/W9ng4v3vciNcc9S27)

The registration will be closed on March 15, 2023. 
<!-- If you missed the deadline and wish to compete please contact one of the organizers (Ayal Taitler or Scott Sanner). -->

 
## Procedure
Information will be release soon.
### Final Competition Domains(TBD)
The competition will include:
- 8 domains (Hopefully 5 instances per domain )
- 5 instances per domain (released at competition time)

| Domain                | pyRDDLGym name         |
|:----------------------|:-----------------------|
| Reservoir Control     |  Reservoir_continuous  |
| HVAC                  |  HVAC                  |

more to come

Instance generators are available for all of these domains. The competition instances will be generated with these generators.
Documentation of the generators is available here:

- [Instance generators](/instancegen.md)


### Competition Dry-run
Information will be release soon.
### Evaluation and Scoring (TBD )
Information will be release soon.

### Results



## Organizers
- [Ayal Taitler](httpsThe results were presented at the 33rd International Conference on Automated Planning and Scheduling ([ICAPS](https://icaps23.icaps-conference.org/)) on July 11 in Prague. The [presentation slides](/results/IPPC2023_results.pdf) of this talk contain additional details.
-[Yuval Aroosh]
-[Palash Chatterjee]
## Advisors
- [Michael Gimelfarb](https://mike-gimelfarb.github.io/) (University of Toronto, CA)
- [Scoot Sanner]
Contact us: [ippc2026-rddl@googlegroups.com](https://groups.google.com/g/ippc2026-rddl)
