# mis561-portfolio




MIS 561 Data Visualization Initial E-Commerce Profitability Analysis, You have been given the company's order extract and asked to make sense of it., https://public.tableau.com/views/MIS561_flex_as3/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link , I would most definitely read the fine print , soemtimes me missing those fine detials made me waste a significant amount of time re reviewing cause it didn't look correct.

MIS 561 Data Visualization Initial E-Commerce Profitability Analysis Pt 2 , You have been given the company's order extract and asked to make sense of it., https://public.tableau.com/views/AdvancinginExcelandTableau-Pt2-AnnieGeorge/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link, I would most definitely read the fine print , soemtimes me missing those fine detials made me waste a significant amount of time re reviewing cause it didn't look correct.


DataCamp : Introduction to Power BI completed on Sept 29th, edited on Oct 5th to get points ; https://public.tableau.com/shared/KCRBNHGWZ?:display_count=n&:origin=viz_share_link

CAPTION: One task Power BI handles automatically that I did by hand in Flex 3 was combining separate tables into one analysis-ready table. I joined the tables manually and then reconciled the row counts afterward to confirm that no records had been dropped or duplicated. Power BI detects matching fields and links the tables in its data model, so nothing has to be merged or recounted. For a task like this I would choose Power BI next time, mainly because the relationships persist when the data refreshes, so a monthly update wouldn't require rebuilding the join. I would still spot-check the totals it produces, since automatic matching can link the wrong fields.


DataCamp: Introduction to DAX in Power BI competed on Sept 29th , edited Oct 5th  ;  https://public.tableau.com/shared/SPFHY7FDH?:display_count=n&:origin=viz_share_link

CAPTION: In Flex 4, I calculated each self-serve customer's net margin by adding up the margin on all of their order lines (revenue minus cost) and then subtracting the cost to serve per account, which was not in the transaction data. In Power BI I would build it as a measure, not a calculated column, because it has to be summed at the customer level and recalculated for whatever date range or segment the reader selects. A calculated column would sit on each order line, where the one-time account cost would be repeated on every row or have no sensible place to go. If that number lives in the model, Anita or Marcus can filter to any time period or customer group in a meeting and see which accounts lose money, without waiting for me to re-run the pivot tables. They also get a list that updates when new orders arrive, so the retire-or-keep decision is never based on last quarter's numbers.

Data Camp: Data Visualization in Power BI ; COmpleted on Oct 12 ; https://public.tableau.com/views/PowerBI-DataCampTrainingCertificates/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

CAPTION: Sarah, I’m ready for BI work at Southwest because I’ve done by hand what Power BI makes durable. I joined separate tables manually, then reconciled row counts to prove no records were dropped or duplicated. In Power BI that becomes a relationship that survives refresh, though I’d still spot-check totals, since automatic matching can mislink fields. I also calculated each self-serve customer’s net margin: order-line margin minus a per-account cost to serve that wasn’t in the transaction data. I’d rebuild it as a DAX measure, not a calculated column, which would repeat that account cost on every order line. Anita and Marcus could filter by date or segment and see which accounts lose money.

I’d use Excel for one-off questions that need cell-by-cell auditing, Tableau when an analyst is chasing an unexpected pattern, and Power BI for a governed model refreshing on schedule for many readers. My gap: I’ve never published to the Power BI Service or maintained a report others depend on. I’d publish a small report, schedule its refresh, and ask a user what confused them.

** I used generative AI (Claude) to help draft and edit this entry; the examples and judgments are my own.

