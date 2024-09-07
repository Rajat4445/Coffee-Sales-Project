<p align="center">
  <img src="https://media.giphy.com/media/5pT419fusqLKnJ6ZUO/giphy.gif?cid=ecf05e4710ej2ymr5jg3tr4sz23tl365yi7xrvqa37xxqno7&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="200" alt="Coffee GIF">
</p>

# ☕ Coffee Sales Report: Data Cleaning, Transformation, and Analysis

![Excel Badge](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Complete-green)

Detailed report can be read in `Coffee Sales Project Report` which has been attached in this repository itself.

## 🚀 Project Overview
This project focuses on analyzing coffee sales data using **Microsoft Excel** to extract insights and make data-driven recommendations. The data was cleaned, transformed, and visualized, culminating in a comprehensive dashboard.

## 📊 Data Cleaning & Transformation

1. **Data Extraction & Loading**: 
   - Imported data into Excel using Power Query for inspection, cleaning, and transformation.

2. **Feature Engineering**:
   - Extracted coffee sizes (Large, Regular, Small) from the `Product Detail` column and created a new `Size` column.
   - Cleaned the `Product Detail` column by removing size information and extra spaces.

3. **New Calculated Fields**:
   - Created a `Total Bill` column using the formula `transaction_qty * unit_price`, formatted as currency.

4. **Date and Time Adjustments**:
   - Extracted only the time from the `transaction_time` column to remove redundant date information.
   - Added `Month Name`, `Day Name`, and `Hour` columns for further analysis.

## 📈 Data Analysis

- Created Pivot Tables to uncover key insights:
  1. 📅 **Hour of Day vs Transaction Quantity (Sum)**
  2. 📊 **Day of Week vs Total Bill (Sum)**
  3. 🍵 **Product Category vs Total Bill (Sum)**
  4. 📆 **Month vs Total Bill (Sum)**
  5. 🛍️ **Product Detail vs Total Bill (Sum)**
  6. ☕ **Product Type vs Total Bill (Sum)**
  7. 🏢 **Store Location vs Total Bill & Total Orders (Distinct count of transaction_id)**
  8. 🥤 **Size vs # of Orders (Distinct transaction IDs)**
  9. 📈 **Day of Week vs # of Orders**

- Developed visualizations and combined charts for an optimized dashboard view with interactive features like slicers and KPIs.

## 🔍 Key Insights

- 📈 **Sales Trends**: Revenue doubled from $81.7K to $166.5K, showing a positive growth trend.
- 🕒 **Peak Hours**: Sales peak from 6 AM to 10 AM and stabilize between 12 PM to 5 PM.
- 📅 **Increasing Sales**: Revenue and orders increased over the weeks.
- 🥐 **Popular Products**: Coffee, Tea, and Bakery items drive the most revenue.
- 📏 **Size Preferences**: Large and Regular sizes are the most popular; Small is the least favored.

## 📍 Location-Specific Insights

- **Lower Manhattan**: Peaks at 7 AM and 10 AM but declines significantly after 4 PM.
- **Astoria**: Peaks at 10 AM, remains stable throughout the day, and operates on shorter hours.
- **Hell’s Kitchen**: Shows peaks at 8 AM and 10 AM; stabilizes after noon.

## 💡 Recommendations

1. **Expand Morning Rush Capacity**: Add more staff or self-service kiosks during peak morning hours.
2. **Promote Afternoon Specials**: Introduce discounts or combos to boost afternoon sales.
3. **Optimize Astoria’s Hours**: Open earlier and close later to capture more traffic.
4. **Address Lower Manhattan’s Evening Decline**: Investigate reasons for the 7 PM drop and implement corrective actions.
5. **Introduce Seasonal Drinks**: Offer limited-time variations of popular products to attract repeat customers.
6. **Enhance Afternoon Engagement**: Use loyalty rewards or sampling events to drive traffic in the slower afternoon hours.

## 📝 Conclusion

This project demonstrates how data analysis can optimize coffee shop operations, highlight peak performance times, and suggest targeted improvements for each location.

<p align="center">
  <img src="https://media.giphy.com/media/eujb1tWaj3ZxS/giphy.gif" width="200" height="200" alt="Barista GIF">
</p>
<p align="center">
  <a href="https://giphy.com/gifs/hoppip-art-film-eujb1tWaj3ZxS">via GIPHY</a>
</p>

## Watch explanation on YouTube

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcGFyZzc3Z2dsc2poZ3JxZHVxNHRmZ3QxcHVydXYzZHk1c2JrZ2NscyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/13Nc3xlO1kGg3S/giphy.gif" width="200" height="100" alt="Funny GIF">
</p>

[Watch the Video on YouTube](https://youtu.be/MO9zQL14ECI)

## 👤 Author
- [Rajat Bahuguna](#)

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
