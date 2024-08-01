### Roster Details<br />
Team Name: BC.Game<br />
Roster: anarkez, CacaNito, joel, Lekr0, pr1metapz<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  769.4<br />
<br />
Final Rank Value (769.4) = Starting Rank Value (659.6) + Head To Head Adjustments (109.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.6
- 400 + ( ( 0.126 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 659.6


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
|           11 |        2 | 2024-08-01 | Sampi             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    20.38 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|           10 |       94 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.512 (0.223)    | 0 (0.000) |    17.91 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            9 |      149 | 2024-07-28 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -8.62 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            8 |      215 | 2024-07-26 | GUN5              | W   | 1.000      | 0.435        | 0.074 (0.032)    | 0.555 (0.241)    | 0 (0.000) |    22.62 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            7 |      253 | 2024-07-25 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -2.25 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            6 |      278 | 2024-07-24 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |    -6.67 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            5 |      322 | 2024-07-23 | GUN5              | W   | 1.000      | 0.435        | 0.074 (0.032)    | 0.555 (0.241)    | 0 (0.000) |    24.43 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            4 |      353 | 2024-07-22 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -2.81 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            3 |      399 | 2024-07-20 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -6.97 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            2 |      512 | 2024-07-18 | Metizport         | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.425 (0.185)    | 0 (0.000) |    25.74 | anarkez, CacaNito, joel, Lekr0, pr1metapz |
|            1 |      642 | 2024-07-16 | SINNERS           | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.768 (0.334)    | 0 (0.000) |    26.10 | anarkez, CacaNito, joel, Lekr0, pr1metapz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
