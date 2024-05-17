# Adventure-sales-Work-Analysis
Hello, I am happy to share my latest work "AdventureWorks Sales Dashboard - 2023 Edition". This project uses Microsoft's official sample dataset, AdventureWorks, which includes order customer,reseller tables. I think it is a very representative example of using BI software to analyze sales data and discover business insights, so I made a couple of pages.
 
I divided the sales dashboard into two reports. The first section (Sales Summary) basically summarizes the overall sales performance and provides some time-related analysis, while the other three sections break down different important dimensions  for detailed analysis.
 
Since there are two pages, I will briefly explain the design idea of the homepage. There are many charts on the homepage, which can be roughly divided into three areas: the upper-left shows the overall trends, the lower-left shows product data (such as top 5 products sales), and the right side shows channel data (such as the proportion of different channels).
 
For a page with large amounts of information, there is usually a problem that new users do not know how to operate. Therefore, how to guide users appropriately is the focus. The solution I provide is to add a "question mark" button in the upper right corner. When users click it, a new layer will pop up and tell users how to use it. You can see the tips for the two-level menus and how to use slicers and customer/reseller drill-through.
 
For the idea of customer/reseller drill-through:
When users select one single customer/reseller, they actually want to know more details about this customer/reseller. This is a very natural data demand.
My solution is that when a customer/reseller is selected, the drill-through button in the upper right corner will be activated, and it can jump to an independent customer/reseller details page. The details page can include basic information, sales, order volume, profit, and other indicators.
After browsing the detail page, users can return to the previous page.
