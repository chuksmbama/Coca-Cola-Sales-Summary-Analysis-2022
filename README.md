# **Project Overview**

This project analyses Coca-Cola’s 2022 sales data to show what is selling, where revenue comes from, and how profitable sales have been. It solves the problem of scattered, hard-to-interpret sales data by bringing key metrics, product performance, regional trends, and yearly sales patterns into one clear dashboard. This project will help decision-makers focus on the right products, markets, and growth opportunities.

# Data Cleaning and Preparation

🔹 **Data Preparation & Transformation**

- Cleaned and transformed the dataset using Power Query to ensure accuracy and consistency
- Standardised all column headers to lowercase to maintain a uniform naming convention
- Created DAX measures to calculate key metrics for Total sales, Total revenue, profit margin, operating profit and total expenses for each beverage
- Sourced and integrated official Coca-Cola beverage logos and product images for visual clarity
- Applied Coca-Cola’s brand colour codes to ensure visual consistency and accurate brand representation

# Dashboards and Data Visualisation

**🔹 Data Visualisation**

- KPI cards presenting total sales, total revenue, operating profit, profit margin, and total expenses across all beverage products
- Line charts illustrating monthly trends in sales, revenue, profit margin, operating profit, and expenses for each beverage throughout the year
- Bar charts highlighting revenue contribution by beverage and comparing sales volume across products
- Line charts analysing the monthly relationship between sales and revenue to assess performance consistency
- Column charts displaying total units sold across beverage categories
- Funnel charts identifying the top five states by sales performance and ranking regions based on total sales contribution
- Map visualisations showing state-level sales distribution for each beverage
- Doughnut charts comparing the proportion of units sold by beverage across different retailers
- Bar charts comparing beverage sales performance across all regions
- Column charts showing average delivery time by beverage and delivery company

# Insights

**🔹 How were sales for the year?**

The year's sales started solidly at **$491,325** in **January;** then there was a slight drop in sales **(-6%)** between **February** and **March,** averaging **$462,790** in sales. **April** held steady at **$468,825**, showing stability. **May** marked the shift where sales jumped by **(+37%)** to **$643,873**, followed by June at **$843,100** **(+31%)** and **July** peaking at **$969,638 (+15%)**. This marked the strongest growth phase of the year. A slight drop in **August** to **$888,450 (-8%)**, with a further drop in **September** and **October** to **$651,025** and **$595,363**. **November** came as a turning point, where sales increased by **(+27%)** to **$753,288**, and by **December,** sales increased further to **$984,700 (+31%).**
In conclusion, despite the decline, we closed the year with a powerful 100% in monthly income compared to January

**🔹 How was revenue during the year?**

The year’s revenue started strong and efficiently. **January** to **March** converted almost fully, with revenue averaging **$462,902**, showing tight control. **April** and **May** changed the pace. Revenue jumped ahead of sales, hitting **$570,553 (+23%)** in **April** and **$729,345 (+28%)** in **May**, suggesting timing or pricing gains. **June** kept up at **$935,875 (+28%),** marking the **highest revenue generated**, while in **July**, there was a slight drop to **$929,413 (-0.7%).** Summer showed pressure. **August** revenue dropped to **$734,250 (-21%)** and then stabilised in **September** and **October**. By **November**, revenue increased by **(+34%)** to **$891,205**, and by **December**, there was a huge drop in revenue to **$698,888 (-22%), the highest drop in revenue**, likely from a discount.

In conclusion, despite a sales peak in December, revenue saw its sharpest decline, suggesting that the high volume of sales was driven by heavy discounting, which affected revenue for the month. But despite that, revenue trailed, indicating that nearly all booked sales were successfully converted, though late-year discounting likely narrowed the final gap. 
Sales and revenue were closely aligned, meaning most sales were successfully converted into profit

**🔹 How was the profit margin for the year?**

The year started steadily, with **January** to **March** holding around **37%**, meaning roughly **37 cents of every sales dollar is profit**. By **April**, profit margin drops to **30%**, likely from higher costs or lower pricing, before a gradual recovery in **May** and **June** to **33-34%**. By **July**, the profit margin jumped to **39%**, and by **August**, it moved further up to **46%**, showing strong efficiency or better pricing. The profit margin went down again in **September** to **38%** and in **October** to **33%**, then fell slightly in **November**. **December** finished the year with an outstanding profit margin of **52%** (**the highest profit margin**), signalling exceptional profitability. 
Overall, our profit margin was highly dynamic, starting at a steady **37%** and scaling through mid-year volatility to reach a record high of **52%** in December.

**🔹 How much was operating profit for the year?**

Imagine we are running a high-end bakery. To know if we are successful, we don't just look at the cash in the register at the end of the day. That's just revenue. We also don't look at the final profit after we've paid back our start-up loans or taxes. Instead, we look at the **operating profit**.
This is the money left over after we pay for the flour, the electricity for the ovens, and the bakers' wages. It’s the purest measure of whether we are actually good at making and selling bread.
The year started flat from **January** to **March**; operating profit fell from **$177,690** to **$167,598**, a combined decline of about **(-5.7%)**, showing steady operations but limited efficiency gains. **April** brought a mild recovery, and operating profit moved to **$169,804 (+1.3%)**.
**May** marked a clear shift: operating profit jumped to **$239,432 (+41%)**, indicating that core operations became more profitable. This momentum continued in **June** at **$314,961 (+31.6%)** and peaked in **July** at **$364,564 (+15.8%),** marking **the highest operating profit of the year**. **August** eased slightly to **$334,411 (-8.3%)**, but remained strong. **September** and **October** saw sharper pressure, falling **(-28.1%)** and **(-9.1%)**, respectively, signalling rising costs or softer demand. However, the year ended strongly; by **November,** operating profit moved up to **$278,433 (+27.3%)**, and by **December** it moved further to **$366,348 (+31.6%)**, showing we finished the year operating with high efficiency.
In conclusion, the operating profit of $3,041,142 showed our business ran efficiently for the year. From $8,166,073 in revenue and only $1,752,701 going into expenses. 

**🔹 How much did we spend for the year on expenses?**

The year started controlled. Expenses fell from **$99,691** in **January** to **$94,126** in **February (-5.6%)**, before rising slightly in **March** to **$99,310 (+5.5%)**. Expenses jumped sharply in Q2. By **April**, it jumped to **$120,280 (+21.1%)**, moved further in **May** to **$150,559 (+25.2%)**, and by **June** surged to **$196,836 (+30.7%)**. This signalled increased operational activity or higher input costs.
**July** peaked at **$210,492 (+6.9%)**, marking the **highest amount of money spent on expenses for the year**. From there, expenses pulled back hard; by **August**, it dropped to **$160,162 (-23.9%)**, and by **September**, it fell further to **$128,651 (-19.7%)**, showing strong cost tightening. 
Q4 was mixed; **October** edged up to **$136,920 (+6.4%)**; **November** spiked sharply to **$198,245 (+44.8%)**, then **December** decreased to **$157,429 (-20.6%)**.
Overall, expenses were heavily concentrated mid-year, with clear cost pressure during peak operations and better control towards year-end. 

**🔹 Which beverage contributed the most to our revenue?**

**Diet Coke** led the revenue for the year, bringing in **$1,807,240**, about **22%** of total revenue generated. **Coca-Cola** followed closely with **$1,673,538 (20%)**, showing that both brands dominated sales. 
**Dasani Water** and **Sprite** contributed **16%** and **16%** respectively, while **Fanta** and **Powerade** added smaller shares at **13%** and **12%**. This showed 42% of our revenue came from our Colas.

**🔹 Which beverage led the overall sales volume?**

**Coca-Cola** led overall sales volume, generating **$1,923,053**, about **23% of total sales**, making it the top seller. **Dasani Water** followed with **$1,639,063 (20%)**, and **Diet Coke** contributed **$1,391,088 (17%)**. **Sprite**, **Powerade**, and **Fanta** made smaller shares at **14%**, **14%**, and **12%,** respectively. This shows classic Coca-Cola remained the most popular choice, with water and diet Coke options also driving significant volume.

**🔹 Beverage sales vs revenue generated**

**Coca-Cola** led in sales volume with **$1,923,053 (23%)**, but revenue was **$1,673,538 (20%),** showing large volume but slightly lower per-unit price. **Diet Coke** earned more in revenue, **$1,807,240 (22%)**, than in sales, **$1,391,088 (17%)**, indicating higher pricing or premium positioning.
**Dasani water** was consistent, **$1,639,063 (20%)** in sales and **$1,321,688 (16%)** in revenue, showing moderate volume with steady margins. **Sprite** and **Powerade** had similar patterns, contributing roughly **14%** in sales but slightly less in revenue, pointing to lower prices. **Fanta** sat at the lower end, **$969,888 (12%)** in sales and **$1,065,065 (13%)** in revenue, suggesting fewer units sold but reasonable pricing. 

**🔹 What were the total units sold?**

**Coca-Cola** led the year in total units sold with **3,989,000 units (23%)**, making it the most popular choice. **Dasani Water** and **Diet Coke** followed closely with **2,890,500 (17%)** and **2,872,000 units (16%)** respectively, showing strong demand for **water** and **diet** options. **Sprite** accounted for **2,588,500 units (15%)**, while **Fanta** and **Powerade** sold **2,100,000 (12%)** and **2,042,500 units (12%)**. Overall, classic cola dominated volume, with water and diet drinks capturing significant portions of the market

**🔹 Which retailer drove the most sales and revenue?**

**Walmart** clearly led in sales and revenue generated; it recorded **$4,403,630** in **sales (54%)** and **$4,340,288** in **revenue (53%)**, dominating both volume and earnings. **CVS** followed with **$2,115,588** in **sales (26%)** and **$2,130,925** in **revenue (16%)**, and **Target** came last with **$404,413** in both **sales** and r**evenue (5%).** 
Overall, this showed Walmart drove most of our sales and revenue, with CVS and Costco providing support and Target playing a minor role. 

**🔹 Which region accounted for the largest share of total sales?**

The **West** region emerged as the top performer, contributing **$2,366,238 (29%)** of total sales, showing it was the strongest market. The **Northeast** followed with **$1,788,348 (22%),** and the **Southeast** added **$1,618,935 (20%)**, reflecting solid demand in these areas. The **South** and **Midwest** brought in smaller shares, **$1,291,535 (16%)** and **$1,150,110 (14%),** respectively. Overall, the **West** drove the majority of sales, highlighting it as a key focus area for growth.

**🔹 Which 5 states were our top sales contributors?**

**California** led with **$582,400**, setting the pace as the strongest contributor. **Florida** followed closely at **$561,950**, with **New York** right behind at, showing strong demand across major population centres. **Texas** added **$440,988**, while **Georgia** rounded out the top five with **$292,210**. Together, these states formed the core of sales performance, accounting for the majority of top-state contributions.

# Recommendations

**🔹 Double down on peak periods** 

Mid-year and year-end consistently delivered the strongest sales and operating profit. I recommend we plan **major campaigns**, **product launches**, and **retailer promotions** around **May–July** and **November–December**, where momentum is proven.

**🔹 Reduce over-discounting in December**

**December** sales peaked, but revenue dropped sharply, showing that heavy discounting hurt value. I recommend we introduce **targeted discounts** instead of blanket price cuts, and push bundles or premium packs to protect revenue and margin.

**🔹 Scale what works in the West, replicate elsewhere**

The **West** was the strongest region. I recommend we use it as a **benchmark for pricing**, **distribution**, and **promotion strategies**, then replicate successful tactics in the **Northeast and Southeast**, which already showed strong demand.

**🔹 Strengthen high-margin brands**

**Diet Coke** and **Fanta** generated more revenue relative to sales volume, indicating better pricing power. I recommend we **increase visibility** and **marketing** for these brands to lift overall revenue without relying on sales volume alone.

**🔹 Protect Coca-Cola volume while improving price mix**

**Coca-Cola** led in sales volume but lagged slightly in revenue share. I recommend we introduce **premium variants, bundles, or limited editions** to increase revenue per unit without risking sales volume.

**🔹 Tighten cost control during growth phases**

Expenses spiked sharply during mid-year growth. I recommend we put **stronger cost controls in place during high-demand** periods to ensure sales growth consistently translates into operating profit.

**🔹 Prioritise top retailers and states** 

**Walmart**, **CVS**, **California**, **Florida** and **New York** drove most of the sales. I recommend we focus on **joint promotions**, **exclusive deals**, and **supply optimisation** in these channels and locations to maximise return on effort.

**🔹 Push water and health-focused products** 

We had strong unit sales for **Dasani Water** and **Diet** options, showing growing health demand. I recommend we **expand these categories** to capture volume growth while using pricing discipline to protect margins.

# Summary

The year showed steady growth with a strong finish. Sales and revenue started well, dipped slightly early in the year, then surged from May to July, marking the strongest growth period. Although sales peaked in December, revenue dropped, indicating heavy discounting, even though sales and revenue remained closely aligned overall.

Profitability improved over time. Profit margin and operating profit strengthened from mid-year and closed at their highest levels, showing better operational efficiency despite cost pressure during peak months. Expenses were highest mid-year but were better controlled toward year-end.

Growth was driven mainly by Coca-Cola and Diet Coke, Walmart, the West region, and a few key states.

In conclusion, the year delivered solid sales and revenue performance, and we closed it in a stronger position, operating more efficiently and profitably than at the start.


**🔹 Tools and Technologies**

- Power BI
- Excel
- Github

<img width="1485" height="832" alt="Screenshot (144)" src="https://github.com/user-attachments/assets/4a02f9c9-fe00-439c-97fd-b248b0b2c249" />
<img width="1486" height="830" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/1529d067-b753-4fb7-b46f-302c573848eb" />
<img width="1486" height="828" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/fdfa61bf-2489-4af1-88c0-294b7a27e2e0" />
<img width="1485" height="833" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/fe8505ea-e384-4393-81fb-2355ba3caa30" />
<img width="1484" height="833" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/caa06585-7ed5-49be-a414-bed2db4bc8fa" />
<img width="1487" height="831" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/39ee97c2-3ff2-46e6-97ec-6ccd1ca6b4cd" />
<img width="1486" height="831" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/fdbdacf0-16d7-4efe-af11-01ab8b034531" />








