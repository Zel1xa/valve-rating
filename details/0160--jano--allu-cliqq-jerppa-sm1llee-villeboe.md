### Roster Details<br />
Team Name: JANO<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  690.1<br />
<br />
Final Rank Value (690.1) = Starting Rank Value (689.4) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.259[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.4
- 400 + ( ( 0.141 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 689.4


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
|           16 |     1475 | 2024-06-02 | FAVBET            | L   | 0.800      | -            | -                | -                | -         |    -9.29 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           15 |     1579 | 2024-05-29 | Zero Tenacity     | L   | 0.775      | -            | -                | -                | -         |    -2.33 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           14 |     2454 | 2024-04-27 | Sashi             | L   | 0.561      | -            | -                | -                | -         |    -1.15 | allu, doto, Jerppa, juho, Sm1llee      |
|           13 |     2635 | 2024-04-20 | Sangal            | L   | 0.512      | -            | -                | -                | -         |    -1.39 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     2668 | 2024-04-19 | NOM               | W   | 0.507      | 0.143        | 0.000 (0.000)    | 0.110 (0.008)    | 0 (0.000) |     4.88 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     2748 | 2024-04-17 | Sampi             | W   | 0.496      | 0.143        | 0.028 (0.002)    | 1.000 (0.071)    | 0 (0.000) |    12.14 | allu, doto, Jerppa, juho, Sm1llee      |
|           10 |     2775 | 2024-04-17 | RUBY              | L   | 0.493      | -            | -                | -                | -         |    -3.01 | allu, doto, Jerppa, juho, Sm1llee      |
|            9 |     2780 | 2024-04-17 | MOUZ NXT          | L   | 0.492      | -            | -                | -                | -         |    -1.74 | allu, doto, Jerppa, juho, Sm1llee      |
|            8 |     2863 | 2024-04-12 | Zero Tenacity     | W   | 0.459      | 0.371        | 0.139 (0.024)    | 1.000 (0.170)    | 0 (0.000) |    12.89 | allu, doto, Jerppa, juho, Sm1llee      |
|            7 |     3029 | 2024-04-08 | Permitta          | L   | 0.432      | -            | -                | -                | -         |    -2.57 | allu, doto, Jerppa, juho, Sm1llee      |
|            6 |     3062 | 2024-04-06 | Johnny Speeds     | L   | 0.420      | -            | -                | -                | -         |    -0.41 | allu, doto, Jerppa, juho, Sm1llee      |
|            5 |     3128 | 2024-04-04 | Gaimin Gladiators | L   | 0.406      | -            | -                | -                | -         |    -1.69 | allu, doto, Jerppa, juho, Sm1llee      |
|            4 |     3614 | 2024-03-12 | kONO              | L   | 0.254      | -            | -                | -                | -         |    -2.66 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            3 |     3704 | 2024-03-08 | INGLORIOUS        | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.25 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            2 |     3819 | 2024-03-04 | Endpoint          | L   | 0.201      | -            | -                | -                | -         |    -4.81 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            1 |     3905 | 2024-02-29 | Sashi             | L   | 0.173      | -            | -                | -                | -         |    -0.37 | allu, doto, Jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($446.75)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
