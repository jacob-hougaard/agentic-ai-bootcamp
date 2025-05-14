 # 🥇 Business Automation - Competitive Insights 

<!--![image](https://github.ibm.com/skol/agentic-ai-client-bootcamp/assets/451557/b9fb42fc-4aa1-4010-b850-5c8f20e3e05a)-->
![image](assets/hypercar.png)


## 🤔 The Problem

ABC Motors Corp's sales department faced challenges in preparing sales proposals for their new line of high performance vehicles. Every time they release a new model, the competitive analysis team spends a great amount of time and resources to deliver their insights. Issues include: 

- Manual research delays decisions and reduces productivity.

- Weak positioning hampers sales differentiation.

- Slow response to market changes without real-time intelligence.

## 🎯 Objective

ABC Motors Corp plans to implement an AI-powered Competitive Intelligence System to automate market research and competitor analysis. This system will help sales teams quickly identify and position their products against competitors, overcoming the inefficiencies of manual research and outdated insights. The goal is to create an AI-enabled system that supports competitive analysis and market research by:

* Extract products from the company’s product catalog.
* Identify and extract key features of each product.
* Search for competitor products based on key attributes.
* Generate a structured competitive comparison table with price, features, and differentiators.
* Perform SWOT Analysis (Strengths, Weaknesses, Opportunities, and Threats) to provide deeper strategic insights.

By automating these tasks, the company aims to accelerate sales processes, improve data accuracy, and enable sales teams to make informed decisions faster.

## 📈 Business Value

* Reduction in manual competitor research time.
* Automated, real-time updates on market competition.
* Improved sales pitch effectiveness

## 🏛 Architecture

To streamline the competitive analysis process, we have designed a Multi-Agent AI Automation System that autonomously extracts and analyzes product data. This system leverages a collaborative multi-agent approach, ensuring efficiency, accuracy, and real-time insights for sales and strategy teams. The architecture consists of specialized AI agents working together to perform key functions:
  * To extract products from the product catalog
  * Extract features of the product from the product catalog,
  * Searches for competitor products
  * Generates a structured competitive comparison table
  * Strengths, Weaknesses, Opportunities, and Threats (SWOT) Analysis

This system leverages 2 AI agents and an Orchestrate agent that collaborate seamlessly to automate competitive research, enhance sales pitch effectiveness, and reduce manual effort.

<img width="979" alt="image" src="https://github.ibm.com/skol/agentic-ai-client-bootcamp/assets/451557/952b54c4-28a4-4ef6-82b4-ef08991d9297">


The use case leverages wxO skills to get product specific data (name, features) from the product catalogue followed by two specialized agents developed within the watsonx.ai's Agent Lab, all of which are integrated into watsonx Orchestrate. Through the watsonx Orchestrate chat assistant, these agents & skills communicate seamlessly to provide comprehensive insights and facilitate informed decision-making. 
  * **Product Search wxO skills** : These skills are designed to search for a specified product and retrieve its details and features in a structured format from the product catalog. It ensures clarity and organization by presenting key product information systematically, making it easy to understand and use.
  * **Link Search Agent** : This agent is expert in finding URLs or links for similar products that share matching features, ensuring users can explore alternatives efficiently.
  * **Comparison Agent** : This agent is designed to compare competitor products using these links, extract key insights, and return a SWOT analysis of all products. The findings should be presented in a well-structured table format, making it easy to understand and compare the information briefly.

> [!IMPORTANT]
> This lab uses a simulator for a Human Capital Management system. However, this could be easily changed to any real system running in production such as Workday or others.



## 📝 Step-by-step Hands-on Lab
You can find step-by-step instructions here :

[Step-by-step hands-on guide](https://github.ibm.com/skol/agentic-ai-client-bootcamp/blob/main/usecases/business-automation/hands-on-lab-buisness-automation.md)

## Demo Video
A video demo of the solution is here:

https://github.ibm.com/skol/agentic-ai-client-bootcamp/assets/453165/83bfd0b0-cfb1-406e-8d74-dd9d2febd2db



It shows how you can implement the use case using watsonx.ai and watsonx Orchestrate. 
