# mis561-portfolio




MIS 561 Data Visualization Initial E-Commerce Profitability Analysis, You have been given the company's order extract and asked to make sense of it., https://public.tableau.com/views/MIS561_flex_as3/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link , I would most definitely read the fine print , soemtimes me missing those fine detials made me waste a significant amount of time re reviewing cause it didn't look correct.

MIS 561 Data Visualization Initial E-Commerce Profitability Analysis Pt 2 , You have been given the company's order extract and asked to make sense of it., https://public.tableau.com/views/AdvancinginExcelandTableau-Pt2-AnnieGeorge/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link, I would most definitely read the fine print , soemtimes me missing those fine detials made me waste a significant amount of time re reviewing cause it didn't look correct.


DataCamp : Introduction to Power BI completed on Sept 29th, edited on Oct 5th to get points ; https://public.tableau.com/shared/KCRBNHGWZ?:display_count=n&:origin=viz_share_link

CAPTION: One task Power BI handles automatically that I did by hand in Flex 3 was combining separate tables into one analysis-ready table. I joined the tables manually and then reconciled the row counts afterward to confirm that no records had been dropped or duplicated. Power BI detects matching fields and links the tables in its data model, so nothing has to be merged or recounted. For a task like this I would choose Power BI next time, mainly because the relationships persist when the data refreshes, so a monthly update wouldn't require rebuilding the join. I would still spot-check the totals it produces, since automatic matching can link the wrong fields.


DataCamp: Introduction to DAX in Power BI competed on Sept 29th , edited Oct 5th  ;  https://public.tableau.com/shared/SPFHY7FDH?:display_count=n&:origin=viz_share_link

CAPTION: In Flex 4, I calculated each self-serve customer's net margin by adding up the margin on all of their order lines (revenue minus cost) and then subtracting the cost to serve per account, which was not in the transaction data. In Power BI I would build it as a measure, not a calculated column, because it has to be summed at the customer level and recalculated for whatever date range or segment the reader selects. A calculated column would sit on each order line, where the one-time account cost would be repeated on every row or have no sensible place to go. If that number lives in the model, Anita or Marcus can filter to any time period or customer group in a meeting and see which accounts lose money, without waiting for me to re-run the pivot tables. They also get a list that updates when new orders arrive, so the retire-or-keep decision is never based on last quarter's numbers.
