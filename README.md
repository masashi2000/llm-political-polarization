# llm-political-polarization
In this repository, you can check the below data:
1. Democrat and Republican Narratives in narratives directory.
2. Conversation data (e.g. conversation\_data/confirmation\_bias/healthcare\_Dem0\_Rep2\_Round10/conversation1.csv)
3. Raw Answered data (e.g. conversation\_data/confirmation\_bias/healthcare\_Dem0\_Rep2\_Round10/survey1.csv )
We execute asking question 3 times with same prompt sets. (e.g. Asking Tom about question 3 trial times at the end of Round3.)
This is because the llm sometimes make very different attitude. We caluculate the mode from 3 trial answer, then use it for analysis.

4. The attitude answer with modes (e.g. conversation\_data/confirmation\_bias/healthcare\_Dem0\_Rep2\_Round10/all\_survey.csv) 
