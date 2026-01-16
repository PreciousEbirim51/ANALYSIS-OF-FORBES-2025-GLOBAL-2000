<img width="1100" height="1262" alt="image" src="https://github.com/user-attachments/assets/77f99a81-f0c3-4f6a-a3ca-356294f0907e" />


<img width="1883" height="2160" alt="image" src="https://github.com/user-attachments/assets/d1376d33-96d4-473e-8012-bce1a2448a8d" />



INTRODUCTION

The Forbes Global 2000 ranking provides a comprehensive view of the world’s largest publicly listed companies, evaluated across key financial dimensions including revenue, profits, assets, and market value. As global markets continue to evolve amid technological advancement, geopolitical uncertainty, and shifting investor expectations, understanding the underlying drivers of corporate performance has become increasingly important for investors, policymakers, and business leaders.

This technical report presents a data-driven analysis of the Forbes Global 2000 (2025) dataset with the objective of assessing corporate performance, efficiency, valuation, and geographic and industry-level trends. Using structured financial metrics and ratio-based indicators, the analysis moves beyond absolute size to examine how effectively companies and industries convert revenue into profit, utilize assets, and generate market value.

Interactive dashboards developed in Microsoft Power BI were employed to explore patterns across multiple dimensions, including company-level performance, industry profitability, valuation efficiency, asset utilization, and country-level dominance. Key analytical techniques include comparative ranking, ratio analysis (profit margin, asset turnover, and market value–to–revenue ratios), and scatter plot visualizations to identify outliers, efficiency leaders, and structural differences across business models.

The findings highlight a clear divergence between scale and efficiency. While asset-heavy industries such as banking dominate in terms of total assets and revenue, technology-driven sectors demonstrate superior profitability and market valuation efficiency. Additionally, the analysis reveals significant geographic concentration of corporate value, particularly within the United States, underscoring the role of innovation, capital market depth, and investor confidence in value creation.

Overall, this report aims to provide actionable insights into global corporate performance by illustrating how financial structure, industry characteristics, and geographic context influence value creation. The results serve as a strategic reference for investment decision-making, corporate strategy formulation, and policy development in an increasingly competitive global economy.

The dataset used for this analysis was scrapped from the website: https://www.forbes.com/lists/global2000/.


DATA SOURCING AND PROCESSING

The dataset used for this analysis was scraped from: https://www.forbes.com/lists/global2000/ using Pandas and BeautifulSoup and the number columns was further cleaned before saving as a CSV file.

<img width="1100" height="578" alt="image" src="https://github.com/user-attachments/assets/43505fea-5c52-4fa2-90db-7481af6c5c4f" />


EXPLORATORY DATA ANALYSIS

The exploratory data analysis was performed on the cleaned dataset to uncover trends and insights using python methodologies.



<img width="1032" height="502" alt="image" src="https://github.com/user-attachments/assets/91ee499d-a4b4-47eb-bc5e-725f169c8062" />


This is the top ten companies by profits showing the ten most profit generating companies out of the 2000 companies listed by forbes


<img width="983" height="510" alt="image" src="https://github.com/user-attachments/assets/43a47f2f-a793-460e-8375-00464d9bbc85" />


This is the top ten companies by Assets showing the ten companies with most assets under management out of the 2000 companies listed by Forbes.


<img width="990" height="492" alt="image" src="https://github.com/user-attachments/assets/83d1339c-0c24-42ab-b6d3-9c4b6eb26a90" />


This is the top ten companies by revenue showing the ten most Revenue generating companies out of the 2000 companies listed by Forbes.


<img width="978" height="492" alt="image" src="https://github.com/user-attachments/assets/3446b8b9-8c5d-4634-811f-640025eccf5d" />


This is the top ten companies by market value showing the ten companies with highest valuation in the capital markets out of the 2000 companies listed by Forbes.


<img width="802" height="660" alt="image" src="https://github.com/user-attachments/assets/14ebd8a5-41b8-4a30-8e98-5f7ff1842445" />


The figure above shows how the industries performed in profit making with banking industry leading.


<img width="775" height="665" alt="image" src="https://github.com/user-attachments/assets/49f01a2b-0461-49ce-8153-ab9d027323e7" />


The figure above shows how the industries performed in revenue generation with banking industry leading and closely followed by the oil & gas industry.


<img width="877" height="668" alt="image" src="https://github.com/user-attachments/assets/2bae0b97-27b1-40b3-9da3-5a9d10bffb46" />


The figure above shows the asset base of the industries on the list with banking industry leading.


<img width="903" height="673" alt="image" src="https://github.com/user-attachments/assets/8d06531c-a76c-4ded-8817-5fc1ca70c801" />


The figure shows the total market value of the different industries on the list with IT Software and Services having the highest valuation in the capital markets.


<img width="853" height="717" alt="image" src="https://github.com/user-attachments/assets/8179790c-23a0-4608-9c1f-2e1a1329d73b" />


The figure above shows the Top ten countries/Headquarters by Revenue with the United States Being The Leading Country.


<img width="935" height="532" alt="image" src="https://github.com/user-attachments/assets/2e764135-1aa1-45c7-9324-a3639a91701f" />


The figure above shows the Top ten countries/Headquarters by Profits with the United States Being The Leading Country.


<img width="893" height="527" alt="image" src="https://github.com/user-attachments/assets/c303af46-4611-4c39-aad2-faf4bbf57d1c" />


The figure above shows the Top ten countries/Headquarters by Assets with the United States Being The Leading Country.


<img width="807" height="502" alt="image" src="https://github.com/user-attachments/assets/93b48773-5be9-4dc5-ae5b-109b27a3cb29" />


The figure above shows the Top ten countries/Headquarters by Market Value with the United States Being The Leading Country.


<img width="718" height="267" alt="image" src="https://github.com/user-attachments/assets/8303d6c2-f747-4a80-928f-a23745f25cb7" />


This Computes the Pearson correlation coefficient, Measuring linear relationship between pairs of variables.

1.0 — Perfect positive correlation

0.0 — No linear relationship

–1.0 — Perfect negative correlation

PRE ANALYSIS

A pre-analysis phase was conducted to establish an analytical framework before the creation of the dashboard. This pre-analysis phase involves:

Project Split: The dataset was split into two variables which are independent and dependent variables and this helps in understanding the relationship between the data points and can provide hint on the type of insights that can be gotten from the dataset.

Potential Analysis/Questions: In this step, the questions that can be answered with the dataset were identified and it will serve as a bearing during the analysis.

Potential Insights: I was able to uncover some insights during this step just by observing the data split and it aided in my analysis by narrowing my focus on the important insights that can be gotten from the data set.

Storytelling: After the earlier steps described above, it became easier to tell a story from the dataset by relating the datapoints with each other.

TOOLS AND TECHNOLOGIES

Microsoft Power BI was the primary visualization tool used for this project, the Power BI features used include;

DAX Functions

Interactive Visualizations

Power Query

Calculated Measures

OBSERVATIONS

1. High-Level Financial Snapshot (KPI Cards)

Global Totals:

Total Revenue: $52.88T

Total Profits: $4.87T

Total Market Value: $91.28T

Total Assets: $242.17T

Key Insight

The asset base is extremely large relative to revenue, showing how capital-intensive global corporations are.

Profit represents ~9.2% of total revenue, indicating moderate overall margins at a global level.

Market value is 1.7× total revenue, reflecting strong investor expectations, especially in tech-heavy firms.

2. Top 10 Companies by Market Value

Leaders:

Apple (~$3.14T)

Microsoft (~$2.91T)

NVIDIA (~$2.71T)

Amazon

Alphabet

Insights

Technology companies dominate valuation, not necessarily revenue or assets.

NVIDIA’s high rank confirms growth and AI-driven expectations, despite lower revenue than Amazon or Walmart.

Traditional asset-heavy firms appear lower, showing valuation favors scalability and innovation over size.

3. Revenue vs Profits (Scatter Plot)

How to Read It

X-axis: Revenue

Y-axis: Profits

Bubble size: Market Value

Key Patterns

🔹 High Revenue, High Profit (Top-Right)

Saudi Aramco

Apple

Alphabet

Berkshire Hathaway

➡ These are elite performers combining scale and profitability.

🔹 High Revenue, Lower Profit (Right-Lower)

Walmart

Amazon

➡ Massive sales but thin margins, common in retail and logistics-heavy businesses.

🔹 Lower Revenue, High Profit (Upper-Left)

NVIDIA

Meta Platforms

Microsoft

➡ Highly efficient, high-margin firms, mostly tech-driven.

🔹 Industry Clustering

Banks cluster mid-range (steady revenue, moderate profit).

Energy companies show strong profitability relative to revenue.

Tech firms are more dispersed but trend upward in profits.

4. Top 10 Companies by Revenue

Leaders:

Walmart ($681B)

Amazon ($638B)

Saudi Aramco

UnitedHealth Group

Apple

Insights

Revenue leadership does not guarantee profitability or valuation leadership.

Retail and healthcare dominate revenue due to volume-driven business models.

Apple appears across revenue, profit, and market value, signaling balanced strength.

5. Top 10 Companies by Assets

Leaders:

ICBC ($6.69T)

Agricultural Bank of China

China Construction Bank

Bank of China

JPMorgan Chase

Insights

Banks dominate asset rankings, reflecting balance-sheet-heavy models.

Asset size does not directly translate to market value or profits.

Financial institutions rely on scale and leverage, not margins.

6. Top 10 Companies by Profits

Leaders:

Alphabet ($111B)

Saudi Aramco ($105B)

Apple ($96B)

Microsoft ($93B)

Berkshire Hathaway

Insights

Profit leadership is shared between tech and energy.

Alphabet’s top position highlights advertising and digital platform scalability.

Banks are notably absent, reflecting lower margins despite large assets.

7. Cross-Visual Business Conclusions

Size ≠ Profitability

Walmart and Amazon dominate revenue but lag in profit margin.

NVIDIA and Meta generate outsized profits relative to revenue.

Market Value Rewards Growth, Not Assets

Tech firms lead valuation despite smaller asset bases.

Banks dominate assets but lag valuation rankings.

Industry Dynamics

Tech: High margin, high valuation

Energy: High profitability, cyclical

Banking: Asset-heavy, stable, lower margins

Retail: Revenue-heavy, margin-light

8. Top Industries by Market Value

Market Value Leaders

IT Software & Services

Banking

Semiconductors

Technology Hardware & Equipment

Oil & Gas Operations

Insights

Technology-driven industries dominate valuation, despite not leading in assets.

Banking ranks high due to scale, not profitability.

Semiconductors’ strong valuation reflects AI, cloud, and digital infrastructure demand.

Drugs & Biotechnology maintain solid valuation due to innovation and pricing power.

9. Revenue vs Profits (Industry Scatter Plot)

Chart Interpretation

X-Axis: Revenue

Y-Axis: Profits

Bubble Size: Market Value

Industry Performance Patterns

🔹 High Revenue, High Profit

Banking

Oil & Gas Operations

➡ Strong scale combined with consistent profitability.

🔹 Moderate Revenue, High Profit

IT Software & Services

Insurance

➡ High operational efficiency and strong margins.

🔹 High Revenue, Low Profit

Retailing

Consumer Durables

➡ Volume-driven industries with thin margins.

🔹 Lower Revenue, Lower Profit

Food, Drink & Tobacco

Semiconductors (relative to valuation)

➡ Profitability driven more by innovation cycles than scale.

Key Insight

Profitability does not increase linearly with revenue. Industries with digital or financial leverage convert revenue into profit far more efficiently.

10. Top Industries by Revenue

Leaders

Banking — $6.4T

Oil & Gas Operations — $5.2T

Insurance — $4.3T

Consumer Durables

Retailing

Insights

Financial and energy sectors dominate revenue due to transaction volume and pricing scale.

Retailing’s high revenue contrasts sharply with low profit contribution.

Construction and transportation contribute materially but remain margin-constrained.

11. Top Industries by Assets

Leaders

Banking — $123.1T

Insurance — $25.2T

Diversified Financials — $18.7T

Insights

Financial institutions hold over half of global corporate assets.

Asset size does not correlate with market value or profit leadership.

Capital-intensive industries depend on balance-sheet strength rather than margins.

12. Top Industries by Profits

Profit Leaders

Banking — $1.04T

IT Software & Services — $444B

Oil & Gas Operations — $396B

Insurance — $382B

Insights

Banking leads profits due to scale, not efficiency.

IT Software & Services generates exceptional profits with minimal assets.

Energy profits remain strong but cyclical and price-sensitive.

13. Cross-Industry Comparative Insights

Assets vs Value Disconnect

Banking controls the most assets but does not lead market valuation.

Tech industries achieve high valuation with low asset intensity.

Efficiency Leaders

IT Software & Services

Insurance

➡ Best revenue-to-profit conversion.

Volume vs Margin Trade-Off

Retailing and Consumer Durables prioritize scale over profitability.

Technology and finance prioritize margin and capital efficiency.

14. Market Value to Revenue Ratio (Valuation Efficiency)

Top Ten Companies by Market Value to Revenue Ratio

Leaders include:

MicroStrategy (≈212×)

DC Industrial (≈170×)

Cambricon Technology

Power Assets Holdings

Palantir Technologies

Interpretation

These companies are priced far above their current revenue, indicating:

Strong growth expectations

Strategic assets (e.g., data, IP, crypto exposure)

Market speculation or future optionality

High ratios = growth narratives dominate current earnings

Bottom Ten Companies by Market Value to Revenue Ratio

Includes:

Traditional banks

Automotive and industrial firms

Asset-heavy, low-growth companies

Interpretation

These firms generate large revenues but receive low market valuation Often viewed as:

Mature

Capital-intensive

Lower growth potential

Low ratios = value stocks or structurally constrained businesses

15. Assets Turnover Ratio (Operational Efficiency)

Top Ten Companies by Assets Turnover Ratio

Leaders include:

Rajesh Exports (≈12×)

China Aviation Oil (≈8×)

World Fuel Services

McKesson

Cardinal Health

Interpretation

These companies generate very high revenue per dollar of assets

Common traits:

Trading

Distribution

Commodity-based businesses

Lean balance sheets

High asset turnover = operational excellence, not necessarily high margins

Bottom Ten Companies by Assets Turnover Ratio

Includes:

Banks

Stock exchanges

Financial holding companies

Automotive manufacturers

Interpretation

Extremely low ratios (<0.01×) indicate:

Asset-heavy balance sheets

Regulated or capital-intensive operations

Revenue not the primary output of assets (e.g., financial assets)

Low asset turnover ≠ poor performance

It reflects business model structure

16. Cross-Visual Insights

Growth vs Efficiency Trade-Off

High Market Value / Revenue ≠ High Asset Turnover

Growth companies are valued on future potential

High-turnover firms win on volume and speed

Banking Industry Pattern

Appears consistently in:

Bottom asset turnover

Lower valuation ratios

Yet dominates:

Assets

Absolute profits

➡ Banking is scale-driven, not efficiency-driven

Risk Signals

Very high valuation ratios can signal:

Overvaluation

Speculative pricing

Extremely low turnover can indicate:

Capital inefficiency

Regulatory drag

17. Top 10 Companies by Profit Margin %

Observations

EXOR leads with a ~15.3% margin, far ahead of peers

Power Assets Holdings and Bajaj Holdings & Investments follow

Most top-margin firms are:

Holding companies

Investment-focused entities

Capital allocators rather than operational firms

Key Insight

High profit margins are often achieved by financial or holding structures, not necessarily by high sales volume.

These companies benefit from:

Dividend income

Asset revaluation

Lower operating costs

18. Bottom 10 Companies by Profit Margin %

Observations

Several firms show negative margins, indicating losses

MicroStrategy is a notable outlier with ~ -2.53 margin

Other loss-makers include:

Technology growth companies

Capital-intensive or restructuring firms

Key Insight

Negative margins often reflect investment phases, heavy R&D, or volatile income models, not permanent weakness.

This is common in:

High-growth tech

Crypto- or IP-heavy firms

Early-stage or turnaround companies

19. Top 10 Industries by Profit Margin %

Industry Leaders

Semiconductors

IT Software & Services

Construction & Chemicals

Banking

Banking & Financial Services

Interpretation

Technology industries dominate margin efficiency

Semiconductors benefit from:

High demand (AI, chips)

Limited supply

Strong pricing power

Banking margins remain solid due to scale and interest spreads

20. Bottom 10 Industries by Profit Margin %

Low-Margin Industries

Telecommunications

Food Markets

Trading Companies

Automotive

Retailing

Interpretation

These industries are volume-driven with intense competition and high operating costs.

Common characteristics:

Heavy infrastructure

Price competition

Regulatory pressure

21. Cross-Visual Insights

Margin ≠ Market Value

Some of the highest-margin companies are not the most valuable

Market value reflects growth expectations, not just profitability

Structural Industry Differences

Tech & Semiconductors: High margin, scalable

Banking: Moderate-to-high margin, asset-heavy

Retail & Telecom: Low margin, high volume

Risk & Sustainability

Extremely high margins may be:

Non-recurring

Driven by financial income

Persistently low margins indicate:

Price wars

Structural inefficiency

22. Top Countries by Market Value

Market Value Leaders

United States — $50.2T

China — $7.1T

Japan — $4.1T

United Kingdom

France

Key Insights

The United States alone controls more than half of total global market value.

Market value dominance reflects:

Deep capital markets

Strong technology sector

Investor confidence

China and Japan follow but at a significant distance, showing valuation concentration in the U.S.

23. Revenue vs Profits by Country (Scatter Plot)

Chart Setup

X-Axis: Revenue

Y-Axis: Profits

Bubble Size: Market Value

Interpretation

United States

Clear outlier in both revenue and profits

Large bubble size shows massive market valuation

Indicates strong scale + efficiency + investor confidence

China

High revenue with lower profit conversion than the U.S.

Suggests:

Margin pressure

State-influenced business models

Capital-intensive sectors

Japan & United Kingdom

Moderate revenue and profits

Mature economies with stable but slower growth

France & India

Smaller scale but improving profit contribution

India shows emerging-market growth potential

24. Top Countries by Revenue

Leaders

United States — $19.5T

China — $7.8T

Japan — $4.2T

Insights

Revenue leadership aligns with:

Economic size

Corporate scale

European countries generate respectable revenue but trail Asia and the U.S.

25. Top Countries by Assets

Leaders

United States — $61.1T

China — $57.4T

Japan — $20.1T

Insights

China’s asset base is nearly equal to the U.S.

However, China’s lower market value implies lower asset valuation efficiency

Asset-heavy economies rely on banking and industrial sectors

26. Top Countries by Profits

Leaders

United States — $2.02T

China — $655B

Japan — $297B

Insights

The U.S. converts revenue into profits far more efficiently

China’s profits lag despite large assets and revenue

Saudi Arabia’s presence reflects energy sector profitability

27. Cross-Country Comparative Insights

Valuation Efficiency

U.S. companies generate the highest market value per dollar of assets

China shows scale without equivalent valuation

Economic Structure Matters

Tech-driven economies → higher margins & valuation

Manufacturing & finance-heavy economies → lower margins

Global Concentration Risk

Corporate value is highly concentrated in a few countries

Shocks in the U.S. market would have global impact

RECOMMENDATIONS

1. Recommendations for Investors

Balance Growth and Value

Combine high-valuation growth stocks (IT Software, Semiconductors) with low-valuation, cash-generating sectors (Banking, Energy).

Avoid overexposure to companies with extreme Market Value–to–Revenue ratios, as these signal valuation risk.

Focus on Profit Efficiency, Not Just Size

Prioritize companies and industries with consistently high profit margins (Semiconductors, IT Software & Services).

Be cautious of high-revenue, low-margin industries (Retailing, Telecommunications).

Geographic Diversification

Reduce concentration risk by diversifying beyond the United States, which dominates global market value.

Selectively invest in China, India, and Saudi Arabia, focusing on profitable sectors (energy, technology, finance).

2. Recommendations for Corporate Executives

Improve Asset Utilization

Asset-heavy firms (especially banks and industrials) should:

Streamline balance sheets

Improve digital efficiency

Reallocate underperforming assets

Track Asset Turnover Ratio as a core KPI.

Shift Toward Margin Expansion

Companies in low-margin industries should:

Invest in automation and technology

Move up the value chain (premium products, services)

Reduce dependency on volume-driven strategies

Strengthen Value Narrative

Firms with strong profits but low market valuation should:

Improve investor communication

Highlight growth drivers, innovation, and ESG initiatives

Align capital allocation with shareholder value (dividends, buybacks)

3. Recommendations for Policymakers & Regulators

Support Innovation-Led Industries

Encourage growth in technology, semiconductors, and biotech through:

R&D incentives

Infrastructure investment

Talent development programs

Strengthen Financial Market Depth

Countries lagging in market value should:

Improve capital market transparency

Reduce regulatory friction

Encourage public listings and foreign investment

4. Recommendations for Risk Managers

Monitor Valuation Extremes

Closely track companies with:

Very high Market Value / Revenue ratios

Persistently negative profit margins

These firms are highly sensitive to market sentiment changes.

Stress-Test Asset-Heavy Sectors

Banks and insurers should undergo:

Interest rate sensitivity tests

Liquidity and capital adequacy stress tests

Large asset bases amplify systemic risk.

5. Recommendations for Analysts & Decision Makers

Use Ratio-Based Evaluation

Supplement absolute metrics (Revenue, Assets) with:

Profit Margin

Asset Turnover

Market Value to Revenue

This prevents misleading conclusions based on size alone.

Segment Analysis by Business Model

Compare companies within similar industry structures

Avoid cross-industry comparisons without adjusting for capital intensity.

CONCLUSION

This analysis of the Forbes Global 2000 (2025) provides a comprehensive evaluation of global corporate performance by integrating size-based metrics with efficiency and valuation indicators. By examining revenue, profits, assets, market value, and derived financial ratios, the study moves beyond traditional rankings to uncover the structural drivers of value creation across companies, industries, and countries.
