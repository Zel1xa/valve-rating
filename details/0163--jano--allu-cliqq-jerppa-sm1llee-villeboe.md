### Roster Details<br />
Team Name: JANO<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
<br />
Final Rank Value:  673.1<br />
<br />
Final Rank Value (673.1) = Starting Rank Value (681.9) + Head To Head Adjustments (-8.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.9
- 400 + ( ( 0.137 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 681.9


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
|           15 |     1610 | 2024-06-02 | FAVBET            | L   | 0.767      | -            | -                | -                | -         |    -8.37 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           14 |     1714 | 2024-05-29 | Zero Tenacity     | L   | 0.742      | -            | -                | -                | -         |    -1.88 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           13 |     2547 | 2024-04-27 | Sashi             | L   | 0.528      | -            | -                | -                | -         |    -1.02 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     2722 | 2024-04-20 | Sangal            | L   | 0.479      | -            | -                | -                | -         |    -1.10 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     2754 | 2024-04-19 | NOM               | W   | 0.474      | 0.143        | 0.000 (0.000)    | 0.106 (0.007)    | 0 (0.000) |     4.88 | allu, doto, Jerppa, juho, Sm1llee      |
|           10 |     2859 | 2024-04-17 | RUBY              | L   | 0.459      | -            | -                | -                | -         |    -2.87 | allu, doto, Jerppa, juho, Sm1llee      |
|            9 |     2864 | 2024-04-17 | MOUZ NXT          | L   | 0.459      | -            | -                | -                | -         |    -1.67 | allu, doto, Jerppa, juho, Sm1llee      |
|            8 |     2945 | 2024-04-12 | Zero Tenacity     | W   | 0.425      | 0.371        | 0.143 (0.023)    | 1.000 (0.158)    | 0 (0.000) |    12.05 | allu, doto, Jerppa, juho, Sm1llee      |
|            7 |     3111 | 2024-04-08 | Permitta          | L   | 0.399      | -            | -                | -                | -         |    -2.10 | allu, doto, Jerppa, juho, Sm1llee      |
|            6 |     3144 | 2024-04-06 | Johnny Speeds     | L   | 0.387      | -            | -                | -                | -         |    -0.37 | allu, doto, Jerppa, juho, Sm1llee      |
|            5 |     3209 | 2024-04-04 | Gaimin Gladiators | L   | 0.373      | -            | -                | -                | -         |    -1.72 | allu, doto, Jerppa, juho, Sm1llee      |
|            4 |     3678 | 2024-03-12 | kONO              | L   | 0.220      | -            | -                | -                | -         |    -2.29 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            3 |     3767 | 2024-03-08 | INGLORIOUS        | W   | 0.193      | 0.143        | 0.000 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     1.93 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            2 |     3877 | 2024-03-04 | Endpoint          | L   | 0.167      | -            | -                | -                | -         |    -3.98 | allu, doto, Jelo, Jerppa, Sm1llee      |
|            1 |     3962 | 2024-02-29 | Sashi             | L   | 0.139      | -            | -                | -                | -         |    -0.30 | allu, doto, Jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($420.17)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
