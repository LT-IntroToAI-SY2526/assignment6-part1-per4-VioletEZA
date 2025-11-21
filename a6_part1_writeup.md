# Assignment 6 Part 1 - Writeup

**Name:** Emma Adan  
**Date:** 11/21/2025

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

R² score tells me basically how the model is like close to the actual data that it was given. So if it's closer to 1 then that's saying that the model is close to 100% perfection and that it's the main proportional impact while if it's closer to 0 then it's the opposite.

---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

I actually don't reall remember but with some help from AI I think that it's basically just how close the predictions are to actual values by averaging the errors and squaring it to make it positive and makes large errors heavily penalized.



---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

I would trust it with 10 hours because our largest data for hours was 9.6 however I wouldn't fully expect it to be completely correct because it is still guessing. You get estimated data that may not be completely right.



---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

It's weak (large variety within the data points), linear(they all kind of go along a line), and positive(goes up and to the right)



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

1. Stress
2. Hours of sleep
3. Missed meals


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

We split our data to get the most accurate information from how the model will maybe act with different data so it's not just learning some things but a larger majority.



---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

I feel like I was a bit confused between the whole split for testing and training data but now I feel like I kind of understand it more compared to before.



---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** Miles Driven
- **Target (Y):** Gas Paid
- **Why this relationship might be linear:**

Might be linear because if you drive more then you have to pay for more gas.



---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
