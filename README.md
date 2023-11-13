## Introduction <a id='data_review'></a>

Megaline is a telecom operator that offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.

### Description of the plans

**Note**: 
- Megaline rounds seconds up to minutes, and megabytes to gigabytes. 
- For calls, each individual call is rounded up: even if the call lasted just one second, it will be counted as one minute. 
- For web traffic, individual web sessions are not rounded up. Instead, the total for the month is rounded up. 
- If someone uses 1025 megabytes this month, they will be charged for 2 gigabytes.

**Surf:**
- Monthly charge: `$20`
- 500 monthly minutes, 50 texts, and 15 GB of data
- After exceeding the package limits:
- 1 minute: 3 cents 
- 1 text message: 3 cents
- 1 GB of data: $10


**Ultimate**
- Monthly charge: `$70`
- 3000 monthly minutes, 1000 text messages, and 30 GB of data
- After exceeding the package limits:
- 1 minute: 1 cent
- 1 text message: 1 cent
- 1 GB of data: $7


### **Project description** <a id='data_review'></a>

This is a preliminary analysis of the plans based on a relatively small client selection. 
The data on 500 Megaline clients: 
- who the clients are, 
- where they're from, 
- which plan they use, 
- and the number of calls they made and text messages they sent in 2018. 

The Purpose is to analyze the clients' behavior and determine which prepaid plan brings in more revenue. 


### **Hypothesis** <a id='data_review'></a>

- Null Hypothesis (H0): The Surf Plan brings in more revenue as it costs less and more people can affort it
- Alternative Hypothesis (H1): The Ultimate Plan brings in less revenue as it costs more and less people can affort it

The Purpose is to analyze the clients' behavior and determine which prepaid plan brings in more revenue. 

### **Task decomposition:** <a id='data_review'></a>

- Data preparation
    - Convert the data to the necessary types
    - Find and eliminate errors in the data
    
- Carrying out data analysis
    - Describe the customers' behavior
    - Find the minutes, texts, and volume of data the users of each plan require per month
    - Calculate the mean, variance, and standard deviation. Plot histograms
    - Describe the distributions
    
- Test the hypotheses
    - The average revenue from users of Ultimate and Surf calling plans differs
    - The average revenue from users in NY-NJ area is different from that of the users from other regions
    - Determine the best alpha value to use, the explain:
        - How the null and alternative hypotheses are formulated 
        - What criterion was used to test the hypotheses and why
        
- Provide an overall conclusion
