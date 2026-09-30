# BUS-G 492 · Causal decision cases

Seven business cases. In each one you make a real decision with data, see what happens when it's put into practice, and then get a second chance.

| # | Case | Your decision | Open in Colab |
|---|---|---|---|
| 1 | Do win-back discounts work? | Which customers get a discount | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case1_rct_retention/case1_part1.ipynb) |
| 2 | Is the sales bootcamp worth it? | Which reps get trained | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case2_controls_training/case2_part1.ipynb) |
| 3 | Does CareBridge reduce readmissions? | Which patients get enrolled | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case3_matching_care/case3_part1.ipynb) |
| 4 | Should we badge more sellers? | Which sellers get a Trusted badge | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case4_panel_badge/case4_part1.ipynb) |
| 5 | Replace the CEO after a bad year? | Which CEOs to replace | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case5_natural_ceo/case5_part1.ipynb) |
| 6 | Should we cut prices? | One shelf price for Q4 | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case6_iv_pricing/case6_part1.ipynb) |
| 7 | Where should the Gold tier start? | The Gold spending threshold | [Part 1](https://colab.research.google.com/github/boyoung-seo/g492-coding/blob/main/cases/case7_rdd_gold/case7_part1.ipynb) |

## How each case works

1. **Read the memo.** A manager has a decision to make. It's a business question, not a statistics question.
2. **Model it (Part 1, in class, in pairs).** Use any AI assistant and any method. Build the best model you can.
3. **Commit.** Submit your decision and the profit you predict it will earn, using the form your instructor shares.
4. **Deployment.** Your instructor runs every team's decision through what actually happens, and you see predicted vs. actual profit for every team.
5. **Part 2 (homework).** New information arrives: a Part 2 notebook and new data files appear in the case folder after class. Answer its questions before writing any code, redo the analysis, and resubmit. Round 2 is deployed at the start of the next class.

## Getting started

- Click a **Part 1** link above. Colab opens the notebook from this repo, so you can't break anything. Keep your work with **File → Save a copy in Drive**.
- The notebook loads its data from this repo automatically. If you run it on your own computer instead, keep the `data/` folder next to the notebook.
- Your AI assistant will sound confident. Your job is to decide whether it's right.

## Repository layout

```
cases/
  case1_rct_retention/
    case1_part1.ipynb      Part 1 notebook
    data/                  data for the case (Part 2 files are added after class)
  case2_controls_training/
  ...
  case7_rdd_gold/
```
