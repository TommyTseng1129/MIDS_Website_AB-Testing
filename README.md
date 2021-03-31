# MIDS_Website_AB-Testing

# Topic
The purpose of this project is to evaluate how the advertisement “tone” in ads for the MIDS program effect click rate. Tone in this context is defined as the notion trying to be conveyed through the ad.

# The Questions
In [insert regions] do advertisements with specific tonalities yield different click rates than generally toned advertisements, and what is the magnitude of this difference?
What advertisements tone yields the biggest change in click rate (if any) over generally toned ads in [insert regions], and what is the magnitude of this difference?

# Project Design

We will conduct A/B(/C) testing of advertisements on (LinkedIn?) for the MIDS page with different tonalities [which specific ones]. 

We will begin by conducting a pilot to see the type of engagement the ads receive and estimate if any sort of treatment effect would even be measurable, and what size of an effect we will prepare to look for. From this baseline we will also be about to estimate the time needed to run the experiment to reach the desired sample size that will yield the statistical power and confidence we want to have. 

# Outlining the Answer
The results of this project will use a hypothesis test looking at the difference in mean in the samples of ad views vs ad clicks between our control and treatment ads. If the difference is found to be significantly different from zero, at a 90% confidence level, we will conclude that the treatment ads do have some effect on the ad clicks. 

This hypothesis test will be conducted for each region in which ads run.

### *Falsifiability* 
> If the results of our hypothesis test do not show a significant difference in means, or show a difference at a confidence level <90%, we will conclude that the treatment ads do not have a significant effect on ad clicks.
Data
Data will be collected via [LinkedIn or Google or Facebook ad analytics].

### *Required variables for analysis*
> The variables needed for this hypothesis test are the total number of clicks on a given ad per region, and the total number of ad views for a given ad per region.

### *Control variables for analysis*
> We will also look to monitor the information surrounding the ads like the time of day (and any other metadata we can get from the ads) of the clicks. Discrepancies in these statistics (say all clicks on ad A happen around 2am, while all clicks for ad B happen at midday) could represent a potential problem in the ad distribution.

![](MIDS_Logo.png)
