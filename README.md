
# The Impact of Influencer Marketing on Brand Loyalty: A Gen Z Consumer Perspective

## Project Overview

This project was conducted as part of my final-year university research project for my BSc (Hons) Business Information Systems degree.

The research investigates the relationship between influencer marketing and brand loyalty among Generation Z consumers. It explores how sponsorship transparency, the perceived authenticity of sponsored content, and engagement with influencers relate to consumers' brand-switching behaviour.

The study uses survey data collected through Google Forms and applies statistical and qualitative analysis to understand consumer perceptions, behaviours, and factors that may influence brand loyalty.

## Research Objectives

Examine the relationship between sponsorship transparency and brand-switching behaviour.

Explore how perceptions of sponsored-post authenticity relate to brand switching.

Investigate the relationship between influencer engagement and brand-switching behaviour.

Identify the factors that may reduce or strengthen consumer loyalty towards brands promoted by influencers.

Understand Gen Z consumers' perceptions and experiences of influencer marketing.

  

## Key Findings

Nearly even between Female (24; 50.0%) and Male (23; 47.9%), with 1 respondent preferring not to say (2.1%).

The Spearman correlation analysis found very weak relationships between the three influencer-marketing factors and brand-switching behaviour.

Most spend 2–4 hours (23; 47.9%) or More than 4 hours (13; 27.1%) per day—three-quarters spend at least 2 hours daily.

Tech (13; 27.1%) and Fashion (13; 27.1%) tie for first, ahead of Beauty (9; 18.8%), Other (8; 16.7%), and Food (5; 10.4%). Fashion and Beauty skew heavily toward female buyers, while Tech and Other skew toward male buyers.

1–5 influencers is the most common group (20; 41.7%), followed by 11+ (12; 25.0%), None (11; 22.9%), and 6–10 (5; 10.4%).

None of the three relationships was statistically significant at the 5% significance level.

The exploratory ordinal logistic regression also found no statistically significant predictor at the 5% level.

Perceived authenticity of sponsored posts showed a result close to, but above, the conventional significance threshold (p = 0.057).

Open-ended responses repeatedly highlighted product quality, negative reviews, honesty, transparency, and authenticity as important considerations in consumer loyalty.

Overall, the findings suggest that influencer-marketing factors examined in this sample did not demonstrate statistically significant relationships with brand-switching behaviour.

## 1. Descriptive Analysis

Descriptive analysis was conducted using Excel  to explore the characteristics and responses of survey participants.

### Interactive Dashboard

The survey findings were also presented through a <a href="https://datastudio.google.com/reporting/96973b35-d08e-474a-bad5-58c02831d0c5">Looker Studio dashboard.</a>

## 2. Statistical Analysis Using Python

Further statistical analysis was conducted using Python in <a href="https://colab.research.google.com/drive/1Ws_oB_yGzPgLdPRbTAe5Bch1_874-d99?usp=sharing">Google Colab</a>

### 2.1 Reliability Analysis

An exploratory Cronbach's Alpha calculation was performed using the three Likert-scale statements.

Cronbach's Alpha: 0.641
Complete responses used: 46


The three statements represented separate independent variables in the research framework and were analysed individually in the subsequent correlation and regression analyses. Therefore, this alpha value was not used to justify combining them into a single composite scale.

  
### 2.2 Correlation Analysis

Spearman's rank correlation was used to examine the relationships between the three independent variables and brand-switching behaviour.

| Predictor                         | Coefficient | Odds Ratio | P-value |
|-----------------------------------|------------:|-----------:|--------:|
| Trust in Sponsorship Transparency |       0.233 |      1.263 |   0.478 |
| Sponsored Post Authenticity*      |      -0.581 |      0.559 |   0.057 |
| Community Engagement              |       0.392 |      1.480 |   0.217 |


At the 5% significance level, there was insufficient statistical evidence to reject any of the three null hypotheses.

Note: The hypothesis statements were formulated from the three independent variables in the research framework.

## 3. Open-Ended Response Analysis

Two open-ended survey questions were analysed to identify recurring themes in respondents' opinions about influencer marketing and brand loyalty.

### 3.1 Factors That Could Reduce Brand Loyalty

Survey question: What would make you stop being loyal to a brand promoted by an influencer?

The responses revealed several recurring themes:
Poor Product Quality: Poor quality, inconsistent results, and products failing to meet expectations.

Negative Reviews: Negative customer feedback and reviews that reduce confidence in a brand.

Controversy: Controversial behaviour or reputational issues involving brands or influencers.

Lack of Transparency: Fake promotions and misleading product information.

Poor Customer Experience: Poor customer service and disappointing product experiences.

Brand-Value Misalignment: A mismatch between a brand's values and consumers' personal values.

Inauthentic Promotion: Overly aggressive or untrustworthy promotional content.

Product quality and negative reviews appeared repeatedly in the responses.

  

### 3.2 Factors That Could Strengthen Brand Loyalty

Survey question: What could brands or influencers do to make you more loyal to a brand?

The responses highlighted several themes:

Honesty and Transparency: Providing genuine product reviews and being transparent about promotional content.

Product Quality: Delivering consistent quality and value for money.

Authenticity: Maintaining genuine, relatable, and trustworthy communication.

Customer Engagement: Building relationships and engaging consistently with customers.

Customer Benefits: Offering discounts, exclusive deals, and additional benefits.

Realistic Product Representation: Showing genuine product results without misleading presentations.

Brand-Value Alignment: Aligning promotions with the brand's identity and consumers' values.

Honesty, transparency, authenticity, and product quality were recurring suggestions for strengthening brand loyalty.

### 3.3 Qualitative Analysis Summary

The open-ended responses provide additional context to the quantitative findings. They highlight the importance of trust, authenticity, transparency, and product quality in influencer marketing.

The responses also suggest that influencer endorsements alone may not be sufficient to maintain customer loyalty when the actual product experience does not meet consumer expectations.

## 4.Dataset

The dataset was collected independently through a <a href="[url](https://docs.google.com/forms/d/e/1FAIpQLSeGAI5hgPVmWAegnkn0iGcuWGXjiu3fp2mXrrLmbXBNnTxC1Q/viewform?usp=sharing&ouid=104972425654608126632)">Google Forms survey</a> as part of my final-year university research project.

Initial responses: 48

Initial dataset size: 48 rows × 15 columns

Complete cases used in correlation and regression: 46

The survey included demographic questions, social media usage, influencer-related consumer behaviour, Likert-scale statements, brand-switching behaviour, and open-ended questions

## 6.Conclusion

This research explored how influencer marketing relates to brand loyalty among Gen Z consumers, focusing on sponsorship transparency, perceived authenticity of sponsored content, and community engagement.

The quantitative analysis did not identify statistically significant relationships between the three examined factors and brand-switching behaviour in the collected sample.

However, the open-ended responses highlighted the importance of product quality, honest communication, transparency, authenticity, and customer experience in shaping consumer perceptions of brand loyalty.

The project provided an opportunity to apply statistical analysis, qualitative interpretation, data visualisation, and analytical tools to a real university research problem.