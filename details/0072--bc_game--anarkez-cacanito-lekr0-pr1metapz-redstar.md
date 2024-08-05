### Roster Details<br />
Team Name: BC.Game<br />
Roster: anarkez, CacaNito, Lekr0, pr1metapz, REDSTAR<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.6<br />
<br />
Final Rank Value (946.6) = Starting Rank Value (869.8) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.8
- 400 + ( ( 0.229 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 869.8


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
|           15 |       17 | 2024-08-04 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.03 | anarkez, CacaNito, Lekr0, pr1metapz, REDSTAR |
|           14 |       30 | 2024-08-04 | RUSH B            | W   | 1.000      | 0.342        | 0.026 (0.009)    | 0.385 (0.132)    | 0 (0.000) |    16.12 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           13 |       59 | 2024-08-03 | ARCRED            | W   | 1.000      | 0.342        | 0.041 (0.014)    | 0.343 (0.117)    | 0 (0.000) |    16.73 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           12 |       94 | 2024-08-02 | Space             | W   | 1.000      | 0.342        | 0.006 (0.002)    | 0.445 (0.152)    | 0 (0.000) |    12.70 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           11 |      134 | 2024-08-01 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.38 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           10 |      227 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.435        | 0.005 (0.002)    | 0.507 (0.220)    | 0 (0.000) |    11.69 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            9 |      282 | 2024-07-28 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -14.82 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            8 |      348 | 2024-07-26 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.569 (0.247)    | 0 (0.000) |    15.75 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            7 |      385 | 2024-07-25 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -5.10 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            6 |      411 | 2024-07-24 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -12.02 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            5 |      455 | 2024-07-23 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.569 (0.247)    | 0 (0.000) |    17.13 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            4 |      485 | 2024-07-22 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.58 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            3 |      529 | 2024-07-20 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.78 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            2 |      636 | 2024-07-18 | Metizport         | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.235 (0.102)    | 0 (0.000) |    12.81 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            1 |      764 | 2024-07-16 | SINNERS           | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.794 (0.345)    | 0 (0.000) |    19.91 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,000.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
