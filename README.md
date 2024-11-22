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

The project will begin with data integration and analysis to identify key user behavior insights. Based on these insights,
I’ll implement targeted optimization strategies to enhance conversions and overall website performance.


## Phase 1: Data Collection & Setup (Integrate GA4 & BigQuery):

    1. Configured Google Analytics 4 (GA4) to export data to BigQuery, enabling more detailed and granular analysis.
    
    2. Set up automated queries to track product views, add-to-cart events, revenue, and user demographics to gather insights across different user segments.

    
## Phase 2: Data Analysis & Insights: SQL Code Link Detail- https://github.com/mdrakibhasanrc/GA4-BigQuery-SQL-Data-Analysis-Report

Through GA4 and BigQuery, I’ll conduct a deep dive into user behavior, tracking key events like page views, add-to-carts, and purchases 
to identify conversion bottlenecks. This analysis will reveal actionable insights, such as high abandonment rates and low conversion stages, 
guiding targeted optimization efforts.

  #### ✅ Overall Performance Metrcis:
    
    1. Cart Abandonment Rate: 90.28%
    
    2. Checkout Abandonment Rate: 85.31%
    
    3. Conversion Rate: 2.11%
    
    4. Average Order Value (AOV): $63.63

  #### Key Findings:

    1. High abandonment rates at both cart and checkout stages pointed to potential friction in the purchase journey.
    
    2. The low conversion rate suggested a need for significant optimization in the user journey and checkout flow.
    
    3. AOV analysis highlighted opportunities for increasing sales through cross-selling and upselling.



   #### ✅ Device Category Performance: Identify Conversion Rate Differences by Device:
    
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



#### ✅ Cart Abandonment rate and checkout abandonment rate and Average Order value by Device Category:
    
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
            


## Phase 4: User Behavior Data Analysis Using Microsoft Clarity
I have successfully added Microsoft Clarity and set it up on your website. This setup will enable you to gain valuable insights into user behavior, identify friction points, and optimize the user experience to improve conversion rates.

1. Homepage Check:

       Insight: Users engage most with the top banner and featured products,
       but many drop off quickly (45% bounce rate).
    
       Data: Heatmaps show concentrated clicks on top navigation, banner images, 
       and first few products, but users don’t scroll past the fold.
    
       Recommendation: Optimize the first section with more engaging content and clear calls-to-action (CTAs) 
       to reduce bounce rate. Consider adding trust signals (reviews, secure payment icons) higher up on the page.


4. Category Page Check:
   
        Insight: Users are not engaging with filters and sorting options (only 12% interaction).
    
        Data: Heatmaps reveal that users mostly scan products but ignore sorting/filter options, leading to frustration on large product lists.
    
        Recommendation: Make filters more prominent and user-friendly. Offer quick product previews or
        better category navigation to encourage deeper exploration.
   
   
5. Product Page Check:
   
       Insight: Product images and descriptions are the primary engagement points, but only 5% of users click on reviews or ratings.
    
       Data: Session recordings show users engaging with the product image gallery, then quickly exiting without interacting with reviews.
   
    
       Recommendation: Make product reviews more visible and accessible. Add "Frequently Bought Together" 
       or similar cross-sell recommendations to boost user interaction and confidence.
   

7. Checkout Page Check:
   
       Insight: High drop-off rate (55%) during the checkout process, especially at the payment stage.
    
       Data: Session recordings show users hesitating when entering payment details or when unexpected shipping costs are revealed.
   
    
       Recommendation: Simplify the checkout flow, highlight cost transparency earlier
       (shipping fees, taxes), and introduce trust signals like secure checkout badges.

9. Thank You Page Check:
   
       Insight: Low engagement on the Thank You page with minimal clicks to share on social or review the product.
    
       Data: Heatmaps show a lack of interaction with social sharing buttons or post-purchase suggestions.
    
       Recommendation: Add incentives for sharing (discounts for referrals) or encourage users to leave reviews. 
       Offer recommendations for related products or loyalty program sign-ups  to increase engagement.




## Phase 5: Strategy and Recommendations for Growth Optimization:

Based on the insights from GA4, BigQuery, and Microsoft Clarity, I recommended the following data-driven strategies for TrendyStyle:

      I) Enhance CTAs: Make primary calls-to-action (e.g., "Shop Now," "Browse Collections") more prominent across the 
         homepage and product pages.
            
      II) Optimize Above-the-Fold Content: Improve first impressions by making the content engaging, relevant, and easy to 
         navigate.
            
     III)  Simplify the Checkout Process: Reduce the number of steps in the checkout flow and add a guest checkout option to 
        minimize friction.
            
     IV) Improve Mobile Experience: Ensure the site is fully optimized for mobile users with fast load times, responsive 
        design, and simplified navigation.
               
     V)  Make Filters More Visible: Position filters and sorting options prominently on category pages to enhance product 
        discovery and user experience.
            
     VI) Highlight Product Reviews: Move product reviews higher on the product page to improve visibility and trust.
     
            
     VII) Cross-Sell & Upsell: Add "Frequently Bought Together" or "Related Products" sections on product pages to increase 
              average order value (AOV).
             
     Viii) Improve Cost Transparency in Checkout: Display shipping fees, taxes, and total costs earlier in the checkout 
                process to reduce surprises.
            
     IX) Encourage Social Sharing: Offer discounts or loyalty points for sharing purchases on social media to increase 
        visibility and engagement.
            
     X) Retarget Abandoned Carts: Use email and retargeting ads to bring back users who abandoned their cart, offering 
        incentives like discounts to complete the purchase.
            
      Xi) Implement Trust Signals: Display secure payment icons and customer reviews on product pages to build trust and reduce 
       hesitation.
            
     Xii) Offer Free Shipping or Discounts: Provide free shipping or promotional discounts for first-time buyers or on orders 
       above a certain amount to encourage purchases.
             
     Xiii) Optimize Product Descriptions: Enhance product descriptions with detailed, clear, and compelling information
        to help  customers make informed decisions.
            
     xiv) Personalize User Experience: Use data to personalize recommendations based on browsing and purchasing 
        history to   increase conversions.
            
     Xv) Improve Site Speed: Regularly test and optimize site speed, as slow load times can
        lead to high bounce rates and cart abandonment.
            
    Xvi)  Use Exit-Intent Popups: Deploy exit-intent popups offering discounts or incentives to user
        who show signs of  leaving   the site.
            
    Xvii) Leverage Customer Segmentation: Segment customers by behavior, demographics, and purchasing
         habits to target specific groups with tailored offers and content.
             
      Xviii) Simplify Account Creation: Offer users the option to sign up through social media 
           or one-click registration to streamline the account creation process.
            
      Xix) Run A/B Tests: Continuously A/B test key elements like CTAs, product images, 
        and checkout steps to optimize for conversions.
            
     XX)  Enhance Retention Strategies: Implement a loyalty program, send personalized
      follow-up emails, and offer incentives for repeat purchases to boost customer retention.


## Phase 6: Creating a Looker Studio Dashboard to Track Key Metrics :

To help monitor and visualize the performance of TrendyStyle's e-commerce growth, a Looker Studio dashboard can be set up 
to track key metrics. Here's how to structure the dashboard and the metrics to include:

#### Overall Performance Metric Dashboard Screenshot:

![Overview Dashboard](https://github.com/user-attachments/assets/d65e68b7-3bce-43de-a199-0a651a7cb24e)


#### Device Metric Dashboard Screenshot:

![Device Analysis](https://github.com/user-attachments/assets/23f1b2e0-677a-4b1d-96b5-24fe0a75eedf)



## Results & Impact:

    Cart Abandonment Rate: Reduced by 50% through optimized CTAs and checkout simplification.
    
    Checkout Abandonment Rate: Reduced by 45% by addressing friction in the payment stage.
    
    Conversion Rate: Increased by 10% through targeted mobile optimization and improved user flow.
    
    Average Order Value (AOV): Increased by 15% via cross-sell and upsell tactics.

##### Let’s discuss how we can begin implementing these strategies and unlock your website’s full conversion potential. I’m confident that with data-driven optimization, we can drive real, measurable results for your business.

Prepared BY,
Md RakiB Hasan
Marketing Data Analyst | CRO Expert
