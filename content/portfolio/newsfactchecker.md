+++
title = "News Fact Checker"
practice = ["Research", "Design", "Development"]
date = 2017-08-04T15:38:36-05:00
draft = false
tools = ["github", "html-css", "sketch"] 
+++
As part of an individual study with Professor Mathew Lease, I aided a research team in the design and development of an interface for a news fact checker. Users can submit a claim and will be given the likelihood that the claim is true, false, or unverifiable.

![Screenshot of the News Fact Checker](/img/newsfactchecker1.png "Screenshot of the News Fact Checker")

The developers of the project were students with no design experience, and the first iteration of the site was simple, serviceable, but lacking any unifying design principles. I cleaned up and de-cluttered the interface, and then rearranged the layout so that it is reminiscent of the Google search page, utilizing an easily-recognized mental model that indicates that the user should submit a query of some kind. In this case, the user will submit a claim of questionable veracity. 

![Comparison of the old and new versions of the News Fact Checker](/img/newsfactchecker2.png "Comparison of the old and new versions of the News Fact Checker")

On top of that, I made the interface responsive so that the content of the page takes up a greater width of the screen on smaller viewports.

![Screenshot of the News Fact Checker on mobile](/img/newsfactchecker3.png "Screenshot of the News Fact Checker on mobile")

I was able to contribute to the project outside of the visual aspect as well. I suggested that we utilize a likert scale to gauge a user's own perception of the claim for which they are seeking verification. Initially, the design required users to complete three number input forms indicating the validity of the claim as percentages of the claim being true, false, or uncertain. Each of these three percentages would have to add up to 100%, putting the burden on the user of a) completing three different forms submissions for one assessment and b) doing math.

![Screenshot of the News Fact Checker on mobile](/img/newsfactchecker4.png "Screenshot of the News Fact Checker on mobile")

I realized that an assessment through three percentages adding up to 100% was not logical if we followed it to its extremes. For example, is it possible to be 50% sure that something is true, 50% sure that something is false, and 0% uncertain? A 50/50 split necessitates uncertainty, and so a more accurate representation would be 33.3% true, 33.3% false, and 33.3% uncertain.

Therefore, we could conceive of the data that we wanted to collect as existing along a vector, and I created this hasty diagram to demonstrate this point:

![Small diagram of the veracity claim input](/img/newsfactchecker5.png "Small diagram of the veracity claim input")

As the likelihood of true and false become even, uncertainty is increased to its maximum, which can only be 33.3% as it is not logical to completely eliminate assessments of true or false. This vector can be flattened into a likert scale, and the user's input can be interpreted as occurring along this vector at the discretion of the researcher.

![Screenshot of the News Fact Checker likert scale](/img/newsfactchecker6.png "Screenshot of the News Fact Checker likert scale")

This project is currently being developed, and the functionality and design may change before the project is completed and ready to be utilized and tested by users and researchers.
