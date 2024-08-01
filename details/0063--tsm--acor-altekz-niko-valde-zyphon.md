### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  985.7<br />
<br />
Final Rank Value (985.7) = Starting Rank Value (971.0) + Head To Head Adjustments (14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.0
- 400 + ( ( 0.277 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 971.0


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
|           16 |       77 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.083 (0.042)    | 0.578 (0.289)    | 0 (0.000) |    19.53 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      135 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.04 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      164 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -16.41 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      336 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.39 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      380 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.222 (0.032)    | 0 (0.000) |     6.62 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      493 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -25.40 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      517 | 2024-07-18 | LEON             | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.131 (0.019)    | 0 (0.000) |     3.48 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      560 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.074 (0.037)    | 0.555 (0.278)    | 0 (0.000) |    12.42 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      584 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.59 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      633 | 2024-07-16 | 500              | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.023 (0.008)    | 0 (0.000) |     0.82 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      669 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.505 (0.252)    | 1.000 (0.500)    | 0 (0.000) |    26.87 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      717 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.187 (0.067)    | 0.971 (0.347)    | 0 (0.000) |    22.81 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      730 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.124 (0.044)    | 0.818 (0.293)    | 0 (0.000) |    25.26 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      789 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.55 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      808 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.26 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      811 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.44 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
