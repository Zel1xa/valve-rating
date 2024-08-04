### Roster Details<br />
Team Name: BC.Game<br />
Roster: anarkez, CacaNito, Lekr0, pr1metapz, REDSTAR<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.7<br />
<br />
Final Rank Value (945.7) = Starting Rank Value (868.6) + Head To Head Adjustments (77.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.199[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.6
- 400 + ( ( 0.229 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 868.6


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
|           15 |        0 | 2024-08-04 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.00 | anarkez, CacaNito, Lekr0, pr1metapz, REDSTAR |
|           14 |       14 | 2024-08-04 | RUSH B            | W   | 1.000      | 0.342        | 0.026 (0.009)    | 0.386 (0.132)    | 0 (0.000) |    16.18 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           13 |       42 | 2024-08-03 | ARCRED            | W   | 1.000      | 0.342        | 0.041 (0.014)    | 0.344 (0.118)    | 0 (0.000) |    16.79 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           12 |       77 | 2024-08-02 | Space             | W   | 1.000      | 0.342        | 0.006 (0.002)    | 0.406 (0.139)    | 0 (0.000) |    12.63 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           11 |      117 | 2024-08-01 | Sampi             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.35 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|           10 |      210 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.509 (0.221)    | 0 (0.000) |    11.73 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            9 |      265 | 2024-07-28 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -14.80 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            8 |      331 | 2024-07-26 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    15.90 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            7 |      368 | 2024-07-25 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -5.05 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            6 |      394 | 2024-07-24 | 1WIN              | L   | 1.000      | -            | -                | -                | -         |   -12.12 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            5 |      438 | 2024-07-23 | GUN5              | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    17.29 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            4 |      468 | 2024-07-22 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -6.62 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            3 |      512 | 2024-07-20 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -14.76 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            2 |      619 | 2024-07-18 | Metizport         | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.235 (0.102)    | 0 (0.000) |    12.70 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |
|            1 |      747 | 2024-07-16 | SINNERS           | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.797 (0.346)    | 0 (0.000) |    19.85 | anarkez, CacaNito, joel, Lekr0, pr1metapz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,000.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
