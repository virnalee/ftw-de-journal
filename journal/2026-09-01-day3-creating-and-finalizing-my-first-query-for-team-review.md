=============================================================================
# 📓 Journal - 2026-09-01 - Day 3: Building the Mart Tables and Q1 Business Analysis
=============================================================================

## 📝 A. Today in one sentence
- 

## 💡 B. What I learned
- How to sync my fork with the original repo on GitHub, and pull those updates into my Databricks Git folder.
- How to merge the latest main branch into my own branch (virna) to keep it up to date, without affecting main itself.
- Added validation files for the Mart layer (Dim_Order, Dim_Product, Fact_OrderProducts) comparing row counts, nulls, duplicates, and referential integrity against the cleaned source tables.

## 📚 C. Terms I am still learning
1. **Viewed** - a checkbox on each file in a PR that marks it as reviewed by you; it's just for your own tracking, not required by GitHub to approve.
2. **Sync fork** - a GitHub button that updates your fork's branch with the latest commits from the original repo it was forked from.
3. **Merge branch** - pulls changes from another branch into your current branch, without changing the source branch.

## 🤔 D. What confused me
- Wasn't sure if merging main into my branch would change anything on main itself — confirmed it only updates my branch (virna), main stays untouched.

## 🎯 E. One small next step
- [x] Chose Business Question 1 (products/departments purchased most) with Sara as partner
- [x] Added sub-questions and metric/dim/col needed for Q1 to the team's shared doc
- [x] Finalized the star schema: Dim_Order, Dim_Product, Fact_OrderProducts
- [x] Wrote and tested queries end to end (clean → mart → analysis) in my test notebook
- [x] Created cleaning, mart, and business analysis .sql files in my branch (virna)
- [x] Added Mart validation files (row counts, nulls, duplicates, referential integrity vs. cleaned tables)
- [ ] Add the missing order_products_clean file to my branch
- [ ] Run all files in my branch in order (clean → mart create → mart validate → analysis) to confirm they work end to end
- [ ] Commit and push my .sql files so they show up on my branch in GitHub
- [ ] Create a Pull Request to main (not sure if I'll get to this today)
- [ ] Carried over: Start building my own beginner-friendly Git/GitHub dictionary

## ✅ F. Git checkpoint
- [x] I created or updated a file
- [ ] I wrote a commit
- [ ] I pushed my changes

## 🧭 G. Decisions or assumptions
- Chose Q1 with Sara (who's already ahead and largely done on her end) because it fits the star schema already built, and it lets us show a real data issue found while checking the data.
- Kept Dim_Order and Dim_Product as 2 dimensions instead of 4, folding aisle and department directly into Dim_Product.

## 📸 H. Evidence from today
- Hit a "Databricks is experiencing heavy load" notice while running files — operations took longer than usual.

## 🪞 I. Reflection
- What felt easy today: 
- What felt difficult today: 
- What I want to understand better next time: 

## 💛 J. Pat on my own shoulder :3

=============================================================================

💛 

=============================================================================