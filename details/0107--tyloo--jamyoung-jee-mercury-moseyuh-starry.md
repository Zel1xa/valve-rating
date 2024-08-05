### Roster Details<br />
Team Name: TYLOO<br />
Roster: JamYoung, Jee, Mercury, Moseyuh, Starry<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  842.8<br />
<br />
Final Rank Value (842.8) = Starting Rank Value (791.7) + Head To Head Adjustments (51.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 791.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 791.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |       16 | 2024-08-04 | Gaimin Gladiators | W   | 1.000      | 0.380        | 0.038 (0.014)    | 0.349 (0.133)    | 1 (1.000) |    20.24 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           12 |       84 | 2024-08-02 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -15.65 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           11 |      124 | 2024-08-01 | Rare Atom         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.481 (0.069)    | 0 (0.000) |    15.02 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           10 |      134 | 2024-08-01 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.237 (0.034)    | 0 (0.000) |     8.56 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            9 |      823 | 2024-07-13 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -17.87 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            8 |      825 | 2024-07-13 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.237 (0.034)    | 0 (0.000) |     7.42 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            7 |      836 | 2024-07-12 | Chinggis Warriors | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.154 (0.022)    | 0 (0.000) |    13.18 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            6 |      840 | 2024-07-12 | Alter Ego         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.079 (0.011)    | 0 (0.000) |     4.79 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            5 |     1309 | 2024-06-08 | Lynn Vision       | L   | 0.816      | -            | -                | -                | -         |    -5.70 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            4 |     1362 | 2024-06-07 | GR                | W   | 0.810      | 0.416        | 0.008 (0.003)    | 0.075 (0.025)    | 0 (0.000) |     8.19 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            3 |     1429 | 2024-06-06 | The QUBE          | W   | 0.803      | 0.416        | 0.005 (0.002)    | 0.063 (0.021)    | 0 (0.000) |     8.54 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            2 |     1486 | 2024-06-05 | Lynn Vision       | L   | 0.796      | -            | -                | -                | -         |    -5.01 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            1 |     1528 | 2024-06-04 | LYG               | W   | 0.790      | 0.416        | 0.003 (0.001)    | 0.033 (0.011)    | 0 (0.000) |     9.35 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,112.50)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
