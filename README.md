# Classifying FIFA Players with Decision Trees

This project uses a decision tree classifier in R to predict a FIFA player’s position group
(Forward / Midfielder / Defender) based on in-game attributes.

## Key idea
- Use FIFA attributes (pace, shooting, passing, dribbling, defending, physic, height, weight)
- Train a decision tree model to classify player position groups
- Evaluate performance using a train/test split and confusion matrix

## Files
- `Enok-Bergh-Classification-Project.Rmd` – full report (text + code)
- `FIFA 15-21.xlsx` – dataset (source: Kaggle)
- (optional) rendered outputs (HTML/PDF if included)

## How to run
Open the `.Rmd` file in RStudio and click **Knit**, or run:

```r
rmarkdown::render("Enok-Bergh-Classification-Project.Rmd")
