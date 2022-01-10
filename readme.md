# Snippets for Psychophyiscal data analyses

Here are some snippets that I often use in my psychophyiscal data analyses.

## Snippets for RStudio

RStudio supports snippets. You can customize RStudio snippets via:

`Preference - Code - Snippets (Enable code snippets)`

You can copy my snippets `rstudio_snippets.txt` and modify your snippets in the pop-up window. 

## Snipeets for Visual Studio Code

VSCode supports various types of snippets in json format. You can find correspondent language snippets via: 

`Preference - User snippets`, and a draw-down list will appear and you need to select your language before you edit it. For Python, select python.json. My snippets also store in the same name here. 

## Usage

When you type part of snippet keywords, the snippet will be pop-up, select the right snippet, press `enter` to unfold the snippet. If the snippet has additional parameters, you can modify them sequentially one by one by press tab key `->|`.

# Types of snippets

## VSCode Python `python.json`

| Snippet | Content |
| ------- | ------- |
| imp, libs  | Import key packages for data analysis |
| csv  | Read csv file |
| rta  | Calculate mean accuracy per participant in reaction time paradigm |
| rtm  | Calculate mean RTs for valid trials per condition |
| msd  | Calculate means and SDs for a given condition |
| pa, pganova | Repeated-measures ANOVA via pingouin |
| pp, pgpair | Pairwise t-test via pingouin |
| pretrial | add pretrial condition in one column |
| pw, pivotwide | spread table wide on one column |
| psyfun | estimate psychometric functions via quickpsy |
| psyplot | plot multiple psychometric curves together |

## RStudio `rstudio_snippets`

| Snippet | Content |
| ------- | ------- |
| libs | import key libraries |
| rtm  | calculate mean RTs in RT paradigm |
| rta  | calculate accuracy in RT paradigm |
| mergeCSV | merge raw experimental csv files |
| killtw | kill-the-twin process for SAT correction in the RT paradigm |
| rmanova | rm-ANOVA via ezANOVA |
| bfanova | Bayes ANOVA |
| pairttest | follow-up paired t-test with p-correction |
| psyfun | estimate psychometric functions via quickpsy |


