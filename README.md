[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1lXY_Wlg)



# Scientific Paper Scraping and Insights Generation System (1st Proposal Draft)

## Overview
Develop a system that scrapes daily new scientific papers from multiple online sources, aggregates the data, and generates insights through natural language processing (NLP) and data visualization techniques. This system will help researchers and academicians stay updated with the latest research trends and developments in their fields of interest.

Develop an RAG-LLM over papers abstract (might add paper pdf) so the user can activly search using natural query for specific topic/point.

This project aims to provide a comprehensive system for scraping, analyzing, and visualizing scientific paper data, offering valuable insights to researchers and academicians. By leveraging advanced NLP techniques and data visualization, the system can significantly enhance the efficiency and effectiveness of research activities.

## Project Scope

1. **Data Collection:**
   - **Sources:** Scrape scientific papers from multiple reputable sources, such as arXiv, PaperWithCode, and CrossRef.
   - **Data Formats:** Collect data in various formats (might include only meta data or meta + paper pdf).
   - **Volume:** Process and store information from thousands of new papers daily.

## Suggested Data Sources

1. **arXiv**
   - **API:** [arXiv API](https://arxiv.org/help/api/index)
   - **Historical Data:** [arXiv Bulk Data Access](https://arxiv.org/help/bulk_data)

2. **CrossRef**
   - **API:** [CrossRef REST API](https://www.crossref.org/services/metadata-delivery/rest-api/)
   - **Historical Data:** [CrossRef Metadata Search](https://search.crossref.org/)

3. **PapersWithCode**
   - **API** 

## Suggested Dimensional Data Modeling

#### Fact Table: `Papers`
#### Dimension Table: `Journals`
#### Dimension Table: `Authors`
#### To be added

## Suggested Insights and Metrics
    - Identify and visualize trending research topics over different time periods.
    - Determine and highlight the most cited papers and influential authors.
    - Assess the impact of different journals based on citation counts and publication frequency.
    - Track the emergence and evolution of keywords over time.



