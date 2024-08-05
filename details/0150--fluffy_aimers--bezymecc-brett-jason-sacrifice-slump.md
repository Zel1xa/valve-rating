### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: bezymecc, brett, jason, sacrifice, slump<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [41]( ../standings_americas.md)<br />
<br />
Final Rank Value:  712.7<br />
<br />
Final Rank Value (712.7) = Starting Rank Value (722.5) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.5
- 400 + ( ( 0.156 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 722.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      191 | 2024-07-25 | NoVum            | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.038 (0.014)    | 0 (0.000) |     4.66 | bezymecc, brett, jason, sacrifice, slump |
|           24 |      229 | 2024-07-24 | E-Xolos LAZER    | L   | 1.000      | -            | -                | -                | -         |   -12.65 | bezymecc, brett, jason, sacrifice, slump |
|           23 |      232 | 2024-07-24 | E-Xolos LAZER    | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.347 (0.166)    | 0 (0.000) |    19.13 | bezymecc, brett, jason, sacrifice, slump |
|           22 |      264 | 2024-07-23 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -5.97 | bezymecc, brett, jason, sacrifice, slump |
|           21 |      266 | 2024-07-23 | Party Astronauts | W   | 1.000      | 0.477        | 0.041 (0.020)    | 0.533 (0.254)    | 0 (0.000) |    26.08 | bezymecc, brett, jason, sacrifice, slump |
|           20 |      552 | 2024-07-16 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -5.38 | bezymecc, brett, jason, sacrifice, slump |
|           19 |      557 | 2024-07-16 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -5.67 | bezymecc, brett, jason, sacrifice, slump |
|           18 |      898 | 2024-06-14 | Elevate          | L   | 0.888      | -            | -                | -                | -         |    -4.74 | brett, jason, nooz, PNDLM, sacrifice     |
|           17 |     1132 | 2024-06-08 | Perseverance     | W   | 0.846      | 0.371        | 0.000 (0.000)    | 0.064 (0.020)    | 0 (0.000) |     7.51 | brett, jason, nooz, PNDLM, sacrifice     |
|           16 |     1223 | 2024-06-06 | Akimbo           | L   | 0.835      | -            | -                | -                | -         |   -10.21 | brett, jason, nooz, PNDLM, sacrifice     |
|           15 |     1240 | 2024-06-06 | NRG              | L   | 0.833      | -            | -                | -                | -         |    -6.42 | brett, jason, nooz, PNDLM, sacrifice     |
|           14 |     1249 | 2024-06-06 | M80              | L   | 0.833      | -            | -                | -                | -         |    -1.13 | brett, jason, nooz, PNDLM, sacrifice     |
|           13 |     1308 | 2024-06-05 | NRG              | L   | 0.826      | -            | -                | -                | -         |    -6.78 | brett, jason, nooz, PNDLM, sacrifice     |
|           12 |     1391 | 2024-06-03 | Akimbo           | W   | 0.813      | 0.371        | 0.003 (0.001)    | 0.076 (0.023)    | 0 (0.000) |    11.14 | brett, jason, nooz, PNDLM, sacrifice     |
|           11 |     1703 | 2024-05-21 | Nouns            | L   | 0.728      | -            | -                | -                | -         |    -4.54 | brett, jason, nooz, PNDLM, sacrifice     |
|           10 |     1706 | 2024-05-21 | Nouns            | L   | 0.728      | -            | -                | -                | -         |    -4.73 | brett, jason, nooz, PNDLM, sacrifice     |
|            9 |     1743 | 2024-05-20 | Perseverance     | W   | 0.721      | 0.477        | 0.004 (0.001)    | 0.248 (0.085)    | 0 (0.000) |    12.89 | brett, jason, nooz, PNDLM, sacrifice     |
|            8 |     1747 | 2024-05-20 | Perseverance     | L   | 0.721      | -            | -                | -                | -         |    -9.94 | brett, jason, nooz, PNDLM, sacrifice     |
|            7 |     1782 | 2024-05-19 | Nouns            | L   | 0.713      | -            | -                | -                | -         |    -4.77 | brett, jason, nooz, PNDLM, sacrifice     |
|            6 |     1836 | 2024-05-17 | Elevate          | L   | 0.702      | -            | -                | -                | -         |    -3.88 | brett, jason, nooz, PNDLM, sacrifice     |
|            5 |     1837 | 2024-05-17 | Elevate          | L   | 0.701      | -            | -                | -                | -         |    -4.02 | brett, jason, nooz, PNDLM, sacrifice     |
|            4 |     1870 | 2024-05-16 | Party Astronauts | L   | 0.695      | -            | -                | -                | -         |    -5.26 | brett, jason, nooz, PNDLM, sacrifice     |
|            3 |     1873 | 2024-05-16 | Party Astronauts | L   | 0.695      | -            | -                | -                | -         |    -5.50 | brett, jason, nooz, PNDLM, sacrifice     |
|            2 |     1906 | 2024-05-15 | MIGHT            | W   | 0.688      | 0.477        | 0.000 (0.000)    | 0.062 (0.020)    | 0 (0.000) |     5.09 | brett, jason, nooz, PNDLM, sacrifice     |
|            1 |     1913 | 2024-05-15 | MIGHT            | W   | 0.688      | 0.477        | 0.000 (0.000)    | 0.062 (0.020)    | 0 (0.000) |     5.32 | brett, jason, nooz, PNDLM, sacrifice     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,025.21)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
