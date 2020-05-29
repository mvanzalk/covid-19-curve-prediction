# covid-19-curve-prediction

## Title
Decision Tree Regression model for predicting COVID-19 cases and the death rate in case of a second wave

## Which is the problem the solution solves?
The corona virus has turned the world upside down - many countries did not expect the effects of the virus and, due to its rapid spread, did not have enough capacity and sufficient intensive care beds in hospitals to adequately treat all corona virus patients. In addition, no one was prepared for the sudden significant increase in the death toll, and this also led to an overload of systems. What the extremely high, unexpected case and death figures mean is shown by the dramatic pictures from Italy or New York. If there are not enough beds, hospitals can become overloaded and health care collapses. Although the dramatic consequences were obvious, it was difficult to predict case and death rates in order to better assess the effects and be prepared for them.

## Solution Pitch
Our code provides a proof concept of the use of simple machine learning to model and forecast the case and death occurring during the COVID-19 crisis for an initial and rough analysis of the pandemic. The model is based on public offered time series of deaths and cases to demonstrate a freeware solution to model and project similar outbreaks with similar respective governmental plans. The code is additionally structured to that the user can define periods that want to be investigated.

## The solution
 We developed a decision tree regression with scikit-learn codes which enables us to predict future cases and death rates in case of a second wave based on past case and death rates. The regression model is trained on publicly available time series data provided by the EU.
 
## Impact on the crisis (max 200 words)
The Machine learning code allows governments and institution to model to simulate and forecast a potential second wave of infection or similar outbreaks for an initial analysis. The forecasts allow the initial organization of resources such as testing kits, hospital beds, mask to name a few for future need. Additionally, if a second wave of infection occurs the model can project death and case for cases where similar restrictions are implemented. The faster responses time for critical event and organization of resources would limit the spread of the infection and most importantly reduce unnecessary deaths. An additional advantage of the code is use publicly accessible time-series data of deaths and infection, and as such it provides a freeware solution to forecast the outbreak for institutions and poorer countries.
