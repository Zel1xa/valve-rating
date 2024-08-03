### Roster Details<br />
Team Name: BC.Game<br />
Roster: anarkez, CacaNito, joel, Lekr0, pr1metapz<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  820.0<br />
<br />
Final Rank Value (820.0) = Starting Rank Value (677.2) + Head To Head Adjustments (142.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 677.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |        7 | 2024-08-03 | ARCRED            | W   | 1.000      | 0.342        | 0.041 (0.014)    | 0.356 (0.122)    | 0 (0.000) |    21.72 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|           12 |       37 | 2024-08-02 | Space             | W   | 1.000      | 0.342        | 0.006 (0.002)    | 0.420 (0.144)    | 0 (0.000) |    18.46 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|           11 |       63 | 2024-08-01 | Sampi             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    19.87 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|           10 |      152 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.528 (0.229)    | 0 (0.000) |    17.32 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            9 |      207 | 2024-07-28 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -9.58 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            8 |      273 | 2024-07-26 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.588 (0.256)    | 0 (0.000) |    21.70 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            7 |      311 | 2024-07-25 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -2.49 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            6 |      336 | 2024-07-24 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |    -7.15 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            5 |      380 | 2024-07-23 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.588 (0.256)    | 0 (0.000) |    23.53 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            4 |      410 | 2024-07-22 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.27 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            3 |      454 | 2024-07-20 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -8.20 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            2 |      561 | 2024-07-18 | Metizport         | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.433 (0.188)    | 0 (0.000) |    25.22 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            1 |      684 | 2024-07-16 | SINNERS           | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.784 (0.341)    | 0 (0.000) |    25.62 | anarkez, CacaNito, joel, Lekr0, pr1metapz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
