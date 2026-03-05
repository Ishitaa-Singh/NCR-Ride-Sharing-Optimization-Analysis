# NCR-Ride-Sharing-Optimization-Analysis

NCR Ride-Sharing Optimization Analysis
End-to-end data analytics project analyzing 150K ride bookings from Delhi NCR region

📊 Dataset Overview
Source: NCR ride-sharing bookings (anonymized real-world data)
Size: 150,000+ records across 6 months (2024)
Key Columns: Booking ID, Date/Time, Vehicle Type, Pickup/Drop Locations, Booking Value, Driver/Customer Ratings, Cancellation flags, Payment Method
Business Context: Optimize ride operations, reduce 38% cancellation rate, maximize high-value ride revenue


🛠️ Tech Stack & Workflow
1. Python (Pandas) - Data Cleaning & Feature Engineering
text
✅ Loaded & inspected 150K messy records
✅ Created datetime features (year/month/weekday)  
✅ Filled missing ratings with median (4.23⭐ baseline)
✅ Engineered high_value flag (>₹500 rides = 70% revenue)
✅ Classified cancel_type (Cust/Driver/None) → 38% failure rate
✅ Clipped outliers (Booking Value, Ride Distance)
✅ Exported production-ready CSV


2. Excel - Interactive Business Analysis
text
📈 4 Production Pivots Built:
1. Vehicle Performance: Auto (37K rides/25%), Go Sedan best quality (4.35⭐)
2. Cancellation Heatmap: Khandsa hotspot (2.1K driver cancels)  
3. High Value Analysis: 32% rides = 70% revenue (₹36Cr)
4. Monthly Trends: Nov 2024 peak (13.8K rides, 64% success)

🎯 Interactive Dashboard: 3 slicers (Vehicle/Payment/Cancel) controlling all pivots

<img width="434" height="264" alt="Image" src="https://github.com/user-attachments/assets/555bebe2-3d26-47b7-b327-9bf5557ccdf0" />
<img width="1049" height="174" alt="Image" src="https://github.com/user-attachments/assets/304b4f61-128d-4bab-87db-241401fa6995" />
<img width="321" height="167" alt="Image" src="https://github.com/user-attachments/assets/07c37370-97f7-4a2c-841d-de80bf2fc9db" />
<img width="756" height="346" alt="Image" src="https://github.com/user-attachments/assets/dfdb5c86-1ce3-498d-89a1-7be6ba0be443" />





🔍 Key Business Insights
Insight	Finding	Impact
Cancellation Crisis	38% bookings fail (57K rides lost)	Driver cancels = 47% of failures
Revenue Concentration	32% high-value rides = 70% revenue	Focus premium service
Vehicle Strategy	Auto volume leader (37K), Go Sedan quality leader (4.35⭐)	Balanced fleet allocation
Location Hotspot	Khandsa: 2.1K driver cancels (#1)	Targeted intervention needed
Demand Peak	Nov 2024: 13.8K rides (64% success)	Capacity planning critical
