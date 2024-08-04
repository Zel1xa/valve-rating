### Roster Details<br />
Team Name: TSM<br />
Roster: acoR, Altekz, niko, valde, Zyphon<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  975.4<br />
<br />
Final Rank Value (975.4) = Starting Rank Value (971.7) + Head To Head Adjustments (3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.445[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.7
- 400 + ( ( 0.280 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 971.7


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
|           17 |       41 | 2024-08-02 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -10.32 | acoR, Altekz, niko, valde, Zyphon |
|           16 |      174 | 2024-07-30 | 9 Pandas         | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.690 (0.345)    | 0 (0.000) |    19.41 | acoR, Altekz, niko, valde, Zyphon |
|           15 |      231 | 2024-07-29 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -20.06 | acoR, Altekz, niko, valde, Zyphon |
|           14 |      260 | 2024-07-28 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -15.74 | acoR, Altekz, niko, valde, Zyphon |
|           13 |      431 | 2024-07-22 | CPH Wolves       | L   | 1.000      | -            | -                | -                | -         |   -22.55 | acoR, Altekz, niko, valde, Zyphon |
|           12 |      474 | 2024-07-21 | Preasy           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.224 (0.032)    | 0 (0.000) |     6.51 | acoR, Altekz, niko, valde, Zyphon |
|           11 |      580 | 2024-07-18 | Nexus            | L   | 1.000      | -            | -                | -                | -         |   -26.05 | acoR, Altekz, niko, valde, Zyphon |
|           10 |      604 | 2024-07-18 | LEON             | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.130 (0.019)    | 0 (0.000) |     3.41 | acoR, Altekz, niko, valde, Zyphon |
|            9 |      647 | 2024-07-17 | GUN5             | W   | 1.000      | 0.500        | 0.073 (0.036)    | 0.570 (0.285)    | 0 (0.000) |    11.66 | acoR, Altekz, niko, valde, Zyphon |
|            8 |      671 | 2024-07-17 | Into the Breach  | L   | 1.000      | -            | -                | -                | -         |   -28.39 | acoR, Altekz, niko, valde, Zyphon |
|            7 |      717 | 2024-07-16 | 500              | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.023 (0.008)    | 0 (0.000) |     0.79 | acoR, Altekz, niko, valde, Zyphon |
|            6 |      749 | 2024-07-15 | 3DMAX            | W   | 1.000      | 0.500        | 0.506 (0.253)    | 1.000 (0.500)    | 0 (0.000) |    26.95 | acoR, Altekz, niko, valde, Zyphon |
|            5 |      796 | 2024-07-13 | Sashi            | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.962 (0.344)    | 0 (0.000) |    22.71 | acoR, Altekz, niko, valde, Zyphon |
|            4 |      809 | 2024-07-12 | Johnny Speeds    | W   | 1.000      | 0.358        | 0.122 (0.044)    | 0.902 (0.323)    | 0 (0.000) |    25.00 | acoR, Altekz, niko, valde, Zyphon |
|            3 |      868 | 2024-07-09 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.88 | acoR, Altekz, niko, valde, Zyphon |
|            2 |      887 | 2024-07-08 | FLuffy Gangsters | L   | 1.000      | -            | -                | -                | -         |   -27.34 | acoR, Altekz, niko, valde, Zyphon |
|            1 |      890 | 2024-07-08 | Passion UA       | W   | 1.000      | 0.358        | 0.172 (0.062)    | 1.000 (0.358)    | 0 (0.000) |    18.83 | acoR, Altekz, niko, valde, Zyphon |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,864.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
