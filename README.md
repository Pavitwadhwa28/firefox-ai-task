# Does Studying More Actually Help?

Mozilla Firefox Club - AI/ML task. Author: [Your Name], [Reg. No.]

**Question:** A school wants to tell students "more study time means better grades". Is that true, and what matters more?

**Dataset:** [UCI Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance). Main analysis uses the Math file; the Portuguese file is used for comparison.

## How to run
```
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```
Then choose Kernel -> Restart & Run All. On Google Colab, upload the two CSV files (see the first code cell).

## Files
- `analysis.ipynb` - full analysis (cleaning, 2 required charts, brownie points)
- `memo.md` - one-page memo for the school
- `data/` - `student-mat.csv`, `student-por.csv`
- `requirements.txt`

## Results in 3 lines
- Study time has only a weak positive link with the final grade (r = 0.10, explains about 1%).
- Past failures (r = -0.36) and the previous period grade G2 (r = 0.90) matter far more.
- The same pattern appears in the Portuguese file; I make no causal claim.
