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

Card Portfolio Review – Contactless Readiness, Which one batch of non-contactless cards should Renee’s team replace early this quarter to get tap-to-pay out to customers without wasting money?, https://public.tableau.com/views/CarPortfolioReview-ContactlessReadiness/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
, I’d add a small label on the chart showing how much money the 1,253 automatic replacements would waste if they got replaced early. Right now the chart makes the 229 bar look like the obvious pick, but it doesn’t show what the other bars would cost if she chose them. Seeing that number would make the decision feel even easier for Renee.



Card Growth Analysis – Wildcat Rewards Offer ; Business question: Which single customer group should receive the one Wildcat Rewards pilot mailing, and how many customers in that group qualify at the 670 FICO cutoff? ; Tableau Public workbook: https://public.tableau.com/views/CardGrowthAnalyst-WildcatRewardsOffer/ExploratoryDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link




One thing I would change: I would add a second chart showing each generation’s total customer count next to its eligible count, so the VP can see at a glance that Gen Z’s 26.4% share comes from a group large enough to support a real pilot.

**Nov 2, 2026 · Data Storytelling with Adobe Express**

Work sample for Sam Okafor, Chief Credit Officer at Bear Down Bank: keep the minimum FICO score for the Wildcat Rewards offer at 670.

[Work sample (PDF)]: https://github.com/ageorge4-cyber/mis561-portfolio/blob/main/adobe/George-data-storytelling.pdf

[Adobe Express]: https://new.express.adobe.com/id/urn:aaid:sc:US:7aaaaff1-409a-421a-91e7-2c7555b84ded?accept=true&invite=true&promoid=Z2G1FQKR&mv=other

Design choice: I used a bar chart of heavy-debt share by FICO band with the 670 minimum marked, because the case for keeping 670 rests on 44.0% of customers below it owing more than twice their annual income, versus 16.3% at 670 and above. I considered a histogram of customer counts by score, but it shows how many customers sit below 670, not whether they carry more debt. I removed the patterned purple background and the textured color bands behind the wordmark and footer, because Sam will scan this page once and a plain white field lets the eye go straight to the 670 line while keeping all text in high-contrast navy and white.

Training completed: [date you finished the Adobe training]

AI use: Claude (Anthropic), Claude Sonnet 5.5, Nov 2, 2026. Prompt: Chose from buttons: “Keep the minimum at 670”
“tell me what to do step by step”
“here is my professors lecture about the guided assignment :” (followed by the pasted lecture transcript)
“Firm name is Arizona Pilares”
Uploaded Exploratory_Dash.png: “here is my dashboard”
“just to show earlier work , ok let’s get started in adobe”
Uploaded a screenshot: “brand kit is done and now I have created the blank page :”
“well I made some changes to the background if that is ok”
Uploaded a screenshot: “how does that look”
Uploaded a screenshot: “ok I did your exact color paletee and added the logo and such , now whaat”
“ok help me bild these : The bar chart in the middle. * The small table below it. * The note, then the footer band.”
“are we supposed to build the data vis in tableau or adobe”
“ok describe in words the bar chart , i’m gonna put it in adobe ai and it’ll gneerate the image :” (followed by the pasted chart and table instructions)
“or can you just create the image please”
Uploaded a screenshot: “ok how does that look”
Uploaded a screenshot: “ok I think I fixed it now what”
“please build this for me :” (followed by the pasted table and note instructions)
“Build this for me :” (the same instructions again)
“tell me how to do step by step :” (followed by the pasted GitHub steps 3 to 5)
“put the findinngs in this format please :” (followed by the pasted README example)
“fill this in for me : I removed [one specific thing from your draft], which [what removing it bought you].”
“what are all the things I typed in today”
