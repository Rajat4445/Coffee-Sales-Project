# Coffee Sales Report: Data Cleaning, Transformation, and Analysis

## Project Overview
This project focuses on analyzing coffee sales data to extract insights and make data-driven recommendations. The data was cleaned, transformed, and visualized using Microsoft Excel, with a final dashboard summarizing the key findings.

## Data Cleaning & Transformation

1. **Data Extraction & Loading**: 
   - The data was imported into Excel using Power Query for initial inspection, cleaning, and transformation.

2. **Feature Engineering**:
   - Extracted coffee size (Large, Regular, Small) from the `Product Detail` column and created a new `Size` column.
   - Removed size information from `Product Detail` by replacing values (Lg, Rg, Sm) with blanks and trimmed extra spaces.

3. **New Calculated Fields**:
   - Added a `Total Bill` column calculated as `transaction_qty * unit_price` with currency formatting.

4. **Date and Time Adjustments**:
   - Extracted time from the `transaction_time` column to remove redundant date information using the "Extract Text After Delimiter" feature.
   - Created new columns (`Month Name`, `Day Name`, `Hour`) using Excel’s extract and add column features.

## Data Analysis

- Created Pivot Tables to analyze key metrics:
  1. Hour of Day vs Transaction Quantity (Sum)
  2. Day of Week vs Total Bill (Sum)
  3. Product Category vs Total Bill (Sum)
  4. Month vs Total Bill (Sum)
  5. Product Detail vs Total Bill (Sum)
  6. Product Type vs Total Bill (Sum)
  7. Store Location vs Total Bill & Total Orders (Distinct count of transaction_id)
  8. Size vs # of Orders (Distinct transaction IDs)
  9. Day of Week vs # of Orders

- Created visualizations from the pivot tables and combined charts to ensure clarity and conciseness in the final dashboard.
- Added slicers for Month, Day, Hour of Day, and Store Location to enable interactive filtering.
- Included KPIs for Total Sales, Total Orders, Average Bill per Person, and Average Order per Person.

## Key Insights

- **Overall Trends**: Sales have doubled over the months, indicating strong business performance.
- **Sales Consistency**: Total revenue and orders remain uniform across weekdays and store locations.
- **Peak Hours**: Coffee sales peak from 6 AM to 10 AM, stabilize between 12 PM and 5 PM, and decline further afterward.
- **Popular Products**: Coffee, Tea, and Bakery items are the top revenue generators. Popular sub-categories include Barista Espresso, Brewed Chai Tea, and Hot Chocolate.
- **Size Preferences**: Large and Regular sizes are most popular; small sizes are least preferred.

## Deeper Insights by Location

- **Lower Manhattan**: Peaks at 7 AM and 10 AM but drops significantly after 4 PM.
- **Astoria**: Peaks at 10 AM and remains stable; it opens later and closes earlier than other locations.
- **Hell’s Kitchen**: Peaks at 8 AM and 10 AM, then stabilizes after noon.
- **Performance Ranking**: Astoria performs consistently well, followed by Hell’s Kitchen and Lower Manhattan.

## Recommendations

1. **Expand Morning Rush Capacity**: Add baristas or self-service options during peak hours (6 AM to 10 AM).
2. **Promote Afternoon Specials**: Use discounts or combo deals to boost sales during uniform hours (12 PM to 5 PM).
3. **Optimize Astoria’s Hours**: Open earlier and close later to capture more traffic.
4. **Address Evening Decline in Lower Manhattan**: Investigate factors behind the 7 PM drop and take corrective action.
5. **Enhance Product Variety**: Introduce seasonal variations of popular items like Barista Espresso and Brewed Chai Tea.
6. **Leverage Astoria’s Consistency**: Highlight Astoria’s steady performance in marketing to attract repeat customers.
7. **Test New Bakery Items**: Introduce healthier or seasonal bakery options to drive sales.

## Conclusion

This project highlights the importance of data-driven decisions in optimizing coffee shop operations. By addressing peak hours, product offerings, and location-specific performance, the coffee shop can further enhance sales and customer satisfaction.

## Authors
- Your Name

## License
This project is licensed under the MIT License - see the LICENSE file for details.
