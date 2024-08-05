### Roster Details<br />
Team Name: JANO<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  671.2<br />
<br />
Final Rank Value (671.2) = Starting Rank Value (680.4) + Head To Head Adjustments (-9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.4
- 400 + ( ( 0.137 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 680.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1589 | 2024-06-02 | FAVBET            | L   | 0.773      | -            | -                | -                | -         |    -8.56 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           14 |     1693 | 2024-05-29 | Zero Tenacity     | L   | 0.748      | -            | -                | -                | -         |    -1.91 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           13 |     2526 | 2024-04-27 | Sashi             | L   | 0.534      | -            | -                | -                | -         |    -1.02 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     2701 | 2024-04-20 | Sangal            | L   | 0.485      | -            | -                | -                | -         |    -1.12 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     2733 | 2024-04-19 | NOM               | W   | 0.480      | 0.143        | 0.000 (0.000)    | 0.110 (0.008)    | 0 (0.000) |     4.98 | allu, doto, Jerppa, juho, Sm1llee      |
|           10 |     2838 | 2024-04-17 | RUBY              | L   | 0.466      | -            | -                | -                | -         |    -2.98 | allu, doto, Jerppa, juho, Sm1llee      |
|            9 |     2843 | 2024-04-17 | MOUZ NXT          | L   | 0.465      | -            | -                | -                | -         |    -1.69 | allu, doto, Jerppa, juho, Sm1llee      |
|            8 |     2924 | 2024-04-12 | Zero Tenacity     | W   | 0.432      | 0.371        | 0.137 (0.022)    | 1.000 (0.160)    | 0 (0.000) |    12.23 | allu, doto, Jerppa, juho, Sm1llee      |
|            7 |     3090 | 2024-04-08 | Permitta          | L   | 0.405      | -            | -                | -                | -         |    -2.25 | allu, doto, Jerppa, juho, Sm1llee      |
|            6 |     3123 | 2024-04-06 | Johnny Speeds     | L   | 0.393      | -            | -                | -                | -         |    -0.37 | allu, doto, Jerppa, juho, Sm1llee      |
|            5 |     3188 | 2024-04-04 | Gaimin Gladiators | L   | 0.379      | -            | -                | -                | -         |    -1.71 | allu, doto, Jerppa, juho, Sm1llee      |
|            4 |     3657 | 2024-03-12 | kONO              | L   | 0.227      | -            | -                | -                | -         |    -2.38 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            3 |     3746 | 2024-03-08 | INGLORIOUS        | W   | 0.199      | 0.143        | 0.000 (0.000)    | 0.015 (0.000)    | 0 (0.000) |     2.03 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            2 |     3856 | 2024-03-04 | Endpoint          | L   | 0.174      | -            | -                | -                | -         |    -4.13 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            1 |     3941 | 2024-02-29 | Sashi             | L   | 0.146      | -            | -                | -                | -         |    -0.31 | allu, doto, Jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($425.33)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
