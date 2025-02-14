# FINTECH ANALYSIS

## Table of Content
- [Project Overview](#Project-Overview)
- [Tools](#Tools)
- [Workflow](#Workflow)
- [Insights](#Insights)
- [Recommendations](#Recommendations)
- [Challenges](#Challenges)

## Project Overview
PedMonie, a fintech startup, is developing a new digital payment solution that consolidates mobile money, bank transfers, and card payments into a unified system. This research aims to analyze the competitive landscape, understand market needs, and provide insights to refine and differentiate the product.

## Tools
### Data Processing
- Excel

### Data Visualization & Interpretation
- Power BI

### Research
- CBN & NBS Reports: Official statistics on financial inclusion, income distribution, and digital finance adoption.
- Industry Research & FinTech Websites: Insights into services, pricing models, and consumer behavior from platforms like Flutterwave, Paystack, OPay, Kuda etc.

## Workflow
### Research & Data Collection
- Survey (20 People): Conducted a small survey to gather initial insights on:
 - Demographics (Age, Gender, Employment, Income Level).
 - Financial Literacy (Understanding of banking, investments, and budgeting).
 - Preferred FinTech Services (Mobile banking, digital payments, micro-loans).
 - Service Delivery Preferences (Self-service vs. agent banking).

- CBN & NBS Reports → Used official financial inclusion data to ensure realistic income levels, banking adoption rates, and digital transaction trends.

- Industry Research & FinTech Websites → Analyzed pricing structures, services, and customer trends from leading Nigerian FinTech firms

### Data Generation & Processing:
- Dataset Creation (200,000 Rows): Based on survey insights and official statistics, a synthetic dataset was generated using Python (NumPy, Pandas).

- Realistic Data Distributions: Ensured accuracy in:
 - Age Groups.
 - Income Levels & Employment (Aligned with Nigerian economic data).
 - Financial Literacy (Classified as Low, Medium and High).
 - Business Ownership Segments (Young Professionals, Urban Professionals, Small Business Owners, Rural Users).
 - Service Preferences (Mobile App, Web Platform, or Agent Banking)

### Data Analysis & Visualization
- Visualized trends and patterns using column charts, bar charts, pie chart etc.

## Insights
### 1. Companies and Their Products
- Digital payments and mobile banking are the most common fintech offerings.
- Blockchain-based companies (Binance, Luno, Roqqu, Flutterwave) are fewer in number.
- Micro-lending is a niche market with only a few players.

![1](https://github.com/user-attachments/assets/4b2d43da-a087-4837-96a7-c8c4a04d41e0)

### 2. Preferred Products by Users
- Digital Payments (85K users) and Mobile Banking (82K users) are the most preferred FinTech products.
- Micro-Lending (20K users) and Blockchain (13K users) have significantly fewer users, suggesting lower adoption.

![2](https://github.com/user-attachments/assets/d5bb1938-01d3-4085-b18b-bd675cadd2ea)

### 3. Product Familiarity by Users
- Digital payments are the most well-known, with 43K experts and 25K novice users.
- Mobile banking has the highest novice user base (49K), indicating high adoption among beginners.
- Blockchain has the lowest user familiarity (6K experts, 1K novices).

![3](https://github.com/user-attachments/assets/60397a20-05f3-49bc-807d-ea5abcb78d79)

### 4. Companies Ranked by Number of Users and Pricing Strategy
- OPay leads with 60K users.
- Moniepoint follows closely with 47K users.
- Kuda ranks third with 29K users.
- Flutterwave (18K) and Paystack (14K) hold mid-tier positions.
- FairMoney (9K) and PiggyVest (5K) are notable among value-based pricing fintechs.
- Smaller players like Roqqu and Luno have the lowest user base at 2K each.
- Competitive Pricing dominates, driving the largest user adoption.
- 
![4](https://github.com/user-attachments/assets/ad629129-0f21-41d7-a20d-5193bdb306e5)

### 5. Distribution of Pricing Strategies
- The majority (90.45%) of FinTech companies use Competitive Pricing, while only 9.55% use Value-Based Pricing.
- This suggests that most companies prioritize market competition over customer-perceived value.

![5](https://github.com/user-attachments/assets/95cbe530-71eb-4399-82bb-aed79f8dcbad)

### 6. Products and Their Fee Structures
- Digital Payments leads in the number of companies, with 86K using this product.
 - 54K companies use a Flat Fee model.
 - 32K use a Percentage Fee model.
- Mobile Banking follows with 81K companies.
 - 45K use a Flat Fee model.
 - 29K use a Percentage Fee model.
 - 7K use a Subscription-Based model.
- Micro-Lending has 20K companies, all using a Flat Fee model.
- Blockchain has 11K companies, all using a Percentage Fee model.
- Flat Fee models dominate across fintech categories.

![6](https://github.com/user-attachments/assets/d5cdb95c-3fbc-49f1-b583-39519dac341c)

### 7. Gaps in Competitive Pricing
- Many FinTech companies offer competitive pricing, but only a few provide user benefits.
- Binance offers Trading Discounts, Kuda has Loyalty Rewards, while OPay and Roqqu provide Cashback.
- Several companies (Flutterwave, Interswitch, Luno, Moniepoint, Paystack) offer no additional user benefits.

![7](https://github.com/user-attachments/assets/53ccfc8a-d8db-4a31-90be-88ec441d1406)

### 8. Gaps in Value-Based Pricing
- Several FinTech companies use a value-based pricing strategy, but their user benefits vary.
- Companies like CowryWise and PiggyVest offer free tools, while FairMoney provides cashback.

![8](https://github.com/user-attachments/assets/a015a3f5-9051-4877-9e1c-70677c415ebd)

### 9. Users by Target Customers
- Young Urban Professionals (80K users) form the largest segment of FinTech users.
- Urban Professionals (70K users) are the second-largest group.
- Small Business Owners (30K users) and Rural Users (20K users) have significantly lower adoption.

![9](https://github.com/user-attachments/assets/fa57e3d4-3cf2-4994-82d2-e4b31df5ab3c)

### 10. Financial Literacy and Usage
- Young Urban Professionals have the highest number of fintech users (80K), with a majority having high financial literacy (56K) and medium literacy (24K).
- Urban Professionals have the same number of highly literate users (56K) but fewer medium-literate users (14K), totaling 70K.
- Small Business Owners have 30K users, with a more balanced split among financial literacy levels: 15K medium, 9K low, and 6K high.
- Rural Users have the lowest fintech usage (20K), with most having low financial literacy (16K) and very few having medium literacy (4K).

![10](https://github.com/user-attachments/assets/67a23c8b-466f-493a-b5a0-3b25ca2499d2)

### 11. Users by Service Preference
- Mobile Apps are the most preferred service with 83K users.
- Web Platforms attract 54K users.
- Agent Banking is used by 34K users.
- Self-Service is the least preferred, with 29K users.
- Digital-first channels (Mobile & Web) dominate user preferences.

![11](https://github.com/user-attachments/assets/6a31c9d0-c02e-4bd1-81a7-176763152848)

### 12. Users and Service Preference
- Young Urban Professionals (80K)
 - Prefer Mobile Apps (48K users)
 - Web Platforms (24K users)
 - Agent Banking (8K users)
- Urban Professionals (70K)
 - Mobile Apps (35K users)
 - Web Platforms (21K users)
 - Self-Service (14K users)
- Small Business Owners (27K)
 - Agent Banking (18K users)
 - Web Platforms (9K users)
- Rural Users (20K)
 - Agent Banking (16K users)
 - Self-Service (4K users)
- Young and Urban Professionals drive digital adoption, while rural users rely on agent banking.

![12](https://github.com/user-attachments/assets/3a30ec03-bec3-487b-ab53-3aad063d350e)

### 13. Income Level by Number of Users
- High-income users: 50.40% are Urban Professionals, while 49.60% are Young Urban Professionals.
- Middle-income users: 42.70% are Young Urban Professionals, followed by 27.92% Urban Professionals, 24.06% Small Business Owners, and 5.32% Rural Users.
- Low-income users: 57.02% are Rural Users, and 42.98% are Small Business Owners.

![13](https://github.com/user-attachments/assets/9b028cfe-c02c-412d-921e-fcedfdfbbdb6)

### 14. Number of User by Location
- Urban users (170.94K, 85.47%) form the overwhelming majority of FinTech users.
- Rural users (29.06K, 14.53%) have significantly lower adoption.

![14](https://github.com/user-attachments/assets/64de4278-82ad-4c0a-ad05-4f8c1c4a2a96)

### 15. Age Group by Number of Users
- Young Adults (94K users) form the largest segment of FinTech users.
- Adults (71K users) are the second-largest group.
- Middle-Aged (21K users) and Aged (14K users) have significantly lower adoption.

![15](https://github.com/user-attachments/assets/a199d38b-5e02-484d-be2c-cf572be1b735)

### 16. Financial Literacy Level & User Base
- High literacy: 118K users, the largest segment.
- Medium literacy: 57K users, showing a moderate engagement.
- Low literacy: 25K users, the smallest group.

![16](https://github.com/user-attachments/assets/ed5111bd-b365-4ac5-a007-4c0ea4f0ca39)

### 17. Financial Literacy Level & Service Preference
- Low: 72.98% rely on Agent Banking, showing dependence on intermediaries.
- Medium: More balanced use of Mobile Apps (37.31%) and Web Platforms (27.84%).
- High: More self-reliant, with 51.91% using Mobile Apps and 30.09% using Web Platforms.

![17](https://github.com/user-attachments/assets/9147395d-78ff-426f-808d-c283df9620e4)

### 18. Transaction Volume
- Young Urban Professionals conduct the highest transaction volume at 80K.
- Urban Professionals follow with 70K transactions.
- Small Business Owners account for 30K transactions.
- Rural Users contribute the least, with only 20K transactions.

![18](https://github.com/user-attachments/assets/dd51897f-fb71-4b6e-9164-ea22c2d0538b)

### 19. Customer Satisfaction Levels
- Young urban professionals report the highest satisfaction (79.99% high, 20.01% moderate).
- Urban professionals also show high satisfaction (70.22% high).
- Small business owners have moderate satisfaction (49.72%), with 20.07% low satisfaction.
- Rural users report the lowest satisfaction (69.93% low satisfaction).

![19](https://github.com/user-attachments/assets/e60af568-4ca8-45d0-9b22-cdbfc309325a)


## Recommendations
- Product Focus: Prioritize Digital Payments & Mobile Banking (most preferred), expand Micro-Lending with better awareness, and promote Blockchain education to increase familiarity.

- Service Delivery: Strengthen Agent Banking for low-literacy users, enhance Mobile & Web platforms for medium- and high-literacy users.

- Customer Targeting: Focus on Young Urban Professionals & Urban Professionals (largest user base), introduce business-specific solutions for SMEs, and boost financial literacy campaigns for rural users.

- Pricing Strategies: Offer loyalty rewards & cashback, implement a hybrid competitive & value-based pricing model, and introduce tiered subscription services for premium users.

- Marketing & Engagement: Use social media for urban professionals, localized campaigns for rural users, and referral incentives to drive adoption.

## Challenges
- Data Privacy Constraints: Limited access to sensitive information, such as revenue data from companies, restricted our ability to provide deeper insights and enhance data quality.
- Integration of Multiple Data Sources: Merging data from surveys, CBN reports, and industry research required careful alignment to maintain consistency and accuracy.
- Data Assumptions in Synthetic Generation: Reliance on estimated distributions for synthetic data generation introduced potential biases, affecting data reliability.
- Realism of Generated Data: Ensuring that the generated dataset accurately reflected real-world user behavior and economic conditions posed a significant challenge.
