# BankofBarodaChallenge

Hey man, first install python libraries such as Numpy, Scipy, Pandas and flask-restplus
(I'll recommend you to install Anaconda since it comes with everything)
Then run Python loan_flask.py 
UI will start running on localhost:5000
Subsequently, you can only use curl request 
curl -X POST \
   --header "Content-Type: application/x-www-form-urlencoded" \
   --header "Accept: application/json" \
   -d "NumberOfOpenCreditLinesAndLoans=12" \
   -d "NumberRealEstateLoansOrLines=0" \
   -d "age=32" \
   -d "DebtRatio=1.247340213" \
   -d "NumberOfDependents=0" \
   -d "MonthlyIncome=12500" \
   -d "RevolvingUtilizationOfUnsecuredLines=0.319779462" \
   -d "NumberOfTimes90DaysLate=12" \
   -d "NumberOfTime60-89DaysPastDueNotWorse=0" \
   -d "NumberOfTime30-59DaysPastDueNotWorse=0" \
   "http://localhost:5000/approve_loan/"
   
   I've used some of my own code for classifier and referred a tut for creating localhost api. let me know if you're stuck somewhere.

Kudos,
Naman
