### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1003.5<br />
<br />
Final Rank Value (1003.5) = Starting Rank Value (986.3) + Head To Head Adjustments (17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.3
- 400 + ( ( 0.285 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 986.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |       10 | 2024-08-06 | ECSTATIC         | W   | 1.000      | 0.333        | -                | 0.077 (0.026)    | 0 (0.000) |     2.93 | acoR, Altekz, niko, valde, Zyphon |
|           21 |       22 | 2024-08-05 | Sashi            | W   | 1.000      | 0.143        | 0.184 (0.026)    | 0.958 (0.137)    | 0 (0.000) |    23.10 | acoR, Altekz, niko, valde, Zyphon |
|           20 |       26 | 2024-08-05 | 777              | W   | 1.000      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |     4.74 | acoR, Altekz, niko, valde, Zyphon |
|           19 |       39 | 2024-08-04 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -14.45 | acoR, Altekz, niko, valde, Zyphon |
|           18 |       47 | 2024-08-04 | TALON            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.13 | acoR, Altekz, niko, valde, Zyphon |
|           17 |       99 | 2024-08-02 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -10.43 | acoR, Altekz, niko, valde, Zyphon |
|           16 |      232 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.081 (0.040)    | 0.700 (0.350)    | 0 (0.000) |    18.98 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      288 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.50 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      318 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -15.78 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      489 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.88 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      532 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.216 (0.031)    | 0 (0.000) |     6.38 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      638 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -26.22 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      662 | 2024-07-18 | LEON             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      708 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.550 (0.275)    | 0 (0.000) |    11.10 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      729 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.55 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      775 | 2024-07-16 | 500              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.74 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      809 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.510 (0.255)    | 1.000 (0.500)    | 0 (0.000) |    26.87 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      854 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.958 (0.343)    | -         |    22.29 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      867 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.122 (0.044)    | 1.000 (0.358)    | -         |    24.84 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      926 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.65 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      945 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.57 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      948 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.57 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
