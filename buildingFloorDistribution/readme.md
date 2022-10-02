*This file is a work in progress; However, sufficent for early stages of builds.*


<h1>a.	Numbering Convention: </h1> 

<h2>Overview:</h2>

Rack names are made up of 3 numerical values separated by a period. RU units may then be appended with an additional period followed by the RU number.

> 0.1.2 = Ground Floor, Floor Distribution 1, Rack 2

> 0.1.2.42 = Ground Floor, Floor Distribution 1, Rack 2, RU42

*Example 1: Rack Numbering Schema*

The first value ‘0’ represents the floor, in this case ground 
The second value ‘1’ represents the floor distribution rack
The third value ‘2’ represents the rack within the floor distribution

The example shown identifies the Ground Floor, Floor Distribution 1, Rack 2 (0.1.2).


<h2>Floor Distribution and Rack Numbering:</h2>

Numbering shall always begin at 0 and increment by 1. The following example describes a building with multiple floors, floor distribution rooms and racks:

> 0.	Ground Floor

>   0.	Floor Distribution 0.0

>     0.	Rack 0.0.0 

>     1.	Rack 0.0.1

>     2.	Rack 0.0.2

> 1.	Floor Distribution 0.1
> 0.	Rack 0.1.0
> 1.	Rack 0.1.1
> 1.	First Floor
> 0.	Floor Distribution 1.0
> 0.	Rack 1.0.0
> 1.	Rack 1.0.1
> 1.	Floor Distribution 1.1
> 0.	Rack 1.1.0
> 1.	Rack 1.1.1

Example 2. Large Office/Campus Numbering 


High-Risers and Basements: 

Values are not limited to 1 digit and in the case of basements shall be appended with the letter ‘B’.

	B1. Basement 1 
0.	Floor Distribution B1.0
0.	Rack B1.0.0
1.	Rack B1.0.1
10. Tenth Floor	
0.	Floor Distribution 10.0
0.	Rack 10.0.0
1.	Rack 10.0.1
1.	Floor Distribution 10.1.0
0.	Rack 10.1.0
1.	Rack 10.1.1

Example 3. High-Rise and Basement Numbering


b.	Access Floor Distribution Layout:

Overview:

Each Floor Distribution (FD) location shall have minimum a primary comms rack, this will always be rack ‘0’ within the FD. All inter-riser cabling shall terminate within the primary comms rack. Where possible, all structured ethernet cabling shall terminate within the primary rack. The current design allows for 336 ethernet cables. If further cabling is required, this may spill into the ‘other’ rack. 

Within each FD (space prohibiting), it is advantageous to have a minimum of 3 comms 




