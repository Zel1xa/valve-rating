### Roster Details<br />
Team Name: BC.Game<br />
Roster: anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  911.3<br />
<br />
Final Rank Value (911.3) = Starting Rank Value (868.2) + Head To Head Adjustments (43.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.354[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.2
- 400 + ( ( 0.242 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 868.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      162 | 2024-09-03 | RUBY              | L   | 1.000      | -            | -                | -                | -         |   -18.73 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz |
|           19 |      567 | 2024-08-23 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -10.80 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz |
|           18 |      593 | 2024-08-22 | GamerLegion       | L   | 1.000      | -            | -                | -                | -         |    -9.47 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz |
|           17 |      639 | 2024-08-21 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -3.29 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz |
|           16 |      657 | 2024-08-21 | ECLOT             | W   | 1.000      | 0.143        | 0.047 (0.007)    | 0.698 (0.100)    | 0 (0.000) |    14.83 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz |
|           15 |     1165 | 2024-08-04 | B8                | L   | 0.968      | -            | -                | -                | -         |    -7.92 | anarkez, CacaNito, Lekr0, pr1metapz, REDSTAR |
|           14 |     1177 | 2024-08-04 | RUSH B            | W   | 0.966      | 0.342        | 0.026 (0.008)    | 0.304 (0.101)    | 0 (0.000) |    14.65 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           13 |     1206 | 2024-08-03 | ARCRED            | W   | 0.960      | 0.342        | 0.036 (0.012)    | 0.427 (0.140)    | 0 (0.000) |    15.86 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           12 |     1241 | 2024-08-02 | Space             | W   | 0.954      | 0.342        | 0.004 (0.001)    | 0.463 (0.151)    | 0 (0.000) |    11.15 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           11 |     1281 | 2024-08-01 | Sampi             | W   | 0.947      | 0.435        | 0.032 (0.013)    | 1.000 (0.411)    | 0 (0.000) |    13.87 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           10 |     1374 | 2024-07-30 | EYEBALLERS        | W   | 0.933      | 0.435        | 0.000 (0.000)    | 0.407 (0.165)    | 0 (0.000) |     6.88 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            9 |     1429 | 2024-07-28 | Permitta          | L   | 0.922      | -            | -                | -                | -         |   -13.88 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            8 |     1495 | 2024-07-26 | GUN5              | W   | 0.907      | 0.435        | 0.091 (0.036)    | 0.959 (0.378)    | 0 (0.000) |    15.20 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            7 |     1532 | 2024-07-25 | SAW               | L   | 0.900      | -            | -                | -                | -         |    -1.51 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            6 |     1558 | 2024-07-24 | 1WIN              | L   | 0.894      | -            | -                | -                | -         |   -13.05 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            5 |     1602 | 2024-07-23 | GUN5              | W   | 0.887      | 0.435        | 0.091 (0.035)    | 0.959 (0.370)    | 0 (0.000) |    16.07 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            4 |     1632 | 2024-07-22 | Passion UA        | L   | 0.879      | -            | -                | -                | -         |    -6.60 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            3 |     1676 | 2024-07-20 | Aurora Young Blud | L   | 0.868      | -            | -                | -                | -         |   -12.11 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            2 |     1783 | 2024-07-18 | Metizport         | W   | 0.853      | 0.435        | 0.019 (0.007)    | 0.487 (0.181)    | 0 (0.000) |    14.15 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            1 |     1911 | 2024-07-16 | SINNERS           | W   | 0.839      | 0.435        | 0.081 (0.030)    | 1.000 (0.365)    | 0 (0.000) |    17.84 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,764.72)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
