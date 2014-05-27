Philadephia Fire Station Brownout Schedule Documents
====================================================

This is a repository of the schedule of Philadelphia's rolling blackouts of fire stations. The policy of re-distributing staff is a cost cutting measure. [Read more about it in the Fire Department's FAQ](http://www.phila.gov/fire/pdfs/Brown-Out_FAQ.pdf). The documents are online here:

http://www.phila.gov/fire/Schedule.html

These documents were used in the [Code for Philly](http://codeforphilly.com) project [StationDown](https://github.com/amberheilman/StationDown), which is attempting to analyse fire data to determine if the brown out policy compromised public safety.

<strong>Note: This repository contains documents up to May 27th 2014</strong>

The PDF documents were downloaded using the [httrack](http://www.httrack.com/) command:

<pre>
<code>httrack http://www.phila.gov/fire/Schedule.html \    
    -O . \
    -* +*.pdf  \
    -v
</pre></code>
