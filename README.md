# Project Tibia
Project Tibia offers an easy way to pre-diagnose Tibial Pseudoarthrosis. 

## How it works?
It does so by capturing and analyzing various aspects of the subject such as the length of the tibial bone, ratio of the tibial bone of the left and the right leg and the amount of swing achieved by the knee joint. Using these metrics, we obtain an arbitrary score which we normalized using data captured through 40,000+ samples taken during the Hackathon where the attendees were observed for their walking pattern. This model is then compared with the live and average data taken from the subject during the test. If a deviation beyond a certain margin is observed, the application recommends consultation of a medical professional for confirmation of the disease.

## Technologies Used:
We used Microsoft's Visual Studio and Kinect for Windows SDK to build Tibia.

## Challenges we ran into.
The biggest challenge we faced was to distinguish and teach our model, how to detect the presence of Tibial Pseudoarthrosis despite having access to the vast amount of healthy samples at the event which was a folly in itself. We did not have access to any of the prior medical history of any of our samples. Access to patients who tested positive to Tibial Pseudoarthrosis using conventional medical tests would go a long way in enforcing our model.

## Lessons.
Today, we got to learn about a lesser known disease that plagues our society and how it can be diagnosed in it's early stages apart from the technical know-how of using a Microsoft Kinect and it's dire potential in such applications.

## What's next?
We would love to get access to some patients of whom, we have prior medical history. We hope that this project leads to a much needed disruption in the field of medical diagnosis through the use of ever-evolving computing devices. 