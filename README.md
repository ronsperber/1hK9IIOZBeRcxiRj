#Term Deposit Marketing

Goal: We want to predict whether a customer at a bank will buy a subscription to a short term deposit. We have the following information about the customers

age : age of customer (numeric)

job : type of job (categorical)

marital : marital status (categorical)

education (categorical)

default: has credit in default? (binary)

balance: average yearly balance, in euros (numeric)

housing: has a housing loan? (binary)

loan: has personal loan? (binary)

contact: contact communication type (categorical)

day: last contact day of the month (numeric)

month: last contact month of year (categorical)

duration: last contact duration, in seconds (numeric)

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)


Model built was a LightGBM model that takes this data and predicts if the customer will purchase the subscription.
