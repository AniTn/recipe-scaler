# Recipe Scaler

A Java command-line program that automatically rescales a recipe based on the desired servings.

## The Problem

When baking or cooking, there could an scarce ingredient that forces people to guess the rest of the recipe. 
There could also be times when a person wants to scale their recipe up or down, though human error can lead those
recipes to failed dishes. 

## How It Works

<img width="1676" height="858" alt=" System Diagram" src="https://github.com/user-attachments/assets/f0fedeff-cb5d-41b4-8145-c65714b4e028" />


## Tech Stack

- **Language:** Java.
- **Libraries:** Java's Scanner
- **Development tools:** Git and Bash

## Setup

```bash
git clone https://github.com/AniTn/recipe-scaler
cd recipe-scaler
javac RecipeScaler.java
```

## Usage

How to actually run the thing, with examples.

```bash
java RecipeScaler
```


Example:

Enter original recipe text:

2 cups flour//1 cup sugar//1/2 tsp salt

Enter Original Serving Size:

10

Enter Desired Serving Size:

5

--- Rescaled Recipe (Scaled to 0.5) ---
- 1 cups flour
- 1/2 cup sugar
- 1/4 tsp salt

## Roadmap

- [ ] Graphical User Interface


## Author


Annie Tran, https://github.com/AniTn
