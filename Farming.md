# Farming

## Introduction

## Items

### Basic Items

| Item Name                                                    | Usage                                                        | Additional Notes                               | Research Cost     | Found In                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------- | ----------------- | ------------------------------------------------------------ |
| [Large Planter Box](https://rustlabs.com/item/large-planter-box) | Holds 9 seeds                                                | Fits neatly into a 1x1 square foundation       | 20x Scrap         | [Barrel](https://rustlabs.com/entity/barrel) 1%, [Primitive Crate](https://rustlabs.com/entity/primitive-crate) 5% |
| [Water Jug](https://rustlabs.com/item/water-jug)             | Holds 5 liters of water. Must-have (multiple) when you are nowhere near a water source and need to travel to a lake/river for water. | Can be bought at Bandit Camp for 5x Scrap each | -                 | [Ration Box](https://rustlabs.com/entity/ration-box) 25%, [Food Crate](https://rustlabs.com/entity/food-crate) 22% |
| [Bota Bag](https://rustlabs.com/item/bota-bag)               | Holds 0.5 liters of water. Cheap alternative to Water Jugs   | Craft for 10x Cloth                            | Default Blueprint | -                                                            |

### Ceiling Light

| Item Name                                                | Usage                                                        | Additional Notes                                             | Research Cost | Found In                                                     |
| -------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------- | ------------------------------------------------------------ |
| [Ceiling Light](https://rustlabs.com/item/ceiling-light) | Provides 100% light to all plants in a large planter box if placed above the center of one. | Each light consumes 2 energy and has a passthrough so you can chain all of them together. Can be bought at Bandit Camp for 30x Scrap | 20x Scrap     | [Sunken Chest](https://rustlabs.com/entity/sunken-chest) 1%, [Crate](https://rustlabs.com/entity/crate) 1%, [Oil Rig Scientist](https://rustlabs.com/entity/oil-rig-scientist) 0.2% |

- Without a light source your plants can't grow. Sunlight also works, but during night or when the sun is angled in a way that it's light doesn't reach your plants, they will die or their yield will be massively reduced. 
- A good setup for a small farm can be done in a 2x2x1 building with the following electrical components:
  - 1x [Large Solar Panel](https://rustlabs.com/item/large-solar-panel) (20 energy generation)
  - 1x [Small Rechargable Battery](https://rustlabs.com/item/small-rechargable-battery) (8 energy output at 10 energy input (due to 80% efficiency))
  - 4x Ceiling Lights (2 energy consumption each, 8 in total)
- With this setup you can branch of 9 energy from before the Battery and power some other things in your house.

### Sprinkler

| Item Name                                        | Usage                                                        | Additional Notes                                             | Research Cost | Found In                                                     |
| ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------- | ------------------------------------------------------------ |
| [Sprinkler](https://rustlabs.com/item/sprinkler) | Slowly gives water evenly to all Planter Boxes in range. Outputs 180ml water per minute in total. | Doesn't require energy but water. Has a passthrough so you can chain Sprinklers together (max. 6). Can be bought at Bandit Camp for 15x Scrap | 20x Scrap     | [Sunken Chest](https://rustlabs.com/entity/sunken-chest) 1%, [Crate](https://rustlabs.com/entity/crate) 1%, [Oil Rig Scientist](https://rustlabs.com/entity/oil-rig-scientist) 0.2% |

- The Sprinkler is a nice tool to help you keep your plants at the water level you want them to be at. Place 2 of them directly in the center of a 2x2 farm and they will keep the water level almost steady. Depending on the amount of W-genes your plants have you will need to manually water your plants or switch of the Sprinklers once in a while.
- Requires a water source to operate, e.g. a [Water Barrel](https://rustlabs.com/item/water-barrel) or Powered Water Purifier with enough water inside. Use a Fluid Switch & Pump to enable/disable the Sprinklers without needing additional energy, if your water source is placed above the altitude of the Sprinklers.
- A setup to automate the Sprinklers to the point where you only have to switch them on/off once in a while:
  - 1x [Water Pump](https://rustlabs.com/item/water-pump) (5 energy consumption)
  - (1x [Powered Water Purifier](https://rustlabs.com/item/powered-water-purifier), if you only have salt water at your disposal (5 energy consumption))
  - 1x [Fluid Switch & Pump](https://rustlabs.com/item/fluid-switch-&-pump) (0 energy consumption if placed correctly, 1 otherwise to power the pump)
  - 2x Sprinklers

### Heater

| Item Name                                                    | Usage                                                        | Additional Notes                                             | Research Cost | Found In                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------- | ------------------------------------------------------------ |
| [Electric Heater](https://rustlabs.com/item/electric-heater) | Provides almost 100% temperature to your plants (Watch [this](https://www.youtube.com/watch?v=YmGT2vG14nk) for more placement info) | Each Heater consumes 3 energy and has a passthrough so you can chain Heaters together. Can be bought at Bandit Camp for 75x Scrap | 75x Scrap     | [Sunken Chest](https://rustlabs.com/entity/sunken-chest) 2%, [Crate](https://rustlabs.com/entity/crate) 1%, [Oil Rig Scientist](https://rustlabs.com/entity/oil-rig-scientist) 0.2% |

- In the winter biome or in all other biomes at night time your plants will drop in temperature, negatively impacting the growth/yield.
- In my tests, 2 Heaters for a 2x2 farm is sufficient to put all plants at 95% (0 H-genes) or 100% (>0 H-genes) temperature. 95% is perfectly fine though, unless you want to farm with fertilizer
- A setup to complement the one explained in the Ceiling Lights paragraph:
  - Branch of 8 energy from before the Battery with an [Electrical Branch](https://rustlabs.com/item/electrical-branch)
  - 1x [Small Rechargable Battery](https://rustlabs.com/item/small-rechargable-battery) (~6 energy output at 8 energy input)
  - 2x Heaters (3 energy consumption each, 6 in total)

### Total Resources (2x2 farm)

Here is a rundown of the Scrap cost to research all items needed for the 2x2 farm described above without the tech tree:

| Item                      | Scrap Cost |
| ------------------------- | ---------- |
| Large Planter Box         | 20         |
| Ceiling Light             | 20         |
| Sprinkler                 | 20         |
| Heater                    | 75         |
| Large Solar Panel         | 75         |
| Small Rechargable Battery | 20         |
| Water Pump                | 75         |
| Powered Water Purifier    | (75)       |
| Fluid Switch & Pump       | 20         |
| Electrical Branch         | 20         |
|                           |            |
| **Total**                 | 345 (+75)  |

## Stages

## Growth

## Yield

## Results

