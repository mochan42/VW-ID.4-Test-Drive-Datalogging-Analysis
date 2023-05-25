# VW-ID.4-Test-Drive-Datalogging-Analysis

* The aim of this project was to record data from a VW ID.4 using RossTech VCDS Hex V2 Diagnotic Tool.<br>
* The recorded data was then analyzed to understand in a simple way the relationship between driving style and battery energy consumption.<br>
* The tests were conducted in October 2021. The VW ID4 had been kindly lent to 42 Wolfsburg by CARIAD. <br>

<br><br>

# Setup of the datalogger : RossTech VCDS Hex V2 Diagnotic Tool

![Capture d’écran 2023-05-25 à 23 20 38](https://github.com/mochan42/VW-ID.4-Test-Drive-Datalogging-Analysis/assets/107719618/638e3804-dd3e-4655-a48d-801f603807d2)

<br><br>

# Results

* With 3 drivers using the same route, we can notice that driver #2 has the highest battery energy consumption : 18.4kWh.

![Capture d’écran 2023-05-25 à 23 23 20](https://github.com/mochan42/VW-ID.4-Test-Drive-Datalogging-Analysis/assets/107719618/b34e9211-c732-4d7d-9582-1688d431f1f5)

<br>

* From the data logged from the vehicle, we can see that the accelerator pedal trace in red for driver #2 has a more aggressive shape than for driver #3 in green. Hence the bigger current draws (negative values) causing a bigger battery state-of-charge-depletion (for instance at t≈550s)
* We can also see driver #2 has higher vehicle speed compared to driver #3 from t≈920s to t≈960s, this resulting in bigger current draws (negative values) leading to bigger battery state-of-charge-depletion.

![Capture d’écran 2023-05-25 à 23 35 28](https://github.com/mochan42/VW-ID.4-Test-Drive-Datalogging-Analysis/assets/107719618/1574a4de-2fef-4d12-9709-09ea5d49e714)
