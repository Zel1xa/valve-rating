### Roster Details<br />
Team Name: JANO<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  689.6<br />
<br />
Final Rank Value (689.6) = Starting Rank Value (688.9) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.259[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 688.9
- 400 + ( ( 0.140 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 688.9


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
|           16 |     1479 | 2024-06-02 | FAVBET            | L   | 0.799      | -            | -                | -                | -         |    -9.28 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           15 |     1583 | 2024-05-29 | Zero Tenacity     | L   | 0.774      | -            | -                | -                | -         |    -2.33 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           14 |     2458 | 2024-04-27 | Sashi             | L   | 0.560      | -            | -                | -                | -         |    -1.15 | allu, doto, Jerppa, juho, Sm1llee      |
|           13 |     2639 | 2024-04-20 | Sangal            | L   | 0.511      | -            | -                | -                | -         |    -1.39 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     2672 | 2024-04-19 | NOM               | W   | 0.506      | 0.143        | 0.000 (0.000)    | 0.110 (0.008)    | 0 (0.000) |     4.87 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     2752 | 2024-04-17 | Sampi             | W   | 0.495      | 0.143        | 0.028 (0.002)    | 1.000 (0.071)    | 0 (0.000) |    12.10 | allu, doto, Jerppa, juho, Sm1llee      |
|           10 |     2779 | 2024-04-17 | RUBY              | L   | 0.491      | -            | -                | -                | -         |    -3.00 | allu, doto, Jerppa, juho, Sm1llee      |
|            9 |     2784 | 2024-04-17 | MOUZ NXT          | L   | 0.491      | -            | -                | -                | -         |    -1.74 | allu, doto, Jerppa, juho, Sm1llee      |
|            8 |     2867 | 2024-04-12 | Zero Tenacity     | W   | 0.458      | 0.371        | 0.139 (0.023)    | 1.000 (0.170)    | 0 (0.000) |    12.85 | allu, doto, Jerppa, juho, Sm1llee      |
|            7 |     3033 | 2024-04-08 | Permitta          | L   | 0.431      | -            | -                | -                | -         |    -2.57 | allu, doto, Jerppa, juho, Sm1llee      |
|            6 |     3066 | 2024-04-06 | Johnny Speeds     | L   | 0.419      | -            | -                | -                | -         |    -0.41 | allu, doto, Jerppa, juho, Sm1llee      |
|            5 |     3132 | 2024-04-04 | Gaimin Gladiators | L   | 0.405      | -            | -                | -                | -         |    -1.70 | allu, doto, Jerppa, juho, Sm1llee      |
|            4 |     3618 | 2024-03-12 | kONO              | L   | 0.252      | -            | -                | -                | -         |    -2.65 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            3 |     3708 | 2024-03-08 | INGLORIOUS        | W   | 0.225      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.23 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            2 |     3823 | 2024-03-04 | Endpoint          | L   | 0.199      | -            | -                | -                | -         |    -4.78 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            1 |     3909 | 2024-02-29 | Sashi             | L   | 0.171      | -            | -                | -                | -         |    -0.37 | allu, doto, Jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($445.64)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
