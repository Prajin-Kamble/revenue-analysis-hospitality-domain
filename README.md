# Revenue Analysis Hospitality Domain
## 1. Business problem statements
AtliQ owns multiple five-star hotels across India and has been operating in the hospitality industry for over 20 years. Recently, due to increased competition and ineffective decision-making, the company has experienced a decline in revenue and market share in the luxury and business hotel segment. To overcome this challenge, the management aims to leverage “Business Intelligence and Data Analytics” to identify performance gaps and take data-driven strategic decisions.

##2. Goal of this dashboard
The primary goal of this analysis is to evaluate AtliQ overall business performance using key hospitality metrics such as Revenue, Occupancy, RevPAR, ADR, Cancellation Rate, Realisation %, and Customer Review Ratings. The analysis focuses on identifying trends across time, cities, properties, and booking platforms, and generating actionable insights to help the management improve revenue and operational efficiency.

## 4.	Tech Stack
### The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

## 5. The key visuals
This revenue analysis dashboard presents a clear overview of hospitality performance using key KPIs like Revenue, RevPAR, Occupancy, ADR, and Realisation. Filters by city, property, room class, and time enable focused analysis. The KPI cards highlight overall stability with minimal week-on-week variation. This helps quickly assess the business’s current revenue health.<br>
The donut chart shows revenue distribution, where Luxury contributes the majority share compared to Business. The trend line chart tracks RevPAR, ADR, and Occupancy across weeks. These visuals make it easy to see how pricing and demand move together. Overall trends appear steady with minor fluctuations.<br>
The lower section focuses on operational and property-level performance. Tables compare weekday and weekend metrics and break down results by individual properties and cities. Bar visuals highlight top revenue-generating hotels and booking platforms. This helps identify strong performers and improvement opportunities quickly.

## 6. Insights
### 1. Overall Performance Insights
AtliQ generated a total revenue of 1.69 Billion, with an overall occupancy rate of 57.8%, indicating moderate room utilisation. The Average Daily Rate (ADR) stands at ₹12.70K, while Revenue per Available Room (RevPAR) is ₹7,337, showing that revenue generation is stable but has room for improvement. The cancellation rate is relatively high at 24.8%, which directly impacts realised revenue. Despite this, the realisation rate of 70.1% suggests that a significant portion of bookings are successfully converted into revenue. The average customer review rating is 3.62, indicating acceptable but not exceptional guest satisfaction.<br>
When comparing weekday vs weekend performance, weekends clearly outperform weekdays. Weekend occupancy is 62.6%, significantly higher than the weekday occupancy of 55.8%. Similarly, weekend RevPAR (₹7,972) and ADR (₹12,725) are slightly higher than weekday values. Realisation also improves marginally on weekends (70.6% vs. 69.9%), indicating stronger demand and better pricing power during weekends.

### 2. Month-wise and Week-wise Insights
From a month-wise perspective, May 2022 recorded the highest revenue (₹582M) and the highest occupancy (58.5%), because may is traditionally observed as a vacation period for children, young  adults, and certain working professionals. Revenue shows a gradual decline in June (₹554M) and July (₹552M), while occupancy and ADR remain relatively stable across months. Cancellation rates hover around 25%, indicating a consistent challenge across the period.<br>
From a week-wise analysis, a clear cyclical pattern is observed. Weeks such as Week 19, 20, 22, 24, 27, 28, and 29 show higher revenues (~₹139–140M) with occupancy above 61%, whereas alternate weeks like Week 21, 23, 26, 30, and 31 show a sharp dip in occupancy (~51%) and revenue (~₹114–115M). This pattern highlights demand fluctuations, possibly driven by business vs. leisure travel cycles.

### 3. ADR (Average Daily Rate) Insight
ADR remains remarkably stable across months, weeks, and segments, staying close to ₹12.6K–₹12.7K. This consistency indicates that AtliQ follows a fixed or static pricing strategy with minimal variation across demand periods. While stability reduces volatility, it also suggests missed revenue opportunities during high-demand periods, especially weekends and peak weeks.

### 4. Booking Platform Insights
Among booking platforms, Logtrip delivers the highest realisation (70.6%) with a healthy ADR of ₹12,705, making it the most efficient channel. Journey and Direct Online platforms also perform consistently with realisation above 70%. Platforms like Tripster and Makeyourtrip show comparatively lower realisation (~69.8–69.9%), indicating higher cancellations or inefficiencies. Overall, direct and premium platforms contribute better quality bookings.

### 5. Property-wise Analysis Insights
* AtliQ Exotica (₹316M), AtliQ Palace (₹300M), and AtliQ City (₹282M) are the top revenue-generating properties, together contributing ₹898M (~53% of total revenue).<br>
* AtliQ Seasons generates only ₹65M with 44.6% occupancy, making it the weakest performer, followed by AtliQ Grands with ₹209M revenue and 52.5% occupancy.<br>
* AtliQ Blu records the highest occupancy at 61.9%, followed by AtliQ Palace at 59.9% and AtliQ City at 59.4%, indicating stronger demand stability.<br>
* Cancellation rates are highest at AtliQ Palace (25.2%), AtliQ Grands (25.1%), and AtliQ City (25.0%), directly impacting realised revenue.<br>
* AtliQ Blu has the highest review rating of 3.96, while AtliQ Seasons has the lowest at 2.30, strongly correlating with their occupancy difference of 17.3 percentage points.<br>
* Realisation remains stable around ~70%, with AtliQ Exotica and AtliQ Seasons at 70.6%, while AtliQ Grands is lowest at 69.9%, reflecting booking quality differences.

### 6. City-wise Analysis Insights
* Mumbai generates the highest revenue at ₹661M, supported by a high ADR of ₹15.38K and RevPAR of ₹8,897, making it the most profitable city.<br>
* Delhi has the highest occupancy at 60.4%, but lower revenue (₹291M) due to a comparatively lower ADR of ₹12.16K.<br>
* Bangalore records the lowest occupancy at 55.7% and lowest review rating at 3.41, indicating possible service quality or competitive pricing challenges.<br>
* Hyderabad shows the highest realisation at 70.3% with the lowest cancellation rate at 24.7%, reflecting better booking quality.<br>
* Cancellation rates remain high across cities at around ~25%, with Bangalore and Delhi at 25.0%, impacting net realised revenue.<br>
* Cities with stronger customer satisfaction such as Delhi (3.78 rating) and Hyderabad (3.66 rating) show more stable occupancy and consistent revenue contribution.

## 7. Recommendations
1.	Adopt Dynamic Pricing Strategies to optimise ADR during high-demand periods such as weekends and peak weeks.<br>
2.	Conduct deeper root-cause analysis for low-performing properties like AtliQ Seasons and AtliQ Grands, especially focusing on poor review ratings.<br>
3.	Improving guest experience and review ratings will directly enhance platform ranking and booking conversion rates.<br>
4.	Focus marketing and inventory allocation toward high-realisation booking platforms such as Logtrip and Direct channels.<br>
5.	Introduce demand-based promotions during low-occupancy weeks to smooth revenue fluctuations.<br>

![Snapshot of Power BI dashboard][https://github.com/Prajin-Kamble/revenue-analysis-hospitality-domain/blob/main/Snapshot%20of%20the%20dashboard.png]
