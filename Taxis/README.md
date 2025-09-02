## 🚕 NYC Taxi Data Analysis

This project explores the Seaborn Taxis dataset, uncovering insights about passenger behavior, payment preferences, fare structures, and city-wide travel patterns. Through data wrangling and visualization, I analyzed how different factors affect ride costs and customer tipping.

### 📌 About the Dataset
The Taxis dataset includes ride-level information about New York City taxis:
- 🚖 Pickup & drop-off zones
- 👥 Passenger count
- 💰 Fare & tip amounts
- 📍 Borough information
- 🕒 Trip duration & distance
- 🎨 Taxi color (yellow, green, etc.)
- 🔍 Key Analyses & Insights

### 🔍 Key Analysis & Insights
**1. 💳 Distribution of Payment Methods**
- Credit cards dominate 🚀 — Around 72% of trips were paid by card, showing the strong preference for digital transactions.
- Cash still relevant 💵 — About 28% of payments were in cash, highlighting that a significant portion of riders still rely on cash

**2. 📍 Most Common Pickup Zones**
- Busy transport hubs — Midtown Center (227 rides) and Penn Station/Madison Sq West (209 rides) are top pickup spots, likely due to high commuter traffic.
- Tourist & business hotspots — Times Sq/Theatre District and Union Sq also rank high, reflecting strong demand in entertainment and business areas.

**3. 👥 Average Fare per Passenger Count**
- Costs are stable per passenger group — Average fares remain in the $18–19 range, regardless of passenger count.
- No major cost-saving from carpooling — Even with higher passenger counts (3–6), the average total fare does not decrease significantly.

**4. 💸 Average Tip % of Total Fare**
- Tipping behavior — On average, riders tipped about 10.1% of the total fare, which is fairly standard in taxi services.
- Moderate generosity — This indicates that most riders are consistent with tipping norms but not overly generous compared to industries like restaurants (where 15–20% is typical).

**5. 🗺️ Most Expensive Pickup–Dropoff Route**
- Long-distance, costly rides — Routes like Sunset Park West → Saint Albans ($94.8) top the list, likely due to crossing multiple boroughs.
- Airports are high-value hubs — Several expensive routes involve JFK Airport, showing how airport trips significantly contribute to revenue.

**6. 🏙️ Which Boroughs Have the Highest Fares?**
- Queens dominates — Average fares are highest in Queens (~$30.9), driven mainly by airport-related rides (JFK, LaGuardia).
- Manhattan surprisingly lower — Despite being a busy hub, Manhattan shows the lowest average fare (~$16.6), likely due to shorter intra-city rides.

**7. 📏 Longest Trips by Distance**
- JFK Airport trips lead — The longest and costliest trip was JFK → JFK (36.7 miles, $174.8), indicating long loop trips, possibly for out-of-town transfers.
- Consistent airport influence — JFK appears multiple times among top distances, highlighting its central role in long and high-value taxi journeys.

**8. 📊 Correlation Between Fare, Distance, and Tips**
- Strong distance-fare link — Distance and fare have a very high correlation (0.95+), confirming that longer rides almost always mean higher fares.
- Tips are less tied to distance — Tip amount has a weaker correlation (~0.47 with distance), suggesting tipping depends more on customer generosity than ride length.

**9. 🎨 Average Fare per Taxi Color**
- Yellow taxis earn more — Average fare for yellow taxis (~$18.6) is higher than for green taxis (~$16.4), suggesting yellow taxis might serve busier or longer routes.
- Green taxis are cheaper — Green taxis may be more common in outer boroughs with shorter rides, which explains their lower average fare.

**10. 🚦 Peak Zones with High Passenger Count**
- Midtown Center is the busiest — With 360 passengers, Midtown Center tops the list, showing it’s the prime hotspot for pickups.
- Tourist & commercial zones dominate — Areas like Clinton East, Upper East Side and Times Sq/Theatre District highlight that high passenger demand comes from business hubs and tourist-heavy areas.

**11. 📈 Total Fare vs Distance of Ride**
- Visualized fare growth with distance.
- Showed a non-linear relationship (short trips disproportionately expensive).

### 🛠️ Tools & Libraries
- **Python** 🐍
- **Pandas** → Data cleaning & manipulation
- **Seaborn & Matplotlib** → Visualizations
- **NumPy** → Statistical calculations

## ✨ Conclusion

This project uncovers fascinating insights about NYC taxi rides — from how people pay to where they travel most, how much they tip, and how fare scales with distance.

**⚡ Taxis don’t just move people — they move data stories too!**
