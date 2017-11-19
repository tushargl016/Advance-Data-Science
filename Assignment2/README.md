#### Command to run the LUIGI pipeline for Accepted Loan Data 
python loandata.py --local-scheduler FeatureEngineering

#### Command to run the LUIGI pipeline for Declined Loan Data
python declined.py --local-scheduler DeclinedFeatureEngineering
