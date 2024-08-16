# Car Data Analysis with Python

This repository provides an in-depth analysis of a car dataset, highlighting trends in car types, origins, prices, and weights. It aims to offer insights for market analysis and pricing strategies in the automotive industry.

## Dataset Columns

The dataset includes the following columns:

- Make: The manufacturer of the vehicle
- Model: The specific model name
- Type: The category of the vehicle (e.g., Sedan, SUV, Sports)
- Origin: The region where the vehicle was manufactured (Asia, USA, Europe)
- DriveTrain: The type of drive system (e.g., Front, Rear, All)
- MSRP: Manufacturer's Suggested Retail Price in USD
- Invoice: The dealer's cost for the vehicle in USD
- EngineSize: The size of the engine in liters
- Cylinders: The number of cylinders in the engine
- Horsepower: The power output of the engine
- MPG_City: Miles Per Gallon for city driving
- MPG_Highway: Miles Per Gallon for highway driving
- Weight: The weight of the vehicle in pounds
- Wheelbase: The distance between the front and rear wheels in inches
- Length: The total length of the vehicle in inches

## Findings

1. **Car Types:**
   - Most common car types: Sedans (262), SUVs (60), and Sports cars (49).

2. **Origin Analysis:**
   - Majority of cars are from Asia (156), followed by the USA (147), and Europe (123).

3. **Price Analysis:**
   - Average MSRP by origin: Asia ($24,741), Europe ($48,349), USA ($28,377).
   -The highest average MSRP is for European cars.

4. **Weight Analysis:**
   - Average car weight: Asia (3319 lbs), Europe (3680 lbs), USA (3769 lbs).
   - European cars tend to be heavier than those from Asia.
  
5. ### MSRP by Type and Origin
- Highest: European Sports cars ($71,998)
- Lowest: Asian Hybrids ($19,920)
- SUVs vary significantly:
  - Europe: $48,346
  - USA: $34,589
  - Asia: $29,569

6. ### Luxury Segment
Top 5 most expensive cars are all European:
1. Porsche 911 GT2 2dr: $192,465
2. Mercedes-Benz CL600 2dr: $128,420
3. Mercedes-Benz SL600 convertible 2dr: $126,670
4. Mercedes-Benz SL55 AMG 2dr: $121,770
5. Mercedes-Benz CL500 2dr: $94,820

7. ### Average MPG
The **MPG_Average** was calculated by averaging the **MPG_City** and **MPG_Highway** values. This shows significant differences in fuel efficiency across vehicle types, with sedans generally offering higher MPG than SUVs, making them more appealing for fuel-conscious consumers.

8. ### MSRP to Invoice Ratio
The **MSRP_Invoice_Ratio** indicates a markup above the invoice price, with all models showing ratios slightly above 1. The **Acura 3.5 RL 4dr** has the highest ratio (1.122), reflecting its premium pricing, while the **Acura RSX Type S 2dr** has the lowest (1.095). This suggests consistent pricing strategies across models, with varying market positions.



9. ## Visualizations

- **Bar Plots :**To compare the average MSRP for different types of cars.
- **Count Plots:**To show the count of different types of cars.
- **Scatter Plots:** To analyze the relationship between Horsepower and MSRP.

10. ## Dataset

- Columns include: Make, Model, Type, Origin, DriveTrain, MSRP, Invoice, EngineSize, Cylinders, Horsepower, MPG_City, MPG_Highway, Weight, Wheelbase, Length.

11. ## Conclusion

The analysis reveals significant car types, origins, and pricing trends, providing valuable insights for automotive market strategies.

