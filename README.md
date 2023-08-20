# Situation Recommender System

> “If a person is presented with too many options, they are less likely to buy.”

On the Internet, where the number of choices is overwhelming, there is a need to filter, prioritize and efficiently deliver relevant information. Recommender systems help drive user engagement on platforms by generating personalized recommendations based on a user’s past behaviour.

The main motivation behind the project was to make a recommender system which is contextually aware since the context can massively change the result. While researching for the project we were not able to find any open sourced contextual recommender systems which only increased our fascination to implement one and the open-source it later.

Context cannot be taken lightly for recommender system, for instance, think you visited a hotel during summers which had everything great but their Air Conditioners were not working then you will leave a bad rating for the place but if you had visited the same hotel during winters the AC wouldn’t have mattered and you would have given them a great rating.

## 🚀&nbsp; Installation

### Installing Required Files

```bash
myenv/Scripts/activate
pip install -r requirements.txt
```

### Django Server

```bash
cd /UI/
python manage.py runserver

```

## 🛠&nbsp; Features

- [x] Content-Based Recommender
- [x] Collaborative Filtering Recommender System
- [x] Hybrid Recommender System
- [x] Context-Aware Recommender System
- [x] Merging Hybrid And Context-Aware Recommender System
- [x] Django Based Interface
- [x] Integrating Django and Recommender System
