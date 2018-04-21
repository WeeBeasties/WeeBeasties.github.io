---
title: Practice Post
layout: post
author: clifton.franklund
permalink: /practice-post/
tags:
- practice
- google doc
- gabriel
comments: TRUE
source-id: 1mx4A_4GqqabGjD39ucNTsqtzrJZ784ibB3SAJ8nFCdM
published: true
---
# Practice Post

This is a first try at using ```Gabriel``` to create a practice _Jekyll_ post for my **Reproducible Assessment** blog.  

I will have to see how this works out. Here is a formula to check out the ability to move $$ \LaTeX $$ code into posts as well. This seems to work ok to put symbols inline like alpha ($$ \alpha $$) and others. 

$$ \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$  

That should be enough for now.   

Adding a little mermaid code too in order to try out a simple chart:

<div class="mermaid">  

sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!

</div>

This is a Gantt chart, but I'm still fighting with the styling...

<div class="mermaid">

gantt  
        dateFormat  YYYY-MM-DD
        title <Name of the project>

%%	<Name of Activity>		: crit if critical else empty,done, active or empty, reference name or empty, Start Date or dependency, End Date or Duration
        section Phase 1 Name
        Activity 1			:	 done,    des1, 2017-01-06, 2017-01-08
        Activity 2               	:	 active,  des2, 2017-01-09, 2017-01-12
        Activity 3               	:        	  des3, 2017-01-12, 5d
        Activity 4              	:         	  des4, after des3, 5d

        section Phase 2 Name
        Activity 5 			: crit, done,		2017-01-06, 24h
        Activity 6		        : crit, done, 		after des1, 2d
        Activity 7		        : crit, active, 		    3d
        Activity 8			: crit,			 	    5d
        Activity 9			:			 	    2d
        Activity 10			: 			 	    1d

        section Phase 3 Name
        Activity 11			: 	active,   a1,	after des1, 3d
        Activity 12			:			after a1  , 20h
        Activity 13			:		 doc1, 	after a1  , 48h

        section Phase 4 Name
        Activity 12			:			after doc1, 3d
        Activity 15			: 	  			    20h
        Activity 16			: 			   	    48h

</div>

