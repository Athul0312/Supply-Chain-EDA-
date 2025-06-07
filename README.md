# Supply-Chain-EDA-
This project performs an exploratory analysis of skincare product performance across five cities using a retail supply chain dataset. The analysis focuses on four core aspects: Availability, Units Sold, Revenue Generated, and Price, combining both visual KDE analysis and bar chart comparisons.

Observations:

* Across the skincare segment, regional performance varies sharply across availability, sales volume, price, and revenue:

* Kolkata stands out with strong sales and revenue, supported by a balanced pricing strategy (visible bimodal price distribution) and decent availability.

* Chennai consistently performs extremely well in revenue with pricing skewed toward the premium side. It shows potential as a high-margin market.

* Chennai however does have only medium availability and sales volume, indicating that perhaps the bottleneck here is the availability. The previous point suggests that PMF here is good, therefore, increasing availability could potentially increase the sales volume and revenue gen. 

* Mumbai has strong revenue with prices indicating a strong market for premium products despite lower availability and fewer units sold — suggesting high sales volumnes of premium products.

* Once again, the availability oculd be the bottleneck here. Mumbai has a VERY distinct bimodal Price distribution => Two clear Segments, which must also be kept in mind while stocking the inventory.

* Delhi appears mid-range in both price and volume, performing decently overall but lacking standout efficiency. DElhi has high sales but medium range revenue generation, as well price per product. 

* This indicates that there is scope for a test programme of introducing higher priced SKUs and then tracking the volume of sales, which if successful, would boost the revenue generation from Delhi.

* Bangalore is the most misaligned: it has the highest availability but lowest sales and revenue, with pricing skewed heavily toward ultra-low. This mismatch likely reflects poor product-market fit.

* These insights suggest that aligning product pricing and inventory with local demand profiles is critical. 

* Bangalore in particular may benefit from reassessment — either by reducing overstocking or introducing better-fitting SKUs.


Key Regional Insights:

  Kolkata:
    Strongest overall performance. High sales and revenue despite moderate availability, with a balanced pricing mix (budget + premium). A well-aligned market — no major bottlenecks.

  Chennai:
    High revenue and premium-leaning pricing suggest strong product-market fit. However, medium availability and sales volumes imply that supply may be the constraint. Increasing availability could unlock additional growth.

  Mumbai:
    Strong revenue despite low availability and moderate sales. Distinct bimodal price distribution suggests dual demand for both budget and premium products. Inventory planning should reflect this price segmentation.

  Delhi:
    High sales but only moderate revenue and average pricing. This suggests Delhi is currently a volume-heavy, low-margin market. A controlled test introducing higher-priced SKUs could help raise overall revenue.

  Bangalore:
    Highest and most consistent availability, but lowest sales and revenue. Heavy skew toward ultra-budget pricing likely reflects poor demand alignment. Suggest reevaluating product mix and introducing more mid-range SKUs.

  Summary:
    This project highlights how availability, price, and demand interact differently across regions. While Kolkata and Chennai show strong alignment, Mumbai and Delhi offer clear strategic opportunities, and Bangalore presents a case for serious course correction.
