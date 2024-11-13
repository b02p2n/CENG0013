java c
CENG0013 Design Project 
Design of a process for the production of methyl acetate 
2024
1. The Process 
You are part of a team looking at the production of methyl acetate, a commodity chemical with many uses. Last year, your team asked you to perform. an analysis of the first step in the production of methyl acetate, the dehydration of methanol (CH3OH) to produce dimethyl ether (CH3OCH3). The next step is to design the process which used this dimethyl ether to produce methyl acetate. The design is to be based on the carbonylation of dimethyl ether to produce methyl acetate:
CH3OCH3 + CO −−→ CH3COOCH3 
This reaction takes place at 460 K.
The team has requested that you individually prepare and evaluate an initial design for this first step by applying your extensive knowledge of the Douglas hierarchy for design.
A stream, consisting of dimethyl ether with 0.001 mole fraction methanol, at ambient conditions, is available as a feed. The rate of this feed stream is (200+10d) kmol h-1. d should be replaced by the last digit of your student number. For instance, if the last digit of your student number were 3, the flow rate of the feed would be 230 kmol h-1. This feed has a cost of 78.2 USD kmol-1. Methyl acetate is considered to have a value of 135 USD kmol-1 to the company.
The carbon monoxide is available in any quantity from your company’s other existing processes, at a cost of 13.2 USD kmol-1 and there is a desire to use up this carbon monoxide to reduce its impact on the environment. This stream has a molar fraction hydrogen impurity of 0.02. The stream is available at 25 ◦C and 1 bar.
The fractional conversion of dimethyl ether in this reaction depends on the residence time and the partial pressure of carbon monoxide which will be a function of the operating pressure. A chemist in your team together with a reactor engineer have designed a full scale tubular reactor which should be suitable for your process. Experiments have been undertaken and the following data have been generated and are shown in Table 1. To use these data in your modelling (see below for the tasks), you will likely wish to find an appropriate function that relates conversion to operating pressure for the reactor. The feed to the reactor must have at least as much carbon monoxide as dimethyl ether present for the reaction to take place to the conversion indicated by the chemist.
Table 1: Data provided by the chemists in the company, showing single pass fractional conversion of dimethyl ether as a function of the operating pressure of the reactor.

2. The design task 
A process needs to be designed to make the most effective use of the dimethyl ether feed available, producing methyl acetate with a molar fractional purity of 0.99. The design of the process flowsheet will be based on the application of the full Douglas approach, levels 1 through 5. You will be expected to identify and to model all the main processing units, along with sizing information, and their interconnections including possible heat exchanges.
3. Cost models 
Table 2 presents the cost models for various types of units. The costs of the different utilities available, for heating, cooling, and electricity, are given in Table 3.
Table 2: Cost models for processing units for estimating the total annualised cost, TAC, in mil-lions of USD, of buying, installing, and maintaining the equipment.

Table 3: Cost data for utilities.

4. Things to do 
Given the chemistry data, the process requirements, and the cost data and models above, de-velop a full process flowsheet for the production of methyl acetate by following these steps. In attempting each of the following steps, fully itemise and justify all the decisions taken. Marks allocated to each step are indicated in the right margin, for a total of 100.
1. Apply levels 1 through 4 of the Douglas approach so as to develop a process flowsheet consisting of the main process units. In your report, summarise the decisions taken, in-cluding the identification of potential design variables, with justification for every decision. Elements of the Douglas hierarchy that do not apply to your case should be included in the discussion, if only to indicate why they do not apply. Do not perform. any economic potential analysis at this point. Sketch the final process structure obtained after level 4 of the hierarchy, labelling all input, output, and recycle streams; diagrams for each of levels 1-3 are not required. [20]
2. Implement a process and cost model based on the process identified in the previous step. Use one of GAMS (recommended), MATLAB, or a spreadsheet calculator. The model should include costing information sufficient to calculate the economic potential for the process design obtained after level 4. Details on how to model the various potential pro-cessing units are given in the Appendices below.
The model should be fully commented and must be included as an Appendix in your report and must also be submitted as a separate file in its native format to allow us to run your model. Up to 10 of the marks may be deducted due to insufficient commentary in the model itself regardless of what modelling language you use.
If you develop代 写CENG0013 Design of a process for the production of methyl acetate 2024Matlab
代做程序编程语言ed your model in either GAMS or MATLAB, the actual text of the module should be included as an appendix in the report. If you used a spreadsheet calculator, include two screenshots in the appendix: one showing typical values for some combination of design variable values and one showing all the equations in the spreadsheet. For a spreadsheet, you must ensure that there is sufficient commentary in the spreadsheet itself to understand the model and its outcomes. [20]
3. For the final flowsheet obtained with level 4 of the Douglas approach, use your model to investigate the behaviour of the economic potential in terms of the chosen design variable(s), considering annual hours of operation as indicated in the lecture notes for the type of process operation expected (level 1 of the Douglas hierarchy). Discuss how the design variables and the decisions you made in levels 1 to 4 impact on the economic potential. Plots of the economic potential with respect to the design variables will be required to support your discussion. [10]
4. Prepare a full stream table for the final process design from level 4 for your choice of design variable value(s). Fully justify your choice of values for the design variable(s) for
Table 4: List of hot and cold streams in an alternative process design where the hot streams must be cooled to their desired outlet temperature and the cold streams heated.

this stream table. [10]
5. Use Aspen Plus to simulate the process identified in the first step. Use this simulation to
a) fill in a stream table for the process and
b) determine the heating and cooling duties of all of the units.
Discuss the possible reasons for the differences you may observe between the stream tables from the previous step (step 4) and this step and also comment on any implications arising from these differences. If you were unable to prepare a stream table for either of the steps, discuss what you may have expected to see when comparing the stream tables. In your report, include a screenshot of the process flow diagram in Aspen and a screenshot of the stream table. The Aspen model must also be submitted as a separate file in Moodle. [10]
6. Another member of your team has also been investigating the process. As part of their investigation, they have identified a set of cooling and heating requirements for their partic-ular design (which may or may not be similar to those you may have obtained in answering the above questions), presented in Table 4. Knowing your expertise in the Pinch method, they have asked you to design a heat exchanger network for them.
Therefore, apply the Pinch method, as taught in the lectures and tutorial sessions and showing all the work, to design and cost a heat exchanger network for the heating and cooling requirements given in Table 4. Use ∆Tmin = 20 ◦C for the pinch analysis and U = 2.0 kW m-2 ◦C -1 for the overall heat transfer coefficient for the design of any exchanger in the network. Sketch the resulting heat exchange network.
Assuming that the heating and cooling requirements are of the same order of magnitude as your own design would have, discuss the economic implications of the heat exchanger network you have designed on your previous conclusions in step 3 regarding the economic potential of the process. [25]
7. Which decisions taken in levels 1 to 4 of the Douglas hierarchy had the most impact on the final design and why? Draw alternative process diagram(s) to illustrate your reasoning. [5]
5. Submission 
The submission, via Moodle, will consist of three parts, each of which is submitted under a separate tab in the submission page (see the top of the submission page on Moodle):
1. A report which answers the above questions, written using a word processor and submitted as a PDF document. This report must include your model (step 2) as an appendix as described above and also two screenshots of your Aspen simulation, one showing the full process flow diagram and one for the stream table. If you have used a spreadsheet calculator for the modelling in step 2, please insert two screenshots of the spreadsheet, one with values and one showing the equations, in the report as the appendix.
2. The model for level 4 from step 2, in your chosen modelling language, including the eco-nomic potential calculations for that level. The model should be submitted in the form. of the original file (e.g. as a .gms file for a GAMS model); a text version of the model must also be included in the report as an appendix, as noted above.
3. Your Aspen Plus simulation model should be included in the form. that Aspen can read. Also include, as noted above, screenshots of Aspen showing your process flow diagram and a screenshot of the stream table within your report.
Please note that parts 2 and 3 must be submitted as original files (e.g. .gms for a GAMS model) and not a PDF document. We must be able to load your model into the appropriate software to verify that it works.
All work must be your own and you must not discuss the project with anybody else. You may use material from the lectures and the various tutorials to discuss relevant topics with others in your class.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
