# Minor_project_5
Sales Operations Analytics project covering end-to-end data processing in Excel: multi-table lookups (INDEX-MATCH, VLOOKUP), data cleaning, conditional aggregations (SUMIFS), Pivot Table reporting, and advanced analytics (running totals, ranking). Features analysis across 2,000+ orders, customers, products, and sales targets.

Formulas & Functions Used
1. Lookup & Reference FunctionsVLOOKUP: Performs standard vertical lookups to pull product categories, unit prices, discounts, and regional rep information across tables.INDEX: Returns specific cell values from multi-column ranges based on row and column index numbers.MATCH: Finds the relative row or column position of a lookup value (used dynamically with INDEX for flexible two-way and dynamic lookups).

2. Conditional Aggregation & Mathematical FunctionsSUMIFS: Adds values across ranges based on multiple criteria (e.g., total sales by region, segment, or specific date window).COUNTIFS: Counts cells that meet multiple criteria (used for order volume analysis and duplicate detection).AVERAGEIFS: Calculates conditional averages across order quantities and profit margins.SUMPRODUCT: Handles array calculations to compute weighted averages, complex multi-condition metrics, and running aggregations without requiring explicit array formulas.MAX & LARGE: Extracts peak values and ranks top-$N$ sales representatives and products.

 3. Logical & Data Cleansing FunctionsIF: Evaluates conditions to return custom logic outcomes (e.g., margin checks, performance thresholds).IFERROR: Traps errors (#N/A, #VALUE!) to output clean default values or blanks.TRIM: Trims extra leading/trailing spaces from text values to clean data inconsistencies.

4. Date & Formatting FunctionsDATE: Constructs valid Excel date serial numbers from year, month, and day inputs.TEXT: Converts numeric dates into formatted text strings (e.g., converting dates into Mon-YY tags).

 Excel Tools & Analytical Techniques UsedPivot Tables & Calculated Fields: 
 Built 2D pivot reporting to analyze sales trends, date-grouped orders, and percentage-of-row total breakdowns.
 Multi-Table Referential Integrity: Linked 5 relational sheets (Orders, Customers, Products, Sales_Reps, Targets).
 Advanced Ranking Models: Combined LARGE + INDEX + MATCH to dynamically construct top-$N$ leaderboard views.
