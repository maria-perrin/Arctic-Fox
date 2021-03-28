---
layout: post
title: Quantitative Energy Requirements
icon: fas fa-bolt
date: 2021-02-25 12:12:00
order: 4
toc: true
math: true
---
## Basal Metabolic Rate for Maintenance
The Basal Metabolic Rate (BMR) for Arctic foxes varies from season to season, with a 36% increase from winter to summer<sup>12</sup>. The lowest ever reported BMR is 471 kJ/day<sup>10</sup>. Other reported values, which are more common, are 735 kJ/day and 883 kJ/day for winter months, when the temperature ranges between -7 and -40 degrees Celsius<sup>10<.sup>. For future equations, I will take the average of the normal BMR values, which is 809 kJ/day (193.3 kcal/day).

![Winter](/assets/img/WinterFox.jpg)
_An Arctic fox in the winter (I17)._

## Daily Energy Expenditure for Maintenance
Daily energy expenditure (DEE) is comparable to field metabolic rate (FMR). An estimate that has been determined is 1,925 kJ/day<sup>10<.sup>. However, FMR can vary a great deal, and a range of 721-5,140 kJ/day has been proposed<sup>10<.sup>. For simplicity, I will use 1,925 kJ/day (460.1 kcal/day) for any future calculations that require DEE.

![Sitting Fox](/assets/img/AnotherFox.jpg)
_An Arctic fox (I18)._

## Daily Energy Expenditure (DEE) for Growth
Energy requirements for growth are typically between 1 and 3 kcal/g<sup>25</sup>. I will use the average of this, 2 kcal/g, for my calculations. I already have a FMR for maintenance, 460.1 kcal/day, but this does not account to the growth rate. For that, I will use the equation Y=0.0543W<sup>0.70</sup>, which is for fissiped carnivores, and according to the Robbins textbook (also the source of the equation), the Arctic fox is such a carnivore<sup>25</sup>. Since the average weight (W) for an adult Arctic fox is 3.5 kg (3500 g)<sup>10</sup>, this equation can be used. So:

Y=0.0543W<sup>0.70</sup>

Y=0.0543(3500)<sup>0.70</sup>

Y=16.43 g/day. This does not match the findings of Frafjord<sup>14</sup>, who found that male pups had gained an average of 34 g/day and females gained 22 g/day on average, however this was for about 130 days, and the pups do not reach their full adult weight in this time, so my calculated value likely makes sense for the average over the entire growth period, during which most of the growth does occur in 3-4 months. As well, these values came from captive foxes that were fed dry food ad libitum<sup>14</sup>, so their diet did not accurately represent what would.be available to wild foxes and may explain the higher gain values.

The last requirement before I can determine the DEE of growth is the energy for daily growth. Since I now have the growth rate, and I already know that the average energy requirement is 2 kcal/day, I just multiply these to get the energy required for that growth.

Energy for growth=16.43 g/day x 2 kcal/g

Energy for growth=32.86 kcal/day.

Finally, I just need to add this to my daily energy for maintenance, so I get

DEE(growth)=460.1 kcal/day + 32.86 kcal/day = 492.96 kcal/day.

Using the average gains determined by Frafjord<sup>14</sup>, I get different values. DEE for growth using his values would be 34 g/day x 2 kcal/g = 68 kcal/day + 460.1 kcal/day = 528.1 kcal/day for males and 22 g/day x 2kcal/g = 44 kcal/day + 460.1 kcal/day = 504.1 kcal/day.
## Daily Energy Expenditure for Reproduction
During gestation for mammals, energy expenditure increases between 17 and 32% compared to the DEE of maintenance<sup>28</sup>. Since I do not know where foxes fall in that range, I am going to take the average, so an increase of 24.5%. This also requires the DEE of maintenance, for which I am using 460.1 kcal/day.

$$ DEE(gestation)=1.245xDEE(maintenance) $$

$$ DEE(gestation)=1.245x460.1\ kcal/day $$

$$ DEE(gestation)=572.82\ kcal/day $$

## Number of Lemmings Needed to Meet BMR and DEE
As previously calculated, the ME for lemmings is 4.2 kcal/g. BMR for Arctic foxes is 193.3 kcal/day.

$$ BMR\ Requirement= \frac{BMR}{ME} $$

$$ = \frac{193.3\ kcal/day}{4.2\ kcal} $$

$$ =46.0, $$ so it would take 46 lemmings to meet the basal metabolic rate energy requirements.

FMR is 460.1 kcal/day.

$$ DEE\ Requirement= \frac{DEE}{ME} $$

$$ = \frac{460.1\ kcal/day}{4.2\ kcal}

$$ =109.5 $$ fresh eggs would be needed to meet daily energy expenditure requirements.
## Number of Snow Goose Eggs Needed to Meet BMR and DEE
As previously recorded, the metabolizable energy of a fresh egg is 195.0 kcal and the metabolizable energy of a stored egg is 174.5 kcal. The average BMR for Arctic foxes is 193.3 kcal/day, and the FMR is 460.1 kcal/day. So, if we divide the BMR by the ME of the eggs, it will give the eggs needed to meet the BMR.

$$ BMR\ Requirement= \frac{BMR}{ME} $$

$$ = \frac{193.3\ kcal/day}{195.0\ kcal} $$

$$ =0.99, $$ so it would take 0.99 fresh eggs to meet the basal metabolic rate energy requirements.

$$ BMR\ Requirement= \frac{193.3\ kcal/day}{174.5\ kcal} $$

$$ =1.11, $$ so if stored (or cached) eggs were being used, it would take 1.11 to meet the BMR.

For DEE, I am using the FMR value 460.1 kcal/day.

$$ DEE\ Requirement= \frac{DEE}{ME} $$

$$ = \frac{460.1\ kcal/day}{195.0\ kcal}

$$ =2.36 $$ fresh eggs would be needed to meet daily energy expenditure requirements.

$$ DEE\ Requirement= \frac{460.1\ kcal/day}{174.5} $$

$$ =2.64 %% stored eggs would be required to meet DEE.

![Summer](/assets/img/Summer.jpg)
_An Arctic fox in the summer (I19)._
