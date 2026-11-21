# DAA Assignment 3 – Interactive Divide-and-Conquer Lab

An interactive website for **Design and Analysis of Algorithms – Assignment 3 (CO3)**.
Each question has a short explanation, its recurrence, and a live experiment that
reports exact operation counts next to the theoretical prediction.

| Section | Topic | What you can run |
|---|---|---|
| Q1 | Max/Min and Binary Search | Comparison counts vs 3n/2 − 2 and ⌊log₂ n⌋ + 1 |
| Q2 | Quick Sort vs Merge Sort | Partition sizes, recursion depth, comparisons |
| Q3 | Karatsuba | Crossover versus overhead slider |
| Q4 | Strassen | Operation counts, cutoff, padding cost |
| Q5 | Closest Pair | Brute force vs D&C distance calculations |
| Q6 | Median of Medians, Meet-in-the-Middle | Selection comparisons, 2^n vs 2·2^(n/2) |
| Q7 | Design challenge | Six-stage checklist |

## Run locally
No build step. Open `index.html` in a browser.

## Deploy with GitHub Pages
1. Push this folder to a new GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site appears at `https://<your-username>.github.io/<repo-name>/`.

## Authors
- Student A: Keerthana S - 192471047
- Student B: K.Dhanaswini - 192421326

## Notes
Counts are exact for the randomly generated inputs. Timing is intentionally not measured in the
browser; run timed trials in your own implementation for the report.
