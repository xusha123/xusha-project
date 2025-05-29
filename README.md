# BookMatchAI: Personalized Book Recommendation Engine

Final project for the Building AI course

## Summary

BookMatchAI is a personalized recommendation system that suggests books based on users’ past reads, preferences, and emotional tone, helping readers discover their next favorite story.  
**Building AI course project**

## Background

Finding a book that truly resonates can be overwhelming in today’s massive digital libraries. Most recommendation systems rely on genre or popularity, not emotional or thematic alignment.

This project aims to:
* make book discovery more emotionally engaging
* reduce decision fatigue for readers
* support independent authors by surfacing relevant matches

Motivation: As a passionate reader, I’ve often felt lost in recommendation lists that don’t reflect my taste or mood. BookMatchAI wants to fix that.

## How is it used?

Users input:
1. Books they've enjoyed in the past
2. Short reviews or emotional keywords (e.g. “hopeful”, “dark”, “adventurous”)
3. Optional: Goodreads or other book data

The system returns recommendations based on content similarity, sentiment, and collaborative filtering.

Use cases:
* Casual readers looking for personalized picks
* Libraries or book clubs offering curated suggestions
* Bookstores building smart kiosks

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Books_Falling_into_Open_Book.jpg" width="300">

## Data sources and AI methods

Data sources:
* [Goodreads public reviews](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home)
* Open Library metadata
* User-submitted feedback

AI methods:
* Natural Language Processing (NLP) for review and title embedding
* Sentiment analysis with transformer models (e.g., BERT)
* Collaborative filtering for behavioral recommendations

| Component | Technique |
|----------|-----------|
| Text embedding | BERT, TF-IDF |
| Sentiment scoring | Pretrained emotion classifiers |
| Recommendations | Cosine similarity + hybrid collaborative filtering |

## Challenges

BookMatchAI _does not_:
* Replace human taste or uniqueness
* Work equally well for obscure books with limited metadata
* Guarantee full genre diversity without data bias

Ethical considerations:
* Recommender systems can reinforce echo chambers
* Importance of exposing users to a variety of cultures, authors, and voices
* Proper handling of copyrighted review content

## What next?

* Build browser extension for instant suggestions while browsing books
* Expand dataset to include non-English books and emotional tagging
* Add community feedback loops for better recommendations over time

Needed:
* Partnerships with book platforms or publishers
* More labeled emotional data from book reviews
* UI/UX help for engaging user experience

## Acknowledgments

* [UCSD Goodreads Dataset](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home)
* [Image: Books falling into open book by Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Books_Falling_into_Open_Book.jpg) / [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)
* Inspired by the joy of discovering a good book, and the desire to improve it with AI
