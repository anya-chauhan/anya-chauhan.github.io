---
title: 'Emerging Horizons in Coding: A Multifaceted Investigation into AI Code Assistants'
subtitle: 'STEM-Away Virtual-Internship'
date: 2023-02-30 00:00:00
description: A comprehensive machine learning project focused on building a sophisticated recommender system for AI code assistant-related content. The system combines advanced NLP techniques with web scraping to deliver personalized article recommendations from Medium, laying the groundwork for a multi-platform content discovery tool.
featured_image: '/images/bytemasters.png'
---

# Project Overview
As Project Management Lead and member of the Machine Learning subteam, I developed an intelligent recommendation system for AI code assistant-related content. The project combined web scraping, natural language processing, and recommendation algorithms to create a sophisticated content discovery tool, starting with Medium articles as our initial data source.

## Key Features
- **Dual Recommendation Methods**: Implemented both Word2Vec and BERT embeddings with cosine similarity for comparative analysis
- **Smart Data Collection**: Developed custom web scraping solutions for Medium articles
- **Intelligent Preprocessing**: Created an aggressive common word removal system to enhance recommendation quality
- **Validation Metrics**: Implemented computed columns for recommendation validation including vector magnitude and similarity scores
- **Project Infrastructure**: Established Airtable-based project management system and Softr website

## Technical Implementation
### Data Collection & Processing
- Built Python-based web scraper to gather article data including titles, subtitles, summaries, and metadata
- Implemented robust preprocessing pipeline with tokenization and advanced common word filtering
- Developed adaptive threshold system for common word removal (refined from 30% to 10% occurrence)

### Recommendation Engine
- Integrated dual embedding approaches:
  - Word2Vec embeddings with cosine similarity
  - BERT embeddings with cosine similarity
- Implemented validation metrics:
  - Vector magnitude calculation
  - Average similarity scoring
  - Highly similar article counting
  - Similarity matrix visualization

### Project Management
- Set up comprehensive Airtable-based tracking system
- Developed Softr site for team collaboration
- Coordinated machine learning subteam efforts

## Challenges Overcome
- Adapted to dynamic website structure changes during scraping
- Refined recommendation algorithms to reduce over-similarity in results
- Balanced multiple project responsibilities while maintaining quality
- Developed novel validation approaches for recommendation quality

## Results & Impact
- Successfully created a robust recommendation system capable of suggesting relevant AI code assistant content
- Established foundation for multi-platform content integration
- Developed scalable infrastructure for future expansion
- Created visualization tools for similarity analysis

## Future Development
The project lays groundwork for:
- Integration with Tableau-based Dashboard
- Chatbot implementation
- Expansion to multiple content platforms
- Enhanced user testing and feedback systems

## Technologies Used
- Python for web scraping and data processing
- Word2Vec and BERT for text embeddings
- Cosine similarity for recommendation generation
- Airtable for project management
- Softr for team collaboration
- Visualization tools for similarity analysis

## Code Repository
- Web Scraper: [GitHub - Medium Articles Scraper](https://github.com/anya-chauhan/bytemasters/blob/main/medium_articles_scraper.py)
- Recommender System: [GitHub - Recommender Notebook](https://github.com/anya-chauhan/bytemasters/blob/main/recommender.ipynb)


