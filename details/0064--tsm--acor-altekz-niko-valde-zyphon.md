### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  973.7<br />
<br />
Final Rank Value (973.7) = Starting Rank Value (971.2) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.2
- 400 + ( ( 0.280 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 971.2


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
|           17 |       30 | 2024-08-02 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -10.29 | acoR, Altekz, niko, valde, Zyphon |
|           16 |      163 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.691 (0.345)    | 0 (0.000) |    19.59 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      220 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.47 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      249 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -16.48 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      420 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.53 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      463 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.224 (0.032)    | 0 (0.000) |     6.52 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      569 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -26.04 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      593 | 2024-07-18 | LEON             | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |     3.41 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      636 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.073 (0.036)    | 0.569 (0.285)    | 0 (0.000) |    11.70 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      660 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.38 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      706 | 2024-07-16 | 500              | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.023 (0.008)    | 0 (0.000) |     0.80 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      738 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.505 (0.252)    | 1.000 (0.500)    | 0 (0.000) |    26.90 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      784 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.964 (0.345)    | 0 (0.000) |    22.68 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      797 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.122 (0.044)    | 0.901 (0.322)    | 0 (0.000) |    25.02 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      856 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.74 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      875 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.33 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      878 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.66 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
