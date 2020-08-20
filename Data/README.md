# DATA DESCRIPTION

For both train and test, each row corresponds to a customer, assigned a unique customer ID (‘ID’). There is some information on the customer (when they joined, birth year etc). The customer’s occupation (‘occupation_code’) and occupation category (‘occupation_category_code’) are also provided, along with the branch code of the office they visit. The final 21 columns correspond to the 21 products on offer.

In Train, there is a 1 in the relevant column for each product that a customer has. Test is similar, except that for each customer ONE product has been removed (the 1 replaced with a 0). Your goal is to build a model to predict the missing product.

SampleSubmission shows the required submission format. For each customer ID, for each product, you must predict the likelihood that that product is one in use by the customer. Notice that the sample submission contains 1s for the products that are included in the test set, so that you can focus on the unknown products

Leave your predictions as probabilities with values between 0 and 1 and do not round them to 0s or 1s.

# FILES

- SampleSubmission.csv - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the ID must be correct.
- Train.csv - this is the file you will use to train your model.
- Test.csv - this is the file you will use to test your model.
- VariableDefintions.txt - descriptions of the variables
