---
title: Practice Post
layout: post
author: clifton.franklund
permalink: /practice-post/
categories: [Practice, Google Doc, Gabriel, Mermaid]
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
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48hd

</div>

