---
layout: post
title: Microorganisms and Robots Part I
date: 2020-03-30 20:00
image-dir: microorg1
summary: How energy systems in microorganisms might look like in a parallel universe of robots
categories: microorganisms energy robots
---

![L'atmosphère: météorologie populaire (1888)](/assets/{{page.image-dir}}/image_1.png)
*L'atmosphère: météorologie populaire (1888)*

I have been thinking a lot about how automatic systems we build resembles natural systems. A complex organization of metal and silicon that is able to move around and learn its surroundings. Automation is a unique thing which is created by humans that does things without the need of human intervention. As a parallel, living beings move and learn their surroundings and form complex chemical structures.

Nature is something that has existed with the help of the sun as energy and earth as the breeding pool. We too supply our robots with electrical energy and our hands and fabrication labs as the breeding pools. Exploring the world of nature and learning from its ability to sustain itself, one can apply this to automatic systems to design a system which fully sustains itself.

Each day, trillions of living cells exist and automatically perform tasks. They exist as little balls of organized chemistry that have some overall goals, gain energy, form chemicals to help them survive, and create more of themselves. However, the environment is a nasty place for these little guys, if there is no sun and no other cells to feed upon, they die of starvation, if the environment has caustic chemicals and or no building blocks, nothing can be formed, and if the dna structure is broken, no more of itself can be created. If they don’t succeed or fail too many times at their goals, they die and their remains are decomposed and given to the scavengers of the cell world. Can the automaton we create live in such a way where they don’t need us, where they can live on without the need for us? For this article and a few others we will go on a journey of studying some interesting things about cells and how it could relate to automaton. However studying every parallel between nature and automaton would take a very long time, because of this, we will only focus on how energy might be produced by automatic systems and what would be a way to store that energy.

Maybe I am going into this with a “too” mad scientist view. This is where robots come and take over right? Make something that creates its own energy, is able to make their environment suitable for themselves, and replicate themselves, would they ever need you? On top of that, you make something that is stronger than any other human and faster at thinking, why wouldn’t it want to kill all of us? Would they want to go and harvest our organ’s for energy to supply their alien mother computer which runs on human organs? Some great questions I don’t really have an answer to, but the topic of creating a fully autonomous system is something people have dreamt about for eons. Exploring this topic is too juicy and my intuition says that we don’t have to worry just yet. So I will continue on without thinking of these issues just yet and ask, how could robots look like these microorganisms and how can some robots already look like them?

There are many types of single cell organisms but they would have never existed without having this one thing that keeps all of us alive, energy. In the case of the world of cells, temperature and chemical energy allows their bodies to stay chemically organized, divide, and make more of itself. In terms of robotics, we think of energy as electrical energy, allowing the circuits to be activated and its motors to turn. However, every cell gathers energy using one of two ways either through producing it themselves or by feeding on other organisms, also known as autotrophs or heterotrophs respectively.

Autotrophs gain energy through external nonliving systems, be it electromagnetic energy also known as photoautotrophs, energy from floating non-organic chemicals also known as chemoautotrophs, or from minerals also known as lithotrophs. Normally, we as humans create energy that the robots can use and provide that through the form of an outlet or an electrical bus. Systems that use an already powered bus could be seen as heterotrophs if a parallel was drawn since they need another system to feed energy upon. To be a true autotroph, the system would have to create its own energy onboard. 

What if there were robots that existed in our world that tended toward environments where they can gain energy. Solar celled robots traveling to deserts to graze on sunlight, robots with large windmill generators finding places of high wind, or robots that parasitically gain energy from wifi or radio signals, these could be possible futures of robots that acted toward gaining energy in their environment. Compared to living beings, there are actually a huge amount of energy capturing mechanisms we could put on a self sustaining robot. This area of research is called energy harvesting and energy scavenging, and there are thousands of papers on energy harvesting (About 31,300 results from google scholar). A quick list of different ways to harvest energy and an awesome graphic of the different ways it could be harvested is shown in this paper on Microwave Antennas for Energy Harvesting Applications.

|Energy harvesting technique|Power density|Efficiency|
|---|---|---|
|Photovoltaic|Outdoors (direct Sun): 15 mW/cm2, Outdoors (cloudiy): 0.15 mW/cm2, Indoors: <10 µW/cm2|Highest 32±1.5% Typical 25±1.5%|
|Thermoelectric|Human: 30 µW/cm2/industrial: 1:10 mW/cm2|±0.1% ±3.5%|
|Pyroelectric|8.64 µW/cm2 at the temperature rate of 8.5°C/s|3.5%|
|Piezoelectric|250 µW/cm2/330 µW/cm2||
|Electromagnetic|Human motion: 1–4 µW/cm2||
|Electrostatic|50–100 µW/cm2||
|RF|GSM900/1800 MHz: 0.1 µW/cm2, Wi-Fi 2.4 GHz: 0.01 µW/cm2|50%|
|Wind|380 µW/cm2 at the speed of 5 m/s|5%|
|Acoustic noise|0.96 µW/cm2 at 100 dB/0.003 µW/cm2 at 75 dB||
|<td colspan=3>Maximum power and efficiency are source dependent — excluding transmisssion efficiency.</td>

Noise power densities are theoritical values.
Table 1.
Power density and efficiency of energy harvesting techniques.

![image_2](/assets/{{page.image-dir}}/image_2.png)
*Example of the different radiating sources*

Analyzing the different power producing energy capturing methods, it’s clear that solar energy is the largest. As a parallel, living organisms also would gain energy in some similar ways. For chlorophyll, by converting the photons into glucose, its efficiency for the right wavelengths of light is at ~30% but the actual efficiency for the solar energy our sun outputs is at around 3%-6%. The energy created in most efficient conversion is glucose, which acts as the cell’s energy storage system. When the cells need to use the stored energy, they convert the stored glucose into ATP, a molecule which aids in doing a variety of things in the cell. This conversion of glucose to ATP has an efficiency of around 38% which gives an overall energy efficiency of 0.7%-2.3% (multiplying the sun efficiency by the Glucose->ATP efficiency). When compared to solar panels built by humans, our solar cells are much more efficient grabbing a larger frequency of light giving a typical efficiency of 25% and the efficiency of battery storage and usage is at around 90% for most batteries only if battery charge and discharge rates are controlled as shown in this peer reviewed study. This gives an overall efficiency of 23% which is about 10x more efficient than biological systems.
The increased efficiency gives robots an edge when it comes to harvesting energy from its environment however to be a true autotroph, or self reliant system, it needs to be able to recreate the solar cells itself. This process is quite complicated and would deserve an article on its own, but it would behove us to at least find how much energy does it take to create one solar cell with a cm^2 area. There are quite a few articles on this and the process has been getting better slowly, but here are some graphics that help quite a bit with the analysis.

Percent of energy costs for Solar cell production.

Energy costs for cells per watt produced

Using the average of all on the figure above, around 3kWh/W, if all energy went into making solar cells using the average energy creation of 15mW/cm^2 and starting with a 1cm^2 area, the robot could make 

However, there are many other ways to gain energy with the energy harvesting components that is nothing really like what living beings have. Using kinetic energies, like flowing water, air pressure or air flow, waves from the ocean, and fossil fuel generators, robots could unlock some unique ways to gain energy from the environment. One could imagine a large amount of these robots existing on earth or other planets setting themselves up such that they are reaping the benefits from these kinetic energies. When thinking of a robot which reclaims this one could think of robots which gather at places where there is free kinetic energy to utilize. There could be robots which gather at the ends of waterfalls or fast moving currents spinning their generators. A robot could have something like a wind generator where the robot moves to places where it can maximize wind energy generation slowly grazing on the wind. Fossil fuel robots could find places where fossil fuels may lie and through a long tube suck up oil to fire up their generators. Each of these systems could exist in a world where robots use nature to gain energy for their circuits. One could see the locations of such robots shown below.

Crude drawing of how robots could be moving from area to area to reap environmental energies

RF and frequencies that require an antenna is another unique energy harvesting component for robots. One could imagine a world where robots living like animals and plants, would communicate using RF signals and robots with RF harvesting components siphoning energy like parasites of a weird robotic world.

********************************** NOT SURE IF STUFF BELOW THIS IS NEEDED ****************
Another consideration is energy harvesting using the other methods shown in the figure above. Biochemical systems that use chemicals for energy, like the ones found in deep atlantic heat vents, use elements like sulfur and iron to create a redox reaction which gives some amount of energy to the organism. The efficiency has not been studied in very much detail. There isn’t much of a parallel that I have seen in industry but there are many types of batteries that get their energy from redox reactions. If a robot could continuously supply chemicals to support that redox reaction in their batteries, it could sustain itself, but there are much better ways of gaining energy without the need of continuously supplying these chemicals as shown in the table, which are much more sustainable.

For antennas, there are many different types but some are especially made to harvest energy. Under this paper <https://www.intechopen.com/books/microwave-systems-and-applications/microwave-antennas-for-energy-harvesting-applications> 

Here is a list of known chemicals and metals that produce a battery structure <https://en.wikipedia.org/wiki/Electric_battery>.

Another less popular one is piezoelectric components, they gain electricity from stress. An example of using peizioelectric components for energy harvesting https://iopscience.iop.org/article/10.1088/0964-1726/25/10/10LT01/meta.

Another example is through heat differentials using a peltier device, they can create electricity by differences in heat and can use electricity to create differences in heat.

Without these organisms, we would never have existed, they form energy slowly over time and store it for usage when it is needed. To these organisms, the main storage technique is glucose. For robots, we have a HUGE array of different storage techniques, but to my mind, the simplest and easiest to form would be inductors. Inductors For heterotrophs, they gain their energy from organic chemicals or from other living organisms. Heterotrophs gain energy in three different ways and specialize in these ways, as scavengers also known as Saprotrophic’s, as ingestors also known as Holozoic, and as parasites also known as parasitic. For these ingestors protozoans feed upon the autotrophs for their energy and metazoans eat those for energy.
In the end, what is this energy really used for, why do these cells need it? It is continuously seen that every living thing needs to fight off one of the strongest forces in the universe, randomness and entropy. Randomness and entropy drives air to be mixed together almost equally if seperated and makes things that seem like they are moving backwards in time to actually be moving backwards in time. It is what seperates us and things that live from things that don’t live. Well the fight against randomness and entropy now has a new enemy, autonomous systems and robots. But something we haven’t figured out yet for our children is how to deal with death. One of our most impressive abilities as living creatures is that we can die, which exactly is, us losing the fight against entropy and randomness. Our cells which were filled with order break and release everything that kept the chemical reactions of life running filling the surrounding area with organic material. However, to break this, life invented a way to even beat death, more life. A continuous revival of itself in different forms which in their own right have the same needs as their parents, get more energy and fight entropy and randomness.


Let’s think of what makes living things live on the smallest scale, single cell organisms.
Sources:
https://biologydictionary.net/autotroph/
https://www.microscopemaster.com/heterotrophs.html
https://www.youtube.com/watch?v=mkR9hMCOIhM&t=199s

Struct:
X Summary of robots and relating to animals and living beings
X Talk about energy systems of microorganisms
Talk about possible parallels of robots while explaining the possibility to create the energy systems, limit to around 3 (solar, kinetic, antenna, others briefly explained)
Talk about how this would require research on how to make a robot first have a system where it can create itself, then how it could create the energy gaining system, and then actually gain that energy so that it could be spent on creating itself. Lastly explain that we will be talking about this stuff in future articles.
Conclude




---


