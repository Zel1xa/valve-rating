### Roster Details<br />
Team Name: Into the Breach<br />
Roster: BOROS, juanflatroo, Keoz, sinnopsyy, smooya<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  739.8<br />
<br />
Final Rank Value (739.8) = Starting Rank Value (636.2) + Head To Head Adjustments (103.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 636.2
- 400 + ( ( 0.115 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 636.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |        8 | 2024-08-04 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |    -2.64 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|           10 |       48 | 2024-08-03 | 9INE          | L   | 1.000      | -            | -                | -                | -         |    -8.36 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            9 |       81 | 2024-08-02 | 9INE          | L   | 1.000      | -            | -                | -                | -         |    -8.59 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            8 |      110 | 2024-08-01 | GUN5          | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    20.82 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            7 |      169 | 2024-07-31 | 1WIN          | L   | 1.000      | -            | -                | -                | -         |    -6.50 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            6 |      253 | 2024-07-29 | Passion UA    | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    27.90 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            5 |      294 | 2024-07-27 | Monte         | L   | 1.000      | -            | -                | -                | -         |    -3.45 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            4 |      360 | 2024-07-25 | Permitta      | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    23.59 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            3 |      466 | 2024-07-22 | INFINITE      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |    11.79 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            2 |      609 | 2024-07-18 | Preasy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.224 (0.032)    | 0 (0.000) |    20.72 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |
|            1 |      695 | 2024-07-17 | TSM           | W   | 1.000      | 0.143        | 0.040 (0.006)    | 0.394 (0.056)    | 0 (0.000) |    28.41 | BOROS, juanflatroo, Keoz, sinnopsyy, smooya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
