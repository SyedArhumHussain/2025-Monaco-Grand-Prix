# 2025-Monaco-Grand-Prix

The 2025 Formula 1 Monaco Grand Prix, held from May 23 to May 25 at the iconic Circuit de Monaco, was a landmark event in the season. Lando Norris achieved his first-ever victory in Monaco, leading from pole position and holding off Charles Leclerc to secure the win.

Race Highlights Winner: Lando Norris (McLaren Mercedes) clinched victory with a time of 1:40:33.843.

Podium Finishers:

2nd: Charles Leclerc (Ferrari), finishing +3.131s behind.

3rd: Oscar Piastri (McLaren Mercedes), trailing by +3.658s.

Top 10 Results:

1.Lando Norris (McLaren Mercedes)

2.Charles Leclerc (Ferrari)

3.Oscar Piastri (McLaren Mercedes)

4.Max Verstappen (Red Bull Racing Honda RBPT)

5.Lewis Hamilton (Ferrari)

6.Isack Hadjar (Racing Bulls Honda RBPT)

7.Esteban Ocon (Haas Ferrari)

8.Liam Lawson (Racing Bulls Honda RBPT)

9.Alexander Albon (Williams Mercedes)

10.Carlos Sainz (Williams Mercedes)

1.Import Libraries Imported necessary libraries for data analysis, visualization, and machine learning.

2. Load Data loaded race and sprint qualifying CSV files into DataFrames for analysis.

3. Initial Exploration Displayed the top rows and structure of the datasets to understand their content.

4. Clean Data Handled missing values and removed rows with critical nulls like missing driver names.

5. Driver Leaderboard Calculated and visualized the top 10 drivers based on total points.

6. Team Performance Grouped and visualized total team points to identify top-performing constructors.

7. Position Gain/Loss Analysis Computed average position changes to identify drivers who gain or lose most places in races.

8. Fastest Lap Analysis Counted and visualized which drivers set the fastest laps most often.

9. Re-import for ML Setup Reloaded data and imported libraries to prepare for machine learning tasks.

10. Encode Categorical Features Used label encoding to convert driver, team, and track names to numeric form.

11. Feature Engineering Created new features like position change, driver consistency, and gain indicators.

12. Train-Test Split and Scaling Split the data and scaled features for better ML model performance.

13. Train Random Forest Model Trained a Random Forest Classifier to predict whether a driver improves race position.

14. Evaluate the Model Evaluated the model using a classification report and confusion matrix.

15. Interactive Visualization Visualized driver performance across tracks using a Plotly line chart.

16. Feature Importance Identified which features most influenced the model’s predictions.

17. Clustering Drivers Clustered drivers based on position change and consistency to find performance patterns.

18. Save Model Saved and reloaded the trained model and scaler using joblib for reuse.

19. Image Display (Winner Pics) Display images of race results and winners using image URLs and local paths.**

![F1 Results 4](https://github.com/user-attachments/assets/c653b8f5-c689-40d3-b1b6-4d9bb9e03b5e)
![F1 Results 2](https://github.com/user-attachments/assets/d348a689-d42e-41af-b3c7-71a9602575dd)

