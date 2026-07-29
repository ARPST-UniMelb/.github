# AR-PST - UniMelb

This organisation collects all open-source developments that have been developed by the research team of the Power and Energy Systems Group at The University of Melbourne (UniMelb) 
as part of the work for [AR-PST initiative](https://www.csiro.au/en/research/technology-space/energy/Electricity-transition/AR-PST/), 
under the leadership of CSIRO and the Australian Energy Market Operator (AEMO).

## Repositories
This organisation currently includes datasets and code developments in *Topic 4 "Planning"*, across *stages 3 - 5*. 
- [Stage 3](https://github.com/ARPST-UniMelb/stage-3/) includes core datasets for the final report:<br><br>
[**Energy infrastructure planning under deep uncertainty: Assessing impacts and benefits of energy system integration**](https://www.csiro.au/en/research/technology-space/energy/Electricity-transition/AR-PST/Stage-3)<br> *Pablo Apablaza, Cristian Alcarruz, Ronggen Chen, Bastian Moya, Sleiman Mhanna, Pierluigi Mancarella*

- [Stage 4](https://github.com/ARPST-UniMelb/stage-4/) includes core datasets for the final report:<br><br>
[**Integrated energy system planning: Unlocking the value and flexibility from distribution networks and electricity-hydrogen energy hubs**](https://www.csiro.au/en/research/technology-space/energy/Electricity-transition/AR-PST/Stage-4) <br> *Cristian Alcarruz, Ronggen Chen, Pablo Apablaza, Bastian Moya, Sleiman Mhanna, Pierluigi Mancarella*

- [Stage 5](https://github.com/ARPST-UniMelb/NEM-reliability-suite/) builds upon multiple core repositories, which are described in detail below. It complements the final report: <br><br>
[**Resource Adequacy, Risk, and Resilience in Low-Carbon Energy System Planning: Methods, Tools, and Metrics**](https://www.csiro.au/en/research/technology-space/energy/Electricity-transition/AR-PST/Stage-5)<br> *Tim Kopka, Muhammad Yasironi, Pablo Apablaza, Bastian Moya, Sleiman Mhanna, Pierluigi Mancarella*

## Overview - *Stage 5* Developments
Five core repositories are developed:
1. **[PISP.jl](https://github.com/ARPST-UniMelb/PISP.jl)**: A data parser to parse public data of AEMO's Integrated System Plan (ISP) into an interoperable format for power system studies.
2. **[PRASNEM.jl](https://github.com/ARPST-UniMelb/PRASNEM.jl)**:
An adequacy framework to enable high-speed, NEM-wide time-sequential operational runs accounting for random unplanned outages using [PRAS](https://github.com/NREL/PRAS).
3. **[SiennaNEM.jl](https://github.com/ARPST-UniMelb/SiennaNEM.jl)**: An operability framework for sequential and time-coupled modelling framework for operational assessments of the NEM using [Sienna](https://github.com/NREL-Sienna).
4. **[SchedNEM.jl](https://github.com/ARPST-UniMelb/SchedNEM.jl)**: A time-sequential modelling framework, designed to be lightweight, fast, and easily customisable. Initially developed for AR-PST Stage 5.
5. **[NEM-reliability-suite](https://github.com/ARPST-UniMelb/NEM-reliability-suite)**: A collection of examples, studies and data to assess reliability of the NEM using the repositories. This includes the scripts necessary for replicating the results presented in the AR-PST final report.


### Schematic Overview
<img width="940" height="578" alt="Figure overview of the repositories" src="https://github.com/user-attachments/assets/55d02de4-2b01-4d30-b4d5-c094dd261eff" />

### Getting started
**NEM-reliability-suite** compromises tutorial scripts and is able to call the packages, therefore, we recommend starting by following the tutorial in its [ReadMe](https://github.com/ARPST-UniMelb/NEM-reliability-suite).

## Contact
For inquiries and details please contact the UniMelb research team lead Prof Pierluigi Mancarella: pierluigi.mancarella@unimelb.edu.au


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
