### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  998.6<br />
<br />
Final Rank Value (998.6) = Starting Rank Value (984.4) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 984.4
- 400 + ( ( 0.285 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 984.4


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
|           21 |        0 | 2024-08-05 | Sashi            | W   | 1.000      | 0.143        | 0.184 (0.026)    | 0.996 (0.142)    | 0 (0.000) |    23.12 | acoR, Altekz, niko, valde, Zyphon |
|           20 |        2 | 2024-08-05 | 777              | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.180 (0.026)    | 0 (0.000) |     4.79 | acoR, Altekz, niko, valde, Zyphon |
|           19 |       18 | 2024-08-04 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -14.48 | acoR, Altekz, niko, valde, Zyphon |
|           18 |       26 | 2024-08-04 | TALON            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.15 | acoR, Altekz, niko, valde, Zyphon |
|           17 |       81 | 2024-08-02 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -10.52 | acoR, Altekz, niko, valde, Zyphon |
|           16 |      215 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.727 (0.363)    | 0 (0.000) |    19.03 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      272 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.49 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      301 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -15.81 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      472 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.83 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      515 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.224 (0.032)    | 0 (0.000) |     6.26 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      621 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -26.27 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      645 | 2024-07-18 | LEON             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.24 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      691 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.073 (0.036)    | 0.569 (0.285)    | 0 (0.000) |    11.16 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      712 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.55 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      758 | 2024-07-16 | 500              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.75 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      792 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.508 (0.254)    | 1.000 (0.500)    | 0 (0.000) |    26.81 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      837 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.996 (0.356)    | 0 (0.000) |    22.34 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      850 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.122 (0.044)    | 0.940 (0.336)    | -         |    24.85 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      909 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.61 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      928 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.56 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      931 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.54 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
