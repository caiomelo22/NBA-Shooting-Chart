# NBA Shooting Chart
Displays a shooting chart for a given NBA player in a season.

# Description
Given the following variables, we get the shot information from the ShotChartDetail endpoint in the NBA API. With this data, we plot those shots in a drawing of a basketball court, displaying either the distribution or the volume of the shots in a given window of dates.

```
season = '2022-23' # Keep this format
start_date = datetime.datetime.strptime('2023-03-01', '%Y-%m-%d') # YYYY-MM-DD format
end_date = datetime.datetime.strptime('2023-03-25', '%Y-%m-%d') # YYYY-MM-DD format
team_abbr = 'PHI' # Choose one of the teams from the list in the cell above
player_name = 'Joel Embiid' # Choose a player from the selected team
season_type = 'Regular Season' # ^(Regular Season)|(Pre Season)|(Playoffs)|(All Star)$
chart_type = 'Distribution' # 'Volume' or 'Distribution'
```

# Example
Using the variables set in the section above, we get the following charts for "Distribution" and "Volume", respectively:

![image](https://user-images.githubusercontent.com/49076270/227799823-ed759a8b-085b-45d9-b9ba-37f12ca54721.png)

![image](https://user-images.githubusercontent.com/49076270/227799807-d1fe6512-a8a2-4d91-8e98-61cf126f3380.png)
