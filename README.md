IPL 2025 Analysis

Introduction to Tableau:
Tableau is a leading data visualization tool that helps users turn raw data into clear, interactive, and shareable dashboards. With its drag-and-drop interface and real-time analytics, it simplifies data exploration and storytelling. Tableau empowers analysts to uncover trends, gain insights, and support faster, more informed decisions across all levels of business. Report was created using Tableau version 2025.1.2

About Data: 
The data used in this project was sourced from Kaggle and falls under the sports analytics domain, specifically focused on cricket. It simulates the IPL 2025 season and includes two CSV files:
•	matches.csv (74 rows × 22 columns) containing match-level details such as scores, results, and player performances, and
•	deliveries.csv (17,183 rows × 19 columns) capturing ball-by-ball information including runs, wickets, and player actions.
Dataset Link: https://www.kaggle.com/datasets/krishd123/ipl-2025-records 

Dimensions:
From deliveries.csv:
•	match_no – Unique number identifying each match
•	date – Date of the match
•	stage – Stage of the tournament (e.g., League, Playoffs)
•	venue – Stadium where the match was played
•	innings – Innings number (1 or 2)
•	over – Over number within an innings
•	batting_team – Team currently batting
•	bowling_team – Team currently bowling
•	striker – Batsman facing the delivery
•	bowler – Bowler delivering the ball
•	fielder – Fielder involved in dismissal (if any)
•	player_dismissed – Player who got out
•	wicket_type – Type of dismissal (e.g., caught, bowled)
From matches.csv:
•	match_id – Unique number identifying each match
•	date – Date of the match
•	venue – Stadium where the match was played
•	team1 – First team in the match
•	team2 – Second team in the match
•	stage – Stage of the tournament
•	toss_winner – Team that won the toss
•	toss_decision – Decision made after the toss (bat or bowl)
•	match_result – Result status of the match (completed, tie, etc.)
•	match_winner – Team that won the match
•	player_of_the_match – Awarded best player of the match
•	top_scorer – Highest run-scorer in the match
•	best_bowling – Player with the best bowling performance
•	best_bowling_figure – Bowling stats (e.g., 3–29)

Measures:
From deliveries.csv:
•	runs_of_bat – Runs scored from the bat
•	extras – Extra runs (wides, no-balls, byes, etc.)
•	wide – Wide ball indicator
•	legbyes – Leg byes scored
•	byes – Byes scored
•	noballs – No-balls bowled
From matches.csv:
•	first_ings_score – Total score in first innings
•	first_ings_wkts – Wickets lost in first innings
•	second_ings_score – Total score in second innings
•	second_ings_wkts – Wickets lost in second innings
•	wb_runs – Winning margin by runs
•	wb_wickets – Winning margin by wickets
•	balls_left – Balls remaining at match end (chasing side)

Problem Statements:
1. Summarize overall tournament stats
2. Showcase Top batsmen and bowlers by performance.
3. Display points table to compare team-wise success.
4. Summarize statistics of particular team .
5. Highlight top performers from the team (Player of the Match).
6. Understand dismissal patterns using wicket type breakdown for the team.
7. Identify top run scorers and wicket takers within the selected team.
8. Track individual player performance across matches (e.g., Abdul Samad’s match-wise runs).
9. Analyse wicket type distribution for a selected player to understand bowling vulnerabilities.
10. Evaluate boundary-hitting ability of players — key power hitters in the team.
11. Assess fielding contributions by identifying top fielders in the tournament.
12. Review venue-wise batting performance of team players:
13. Identify the most attacking batters based on strike rate during overs 1–6.
14. Determine the most effective bowlers in early overs based on wickets taken.
15. Track total runs, wickets, economy rate, dot ball %, and 6s during the powerplay.
16. Analyse strike rate trends across each powerplay over.
17. Study the relationship between wickets taken and economy rate.
18. Identify top finishers based on strike rate and six-hitting ability.
19. Highlight the most successful death bowlers by wickets and dot balls.
20. Evaluate team-wide performance metrics like run rate, economy, dot ball %, and wickets.
21. Understand over-wise strike rate fluctuations from overs 17 to 20.
22. Explore wicket-to-economy relationships through scatter analysis.
 
