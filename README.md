Executive Sales Dashboard

I built this Power BI dashboard to give a sales leadership team one page where they can see how the business is doing: how much we sell, how much of it is profit, where it comes from, and how it moves through the year.



The numbers at the top
	
Orders	2,707
Units sold	6,698
Revenue	645.22K
Gross profit	296.38K
Gross margin	45.94%

Worth knowing: that works out to about 238 per order in revenue and about 109 per order in gross profit, with roughly 2.5 units in a typical order.

Situation

The sales data was split across orders, countries, channels and products, and nobody could get a quick answer from it. If a manager wanted to know which countries were pulling their weight, or whether sales were slipping, someone had to build a report for them. By the time it came back, the question had usually moved on.

Task

I wanted a single page that a non-technical person could open and understand in a few seconds. It had to cover five things:

headline KPIs
revenue and profit over time, side by side
the best and worst countries
revenue by sales channel and by product category
filters for quarter, month, product and country, so people can poke around without asking me
Action

I started with the data. I cleaned it up, set it up as a fact table with date, product and country tables around it, and made a proper date table so the quarter and month filters behave.

Then I wrote the measures: orders, quantity, revenue, gross profit, and gross margin (gross profit divided by revenue).

For the layout, I put the KPI cards across the top, because that's what an executive looks at first. The middle row has the monthly line chart and the two country charts. The bottom row has the channel pie, the category donut and a map.

A few choices behind that:

Revenue and profit on the same line chart. The distance between the two lines tells you the margin story without needing a third chart.
Top 5 and Bottom 5 countries as two separate bar charts in different colours. It's much easier to see winners and laggards when they aren't mixed into one long list.
Pie and donut for channel and category. There are only a handful of slices, and the question is simply "how is it split", so they do the job.
Four slicers that filter everything. Quarter, month, product and country.

I went with a dark theme and a blue and amber palette so the numbers stand out.

Result

The dashboard answers those original questions in one screen. Here's what it shows:

Margin is steady. Gross margin is about 46% overall, and month by month it stays between roughly 43% and 47%. So profit mostly rises and falls with sales volume, not with pricing or costs.

Revenue swings a lot across the year. The best month (June) brings in about 70K and the weakest (February) about 36K, which is nearly half. Profit follows the same pattern, from about 31K down to 17K.

A few countries carry the business. The UK (74K), Germany (70K), France (55K), Italy (50K) and Spain (47K) add up to about 296K, which is around 46% of all revenue. The UK and Germany alone are roughly 22%.

The bottom five are close together, except Ireland. Belgium, Switzerland, Finland and Czechia sit between 23K and 26K. Ireland is at 17K, well below the rest.

One sales channel dominates. The biggest channel makes up 46.3% of channel revenue, more than double the next one at 20.6%. Product categories are more evenly spread, with the largest at 28.4% and the smallest at 10.8%.

What I'd do with this
Keep a close eye on the top five markets, since so much depends on them.
Dig into why Ireland is so far behind. It could be pricing, distribution or just demand, and the dashboard can't tell me which.
Look at what's happening in the slow months and whether a promotion could help.
Think about how exposed we are to the biggest sales channel.
Things I'd like to add

Year-over-year growth, targets on the KPI cards, a product drill-down page, and customer metrics like repeat buyers.

Built with Power BI, DAX and Power Query.

Tanishq Maurya 
tanisssshhq8@gmail.com
