# anomaly-detection-in-electricity-consumption

Nowadays, modern societies are confronted with the important problem of the aging of their population.
Older people often have to leave their homes for treatment by relatives or go to specialized centers for the elderly.
On the other hand, it is the same for people with disabilities who need the support of others for their daily activities.
This phenomenon has important social and economic consequences. In the activities of daily life of the elderly,
it is necessary to monitor different aspects of their physical activity, such as the detection of critical situations
(such as falls) or dangerous situations (such as floods or gas leaks). The purpose of this internship is to analyze the
consumption of different household appliances in order to model a normal behavior in the daily activities of a house.
Through the consumption of electrical appliances, the objective is to detect abnormal behaviors that lead to the emergence
of potential problems due to changes in the consumption pattern.

we use AE to reduce the dimension of data and classify it to normal or anomaly behaviour.


Requirements:
  -Keras
  -SKlearn
  -Numpy
  -Pandas
  -Scipy
  -Matplotlib
  -NILMTK : https://github.com/nilmtk/nilmtk



We use UK-DALE dataset, which is available here:
http://data.ukedc.rl.ac.uk/simplebrowse/edc/efficiency/residential/EnergyConsumption/Domestic/UK-DALE-2017


Final results:

| appliance  | f1-score (simple AE) | f1-score (VAE) |
| ------------- | ------------- | ------------- |
| télévision  | 0.93  | 0.96 |
| microwave  | 0.84  | 0.90 |
| kettle  | 0.84  | 0.88 |

