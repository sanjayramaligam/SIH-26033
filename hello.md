


Smart India Hackathon Workshop
Date: 24/11/2026
Reference Number: 26011909
Name: SANJAY R

Problem Title
SIH 26033: Multiple intermediaries reduce farmers' earnings and
increase consumer prices

Problem Creator's Organization
Ministry of Consumer Affairs, Food & Public Distribution

Theme
Agriculture, FoodTech & Rural Development

Problem Description
Multiple intermediaries in the agricultural supply chain can reduce the
share of the final selling price received by farmers while increasing
the price paid by consumers. Limited access to buyers, fragmented
logistics, information gaps, and unpredictable demand can contribute to
delays, wastage, and inefficient price discovery.

The expected solution is a digital marketplace that:

Connects farmers and Farmer Producer Organisations (FPOs) directly
with consumers and bulk buyers.
Provides logistics support for pickup, storage, and delivery.
Uses AI-based demand forecasting and route optimization.
The intended benefits are better price realization for farmers, more
competitive prices for consumers, and reduced supply-chain
inefficiencies.

Proposed Solution
We propose FarmConnect, a digital agricultural marketplace that
brings farmers, FPOs, consumers, retailers, restaurants, and
institutional buyers onto one platform.

Farmers and FPOs can create verified profiles, list available produce,
specify quantity and expected prices, upload product photographs, and
update stock availability. Buyers can search and compare produce by
crop, location, quality grade, quantity, and price. They can place
orders directly with the seller or submit bulk purchase requests.

The platform will provide transparent price information and order
tracking so that both parties can follow a transaction from listing to
delivery. A logistics module will help coordinate pickup and delivery
through available transport partners. It can group nearby orders and
match them with suitable transport options to reduce avoidable travel
and handling.

An AI-assisted demand forecasting module will use available historical
sales, seasonal patterns, location, and order data to estimate demand.
These estimates can help farmers and FPOs plan listings and help buyers
plan procurement. A route-planning module can recommend efficient
delivery routes based on delivery locations, vehicle capacity, and order
priorities.

The platform is intended to support direct trade rather than require
every transaction to pass through multiple intermediaries. Optional
services such as quality checks, payment support, and logistics
coordination can be offered transparently, with any applicable fees
shown before an order is confirmed.

How the Solution Addresses the Problem
Direct market access: Farmers and FPOs can reach multiple buyers
without depending entirely on a chain of intermediaries.
Price transparency: Buyers can compare listings, while sellers
can view market information before setting or negotiating prices.
Simplified bulk procurement: Retailers, hotels, restaurants, and
other institutions can discover suppliers and request larger
quantities.
Coordinated logistics: Pickup and delivery coordination can
reduce delays, unnecessary handling, and transport costs.
Demand-informed planning: Forecasts can help sellers make
better-informed decisions about quantities and timing.
Order visibility: Digital order status and transaction records
can improve communication and accountability.
Innovation and Uniqueness
FarmConnect combines direct farmer-to-buyer discovery, bulk procurement,
logistics coordination, and AI-assisted planning in one marketplace. Its
focus is not only on listing agricultural products but also on
coordinating the steps between order placement and delivery.

The platform can be designed for mobile use, regional languages, and
low-bandwidth environments. FPOs or authorized field coordinators can
assist farmers who have limited access to digital services.
Recommendations will support decision-making; farmers and buyers will
remain in control of prices and final transactions.

Technical Approach
Proposed Technologies
The following technologies are proposed for a scalable prototype:

Frontend: React for the web application and React Native or
Flutter for a mobile application.
Backend: Python with FastAPI or Node.js with Express for APIs
and business logic.
Database: PostgreSQL for users, listings, orders, payments, and
logistics records.
AI and data analysis: Python, pandas, and scikit-learn for
demand forecasting and data analysis.
Maps and routing: A mapping and directions service, with route
optimization based on delivery locations and vehicle capacity.
Authentication: Role-based access for farmers, FPO
administrators, buyers, logistics partners, and platform
administrators.
Cloud hosting: A cloud platform for application hosting,
database management, backups, and monitoring.
Notifications: SMS, email, or app notifications for order
updates and delivery status.
Technology choices may be adjusted after prototype testing and
evaluation of cost, connectivity, and deployment requirements.

Methodology and Implementation Process
Requirement analysis: Identify the needs of farmers, FPOs,
consumers, bulk buyers, and logistics partners.
User and role design: Define secure registration and access
permissions for each user category.
Marketplace development: Build produce listings, search,
filters, price display, buyer enquiries, and order management.
Logistics module: Add pickup requests, delivery assignment,
shipment status, and basic route planning.
AI module: Prepare sample or pilot datasets and develop a
baseline demand forecasting model. Evaluate its accuracy before
using forecasts in recommendations.
Integration: Connect marketplace, order, notification, and
logistics modules through APIs.
Testing: Test usability, security, performance, data validation,
and end-to-end order workflows.
Pilot deployment: Run a limited pilot with a small group of
farmers/FPOs and buyers in one selected region.
Evaluation and improvement: Collect feedback and measure order
completion, delivery time, user adoption, and price realization
before expanding.
Proposed System Flow
Farmer / FPO                 Buyer
     |                         |
     v                         v
Register and verify       Register and verify
     |                         |
     v                         v
List produce  -------->  Search and compare
     |                         |
     +----------+--------------+
                |
                v
          Place / confirm order
                |
                v
       Logistics coordination
                |
                v
      Pickup and route planning
                |
                v
          Delivery to buyer
                |
                v
       Order completion and feedback

Historical listing, order, and seasonal data
                |
                v
       AI demand forecasting
                |
                v
     Planning recommendations
Feasibility and Viability
Feasibility
The proposed system can be developed using established web, mobile,
database, mapping, and machine-learning technologies. A minimum viable
product can begin with user registration, produce listings, buyer
search, order management, and basic logistics coordination. AI
forecasting and advanced route optimization can be introduced in later
stages after sufficient reliable data becomes available.

A pilot can be conducted in one district or agricultural cluster with a
limited number of crops and participating FPOs. This phased approach
keeps initial development and operational requirements manageable.

Potential Challenges and Risks
Digital literacy: Some farmers may need assistance using a
digital platform.
Connectivity: Rural areas may have inconsistent internet access.
Data quality: Forecasts may be unreliable if listing, sales, or
seasonal data is incomplete.
Quality and grading differences: Buyers and sellers may have
different expectations about produce quality.
Logistics availability: Transport capacity may vary by location,
season, and order volume.
Trust and dispute resolution: Users need confidence in listings,
payments, delivery, and complaint handling.
Adoption and network effects: The marketplace needs enough
sellers and buyers in the same area to be useful.
Mitigation Strategies
Provide a simple mobile-first interface, regional-language support,
and assisted onboarding through FPOs or field coordinators.
Support low-bandwidth usage and allow users to update listings when
connectivity is available.
Start with transparent, explainable forecasting and show confidence
or limitations rather than presenting estimates as guarantees.
Define clear listing fields for quantity, grade, origin,
photographs, and harvest or availability date.
Onboard multiple logistics partners and provide manual assignment as
a fallback when automated matching is unavailable.
Maintain verified profiles, digital order records, clear
cancellation rules, and a structured complaint process.
Begin with a focused pilot area and expand after measuring repeat
usage and successful order completion.
Viability and Sustainability
Potential operating models include a clearly disclosed transaction fee,
logistics coordination fee, or subscription services for institutional
buyers. Basic access for small farmers can be kept affordable, with any
charges communicated before a transaction. Partnerships with FPOs,
cooperatives, local institutions, and logistics providers can support
onboarding and operations. The business model should be validated during
the pilot to ensure that platform costs do not undermine the benefit to
farmers or consumers.

Impact and Benefits
Benefits for Farmers and FPOs
Wider access to consumers and bulk buyers.
More opportunities to negotiate and compare offers.
Better visibility into demand and buyer requirements.
Potential improvement in net price realization through reduced
dependence on multiple intermediaries.
Digital records of listings, orders, and transactions.
Benefits for Consumers and Bulk Buyers
Easier discovery of produce from nearby farmers and FPOs.
More transparent product and price comparisons.
A simpler process for placing household or bulk orders.
Better visibility into order and delivery status.
Potential reduction in avoidable supply-chain costs.
Economic and Operational Benefits
More direct connections between producers and buyers.
Improved coordination of procurement, pickup, and delivery.
Better-informed planning through demand estimates.
Opportunities for local FPOs and logistics providers to participate
in the digital supply chain.
Social and Environmental Benefits
Greater digital participation for farmers through assisted
onboarding and regional-language access.
Potential reduction in spoilage through improved coordination and
timely movement of produce.
Potential reduction in unnecessary transport through grouped
deliveries and route planning.
Stronger local agricultural networks through direct engagement
between producers and buyers.
Suggested Pilot Success Indicators
The pilot can track:

Number of active farmers, FPOs, and buyers.
Number and value of completed direct transactions.
Average farmer net realization compared with the farmer's previous
sales channel.
Buyer price compared with the buyer's previous procurement channel.
Order fulfilment rate and average delivery time.
Produce loss or spoilage reported during pilot transactions.
Repeat purchase rate and user satisfaction.
Forecast error and route-planning performance.
These indicators should be measured against a baseline; improvements
should be reported only after pilot data confirms them.

Research and References
The following sources provide background for designing and validating
the proposed platform. The team should review the latest documentation
and applicable rules before implementation.

Ministry of Agriculture & Farmers Welfare, Government of India
--- Agricultural policies, schemes, and farmer-focused initiatives:
https://agriwelfare.gov.in/
e-NAM (National Agriculture Market) --- Information about
India's electronic agricultural trading platform:
https://www.enam.gov.in/
Small Farmers' Agribusiness Consortium (SFAC) --- Information
and resources related to Farmer Producer Organisations:
https://sfacindia.com/
Department of Agriculture & Farmers Welfare --- Agricultural
statistics, reports, and policy information:
https://agriwelfare.gov.in/
India Meteorological Department (IMD) --- Weather information
that may support agricultural planning: https://mausam.imd.gov.in/
OpenStreetMap --- Open geographic data that may be evaluated for
mapping and route-planning features: https://www.openstreetmap.org/
PostgreSQL Documentation --- Database design and implementation
reference: https://www.postgresql.org/docs/
FastAPI Documentation --- Backend API development reference:
https://fastapi.tiangolo.com/
scikit-learn Documentation --- Machine-learning methods and
model evaluation reference: https://scikit-learn.org/stable/
Note: FarmConnect is a proposed concept. Forecasting accuracy,
logistics savings, price improvements, and reductions in wastage must be
validated through a field pilot rather than assumed in advance.





