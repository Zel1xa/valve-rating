### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1000.0<br />
<br />
Final Rank Value (1000.0) = Starting Rank Value (985.9) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.417[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 985.9
- 400 + ( ( 0.286 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 985.9


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
|           21 |       10 | 2024-08-05 | Sashi            | W   | 1.000      | 0.143        | 0.184 (0.026)    | 0.982 (0.140)    | 0 (0.000) |    23.10 | acoR, Altekz, niko, valde, Zyphon |
|           20 |       13 | 2024-08-05 | 777              | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.177 (0.025)    | 0 (0.000) |     4.74 | acoR, Altekz, niko, valde, Zyphon |
|           19 |       29 | 2024-08-04 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -14.47 | acoR, Altekz, niko, valde, Zyphon |
|           18 |       37 | 2024-08-04 | TALON            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.14 | acoR, Altekz, niko, valde, Zyphon |
|           17 |       93 | 2024-08-02 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -10.49 | acoR, Altekz, niko, valde, Zyphon |
|           16 |      226 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.717 (0.358)    | 0 (0.000) |    19.00 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      282 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.52 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      312 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -15.80 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      483 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.87 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      526 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.221 (0.032)    | 0 (0.000) |     6.36 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      632 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -26.27 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      656 | 2024-07-18 | LEON             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.24 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      702 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.562 (0.281)    | 0 (0.000) |    11.13 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      723 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.56 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      769 | 2024-07-16 | 500              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.74 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      803 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.509 (0.254)    | 1.000 (0.500)    | 0 (0.000) |    26.83 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      848 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.982 (0.351)    | 0 (0.000) |    22.30 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      861 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.122 (0.044)    | 1.000 (0.358)    | -         |    24.80 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      920 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.68 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      939 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.58 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      942 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.173 (0.062)    | 1.000 (0.358)    | -         |    18.61 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
