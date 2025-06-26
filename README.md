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
1. match_no – Unique number identifying each match
2. date – Date of the match
3.	stage – Stage of the tournament (e.g., League, Playoffs)
4.	venue – Stadium where the match was played
5.	innings – Innings number (1 or 2)
6. over – Over number within an innings
7.	batting_team – Team currently batting
8.	bowling_team – Team currently bowling
9.	striker – Batsman facing the delivery
10.	bowler – Bowler delivering the ball
11.	fielder – Fielder involved in dismissal (if any)
12.	player_dismissed – Player who got out
13.	wicket_type – Type of dismissal (e.g., caught, bowled)
From matches.csv:
1.	match_id – Unique number identifying each match
2.	date – Date of the match
3.	venue – Stadium where the match was played
4.	team1 – First team in the match
5.	team2 – Second team in the match
6.	stage – Stage of the tournament
7.	toss_winner – Team that won the toss
8.	toss_decision – Decision made after the toss (bat or bowl)
9.	match_result – Result status of the match (completed, tie, etc.)
10.	match_winner – Team that won the match
11.	player_of_the_match – Awarded best player of the match
12.	top_scorer – Highest run-scorer in the match
13.	best_bowling – Player with the best bowling performance
14.	best_bowling_figure – Bowling stats (e.g., 3–29)

Measures:
From deliveries.csv:
1.	runs_of_bat – Runs scored from the bat
2.	extras – Extra runs (wides, no-balls, byes, etc.)
3.	wide – Wide ball indicator
4.	legbyes – Leg byes scored
5.	byes – Byes scored
6.	noballs – No-balls bowled
From matches.csv:
1.	first_ings_score – Total score in first innings
2.	first_ings_wkts – Wickets lost in first innings
3.	second_ings_score – Total score in second innings
4.	second_ings_wkts – Wickets lost in second innings
5.	wb_runs – Winning margin by runs
6.	wb_wickets – Winning margin by wickets
7.	balls_left – Balls remaining at match end (chasing side)

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

Insights:

1.Royal Challengers Bangalore (RCB) emerged as the IPL 2025 champions.
2.A total of 25,196 runs were scored and 872 wickets were taken throughout the season.
3.Sai Sudharsan won the Orange Cap with 759 runs, making him the highest run-scorer of the season.
4.Abhishek Sharma posted the highest individual score of 127 in a single match.
5.Prasidh Krishna claimed the Purple Cap with 26 wickets, leading the bowling charts.
6.Shreyas Iyer and Krunal Pandya both earned the most Player of the Match awards (3 each), showcasing their all-round impact.
7.Winning toss didn’t guarantee match success, despite often choosing to bowl.
8.Win percentages vary significantly across venues, with some stadiums proving to be more favorable than others.
9.Naman Dhir has the highest strike rate of 233.33 in Power Play, making him the most explosive batter in the power play.
10.Jaiswal leads the power hitting chart with 22 sixes in Power Play itself, showing his dominance at the top.
11.The average strike rate during powerplay is 146.0, showing a healthy scoring rate.Highest peak appears around overs 3 to 5 .
12.Trent Boult leads with 8 wickets in Power Play, proving his impact with the new ball.
13.Bhuvneshwar Kumar follows with 7 wickets, maintaining his reputation as a power play specialist.
14.39.09% dot ball rate in Power Play indicates effective bowling and pressure created early on.
15.Wickets vs. Economy Plot shows Power Play bowlers who took wickets generally maintained lower economy rates.
16.Shepherd dominates with a strike rate of 300, the highest in death overs.
17.Pooran smashed the most sixes — 40 in this phase, making him the cleanest striker late in the innings.
18.The average strike rate peak is observed in overs 18 and 19.
19.Pathirana is the top performer in dot balls with 28 dot balls, an exceptional stat in the death overs.
20.Most bowlers with 1 wicket have economy ranging from 8 to 12, but a few outliers go beyond 15—indicating expensive but wicket-taking spells.

Social Media Post:
LinkedIn Post 
Link: https://www.linkedin.com/posts/nehal-jain-1694b031b_dataanalytics-tableau-sportsanalytics-activity-7340676023220391938-iOWI?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFENm-EBx7j_8sBOAmJ57S3iCgyufl4zXz0 

 
