## 🚀 Feature Engineering Task

Your task is to create new features for your analysis and upload your completed Python file 📂

As before, a good way to quickly learn how to effectively feature engineer is to build a framework to follow. Below is an example of how you could attempt this task:

---

### ❓ Questions to guide your process

**1️⃣ First - can we remove any of the columns in the datasets?**  
There will almost always be columns in a dataset that can be removed, perhaps because they are not relevant to the analysis, or they only have 1 unique value.

**2️⃣ Second - can we expand the datasets and use existing columns to create new features?**  
For example, if you have “date” columns, in their raw form they are not so useful. But if you were to extract month, day of month, day of year and year into individual columns, these could be more useful.

**3️⃣ Third - can we combine some columns together to create “better” columns?**  
How do we define a “better” column and how do we know which columns to combine?  
We’re trying to accurately predict churn - so a “better” column could be a column that improves the accuracy of the model.  
And which columns to combine? This can sometimes be a matter of experimenting until you find something useful, or you may notice that 2 columns share very similar information so you want to combine them.

**4️⃣ Finally - can we combine these datasets and if so, how?**  
To combine datasets, you need a column that features in both datasets that share the same values to join them on.  
At this stage, your data could look vastly different, or may have just some subtle differences to how it was before.

---

🧠 You will be done with this task when you’re happy with the new set of features that you’ve created and you think you’re ready to build a predictive model to see which of these features are useful for predicting churn.

📌 Don’t forget to upload your Python file when you’re done!
