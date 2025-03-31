# Home_Sales

## Instructions

Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![Screenshot 2025-03-30 at 6 17 56 p m](https://github.com/user-attachments/assets/9c87b065-4037-4dad-ac42-0704765286e5)

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![Screenshot 2025-03-30 at 6 18 00 p m](https://github.com/user-attachments/assets/b32f84ec-b7d4-41b4-8611-7cd4174c0c64)

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![Screenshot 2025-03-30 at 6 18 06 p m](https://github.com/user-attachments/assets/1ba55cec-2b02-4c97-affa-12cb21f61180)

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![Screenshot 2025-03-30 at 6 18 18 p m](https://github.com/user-attachments/assets/4e9b0c29-f6a6-4eba-b428-f4736e303150)

Cache your temporary table home_sales.
Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![Screenshot 2025-03-30 at 6 18 24 p m](https://github.com/user-attachments/assets/aa91aea2-ab74-4794-bd1c-b2ba2f396bbf)

Partition by the "date_built" field on the formatted parquet home sales data.
Create a temporary table for the parquet data.
Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![Screenshot 2025-03-30 at 6 18 33 p m](https://github.com/user-attachments/assets/e2267596-8118-4043-8252-82911dbf3a60)

