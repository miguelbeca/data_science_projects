
This project is an analysis of Medicare charges data obtained from CMS in order to identify possible relationships between charges and demographics. Tools used included Oracle SQL and Python (libraries: pandas, pyplot). 

The final report of the project can be found [here](https://github.com/miguelbeca/springboard_data_science/blob/master/Capstone%20Project%201%20-%20Medicare%20Charges/Capstone%20Project%201%20-%20Final%20Report.pdf).

The presentation can be found [here](https://github.com/miguelbeca/springboard_data_science/blob/master/Capstone%20Project%201%20-%20Medicare%20Charges/Capstone%20Project%201%20-%20Presentation.pdf).

Project Summary and Conclusions:

The focus of this capstone project was to try to determine if there was a possible explanation for
the variability in submitted charges by various providers for standard medical procedures.
The dataset, however, had its limitations, as the charges data provided are average charges,
which in itself can somewhat distort the true range of values. Additionally, the fact that the
dataset includes data for bulk charges, it introduced some noise which made it more difficult to
come to a definite conclusion.

Despite these limitations, and based on the analysis performed, it can be concluded that there is
a moderate negative correlation between average charges and population size, meaning that
rural areas of the country may have higher submitted charges than more populated parts of the
country.

However, even filtering for extreme values, as it was performed using the 10% and 90%
percentile ranges, there is still quite a discrepancy between average charge values at the lower
end and those at the higher end. As a consumer of healthcare, and after performing this
analysis, I do not find a clear reason for why such discrepancies exist, other than there is not
much regulation regarding healthcare costs and providers are pretty much free to charge
whatever they like. Also, a lack of competition in rural areas can explain part of the issue,
however, this factor should not be used a reason to do so.

One other cause of concern when analysing healthcare charges data is also the possibility of
fraud. Unfortunately, fraud with Medicare and other government programs in not uncommon,
and making this sort of analysis can be relevant to help spot anomalies and unusual situations
in the data. Just as an example, one of the largest Medicare fraud cases in the United States is
now in its initial court proceedings, involving a total of around $1 billion dollars, while recently,
Walgreens settled a fraud case in the amount of $296 million dollars.

Lastly, this dataset provided many avenues of exploration and, for future work, it would be
interesting to analyse average charges based on the qualifications of the providers in order to
understand if there is any sort of relationship between the two variables.
