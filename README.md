Interpreting decision-tree models
=================================

This repository contains materials related to a talk by Ralph Haygood at the Research Triangle Analysts meeting on
January 17, 2017 (https://www.meetup.com/Research-Triangle-Analysts/events/236609631/).


Abstract
--------

Decision-tree models, particularly random forests and gradient-boosted tree models, are popular for both classification
and regression tasks. For many tasks, they offer not only accurate predictions but also plain interpretations, that is,
insights into the relationships between the input variables and the output variable: Which inputs are most influential?
How do they shape the output? Which ones combine non-additively? For practical purposes, answering these questions is
often more important than providing accurate predictions per se. In this talk, I'll briefly introduce decision trees,
random forests, and gradient-boosted tree models. I'll then explain and demonstrate (in Python) feature importances -
Which inputs are most influential? - partial dependence functions - How do they shape the target? - and feature
interactions - Which ones combine non-additively? Regarding feature interactions, I'll discuss Friedman and Popescu's
*H* statistics, a topic from the research literature that I've found useful in my own practice.


Thanks
------

To Research Triangle Analysts (https://www.meetup.com/Research-Triangle-Analysts/) for the opportunity to speak and to
Chris Calloway (https://github.com/cbcunc) for producing the video (https://youtu.be/KB9P2EwS3-4).


Contact
-------

Ralph Haygood (https://ralphhaygood.org/)  
ralph@ralphhaygood.org.
