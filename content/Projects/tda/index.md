---
title: "Automated Online Ad Reporting System (cross-media measurement)"
weight: 1
draft: false
description: "tda"
slug: "tda"
tags: ["Data Analytics", "Data Visualization", "Product"]
# series: ["Project"]
# series_order: 1
---

## Overview

Taipei Digital Group is the leading digital marketing agency in Taiwan that provides digital marketing solutions to grow business with 2000+ clients by Web Design, SEO, Google Business Photo, Media Buy and Integrated Marketing services.

I was a product manager in the core business Taipei Digital Advertising, and improving media buy efficiency is the key to expand our business, increase revenue and productivity but also keep good partnership with our existing clients.

I led a cross-functional team with data engineers, designers, account managers and sales managers to build an automated online ad reporting system from scratch and serve 500+ clients.

This product aligns metrics across Google, Facebook, Instagram, Yahoo and LINE media and attributes Google Analytics metrics and conversions to ad level data. Besides, it updated data on a daily basis. It is a powerful tool to enhance media buy efficiency with cross-media measurement and unleash productivity with updating data automatically.

## Time

2019-2021

## Role

Product Manager

I took the ownership and delivered data-centric solution throughout the product development lifecycle, including:

- Defining product vision and differentiators
- Devising success metrics and product roadmap
- Struturing analytical stories and data visualization in dashboard
- Defining data schema
- Designing tracking mechanism to align cross-media conversion metrics and GA attribution
- Debugging data discrepancy with QA testing
- Iterative product development with user feedback
- Stakeholder management
- Product Marketing

## Product

{{< scroll-image src="/tda/product.png" alt="product" >}}

## Outcome

- Apply to 500+ clients, including key clients GU (a sister brand of UNIQLO) and Clorox
- Generate 10+ new clients leads per month
- Coopertate with 2 other media agency

## Product Development

### Key Users

We have three key users:

![keyUsers](/tda/keyUsers.png)

**1. Account Manager:** Each account manager is responsible for a specific media account management (either Facebook, Google, Yahoo or LINE) and hold 10-30+ client accounts depends on budget and complexity. Account manager needs to deliver weekly, monthly and post-buy ad reporting, performance analysis and optimization suggestion to clients or sales managers.

**2. Sales Manager:** Each sales manager is responsible for multiple clients. In some key clients' cases, sales managers would take responsibility to provide integrated media buy performance review and optimization suggestion to their clients.

**3. Clients:** Clients are advertisers who be charged of commission fee for ad account management, performance report and optimization.

### User Interview & Survey

_I used to be an account manager at media agency in my early career, and transfered to an in-house marketing analyst role, so I deeply understand user pain points and service gap between agency and advertiser._

_But I could only speak up for my own experience, I still interviewed key stakeholders and made survey to get insight on current reporting workflow and service for further MVP planning._

**1. Account Manager:**

- I usually take the whole monday to deal with 15+ weekly reports manually, it's too overwhelming.
- I need to focus on ad account management, performance review and ad optimization. It is redundant to do the work of pulling data out from media accounts, clean data and make pivot tables in Excel.
- Sometimes, my clients or sales manager would have ad-hoc reporting requests but I already prioritize my tasks of the day.

**2. Sales Manager:**

- I need to collect media reports from different account managers to make integrated media buy report for my key clients, it's not efficient.
- I find the reporting is lack of visualization to highlight the performance. Therefore, it's time-consuming to interpret data into insightful story for clients.

_Average working hours of completing weekly ad reports_
{{< chart >}}
type: 'bar',
data: {
labels: ['AM(Google)', 'AM(Facebook)', 'AM(LINE)', 'AM(Yahoo)', 'AM(IMC)', 'Sales Manager'],
datasets: [{
label: 'avg. hours per week',
data: [5.2, 7.5, 4.5, 2, 8, 6.3],
}]
}
{{< /chart >}}

**3. Clients:**

- **Integrated Marketing Service Clients:**
  Media buy efficiency is my top priority to evaluate a media agency performance. I know that a cross-media performance report and analysis is time-consuming, especially with Google Analytics metrics. I need ad performance review across all media and aligns with Google Analytics metrics to make budget allocation and creative-wise optimization, that is the key to increase ROAS and boost my business growth. In addition, I would appreciate the performance report with some data visualization to highlight performance drivers.
- **Non integrated Marketing Service Clients:**
  My sales representive let different account managers email me the media report directly, and I could discuss media performance, strategy and optimization with each account manager. However, I have some ad-hoc reporting requests need to be handled from time to time, sometime it's urgent sometime it's not but it would be great if I could receive reporting within that day.

### User Pain Points

- It is time-consuming and inefficient to deliver weekly report/ad-hoc report to clients.
- It is time-consuming and overwhelming to provide cross-media performance report to key clients.
- Lack of data visualization to interpret numbers into insightful story.

### Epics

{{< scroll-image src="/tda/epic.png" alt="epic" >}}

### Data Pipeline

- Most of our key users use G suite at work
- Build with Google products to establish ecosystem
- Scalability & Flexibility

![data-pipeline](/tda/data_pipeline.png)

### Data Schema

- Align metrics from multiple media for cross-media measurement
- Attribute Google Analytics data(session, transactions and revenue) to ad level data

![data-schema](/tda/data_schema.png)

### MVP, Beta & Launch version

_Start from small and make big_

We were aim to build an automated cross-media ad reporting system. In that time, no other competitors did that, providing ad reporting is a labor-intensive work...a lot of Excel and spreadsheet works.

{{< scroll-image src="/tda/mvp.png" alt="mvp" >}}

{{< scroll-image src="/tda/beta.png" alt="beta" >}}

{{< scroll-image src="/tda/launch_v1.png" alt="launch_v1" >}}

## Reflection

1. Data Quality and Validation: Ensuring the data from different platforms is clean and consistent can be challenging. Implementing robust data validation and transformation processes could enhance the system's reliability.

2. Advanced Analytics and AI/ML: Consider adding capabilities for predictive analytics or AI/ML models to forecast performance trends, optimize ad spend or provide AI-powered analysis.

3. Attribution Modeling: The project could explore different attribution models to better understand the impact of each platform and optimize the marketing mix.
