# NBA-Shooting-Chart
Displays a shooting chart for a given NBA player in a season.

# Description
Given the following variables, we get the shot information from the ShotChartDetail endpoint in the NBA API. With this data, we plot those shots in a drawing of a basketball court, displaying either the distribution or the volume of the shots in a given window of dates.

```
season = '2021-22' # Keep this format
start_date = datetime.datetime.strptime('2022-05-14', '%Y-%m-%d') # YYYY-MM-DD format
end_date = datetime.datetime.strptime('2022-05-16', '%Y-%m-%d') # YYYY-MM-DD format
team_abbr = 'DAL' # Select one of the teams from the list in the cell above
player_name = 'Luka Doncic' # Select a player from the selected team
season_type = 'Playoffs' # ^(Regular Season)|(Pre Season)|(Playoffs)|(All Star)$
chart_type = 'Distribution' # 'Volume' or 'Distribution'
```

# Example
Using the variables set in the section above, we get the following chart:

![Luka Doncic-2021-22](https://user-images.githubusercontent.com/49076270/168707711-59a4e63c-9dcb-483d-9a43-29239b39f718.jpg)
