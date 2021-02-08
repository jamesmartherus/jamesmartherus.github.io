---
title: 
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  ## Code
---

In my spare time, I enjoy building R packages. Some of them are useful, some of them... not so much. 

<img src="/man/figures/anesr.png" align="left" width=90 style="float:left; padding-right:10px" />[anesr: Easy access to ANES data in R](https://github.com/jamesmartherus/anesr)

The American National Election Studies are one of the most important sources of data for political scientists. `anesr` provides easy access to ANES data for R users. `anesr` includes tidy versions of all ANES pilot and time series studies as compact, rda objects. Once the package is installed and loaded, any dataset can be accessed using the `data()` function. `anesr` also includes documentation for some studies in tidy format. Documentation files include descriptions, coding, and marginals or summary statistics for all variables in the dataset.

<img src="/man/figures/debates.png" align="left" width=90 />[debates: Tidy presidential debate transcripts](https://github.com/jamesmartherus/debates)

Presidential debates are an important opportunity for candidates to share their platforms. `debates` provides easy access to debate transcripts from Presidential, Vice Presidential, and primary candidate debates. The current version includes Presidential and Vice-Presidential debate transcripts starting in 1960, and for most debates from the 2012, 2016, and 2020 primary elections. `debates` includes one dataset, `debate_transcripts`, as a compact rda object. Once the package is installed and loaded, the dataset can be loaded using the `data()` function.

`debate_transcripts` includes speaker-level and debate-level data. Each row in `debate_transcripts` represents one statement. Along with the text of the statement, each row includes the speaker's name and an indicator variable that identifies whether or not the speaker is a candidate (as opposed to being a moderator, an announcer, or someone asking a question). Each row also indicates the date, location, and type of debate. To suggest additional fields, please open an issue.

<img src="/man/figures/drumr.png" align="left" width=90 />[drumr: Turn R into a drum machine](https://github.com/jamesmartherus/drumr)

`drumr` allows you to play drum beats from within R. At present the package contains only two functions -- `beat()`, which plays a beat from a given `kit` and `drum`, and `tempo()`, which sets the spacing between beats.

<img src="/man/figures/nhldata.png" align="left" width=90 />[nhldata: Easy access to basic NHL data in R](https://github.com/jamesmartherus/nhldata)

`nhldata` contains three datasets provided by [Corsica Hockey](https://www.corsicahockey.com/) and [Natural Stat Trick](https://www.naturalstattrick.com/):

* skaters: For each season from 2007-2008 to 2018-2019, skaters statistics for all NHL players with at least 50 minutes of TOI (Time on Ice).
* goalies: For each season from 2007-2008 to 2018-2019, goalie statistics for all NHL goalies with at least 200 minutes of TOI (Time on Ice).
* teams: For each season from 2007-2008 to 2018-2019, team statistics for all NHL teams.

<img src="/man/figures/shotplot.png" align="left" width=90 />[shotplot: Scrape and plot NHL shot location data](https://github.com/jamesmartherus/shotplot)

`shotplot` contains functions to help easily visualize NHL shot location data. `geom_shotplot()` wraps `geom_point()` and includes a standard NHL rink as a background image. `scrape_shots()` uses the NHL API to get coordinates, shot type, shooting player, and shooting player's team from a given range of seasons.