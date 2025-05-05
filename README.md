### ➡️ Conversion Funnel Analysis for D2C E-Commerce Brand

#### ⚡ Summary
This repository documents my end-to-end analysis of the customer conversion funnel for a direct-to-consumer (D2C) e-commerce brand operating on the Shopify platform. The analysis identifies critical drop-off points in the customer journey, quantifies conversion rates between stages, and provides data-driven recommendations that led to a 27% increase in overall conversion rate. 

**In plain language: Where are customers falling off before they buy, why is it happening, and what can we do to fix it?** This project walks through the full process, from data extraction and cleaning to funnel visualization and actionable insights that directly improved sales performance.

<sub>**Note:** Proprietary and sensitive business data has been transformed to maintain confidentiality while preserving analytical integrity and insights. All metrics and patterns accurately reflect the original analysis.</sub>

#### ⚡ Business Context
The D2C retail brand faced several conversion challenges:

- High traffic but below industry standard add-to-cart rates (2.8% vs industry 4.2%)
- 72% cart abandonment rate across desktop and mobile
- Inconsistent performance across product categories
- Purchase hesitation at specific price thresholds
- Disparate conversion rates between marketing channels

#### ⚡ Analysis Methodology

My approach included:

1. **Data Integration & Preparation**
   - Connected Shopify store data with Google Analytics 4 events
   - Created unified customer journey dataset
   - Developed segmentation framework by product category and customer behavior

2. **Funnel Stage Definition & Analysis**
   - Mapped complete customer journey from landing to purchase
   - Calculated conversion rates between each stage
   - Identified critical drop-off points with statistical significance

3. **Segmentation Analysis**
   - Analyzed performance by device, product category, and acquisition channel
   - Identified high-value segment behavior patterns
   - Quantified price sensitivity thresholds

4. **Optimization Testing**
   - Executed A/B testing for checkout flow improvements
   - Analyzed user session recordings at key drop-off points
   - Measured impact of shipping threshold modifications

#### ⚡ Key Findings

- **Critical Drop-off Points:**
  - 68% of visitors exit without viewing a product
  - 76% of product viewers don't add items to cart
  - 63% abandonment during shipping information entry

- **Product Performance:**
  - Premium products (>$120) have 2.3x higher AOV but 0.7x conversion rate
  - Accessory conversions 3.2x higher than overall site average
  - Bundle offers increase AOV by 42% when shown on product pages

- **Price Sensitivity:**
  - Conversion declines 38% at $75+ price point without shipping incentive
  - Free shipping threshold at $75 improves conversion by 25% for orders $85-120
  - Limited edition products show 50% less price sensitivity

- **Channel Effectiveness:**
  - Instagram traffic shows 2.1x higher engagement but 0.8x lower conversion
  - Email campaigns deliver 3.4x ROAS compared to paid social
  - Organic search traffic has highest completion rate once in cart

#### ⚡ Business Impact

Implementing the recommendations from this analysis resulted in:

- 27% increase in overall conversion rate
- 42% reduction in checkout abandonment
- 31% increase in average order value
- 18% improvement in return customer purchase rate

#### ⚡ Technical Skills Used

- **Data Integration:** Shopify API, Google Analytics 4, SQL
- **Python Analysis:** Pandas, NumPy, SciPy, Matplotlib, Seaborn
- **Statistical Methods:** A/B test analysis, significance testing, cohort analysis
- **Visualization:** Interactive dashboards, funnel visualizations, heatmaps

#### ⚡ Repository Structure

- `/notebooks`: Analysis workflow from data processing to visualization
- `/data`: Representative sample data structure with transformed values
- `/visualizations`: Key charts and dashboards from the analysis
- `/recommendations`: Detailed improvement strategies with expected impact
