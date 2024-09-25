# Cold Email Generator for Services Companies

This project leverages **Groq**, **Langchain**, and **Streamlit** to automate the process of generating personalized cold emails for business development purposes. The tool allows users to input the URL of a company’s careers page, from which it extracts job listings. It then creates tailored cold emails with links to relevant portfolios sourced from a vector database. The emails are personalized based on specific job descriptions, enabling service companies to pitch their services to potential clients more effectively.

This automation reduces the time and effort spent on manual outreach and improves the relevance of cold emails sent to target companies.

## Why did I do this project?

The goal was to automate and streamline the process of business development outreach, specifically for services companies aiming to offer specialized staffing solutions. **Cold emailing** is a common method used in business development, and I saw an opportunity to improve its efficiency by generating personalized, data-driven emails that directly target potential client needs.

## Purpose/Objective

The main objective is to build a tool that automates the process of **cold email generation**, personalized to each job posting. This helps business development teams reduce the time spent on manual email crafting and improves the quality and relevance of emails, leading to higher response rates from potential clients.

## Problems Solved

This tool solves the problem of manual, time-consuming cold email creation for business development executives. It automates the extraction of job listings from a company's careers page, analyzes the job descriptions, and generates a personalized email pitch with **portfolio links** that are relevant to the job being offered. This saves time, ensures relevance, and increases the likelihood of engagement from the target company.

## Technologies Used

- **Groq** for computational optimizations
- **Langchain** for natural language processing and linking to external data like job descriptions and portfolios
- **Streamlit** for the user interface framework
- A **vector database** to store and retrieve relevant portfolio links based on job descriptions

## Project Workflow

1. **Input URL**: The user provides the URL of a company’s careers page.
2. **Job Listings Extraction**: The tool uses **Langchain** and **web scraping** techniques to extract job postings from the provided URL. The job details are processed and stored temporarily.
3. **Portfolio Matching**: The tool searches a **vector database** for relevant portfolio links based on job descriptions.
4. **Cold Email Generation**: Using the job details and matched portfolios, the tool generates a personalized cold email, including a custom pitch and relevant portfolio links.
5. **Email Preview & Edit**: The user is shown a preview of the generated email and can make any necessary edits before sending.
6. **Email Delivery** (optional): Depending on the implementation, the email can be copied for manual sending or sent directly using an integrated email API.

