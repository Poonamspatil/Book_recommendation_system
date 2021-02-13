# Book Recommender System
### Memory-based and model-based collaborative filtering

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Installation](#installation)
* [Description](#description)

## Introduction

Analyzing user behaviour and providing recommendation of what user might like without them needing to search is prevalent in many consumer based businesses like social-media, news, books, e-commerce, marketing etc. There are context-based filtering, collaborative filtering and hybrid techniques to provide accurate recommendations. Context-based filtering uses only user or item or both data to recommend new items. Whereas, collaborative filtering technique makes use of community data to make recommendation, which means interaction data of other users is used to make new recommendations. This notebook demonstrate different collaborative filtering techques for book recommendation.

## Technologies
Project is created with:
* Python : 3.7

## Installation
Install surprise library:
http://surpriselib.com/

## Description
 The notebook illustrate below methods of collaborative filtering to make book recommendations:
1. Memory-based collaborative filtering
	a. User-based (using Euclidean distance measure)
	b. Item-based (using Cosine similarity distance measure)
2. Model-based collaborative filtering
	a. Matrix factorization
	b. SVD++
