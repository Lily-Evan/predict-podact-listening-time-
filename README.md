# predict-podact-listening-time-
📝 Competition Summary
This competition is part of the 2025 Kaggle Playground Series (Season 5, Episode 4). The task was to predict the listening time (in minutes) of podcast episodes using a synthetic tabular dataset designed to resemble real-world behavior.

Start Date: April 1, 2025

End Date: April 30, 2025

Evaluation Metric: Root Mean Squared Error (RMSE)

Submission Format:

python-repl
Αντιγραφή
Επεξεργασία
id,Listening_Time_minutes
750000,45.437
750001,45.437
...
💡 My Approach & Submissions
🔹 Before the Competition
I made one early attempt before the competition officially started (in March). This was mostly to explore the dataset and test a basic model. The result was:

Public Score: 52.92593

It was a very simple approach without much tuning or preprocessing.

🔸 During the Competition
I created a version called "V1 ", which became my best official submission:

Public Score: 12.76847

This version included a better preprocessing pipeline and a LightGBM model. I also documented this version directly in the notebook README.

🔻 After the Deadline
After the competition ended, I continued experimenting and submitted two additional versions. These were not ranked but helped me evaluate improvements:

Best Public Score (post-deadline): 11.64392

Private Score: 11.56906

These versions improved due to better feature handling and some hyperparameter tuning.

