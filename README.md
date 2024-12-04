# YouTube Data Scraping and Analysis Project

With the rise of social media analytics, YouTube channel data has become invaluable for understanding audience engagement, video performance, and content trends. This project aims to make gathering and analyzing YouTube data seamless, transforming raw metrics into meaningful insights. By using Python and the YouTube Data API, this project automates data collection and visualization, making it easy to uncover trends across multiple YouTube channels.

![panda](https://github.com/user-attachments/assets/11e49cb0-f83a-400c-9359-d01fea4fbaee)

## Table of Contents

Project Background

What This Project Does

Getting Started

Data Structure

Visualizations

Libraries Used

Expanding the Project

Contributing

## Project Background

Understanding how YouTube channels perform can be key to refining content strategies, identifying audience preferences, and evaluating the effectiveness of specific videos. However, gathering and analyzing YouTube data manually is both time-consuming and complex. This project was built to streamline that process, providing a structured way to scrape and visualize YouTube data at scale, transforming it into actionable insights.

The project is centered on gathering metrics from The Weeknd’s YouTube channel while demonstrating the power of data-driven insights for any YouTube content. This analysis isn’t limited to fan curiosity—it’s a foundation for anyone wanting to improve content engagement, assess market trends, or track audience growth.

## What This Project Does

The project serves as a data collection and analysis tool that pulls key YouTube metrics from multiple channels. Specifically, it:

Retrieves Channel Data: Collects foundational metrics like total subscribers, view count, video count, and playlist IDs across multiple channels.
In-depth Video Analysis: Using The Weeknd's channel as an example, it dives deeper to analyze individual videos. The project extracts key metrics like views, likes, comments, and publishes dates to understand what’s driving engagement.
Interactive Data Visualization: Includes both static and interactive graphs to give users a closer look at channel trends, top-performing videos, and monthly publishing frequencies. With Plotly Express, users can actively explore the data and identify insights in real-time.
Whether you’re a digital marketer, content creator, or data enthusiast, this project can help you answer questions like:

Which videos have the highest engagement?

How do engagement metrics like views and likes correlate?

What publishing trends appear over time?

## Prerequisites

Python 3.x

YouTube Data API key (obtain from the Google Developer Console)

## Data Structure
The project extracts two main types of data:

Channel-Level Data: Essential channel information like Channel_Name, Subscribers, Views, Total_Videos, and Playlist_ID.
Video-Level Data for The Weeknd: Using playlist IDs, this project extracts specific video data, including Title, Published_Date, Views, Likes, Comments, and Month.
This data structure is designed to be flexible, so additional YouTube channels or data columns can be added as needed.

## Visualizations
The visualizations turn raw YouTube data into insights across engagement metrics, monthly trends, and audience preferences. Here’s a breakdown:

Channels Overview:

YouTube Channels by Subscriber Count (bar)

YouTube Channels by View Count (bar)

YouTube Channels by Videos Uploaded (bar)

The Weeknd’s Video Insights:

Top 10 Most Viewed Videos (bar)

Videos Released per Month (bar)

Views vs. Likes (interactive scatterplot) – Explore relationships between views and likes.

Total Views per Month (interactive bar) – Monthly video views to identify publishing trends.

Distribution of Views for Top 10 Most Viewed Videos (interactive boxplot) – Shows view distribution patterns.

Average Likes per Month (interactive line) – Monthly engagement trend via likes.

Distribution of Likes for Top 10 Most Viewed Videos (interactive pie chart) – Visualizes like distribution across top videos.

## Recommendations

Recommendations for further investigation:

- Content strategy: Analyze correlation between video types and engagement metrics
- Optimal publishing times: Investigate if certain months or days yield higher engagement
- Audience retention: Examine relationship between video duration and view count
- Cross-channel comparison: Compare The Weeknd's performance metrics with other analyzed channels
  
## Libraries Used

Pandas: For data manipulation and storage.

Matplotlib and Seaborn: For static, descriptive visualizations.

Plotly Express: For creating interactive graphs, ideal for exploratory data analysis.

Google API Client: Used to access the YouTube Data API, allowing for real-time data scraping.

## Expanding the Project
Future enhancements include:

Adding sentiment analysis on comments for deeper audience insights.

Expanding the scraping scope to include more channels and playlists.

Creating time-series visualizations to track long-term trends.

This project is a versatile tool for anyone needing robust YouTube data for trend analysis, content evaluation, or social media strategy.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the project and submit a pull request with improvements or bug fixes.
