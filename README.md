# Netflix Content Analysis & Recommendation Engine

## Project Overview
Analyzed 8,800+ Netflix titles to uncover growth patterns, content strategy, and audience preferences.
In addition, a genre-based recommendation engine was built to simulate how Netflix could suggest similar content based on user preferences.

## Objectives
- Understand how Netflix’s content strategy evolved over time
- Compare growth trends between Movies and TV Shows
- Analyze genre, rating, and country-level patterns
- Build a lightweight recommendation system using content similarity

## Key Questions Answered
1. **When did Netflix scale aggressively?** Post-2016 exponential growth
2. **Movies vs TV Shows?** Movies gaining rapidly since 2018  
3. **Global expansion?** International content rivals US post-2016
4. **Target audience?** Mature ratings (TV-MA) dominate

## Key Insights
- **Drama Dominance**: 2427 titles (27% catalog) - emotional storytelling drives retention
- **Comedy Reliability**: 1831 titles (21%) - low-risk, high completion rates  
- **International TV Surge**: 1831 titles beats US TV Dramas - global strategy winning
- **📺 TV Shift**: 3/5 top genres are TV shows (growth validated)
- **85%+ content post-2016** - streaming pivot success
- **Top 5 countries = 70%** but India/UK challenging US lead

**Genre Concentration: 48% catalog = Drama + Comedy** proves comfort viewing formula.

## Genre-based recommendation system
Approach:
Each title is represented as a set of genres.
Similarity is computed using Jaccard similarity
Recommendations prioritize:
    - Higher genre overlap
    - More recently added titles (recency bias)
example:
```python
Enter any Netflix title:  House of Cards
#Output:
#Target: 'House of Cards'
#Genres: TV Dramas, TV Thrillers
#   1. Squid Game (TV Show)
#   2. Fatma (TV Show)
#   3. 50M2 (TV Show)
#   4. Tiny Pretty Things (TV Show)
#   5. Children of Adam (TV Show)
```

## Visualizations

<img width="779" height="490" alt="image" src="https://github.com/user-attachments/assets/91914e24-30e8-4d43-96c4-59a822899316" />

<img width="1155" height="548" alt="image" src="https://github.com/user-attachments/assets/0b2a90a7-ff84-46ec-83cb-643c44228592" />

<img width="779" height="590" alt="image" src="https://github.com/user-attachments/assets/2f0108ea-89e5-4f99-bb56-9694d5470383" />


## 🛠️ Tech Stack
Python | Pandas | Matplotlib | Seaborn | Jupyter

## Dataset
[Kaggle: Netflix Movies & TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
