# Fintech2022-Module1Challenge-CaseStudy

# **ROBINHOOD – Financial Literacy For All**
## **Table of content**
+ 1. Overview and Origin.
+ 2. Business Activities.
+ 3. Landscape.
+ 4. Results.
+ 5. Recommendations. 
+ 6. Reference list

---

<div style="text-align: justify"> 

## **1. Overview and Origin**
**Robinhood Markets, INC** (Robinhood) was founded in 2013 by Vladimir Tenev and Baiju Bhatt at Menlo Park, California, U.S. 

While working for trading firms, both of the founders realised the financial institutions were paying *“fraction of a penny”* (Steib, 2021) for trading and transaction. This is the foundation where Robinhood was built from. The main mission of the company is to provide **“financial literacy for all"**. 

Robinhood was funded by many categories of investors such as VCs, investment banks, financial institutions, etc. Crunchbase (2022) has estimated that, over 29 rounds of funding, $6.2B was raised. The company went public in 2021 under the ticker NASDAQ:HOOD. By 28th Jan 2021, post money valuation of the company was in range of $10B. 

![](Robinhood.jpg)

<p align="center">
Robinhood Markets, INC
</p>

---

## **2. Business Activities**
### ***2.1 Value propositions***
There are few barries that retail investors need to get over in order to get into the financial markets. These could be either costly trading commission fees, large capital requirement or low accessibility to trading platforms. Robinhood most significant focus are to offering zero-commission-fee and a minimal trading platform which micro investors can access, trade anywhere with any amount of capital they can (Robinhood, 2022). Moreover, Robinhood is broadening their product range into cryptocurrency, cashcard, and also providing financial education resources. 
>By doing this, the company is ***”providing democratized finance access to all”***.

### ***2.2 Customer segments***
As previously mentioned, retail investors or micro investors are the customer segment which Robinhood targeted initially. They customers can be either beginners – millennials interested in trading – or high-frequency traders (Curry, 2022). However, it would be insufficient if retail brokerage marketing firms and electronic trading firms are not considered. While there is no adequate information to value the whole market size of Robinhood’s targeted customer segments, by 2022, the company is estimated to have a user base of 31 million (Pereira, 2022).
### ***2.3 Strengths***
When founded in 2013, Robinhood was the first-ever trading platform which offered zero-commission fee. Now, there are many players in the market that can offer similar pricing strategy. However, it is undeniable that Robinhood’s first-mover advantage has created such a strong brand recognition and customers’ loyalty (Shevlin, 2022). In addition, Robinhood’s accessibility to the financial market provided to customers is formidable. This can be seen by their extremely easy to use mobile app, wide range of product offering such as stocks, ETFs, options, cryptocurrency. These allow users to invest and trade with easy and comfort. 
### ***2.4 Implemented technologies***
Robinhood is an electronic trading platform which requires high-level of engineering in distributed systems, observability, and data infrastructure. There are many technologies which the company has utilised, some of the most critical technologies that help building the backbone of Robinhood can be listed as following (Meyerson, 2020): *(You can listen to the full podcast about Robinhood's implemented technologies in details [here](https://softwareengineeringdaily.com/2020/09/22/robinhood-engineering-with-jaren-glover/))*
-	***Cloud computing***: Robinhood utilised Amazon Web Services (AWS) for their could-computing platform, APIs, data store. Most of their APIs are written in Python and Go. 
-	***Network Time Protocol (NTP)***: as a global trading platform, Robinhood relies on NTP in order to manage, process and execute orders received in the same order that the customers placed them and route them correctly. This is required by NIST, a non-regulating agency of the US Department of Commerce (Quastor, 2022).
-	***Customised sharding system at the application layer***: in order to scale the company’s infrastructure horizontally to meet the growing customer base, Robinhood implemented sharding strategy of their large system. They built three main new layers to execute this idea:
    -	*Routing Layer.*
    -	*Aggregation Layer.*
    -	*Kafka Message Streaming.*

![](Horizontal.png)
<p align="center">
Horizontally scalling for more reliability (Robinhood, 2021)
</p>

---
## **3. Landscape**
With the services offered from Robinhood, the company can fit well in both **“Capital Investment”** and **“Investment Management”** domains of Fintech. In the last 5-10 years, there are many trends and innovation that came and changed these domains. *Artificial Intelligence*, *Big Data*, *Machine Learning* and *Cryptocurrency* can be considered as top technologies and innovation recently. For the business trends and models, Townsend (2019) has stated few of them such as *demographic-focused products*, *different fee structures built on digital infrastructure*, and *Bank-as-a-service*. In case of Robinhood, it can be seen that the company utilised Machine Learning and Cryptocurrency as the technologies and “Different fee structures built on digital infrastructure” model to construct their business. 

Direct competitors of Robinhood are: E*Trade, Webull, TradeStation, M1 Finance.

---
## **4. Results**

Robinhood disrupted the industry with the idea of providing tremendous accessibility to anyone who would like to invest. Prior to the company formation, commission fee was one of the barriers for beginner investors and investing was considered to be complicated. In 2019, major brokerages had decided to move to zero-commission fee when their customers investing in major financial instruments such as EFTs, options, and individual stocks (Steib, 2021). Moreover, micro investors are now considered to be a new market sector and promising. 

In regards to core metrics to measure success, for online trading platforms, investors would consider: **user (customer) base**, **assets under management**, **average account size**, and **annual revenue**. Compared with other competitors such as E-Trade, TD Ameritrate or Charles Schwab, Robinhood is at the small side of the scale. However, the growth of the company is enormous. Pereira (2022) has provided statistics of “Trading volume at Online Brokerages (Number of Shares)” where Robinhood achieved <span style="color: green;">139% </span> growth in Q2-2020 compared to <span style="color: red;">76%</span> growth from TD Ameritrade, <span style="color: red;">56%</span> from E-Trade and <span style="color: red;">24%</span> from Schwab. 

![](robinhood-business-model-04-2048x1152.png)
<p align="center">
Pereira (2022)
</p>


*The company's Revenue and Usage Statistics can be view in full [here](https://www.businessofapps.com/data/robinhood-statistics/)!*

---

## **5. Recommendations**
Robinhood should improve their information resources for research purpose of the users. While its competitors offer access to at least seven third-party reports for users (Reinkensmeyer & McKhann, 2022), Robinhood only provides a few pieces of information such as market cap size and current price. 

When the investors have access to a wide range of creditable resources, they should be able to make better investing decision. Thus, possibility of better portfolio performance is higher and it may lead to stronger customers’ loyalty and trust.

If this service is utilised, Robinhood would need to employ API and Machine Learning. API is for creating a link between third-party reports providers to the users. Machine Learning would be appropriate to learn the users’ preferences when they research about a company such as their favourite indicators or financial ratios. Then, the app can recommend stocks which users can be interested in in the future. 

---
</div>

## **6. Reference list**
- Crunchbase. (2022). Crunchbase - Robinhood. Retrieved 26 June 2022, from https://www. crunchbase.com/organization/robinhood/company_financials
- Curry, D. (2022). Robinhood Revenue and Usage Statistics (2022). Retrieved 26 June 2022, from https://www.businessofapps.com/data/robinhood-statistics/
- Johnston, M. (2022). How Robinhood Makes Money. Retrieved 26 June 2022, from https://www.investopedia.com/articles/active-trading/020515/how-robinhood-makes-money.asp
- Meyerson, J. (2020). [Podcast]. Retrieved 26 June 2022, from https://softwareengineeringdaily.com/2020/09/22/robinhood-engineering-with-jaren-glover/
- Pereira, D. (2022). Robinhood Business Model. Retrieved 26 June 2022, from https://businessmodelanalyst.com/robinhood-business-model/#Robinhoods_Customer_Segments
Quastor. (2022). Robinhood's Tech Stack. Retrieved 26 June 2022, from https://blog.quastor.org/p/robinhoods-tech-stack
- Reinkensmeyer, B., & McKhann, C. (2022). Robinhood Review. Retrieved 26 June 2022, from https://www.stockbrokers.com/review/robinhood
- Robinhood. (2021). Horizontally Scaling For More Reliability [Image]. Retrieved from https://miro.medium.com/max/1400/1*fMvOCvQ0FmvzJnMDo1fwsw.png
- Robinhood. (2022). Retrieved 26 June 2022, from https://blog.robinhood.com/
- Shevlin, R. (2022). Robinhood: The $30 Billion Cockroach Of Fintech. Retrieved 26 June 2022, from https://www.forbes.com/sites/ronshevlin/2021/07/06/robinhood-the-30-billion-cockroach-of-fintech/?sh=1b2dfb974339
- Steib, B. (2021). "The Robinhood Effect" - Digital technology in global financial markets and its effects on investor decision making" (Honors Theses). Colby Colledge.
- Townsend, Z. (2021). Scanning the fintech landscape: 10 disruptive models. Retrieved 26 June 2022, from https://www.mckinsey.com/industries/financial-services/our-insights/banking-matters/scanning-the-fintech-landscape