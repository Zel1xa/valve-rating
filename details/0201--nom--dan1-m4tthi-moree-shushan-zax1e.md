### Roster Details<br />
Team Name: NOM<br />
Roster: dan1, m4tthi, MOREE, shushan, Zax1e<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [25]( ../standings_asia.md)<br />
<br />
Final Rank Value:  570.8<br />
<br />
Final Rank Value (570.8) = Starting Rank Value (541.0) + Head To Head Adjustments (29.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.073<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 541.0
- 400 + ( ( 0.073 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 541.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      240 | 2024-08-30 | DRILLAS     | L   | 1.000      | -            | -                | -                | -         |   -17.34 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           14 |      271 | 2024-08-29 | Onyx Ravens | L   | 1.000      | -            | -                | -                | -         |   -21.64 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           13 |      322 | 2024-08-28 | Qiang       | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.151 (0.022)    | 0 (0.000) |    16.51 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           12 |      330 | 2024-08-28 | Al-Ittihad  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.046 (0.007)    | 0 (0.000) |    15.74 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           11 |     1292 | 2024-08-01 | GUN5        | L   | 0.946      | -            | -                | -                | -         |    -4.35 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|           10 |     1410 | 2024-07-29 | 1WIN        | L   | 0.926      | -            | -                | -                | -         |    -3.24 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            9 |     1452 | 2024-07-28 | GUN5        | W   | 0.919      | 0.143        | 0.091 (0.012)    | 0.959 (0.126)    | 0 (0.000) |    24.86 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            8 |     3129 | 2024-05-18 | GUN5        | L   | 0.448      | -            | -                | -                | -         |    -1.23 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            7 |     3163 | 2024-05-17 | Rare Atom   | W   | 0.441      | 0.143        | 0.025 (0.002)    | 0.449 (0.028)    | 0 (0.000) |    11.59 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            6 |     3325 | 2024-05-14 | Heimo       | W   | 0.419      | 0.143        | 0.004 (0.000)    | 0.071 (0.004)    | 0 (0.000) |     8.59 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            5 |     3346 | 2024-05-13 | Rare Atom   | L   | 0.412      | -            | -                | -                | -         |    -1.95 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            4 |     3883 | 2024-04-19 | JANO        | L   | 0.254      | -            | -                | -                | -         |    -2.89 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            3 |     3935 | 2024-04-18 | RUBY        | L   | 0.247      | -            | -                | -                | -         |    -1.05 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            2 |     3974 | 2024-04-17 | Sampi       | W   | 0.240      | 0.143        | 0.032 (0.001)    | 1.000 (0.034)    | 0 (0.000) |     6.69 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            1 |     4327 | 2024-04-04 | KOI         | L   | 0.154      | -            | -                | -                | -         |    -0.44 | dan1, meztal, MOREE, shushan, tN1R   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
