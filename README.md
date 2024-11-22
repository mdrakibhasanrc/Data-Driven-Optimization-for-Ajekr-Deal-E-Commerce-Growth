## Data-Driven Optimization for Ajker Deal E-Commerce Growth

## Project Overview:

### Company: Ajker Deal
### Industry: E-commerce (Fashion & Apparel)

## Project Focus:

The goal of this project was to enhance Ajker Deal website conversion rate by analyzing customer behavior, identifying drop-off points, 
and implementing data-driven solutions to improve the user experience and boost sales.

## Tools & Technologies Used:

    1. Google Analytics 4 (GA4): For tracking user behavior, events, and conversions across the website and app.
    
    2. BigQuery: For advanced data analysis and querying large datasets from GA4.
    
    3. Looker Studio: For creating visual reports and real-time dashboards to track KPIs.
    
    4. Microsoft Clarity: For heatmaps and session recordings to understand user behavior and friction points.

    5. Python: 


## Project Phases & Approach:

### Phase 1: Data Collection & Setup (Integrate GA4 & BigQuery):

    1. Configured Google Analytics 4 (GA4) to export data to BigQuery, enabling more detailed and granular analysis.
    
    2. Set up automated queries to track product views, add-to-cart events, revenue, and user demographics to gather insights across different user segments.

    
### Phase 2: Data Analysis & Insights:

  #### Overall Performance Metrcis:
    
    1. Cart Abandonment Rate: 90.28%
    
    2. Checkout Abandonment Rate: 85.31%
    
    3. Conversion Rate: 2.11%
    
    4. Average Order Value (AOV): $63.63

  #### Key Findings:

    1. High abandonment rates at both cart and checkout stages pointed to potential friction in the purchase journey.
    
    2. The low conversion rate suggested a need for significant optimization in the user journey and checkout flow.
    
    3. AOV analysis highlighted opportunities for increasing sales through cross-selling and upselling.



   ####  Device Category Performance: Identify Conversion Rate Differences by Device:
    
            Mobile:
             
            Conversion Rate: 1.7%
            
            Revenue: $146,768
            
            Total Purchases: 9,200 items
            
            Desktop:
            
            Conversion Rate: 1.6%
            
            Revenue: $208,815
            
            Total Purchases: 13,182 items
            
            Tablet:
            
            Conversion Rate: 0.5%

            Revenue: $6,582
            
            Total Purchases: 111 items

  #### Key Findings:

    1.Mobile Users: Higher conversion rate (1.7%), but lower revenue ($146,768) and fewer purchases (9,200 items) 
    compared to desktop. Opportunity to increase average order value (AOV) on mobile.

    2. Desktop Users: Higher revenue ($208,815) and total purchases (13,182 items), with a slightly lower conversion rate (1.6%). 
    Desktop drives larger purchases, suggesting potential for further conversion optimization.

    3. Tablet Users: Significantly lower conversion rate (0.5%) and revenue ($6,582), with only 111 purchases. 
     Clear need for optimization to boost engagement and sales.



#### Cart Abandonment rate and checkout abandonment rate and Average Order value by Device Category:
    
            Mobile:

            Cart Abandonment Rate: 89.6%
            
            Checkout Abandonment Rate: 85.6%
            
            Average Order Value (AOV): $79.29
            
            Total Purchases: 2,355
            
            Desktop:
            
            Cart Abandonment Rate: 90.52%
            
            Checkout Abandonment Rate: 85.52%
            
            Average Order Value (AOV): $82.18
            
            Total Purchases: 3,226
            
            Tablet:
            
            Cart Abandonment Rate: 91.2%
            
            Checkout Abandonment Rate: 85.92%
            
            Average Order Value (AOV): $67.86
            
            Total Purchases: 111

 #### Key Findings:

            Mobile vs. Desktop:
            
            Both devices have similar abandonment rates, but desktop users convert better, with more total purchases (3,226 vs. 2,355).
            
            Desktop users also have a higher AOV ($82.18 vs. $79.29).
            
            Mobile vs. Tablet:
            
            Mobile users have lower abandonment rates and significantly higher purchases (2,355 vs. 111).
            
            Tablet users have the highest abandonment rates and the lowest AOV ($67.86).
            
            Desktop vs. Tablet:
            
            Desktop users have much better conversion (3,226 vs. 111) and a higher AOV ($82.18 vs. $67.86), 
            with tablet users showing the highest abandonment rates across both cart and checkout stages.
            


### Phase 4: User Behavior Data Analysis Using Microsoft Clarity
I have successfully added Microsoft Clarity and set it up on your website. This setup will enable you to gain valuable insights into user behavior, identify friction points, and optimize the user experience to improve conversion rates.

1. Homepage Check:
       Insight: Users engage most with the top banner and featured products,
       but many drop off quickly (45% bounce rate).
    
       Data: Heatmaps show concentrated clicks on top navigation, banner images, 
       and first few products, but users don’t scroll past the fold.
    
       Recommendation: Optimize the first section with more engaging content and clear calls-to-action (CTAs) 
       to reduce bounce rate. Consider adding trust signals (reviews, secure payment icons) higher up on the page.


2. Category Page Check:
   
        Insight: Users are not engaging with filters and sorting options (only 12% interaction).
    
        Data: Heatmaps reveal that users mostly scan products but ignore sorting/filter options, leading to frustration on large product lists.
    
        Recommendation: Make filters more prominent and user-friendly. Offer quick product previews or
        better category navigation to encourage deeper exploration.
   
   
4. Product Page Check:
   
       Insight: Product images and descriptions are the primary engagement points, but only 5% of users click on reviews or ratings.
    
       Data: Session recordings show users engaging with the product image gallery, then quickly exiting without interacting with reviews.
    
      Recommendation: Make product reviews more visible and accessible. Add "Frequently Bought Together" 
      or similar cross-sell recommendations to boost user interaction and confidence.

5. Checkout Page Check:
   
      Insight: High drop-off rate (55%) during the checkout process, especially at the payment stage.
    
      Data: Session recordings show users hesitating when entering payment details or when unexpected shipping costs are revealed.
    
      Recommendation: Simplify the checkout flow, highlight cost transparency earlier
      (shipping fees, taxes), and introduce trust signals like secure checkout badges.

6. Thank You Page Check:
   
       Insight: Low engagement on the Thank You page with minimal clicks to share on social or review the product.
    
       Data: Heatmaps show a lack of interaction with social sharing buttons or post-purchase suggestions.
    
       Recommendation: Add incentives for sharing (discounts for referrals) or encourage users to leave reviews. 
       Offer recommendations for related products or loyalty program sign-ups  to increase engagement.
 


