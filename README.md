# Blog-Analytics-with-Express-and-Lodash
Blog Analytics and Search Tool
This middleware-based blog analytics and search tool is developed using Express.js and Lodash. It enables you to retrieve data from a third-party blog API, perform data analysis, implement a blog search functionality, and includes error handling and caching mechanisms.

# Table of Contents
1.Features
2.Prerequisites
3.Data Analysis
4.Respons
5.Error Handling


# Features
Data Retrieval:

Use Express to create a route at /api/blog-stats.
Fetch blog data from a third-party API.

# Prerequisites
Node.js and npm installed on your computer.


# Data Analysis:

Calculate the total number of blogs fetched.

Find the blog with the longest title.

Determine the number of blogs with titles containing the word "privacy."

Create an array of unique blog titles (no duplicates).

# Response:

Respond to the client with a JSON object containing the following statistics:

Total number of blogs.

The title of the longest blog.

Number of blogs with "privacy" in the title.

An array of unique blog titles.

Blog Search Endpoint:


Create a search functionality that filters the blogs based on the provided query string (case-insensitive).
The search functionality is an original implementation.

# Error Handling:

Handle errors that may occur during data retrieval, analysis, or search.
If the third-party API is unavailable or returns an error, an appropriate error message is returned.

