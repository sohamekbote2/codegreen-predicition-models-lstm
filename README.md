# Project-Code-Green-LSTM-Time-Series-Forecasting

## Overview

This project focuses on time series forecasting of the percentage of renewable energy using Bidirectional Long Short-Term Memory (LSTM) models implemented in Python with TensorFlow. The forecasting model is customized for multiple countries, with each country having different sequence lengths, scaling techniques, and hyperparameters to optimize the forecasting results.

## Introduction

Renewable energy plays a crucial role in our efforts to mitigate climate change. Accurate forecasting of renewable energy percentages can aid in optimizing high-energy computations during optimal timeframes. In this project, we use Bidirectional LSTM models to forecast renewable energy percentages for multiple countries.

## Countries

The project provides forecasting models for the following countries, each with specific settings and hyperparameters:

1. Sweden
    - Sequence Length: 24
    - Scaling Technique: Standard Scaling
    - Model: Bidirectional LSTM

2. Spain
    - Sequence Length: 24
    - Scaling Technique: MinMax Scaling
    - Model: LSTM

3. Estonia
    - Sequence Length: 60
    - Scaling Technique: Standard Scaling
    - Model:  Bidirectional LSTM

4. Bulgaria
    - Sequence Length: 24
    - Scaling Technique: MinMax Scaling
    - Model:  Bidirectional LSTM

5. Belgium
    - Sequence Length: 60
    - Scaling Technique: Standard Scaling
    - Model :  Bidirectional LSTM

## Project Structure

The project is organized as follows:

- `Datasets/`: Contains datasets for each country.
- `Model_Codes/`: Includes model codes for each country.
- `Saved_Models/`: Trained models in h5 format.

## Prerequisites

Before getting started, ensure you have the following prerequisites:

- Python
- TensorFlow
- Jupyter Notebook (for running notebooks)

## Setup and Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/sohamekbote2/codegreen-predicition-models-lstm.git


