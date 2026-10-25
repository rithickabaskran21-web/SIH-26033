
Smart India Hackathon Workshop

Date: 25 October 2026
Reference Number: 26015841
Name: RITHICKA B

Problem Title

SIH 26033: Multiple intermediaries reduce farmers' earnings and increase consumer prices.

Problem Creator's Organization

Ministry of Consumer Affairs, Food & Public Distribution

Theme

Agriculture, FoodTech & Rural Development

Proposed Solution — AgriBridge DemandLink

1. Detailed Explanation

AgriBridge DemandLink is a digital platform designed to help farmers sell their products based on advance customer demand. It connects farmers, Farmer Producer Organizations (FPOs), retailers, hotels, and consumers.

Unlike traditional selling methods, buyers can place advance requests for agricultural products. Farmers can check the quantity required, expected price, and delivery location before planning their harvest.

The platform also introduces Village Collection Hubs, where products from nearby farms are collected, sorted, and distributed to buyers. This approach can reduce transportation expenses and unnecessary handling.

2. How It Addresses the Problem

- Connects farmers directly with retailers and bulk buyers.
- Allows buyers to request products before harvest.
- Displays expected prices and available quantities.
- Organizes product collection through nearby village hubs.
- Helps farmers plan production according to buyer demand.
- Reduces avoidable transportation and handling costs.

3. Innovation and Uniqueness

The main innovation is the Advance Demand Booking System.

Buyers can submit their requirements before the harvesting season. For example, a hotel may request 100 kg of tomatoes for the following week. The platform can display this demand to nearby farmers, allowing them to plan their harvest and delivery.

The Village Collection Hub feature can combine products from multiple farmers before sending them to buyers. This may reduce transport costs and improve coordination.

The initial version can use simple demand-matching rules. Demand forecasting and automatic delivery planning can be introduced in future versions.

Technical Approach

1. Technologies to Be Used

- Frontend: HTML, CSS and JavaScript
- Backend: Python with Django
- Database: SQLite for the initial prototype
- Demand Analysis: Python data analysis libraries
- Maps: OpenStreetMap
- Version Control: Git and GitHub

2. Methodology and Implementation

1. Farmers register and provide details about their crops and expected harvest dates.
2. Buyers enter their product requirements and required quantities.
3. The platform matches buyer demand with available or upcoming farm produce.
4. Farmers receive demand information and plan their harvest.
5. Products are collected at nearby Village Collection Hubs.
6. Orders are sorted and assigned for delivery.
7. Farmers and buyers can view order status and price details.

Technical Flow Diagram

+--------------------------+
| Farmers and FPOs         |
+--------------------------+
             |
             v
+--------------------------+
| Crop and Harvest Details |
+--------------------------+
             |
             v
+--------------------------+
| Buyer Demand Booking     |
+--------------------------+
             |
             v
+--------------------------+
| Demand and Supply        |
| Matching System          |
+--------------------------+
             |
             v
+--------------------------+
| Village Collection Hub   |
+--------------------------+
             |
             v
+--------------------------+
| Retailers, Hotels and    |
| Other Buyers             |
+--------------------------+

Feasibility and Viability

1. Feasibility

A basic prototype can be developed using Django, HTML, CSS, JavaScript, and SQLite. The first version can include farmer registration, advance demand booking, product matching, and order tracking.

Village Collection Hubs can initially operate through existing FPOs or local agricultural groups, reducing the need to build new facilities.

2. Potential Challenges and Risks

- Buyers may change or cancel their orders.
- Actual harvest quantities may differ from expected quantities.
- Collection hubs require proper coordination.
- Farmers may have limited internet access or digital experience.
- Maintaining product freshness during transportation can be challenging.

3. Strategies to Overcome Challenges

- Introduce order confirmation before harvest planning.
- Allow farmers to update expected crop availability.
- Use existing FPO facilities as collection points.
- Provide a simple interface with local-language support.
- Display product quality, quantity, and expected delivery details.
- Start with a small group of farmers and buyers before expanding.

Impact and Benefits

Benefits for Farmers

- Better visibility of future market demand.
- Reduced uncertainty when planning harvests.
- Improved access to retailers and bulk buyers.
- More transparent price information.
- Potential improvement in earnings by reducing avoidable costs.

Benefits for Consumers and Buyers

- Easier access to agricultural products.
- Better planning of bulk purchases.
- Improved information about availability and delivery.
- Potential savings through coordinated collection and transportation.

Social and Environmental Benefits

- Encourages digital adoption in rural communities.
- Supports cooperation among farmers and FPOs.
- May reduce food wastage through better demand planning.
- Coordinated deliveries may reduce unnecessary vehicle trips.

These benefits depend on accurate demand information, reliable logistics, fair pricing, and successful implementation.

Research and References

1. Smart India Hackathon Problem Statement Repository: https://github.com/selvasachein/SIH-26033
2. Django Documentation: https://docs.djangoproject.com/
3. Ministry of Agriculture and Farmers Welfare: https://agriwelfare.gov.in/
4. OpenStreetMap: https://www.openstreetmap.org/
