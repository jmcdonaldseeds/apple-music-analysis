<h1> Music Engagement Across Platforms </h1>

<hr>

<h2>Project Description</h2>
<p>
For my final project, I analyzed my personal music streaming data from Apple Music, which I obtained by requesting my data through Apple’s privacy portal. The dataset included information on my listening habits, such as play counts, song durations, and the amount of time I listened to each track. My focus was on examining how these variables relate to my attention span, particularly looking at the frequency with which I skip songs before they finish.
</p>
<p>
To provide a broader context, I incorporated data from Spotify’s API and the Billboard Top 100 Charts to explore global music trends. By analyzing both personal and external datasets, I aimed to understand how song length influences listener engagement and its potential correlation with song popularity, especially in relation to modern attention spans.
</p>

<hr>

<h2>Overview</h2>
<p>
This repository contains the final project for the Spring 2025 <em>Data Wrangling and Management with R</em> course at Rutgers University. The goal of the project was to demonstrate proficiency in data wrangling techniques by integrating, cleaning, transforming, and analyzing data from multiple sources. Students were encouraged to choose a topic of personal interest and to work with at least one nontrivial dataset (e.g., requiring API access, web scraping, or substantial cleaning).
</p>

<hr>

<h2>Files</h2>
<ul>
  <li><code>finalprojsp2025.Rmd</code>: R Markdown source file containing the full analysis and write-up.</li>
  <li><code>finalprojsp2025.html</code>: Rendered HTML output of the report.</li>
</ul>

<hr>

<h2>Technologies & Packages</h2>
<ul>
  <li><strong>R</strong> (base, tidyverse)</li>
  <li><code>dplyr</code>, <code>tidyr</code>, <code>ggplot2</code>, <code>readr</code>, <code>stringr</code>, <code>lubridate</code></li>
  <li><code>billboard</code>: Python package used via R for Billboard Hot 100 chart scraping</li>
  <li>Spotify Web API (accessed using custom scripts and token authentication)</li>
  <li>Apple Music Privacy Export (personal data)</li>
</ul>

<hr>

<h2>Data Sources</h2>
<ul>
  <li><strong>Apple Music Listening History</strong>: Exported via Apple’s privacy portal, in JSON format, requiring parsing and cleaning.</li>
  <li><strong>Spotify Track Metadata</strong>: Retrieved through the Spotify Web API using song titles from Apple data.</li>
  <li><strong>Billboard Hot 100</strong>: Collected using the <code>billboard</code> Python package to compare personal listening with popular trends.</li>
</ul>

<hr>

<h2>Project Objectives</h2>
<ul>
  <li>Import and merge datasets from three distinct platforms.</li>
  <li>Tidy and standardize date formats, artist and title naming conventions, and structure.</li>
  <li>Quantify song skip rates based on incomplete playbacks.</li>
  <li>Explore the relationship between track duration and listener engagement.</li>
  <li>Compare personal listening behavior with global music trends.</li>
  <li>Save a cleaned, tidy version of the final dataset as a CSV for reproducibility.</li>
  <li>Produce clean, well-formatted tables and figures explaining each step of the wrangling process.</li>
</ul>

<hr>

<h2>Author</h2>
<p>
<strong>Justin McDonald</strong><br>
Rutgers University – Class of 2025<br>
Major: Information Technology<br>
Minors: Data Science and Labor Studies
</p>
