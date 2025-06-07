# Supply-Chain-EDA-
This project performs an exploratory analysis of skincare product performance across five cities using a retail supply chain dataset. The analysis focuses on four core aspects: Availability, Units Sold, Revenue Generated, and Price, combining both visual KDE analysis and bar chart comparisons.

This was meant to be a lightweight EDA exercise…
And then it kind of turned into a (a very deep) rabbit hole.
So here’s what this repo is and what it isn’t:

What I Did:
  I picked a subset of the full retail supply chain dataset — specifically, skincare products.
  Looked at how they performed across five cities: 
    Bangalore, Mumbai, Delhi, Kolkata, and Chennai
  Focused on four core variables:
    Availability, Units Sold, Revenue Generated, and Price
  Compared these across cities using both KDE plots and summary stats
  My primary focus was to leran how to draw actionable insights based on mismatches between stocking, pricing, and performance, instead of just coming up with pretty plots. It would've taken me less time to just pull up plots including all 24 variables and just leave it at that, but my aim was to make sense of the limited variables I was focussing on and learn how to draw insights.


Why I Did Only This:
  There are ~20+ other variables in the dataset — lead times, defect rates, shipping, carriers, routes, etc.
  And yes, I didn’t touch them.  
  This wasn’t meant to be a comprehensive dashboard-style project.
  The goal was to go deep into a few important variables rather than surface level over all 24 , and try to answer one key question:
     “How well are we selling skincare across locations — and why?”
  If this were a real case study, that’s the slice of the business I was trying to understand.

Where the Actual Insights Are:
  Let’s be honest — the top part of the notebook is a bit fluffy.
  Some warm-up plots, basic bar charts, setting the stage.
  The real meat — the multi-variable deep dive into skincare by location — is further down the notebook.
  If you’re just here for the good stuff, Ctrl+F for: Skincare Analysis by Location


Core Findings:
  Kolkata: Great efficiency — strong revenue + sales from moderate availability. Balanced price mix.
  Chennai: Premium-leaning, high revenue, but medium supply → scale up availability.
  Mumbai: Low stock, low sales, high revenue → premium products likely carrying the weight.
  Delhi: High sales, average revenue → test premium SKUs.
  Bangalore: Well-stocked, badly performing → pricing too low, demand mismatch.


TL;DR

This project was a scoped deep dive into one product category to understand regional demand and pricing alignment.
I felt there would be more to leearn by going deep into a few variables than surface level skimming over 24 variables.
It’s not flashy. It’s not complete. But it’s real. 
And I learned a lot doing it.


