# Player2Vec

## Overview

**Player2Vec** is an extension of the previous NBA player tracking project, aimed at enhancing player tracking and analysis by integrating learnable player embeddings into the tracking engine. The goal is to build upon the pre-trained Transformer encoder model from previous work, **[TrackingMAE](https://github.com/jacksonlewis87/TrackingMAE)**, and create embeddings that capture rich, meaningful representations of individual players' behaviors and characteristics.

By attaching these embeddings to our player tracking engine, **Player2Vec** seeks to improve various downstream tasks such as player similarity analysis, performance prediction, and game strategy optimization.

## Key Features

- **Learnable Player Embeddings**: Integrates embeddings that are learned from the pre-trained Transformer model, capturing nuanced player information.
- **Enhanced Tracking Engine**: Builds on the existing player tracking data to provide more insightful analysis and predictions.
- **Flexible Architecture**: Designed to be extensible for future enhancements and additional analytics tasks.

## Model Architecture

**Player2Vec** extends the Transformer encoder model with a learnable embedding layer for each player. The architecture consists of:

1. **Pre-trained Transformer Encoder**: Utilizes the transformer model pretrained on NBA tracking data to understand player movements and interactions.
2. **Player Embeddings**: Adds an embedding layer that learns to represent individual players in a continuous vector space.
3. **Enhanced Tracking Engine**: Combines embeddings with tracking data to improve analysis and predictions.
