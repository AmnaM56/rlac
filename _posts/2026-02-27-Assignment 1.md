---
title: "Assignment 1"

categories:
  - assignments
  
tags:
  - Assignments
  - Corpora
  - R
  - Voyant Tools
---

## 1. Introduction: Violence in Harry Potter

  The Harry Potter series, by J.K Rowling, is built around
violence; duels, wars, curses and death shape both the original novels as well as the vast landscape of over a million fanfictions they inspired. While fanfiction draws from Rowling’s style, authors often reimagine tone and emotional intensity. This project asks: How does the use of explicit violent language differ between Rowling’s novels and Harry Potter fanfiction, and what does this suggest about how each text portrays conflict?

  In order to investigate this question, we analyzed two novels
by J.K Rowling (Goblet of Fire and Deathly Hallows), in comparison to three fanfiction texts. Two computational text analysis softwares were used for this analysis: Mhara conducted an analysis in Voyant tools, Amna conducted an analysis in R (Posit Cloud), and a cross-examination of the results from both software was discussed in order to gain a wider, more in-depth understanding. Using these two analysis softwares, we examined patterns in violent vocabulary across approximately one million words of text in total. We use distant reading to identify broader linguistic patterns in how violence is represented. 

## 2. Corpus Selection & Context 

  Our corpus includes two Rowling novels: Harry Potter and the
Goblet of Fire (195,773 words) and Harry Potter and the Deathly Hallows (200,119 words). In addition, the three fanfiction texts were: The Best of Fathers, by Guitérres De La Torre (207, 997 words), Harry Potter: Djinn Awakened, by Invaderdoom/Wishmaster1983 ( 107,151 words), and Dragonheart Caravan, by Witchdragon (240,337 words). 

  We selected later Rowling novels because they contain sustained
depictions of war, allowing meaningful comparison with darker fanfiction narratives. The texts are also relatively similar in length, which supports balanced comparison.

## 3. Methodology: Building a Violence Dictionary in R

<img src="{{ '/assets/images/RLAC A1 F1.png' | relative_url }}" alt="Figure 1. Violence dictionary for analysis in R (124 terms)
">

  To systematically measure violent action language, we constructed a custom ‘violence dictionary’ in R, shown
in Figure 1. This violence dictionary included terms such as “attack”, “kill”, “curse”, “blood”, “wound”, “fight”, and magical combat terms like “Avada”, “Crucio”, and “sectumsempra”. The dictionary contains 124 terms, including grammatical variations (e.g., “attack”, “attacked”, “attacking”), allowing us to systematically capture violence-related language across texts.We normalized results by measuring mean frequency per 10,000 words on R to ensure proportional comparison across texts of different lengths.

