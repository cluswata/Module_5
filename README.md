# Module_5
Practical Application Assignment 5.1
Findings for Bar Coupons
[Read_me_module5.docx](https://github.com/cluswata/Module_5/files/15298858/Read_me_module5.docx)

Aim 1: Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
H0: Drivers who go to a bar more than 3 times a month are less likely to accept bar coupons compared to drivers who go to a bar 3 or fewer times a month.
Conclusion: From the analysis it was observed that the acceptance rate among those who went to a bar 3 or fewer times a month was 52.8% compared to 76.9% of those who went more than 3 times.

Aim 2: Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?
H0: Drivers aged 25 and older who go to a bar more than once a month are less likely to accept bar coupons compared to all others.
Conclusion: The acceptance rate among drivers who went to a bar more than once a month and were over the age of 25 was 69.5% while it was 33.5% among all others.

Aim 3: Compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.
H0: Drivers who go to bars more than once a month with passengers other than a kid and are in occupations other than farming, fishing, or forestry are less likely to accept bar coupons compared to all others.
Conclusion: The acceptance rate among drivers who went to bars more than once a month and had passengers that were not a kid and were in occupations other than farming, fishing, or forestry was 71.3% while it was 29.5% among all others.

Aim 4: Compare the acceptance rates between those drivers who:
•	go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
•	go to bars more than once a month and are under the age of 30 OR
•	go to cheap restaurants more than 4 times a month and income is less than 50K.

H01: Drivers who go to bars more than once a month with passengers other than a kid and are not widowed are less likely to accept bar coupons compared to all others.
H02: Drivers who go to bars more than once a month and are under the age of 30 are less likely to accept bar coupons compared to all others.
H03: Drivers who go to cheap restaurants more than 4 times a month and earn an income less than 50K are less likely to accept bar coupons compared to all others.

Conclusion: The acceptance rate among those drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed was 71.3% while for those drivers who go to bars more than once a month and are under the age of 30 was 72.2% and for those drivers who go to cheap restaurants more than 4 times a month and income is less than 50K was 45.4%. The acceptance rate among those drivers who belonged to at least one of the 3 categories above was 58.9%.

Independent Investigation: Characteristics of passengers/drivers who accepted the Coffee House coupons.
From the analysis, acceptance rate for coffee house coupons was 49.9%.

Using the decision tree classifier with entropy criterion, the predictor spaces below were selected for further analysis.

1.	(driving destination ==No Urgent Place) X (time at or before 6PM) X (expiration == 2h)
2.	(driving destination ==No Urgent Place) X (income outside the range "$75000 - $87499") X (occupation not Student)
3.	(driving destination ==No Urgent Place) X (occupation == Student)

Conclusion: The acceptance rate of Coffee House coupons was highest among students who had no urgent driving destination/place (73.3%) followed by non-students earning outside the range $75000 - $87499 and had no urgent place to be (57.4%). For coffee house coupons expiring within 2 hours, drivers who had no urgent destination to go at or before 6pm accepted them at a rate of 53.3%.

The acceptance rate among drivers who belonged to at least one of the 3 categories above was 58.6%.

Sensitivity analysis: Incorporating number of times been at a coffee house and gender.
None of the predictor space in the CART model/decision tree selected gender. The interaction pattern below was further explored.
1.	(Ever been at the coffee house) X (expiration > 2h) X (driving destination!=No Urgent destination)

Conclusion: The acceptance rate of coffee house coupons expiring within a day among drivers heading to work or home and have ever been to a coffee house was 62.8%.
