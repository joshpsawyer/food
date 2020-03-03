# Pastry & Cakes

- [Carrot Cake](carrot_cake.md)

## Oatmeal Raisin Bread

```{r echo=FALSE, message=FALSE, warning=FALSE}
oatmeal <- read_csv(
  here::here("recipe_excel","oatmeal_raisin_bread.csv"),
  col_names = TRUE
  )

knitr::kable(
  oatmeal, booktabs = TRUE,
  caption = 'Ingredients for Oatmeal Raising Bread'
) %>% kable_styling(bootstrap_options = "striped", full_width = F)
```

1. Mix all dry ingredients
2. Mix all wet ingredients
2. let stand 20 minutes before baking
2. 350 F for 45 minutes

## Every Day Streusel
### Description
This is a recipe used commonly at The Bakery.

### Ingredients

|Ingredient|Baker's %|Weight|
|---|---|---|
| Flour  | 100%  | 3 lbs |
| Sugar, White  | 33.33% | 1 lb |
| Sugar, Brown  | 50% | 1 lb 8 oz|
| Butter |   | 2 lbs 8oz  |
| Salt  |   | 1 1/2 tsp  |
| Cinnamon | | 1 tablespoon |

### Instructions

1. Mix all dry ingredients.
2. Cut butter into small pieces and toss with dry ingredients.
3. Beat either by hand or in mixing bowl until clumps together into the size you'd like.
4. Use to top baked goods prior to baking.
