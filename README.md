67-272: GPBO Project - Phase 5
===
Unleash your creativity!
===

We will continue our project to develop an advanced version of the Baking Outlet system in this phase. We will focus our efforts on designing and creating high-fidelity wireframes for two different dashboards. Your wireframes are expected to include:
 
 * Colors, pallets, and fonts.
 * Visualizations fully colored, labeled, and properly presented.
 * Flows and processes. From a user logging into your dashboard to clicking each detail on your dashboard.
 * Labels, titles, and text, when and where necessary.
 * Navigation bars and menus where appropriate.
 * Icons for profiles, search bars, and whatever you deem necessary.
  
Read carefully the description of each dashboard below.

**Grading**

This phase will constitute **6 percent** of your final course grade and is broken down into the following two part.

### Part 1. Shipper Dashboard

At the beginning of the semester, you were all given the following description of shippers:
- After logging into the system, a Shipper needs to see a list of all the unshipped orders ordered chronologically. 
- For each order, the shipper should see the items and quantities ordered, information on the recipient, and his address (address of the recipient). 
- As each order item is placed in the shipping box, the shipper can check off that item, and its shipped date will be marked with the current date. In most cases, all the items for an order are shipped together at one time. That said, if there is a backlog for a particular item in the inventory, then a partial shipment is made, and what can be shipped is sent, and the rest of the order is filled when the new inventory arrives. When the order is complete and all the items in the order are in a sealed box (or set of boxes), the order should disappear from the shipping list.

**Hint**: It is clear from this description that shippers require the following data:

* Orders (shipped and pending)
* Order details (recipients, addresses)
* Shipping details (weight of orders, shipping costs, and destinations)
* Inventory data (categories and items available in physical stock at GBPO and in transit)

From the above data, consider the following when creating a shipper dashboard:

* Write at least three questions that shippers would ask with the data provided.

<!--  what are we interested as a shipper?
- popularity of category and items
- areas and addresses
- time of shipping
- weight of the orders: so we can tell whcih packages are we packing together
- where am I going?
- logistics of trucks: order of delivery 
-->

* Describe at least three metrics that the shipper would be interested in measuring and justify your choices. Consider that these might not be the standard web analytics metrics but could be geared towards this specific data and the shipper's needs. For instance, a shipper might be interested in learning about the weight of the items in a given order to figure our the packaging, etc.

### Part 2. Business and Stakeholders Dashboard

VPs and Owners of GPBO will use this dashboard. They are in the position to make business decisions concerning GPBO. Business decisions can involve questions such as: What is the future direction of GPBO? Is it possible to open new stores around Pittsburgh in X amount of years? How is our money being spent, and how can we yield higher sales? How is our current GBPO website helping drive business?

Types of data they could benefit from: 

* **Sales**
	* Consider what type of sales data would be helpful to a VP. 
	* Do you want to show the total? What about shipping costs? 
	* Are you interested in revenues or profits or neither?
	* Write down at least two questions your VP would have about sales.
	* Justify why you chose to display certain types of sales data and not others.
* **Users**
	* Write down at least three questions your VP would have about user data.
	* Justify why you chose to display certain types of user data and not others.
	* Consider at least three metrics essential to tracking users in GPBO, which would generate insights for GPBO's VPs.

* **Website traffic**
	* VPs are not interested in every detail of GBPO's website operation (at least not in the same way developers would be); therefore, think of at least two metrics that would bring value to VP's decisions.
	* How are users interacting with the web application? 
	* You should include a measure for conversion rate and provide your reasoning behind how to interpret the conversion rate for GBPO.
	* Justify your choices in metrics; why are these important for VPs?

<!-- ### Operations Performance Dashboard

Developers have different interests than decision-makers and shippers; they want to monitor the website and make sure it's kept healthy. This could involve from capturing javascript error rates up to conversion rates.

* Users
	* Write down at least three metrics that could help developers answer the following questions:
		* How are users interacting with the web application? 
		* How can you measure the quality of their experience and track how different parts of the GBPO website can impact their experience?
	* Make sure you justify your previous choices.
	* You should include a measure for conversion rate and provide your reasoning behind how to interpret the conversion rate for GBPO.
* Website health metrics
	* During class, we talked about core metrics for website performance and which metrics would be a top priority to track for GPBO. Include at least four of these in your Operations Performance dashboard.  -->

### General Notes

* Each of your dashboard designs will be judged on:
	* Thoughtful reasoning of data that would be collected to produce the metrics on the dashboards. We want to see that you thought about how each metric would benefit each type of dashboard user and how you decided to track each metric. Random use of metrics or answers such as "this is a core metric" or "this metric was showed in class" will yield you very low points in this Phase.
	* Conscious application of data visualization concepts learned in class. When considering how to track data for each dashboard, you should also consider the best way to visualize and organize (data storytelling) these data. 
	* Consistency! Even though we are requiring you to do high fidelity wireframes for two different wireframes, you should consider that they all correspond to GPBO; therefore, be consistent with your design decisions.
	* Be considerate of avoiding clutter and reducing dashboard users' cognitive loads.
	* Be mindful of static vs. historical data and consider it when choosing and justifying your metrics and your dashboard layouts (useful for choosing the type of the dashboard: explanatory, exploratory, both, etc.).

**Wireframing tool**

For this phase, we recommend to use [Figma](https://www.figma.com/), is a graphics editor and prototyping tool which is primarily web-based, with additional offline features enabled by desktop applications for macOS and Windows. 

To learn more about designing dashboards in Figma, please takse some time to watch the following short video tutorials:

- [Figma for Beginners Tutorial](https://www.youtube.com/watch?v=Cx2dkpBxst8&list=PLXDU_eVOJTx7QHLShNqIXL1Cgbxj7HlN4)
- [How to Design a Dashboard UI Design in Figma](https://www.youtube.com/watch?v=xkRaB4PQZ8g)
- [How to Design a Dashboard UI in Figma (Tutorial)](https://www.youtube.com/watch?v=EFSef5ntYjI)
- [Let's Design a UI Dashboard in Figma](https://www.youtube.com/watch?v=HHkNcv5HbnU)

**Best Dashboards Awards**

The three best dashboard designs and contents will be awarded with additional bonus points: 
- 10 points to the best one; 
- 7 points to the second best; 
- 4 points to the third best.

**Turning in Phase 5**

Your submission for this phase has two main parts:

1. Filling out [this Google Form](https://forms.gle/sENHJWmiEUpgRmaC9) with the answers to the questions in each part.  You will need to be signed in to Google using your Andrew ID to see this form.

2. The wireframes covering all the scenarios and dashboards described above. 

We highly recommend you start by answering the questions one by one, and indicate your reasoning before you start designing the wireframes. Having the answers clear, will help you design and create better and clearer wireframes efficiently.

Your wireframes should be turned in via your private repository on GitHub **before 11:59 pm, on Thursday, April 28th, 2022**. No late assignments will be accepted after this deadline.

Again, if you have questions regarding the turn-in of this project, please post them on Piazza or ask someone well in advance of the turn-in date. Waiting until the day before it is due to get help is unwise -- you risk not getting a timely response that close to the deadline.

**Good luck and have fun!**