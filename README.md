# Titan-realtime-problem
Cement Mill Process
This is a mimic of the Cement Mill in PECEM Plant in Brazil. This gives an overview of the process
of the mill.

You can find a more detailed mimic in a separate file accompanied with an excel file which maps
the numbers in the mimic with the tag names of the sensor variables.


Block 1: Separator Motor Block
For analysis purposes the production process can be broken down to several blocks. Each block
describes a specific part of the process. For example, the Separator Motor Block gives us the
dependence of the energy expenditure of the separator from the input variables. These
dependencies have been determined by business knowledge, which means that there might be
other dependencies that can be identified by extra analysis.

Block 2: Mill Differential Pressure Block


Tasks
You are given a dataset that contains measurements for a 4-month period from a cement mill
plant. There are 2 separate problems that need to be addressed, i.e. the Blocks above. Each of
these has a series of inputs (which are the independent variables that should be used) and one
output (that will serve as the target variable). These are described in the Figures above.
For each of the two blocks:
1. Check the dataset for irregularities (e.g. missing or extreme values, values in bad format)
and make the appropriate actions if needed.
v
3. Quantify the delay time (if any) between a variation in the input variables and the
outcome effect in the output variable.
4. Explore the correlation of the output variable with the input variables using visual and
statistical methods and describe the influence on the output variable that a variation of
the input values causes.
Main Task
5. Using the proposed input variables (and any other variable from the received dataset
that you think is relevant) create a model that, given the operating conditions of the
mill, can predict the output variable for the next 5 minutes, in 30 second intervals.
Bonus Tasks
6. Investigate if the use of any other variables, not present in the block’s “input variables”,
can help.

##How Panagiotis this dumb fuck thinks of the task with google , stackoverflow and chatgpt maybe some other AIs
    Data Cleaning:
        Check the dataset for irregularities such as missing or extreme values and values in bad format.
        Take appropriate actions to handle these irregularities, such as removing or imputing missing values and addressing extreme values.

    Statistical Analysis:
        Understand the main statistical characteristics of the important input and output variables in the dataset.
        Use visual and statistical methods to analyze the variables and gain insights into their distributions, central tendencies, and variations.

    Delay Time Analysis:
        Quantify the delay time, if any, between a variation in the input variables and its effect on the output variable.
        Explore how changes in the input variables relate to changes in the output variable over time.

    Correlation Analysis:
        Explore the correlation between the output variable and the input variables using visual and statistical methods.
        Describe the influence of input variable variations on the output variable.
