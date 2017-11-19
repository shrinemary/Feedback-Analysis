# Feedback-Analysis
With this project, we are trying to lessen the work of companies or organisation by summarising the feedback of their services or products into a score measuring the positive,negative and neutral reviews present in the feedback. We are implementing the concept of SVO extraction along with Sentimental Analysis for the project. 

Target
 Objective of the project is to input a feedback consisting of many lines and then show whether the feedback is mostly positive/negative/neutral depending sentimental analysis.
STEPS INCLUDED :
 1.Implement SVO extraction and obtain triplets  from the sentences.
 
 2.Perform sentimental analysis to obtain the results.
    
 3.Reduce the time of reading through feedbacks.
    
 4.Increase readability.
 
 REQUIREMENTS
   1. Install nltk.
   2. Install Stanford Parser
   3. Install numpy
   4. Install keras
   5. Install vaderSentiment
   6. Install twython
   7. Install tensorflow
   8. Install scikit-learn
   9. Download a dataset for analysis.
   
   Run svo-senti.py as python3 svo-senti.py.
    This will produce the svo triplets for each sentence. Each triplet pair of the sentence is given to method for sentimental analysis where sentimental analysis is performed on the SVOs using vaderSentiment tool.
     The output will be displayed as polarity scores for each sentence.
     
SAMPLE 
 Input: The place is fine.
 Output: The place is fine.
         SVO : {'place','is','fine'}
         Noun phrase:
         The place
         polarity scores:
         compound: 0.2023
         neg:0.0
         pos:0.375
         
        
         
       
      
