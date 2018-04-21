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
    title A New Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
        A task         :a1, 2014-01-01, 14d
        Another task   :after a1, 7d
    section Another
        Task in sec    :2014-01-12, 14d
        another task   :10d
    section Last
        Publish        :c1, 2014-01-19, 7d
        Perish         :after c1, 10d

</div>

