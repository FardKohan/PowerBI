Here I have created a simple example/workaround as a demo to show how to access slicer panel across a vertical single page scrolling report in Power BI and especially at the bottom of the page in each section if we had a long vertical scrolling report page. Actually I've used the same simple bookmarking technique plus synced slicers on a single page. 

> 🔄 **When multiple slicers from the same field need to sync, simply checking them in the Sync slicers pane isn’t enough. You also need to assign them the same group name in Advanced options.**

It was for collaboration when I came across Line Arnbjørn Krogh and Julian Barker's post on LinkedIn, who were looking for a solution to create a "sticky header" in Power BI to create a scrollable page where filters stay on top. A great idea, but unfortunately at the time of this idea, there was no native solution in Power BI except for embedded report, which is a completely separate issue.

![Preview of the Single Page Scrolling report with access to Synced Slicers](https://github.com/FardKohan/PowerBI/blob/main/Single%20Page%20Scrolling%20report%20with%20access%20to%20Synced%20Slicers/PBI%20scrolling%20page%20with%20access%20to%20header%20slicers.gif)
*Preview of the Single Page Scrolling report with access to Synced Slicers*

[LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7229926934887989249/)

