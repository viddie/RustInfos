# Damage Dropoff

Explanation for the weapon stats listed below:

| Stat      | Explanation                                                  |
| --------- | ------------------------------------------------------------ |
| Start     | The start of the damage dropoff in meters. At and before this point the weapon always does full damage |
| End       | The end of the damage dropoff in meters. At and after this point the weapon always does 80% of the full damage |
| Loss/m    | How much percent of the weapons full damage is lost every meter after the start of the damage dropoff, up until the end. Always adds up to 20% over the entire range. |
| Confirmed | Whether these values are accurate and confirmed through various ingame tests |

Note: The data points in the images below are raw values extracted from the ingame console using the combatlog after shooting horses. Due to rounding of both the distance and the damage in the combatlog, the data points might not necessarily form a perfect linear shape during the dropoff. 

## Bolt Action Rifle

| Stat      | Value                                                        |
| --------- | ------------------------------------------------------------ |
| Start     | 35 m                                                         |
| End       | 175 m                                                        |
| Loss/m    | ~0.142857 %                                                  |
| Confirmed | Yes (But I don't see how the range (574) impacts these values) |

![](resources/dmg-dropoff/bar.png)

## Bow

| Stat      | Value                |
| --------- | -------------------- |
| Start     | 10 m (2/3 the range) |
| End       | 60 m (4x the range)  |
| Loss/m    | 0.4 %                |
| Confirmed | Yes                  |

![](resources/dmg-dropoff/bow.png)

## Crossbow

| Stat      | Value      |
| --------- | ---------- |
| Start     | 15 m       |
| End       | 90 m       |
| Loss/m    | ~0.26667 % |
| Confirmed | Yes        |

![](resources/dmg-dropoff/crossbow.png)

## Revolver

| Stat      | Value                |
| --------- | -------------------- |
| Start     | 4 m (1/9 the range)  |
| End       | 24 m (6/9 the range) |
| Loss/m    | 1 %                  |
| Confirmed | Yes                  |

![](resources/dmg-dropoff/revolver.png)

## Semi-Automatic Rifle

| Stat      | Value                                                        |
| --------- | ------------------------------------------------------------ |
| Start     | ~20,88888 m                                                  |
| End       | ~104,44444 m                                                 |
| Loss/m    | ~0,239362 %                                                  |
| Confirmed | No (Still searching for nice values deductible from the range, but I don't currently see how...) |

![](resources/dmg-dropoff/sar.png)