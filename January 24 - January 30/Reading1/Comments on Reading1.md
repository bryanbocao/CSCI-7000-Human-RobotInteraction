<<<<<<< HEAD
# CSCI-7000-Human-Robot-Interaction
=======
# Reading 1
## Comments due midnight on Tuesday 1/24
Note: You may need to use the CU Boulder VPN service to access the readings. Information on the VPN can be found here: http://www.colorado.edu/oit/services/network-internet-services/vpn

The first reading contains a survey of HRI by Michael Goodrich and Alan Schultz. For your comments, respond to the questions listed below the reading. Post your response in this forum.

Goodrich & Schultz: Human-Robot Interaction: A Survey (2007)

Goodrich states: "In essence, a designer can affect five attributes that affect the interactions between humans and robots." Do you agree with this list of attributes? Is it complete?
Table 5.1 presents several examples of roles and proximity patterns that arise in several application areas. Which do you find most interesting? Why?
Section 7 describes the relationship of HRI to many closely related fields. Can HRI really be considered a distinct discipline, or should it be considered a sub-field of another area of study (e.g., robotics, hci, etc.)? Why or why not?
Anything else you found interesting about the article or didn't understand?
Alternative direct-download link to reading: [Human-Robot Interaction: A Survey](https://moodle.cs.colorado.edu/pluginfile.php/33717/mod_forum/intro/Goodrich%20-%20Survey.pdf)



Comments on Human-Robot Interaction: A Survey
by Bo Cao - Saturday, January 21, 2017, 4:10 PM



### Goodrich states: "In essence, a designer can affect five attributes that affect the interactions between humans and robots." Do you agree with this list of attributes? Is it complete?

Me:

Somewhat agree.

I think the list covers many different dimensions that interactions can be affected. For Autonomy, scale of autonomy is shown clearly; the communications medium and the format of the communications determine the information exchange; team provides the general problem of the payloads of the number of humans and robots, the organization of humans and robots; Adaption, Learning and Training talks about how humans and robots learn from each other to fulfill a task collaboratively and more efficiently; Task-Shaping makes task easier for humans with assist of robots.

However, some factors came to my mind when reading this article but were still not in the list. One of these is in the information exchange, the communication channels mentioned in this article are mainly external like natural language, audio, physical interaction and haptics(even in this interaction tactile interaction could be added as well) and visual interaction including computer vision for robots and computer graphics for humans. Some missing interactions regarding this type include but not limited to: olfactory sensation, gustatory sense, touch/pressure sense, or even internal communication channel like using Electroencephalography(EEG) from human's brain directly.

In terms of team attribute, if we think of different components of robots as different resources that we could use, like sensors, actuators and so on, various forms of communications as messaging systems, I think HRI can learn and use the methods and theories from Network and Distributed Systems.

Last but not least, this article articulates the problems in information exchange, one attribute would be worth discussing is information storage. The reason behind this is that, normally, much of data used during robot’s performing a task would eventually be deprecated, seldom has been designed to store these data. Partially because the aim of the design of these robots is to finish the tasks efficiently in light weight of data storage, thus leaving the job of designing models to robot designers; a second reason is due to the fact that data coming from sensors is huge, especially image data, which makes data storage expensive. Once these data are saved, machine learning techniques can be used to help robots understand more about both the physical world and humans themselves, for newer robots to have a better interaction and more efficient working capacity, which also benefit the attribute of Adaption, Learning and Training.


### Table 5.1 presents several examples of roles and proximity patterns that arise in several application areas. Which do you find most interesting? Why?

Me:

I think regarding robots as peer would be interesting. In search and rescue application, robots extend the limits of humans’ physical activities and sensing the environment, they could also detect sign of life that humans could hardly detect. In this case treating human as pure supervisor may not be the perfect role due to the limits of humans. However, robots currently are not in such a high level of intelligence that still requires humans’ assistance, making the role of peer more appropriate between humans and robots.

As for Space Exploration, example like BB-8, C-3PO and R2-D2 in Starwar play roles like robotics assistant astronaut, not purely a tool that is controlled by humans.

In terms of entertainment, robots provide the same function as humans to entertain audience with different perceptions. They are more advanced than pure tools.

In the application area of home, which is seldom mentioned in this article, proximal robots can be treated as one of the family members like pet but can provide unique contributions rather than pet. Examples include Jibo, Robi, Baymax and so forth.


### Section 7 describes the relationship of HRI to many closely related fields. Can HRI really be considered a distinct discipline, or should it be considered a sub-field of another area of study (e.g., robotics, hci, etc.)? Why or why not?

Me:

Based on this article, though strong arguments can be found to support that HRI could be a sub-field of another realm of study, in my opinion, it's much more reasonable to regard HRI as a unique research area.

Admittedly, if we look in-depth of HRI, many of the knowledge, methodologies, techniques, theories come from different existing research realms. For example, in section 4, Goodrich and Schultz shaped five attributes in HRI problems, “Autonomy is mainly implemented using techniques from control theory, artificial intelligence, … and linguistics”. Even in one aspect of these attributes, Autonomy covers a number of research fields, not to mention the other four. It covers a wide range of topics in various fields, though heavily contributed by robotics researchers, including computer science, design, psychology, social science, education and so forth.

However, when converging works from distinct fields, new problems, that may fundamentally change the kernel from each previous field, might emerge, which may not be able to solved based on techniques from a previous research realm. Rather, seeking a new solution to these problems makes HRI distinct from each single field that it covers. This is the same opinion mentioned in “4.6 Finding a Unifying Theme”.

When taking HCI into consideration, it’s easy to think that HRI borrows, extends the research methodologies, design principles and computing metaphors from it, therefore regarding HRI as a subset of HCI sound reasonable. But one of the key facts mentioned in section 7 that distinguishes HRI from HCI is that, robots occupy physical space. With more than this unique challenges in HRI, it’s hard to classify it under a category of HCI.

To sum, HRI can be thought of a unique discipline due to its unique research problems extending from various previous ones. One of the important concepts mentioned in this article that distinguishes HRI from interactions of pure teleoperation and pure supervisory control is “Dynamic Interaction”. Addressing these problems can hardly be done by purely using the existing methods from the fields that HRI covers.


### Anything else you found interesting about the article or didn't understand?

Me:

I think the Cognitive Modeling and Team Organizations and Dynamics in 6.3 Solution Themes look interesting since these are the core topics behind the scene of how humans can effectively interact with robots. Another reason is that the image of robot is "cold" for decades, while decent solutions of these themes can have positive social impacts on humans.

Not quite understand:

In Page 32, Scholtz provides a list of the roles that robot can be in this articles including Mechanic & Bystander, however, in Table 5.1 and the remaining in this section, seldom about these two roles has been described explicitly, which made me confused.

From my understanding, robot can play the role of Mechanic in many different application areas where physically interaction with the world is necessary, like Search and rescue, Assistive Robotics or Space, robots of Ground Vehicle or UAV extend the limits of human’s ability to move and sense the dangerous places. Furthermore, they can extend the knowledge for humans by data processing techniques such as machine learning that may take years for human to discover. Also they can be in the field of Cybernetics.

However, I could not think of how the role of Bystander can be fit into one of the application areas listed because in each field, robots have at least some sort of data exchange with humans, which indicates the participation of robot. While as a Bystander, the robot is present but does not participate in the event. But it makes sense if we think of humans as Bystanders who just watch the robots to finish a task without any interference.


