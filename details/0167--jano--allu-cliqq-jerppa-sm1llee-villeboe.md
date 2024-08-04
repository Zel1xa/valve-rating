### Roster Details<br />
Team Name: JANO<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
<br />
Final Rank Value:  671.1<br />
<br />
Final Rank Value (671.1) = Starting Rank Value (680.6) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.6
- 400 + ( ( 0.137 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 680.6


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
|           15 |     1536 | 2024-06-02 | FAVBET            | L   | 0.784      | -            | -                | -                | -         |    -8.71 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           14 |     1640 | 2024-05-29 | Zero Tenacity     | L   | 0.759      | -            | -                | -                | -         |    -1.93 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           13 |     2473 | 2024-04-27 | Sashi             | L   | 0.545      | -            | -                | -                | -         |    -1.05 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     2647 | 2024-04-20 | Sangal            | L   | 0.496      | -            | -                | -                | -         |    -1.18 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     2679 | 2024-04-19 | NOM               | W   | 0.491      | 0.143        | 0.000 (0.000)    | 0.110 (0.008)    | 0 (0.000) |     5.08 | allu, doto, Jerppa, juho, Sm1llee      |
|           10 |     2784 | 2024-04-17 | RUBY              | L   | 0.476      | -            | -                | -                | -         |    -2.97 | allu, doto, Jerppa, juho, Sm1llee      |
|            9 |     2789 | 2024-04-17 | MOUZ NXT          | L   | 0.476      | -            | -                | -                | -         |    -1.75 | allu, doto, Jerppa, juho, Sm1llee      |
|            8 |     2870 | 2024-04-12 | Zero Tenacity     | W   | 0.443      | 0.371        | 0.137 (0.022)    | 1.000 (0.164)    | 0 (0.000) |    12.50 | allu, doto, Jerppa, juho, Sm1llee      |
|            7 |     3036 | 2024-04-08 | Permitta          | L   | 0.416      | -            | -                | -                | -         |    -2.31 | allu, doto, Jerppa, juho, Sm1llee      |
|            6 |     3069 | 2024-04-06 | Johnny Speeds     | L   | 0.404      | -            | -                | -                | -         |    -0.40 | allu, doto, Jerppa, juho, Sm1llee      |
|            5 |     3134 | 2024-04-04 | Gaimin Gladiators | L   | 0.390      | -            | -                | -                | -         |    -1.71 | allu, doto, Jerppa, juho, Sm1llee      |
|            4 |     3602 | 2024-03-12 | kONO              | L   | 0.237      | -            | -                | -                | -         |    -2.50 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            3 |     3691 | 2024-03-08 | INGLORIOUS        | W   | 0.210      | 0.143        | 0.000 (0.000)    | 0.016 (0.000)    | 0 (0.000) |     2.12 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            2 |     3801 | 2024-03-04 | Endpoint          | L   | 0.184      | -            | -                | -                | -         |    -4.38 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            1 |     3886 | 2024-02-29 | Sashi             | L   | 0.156      | -            | -                | -                | -         |    -0.34 | allu, doto, Jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($433.72)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
