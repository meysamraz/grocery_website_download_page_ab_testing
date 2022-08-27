# Grocery Website Download Page AB Testing 


**In this use case I am working as an analyst for a large grossery chain. One of the goals our company has, it's to drive more customers to download thier mobile app and register for the loyalty program.**

One of the goals of the company discussed here is to get more users to download the mobile app and sign up for the customer loyalty program.

<p><img src="src/demo.png" alt=""></p>

##### The company is making a link change to a button in the app store and asking if clickthrough rates will increase for the app download page?

## <font color='#d62828'>1- Explain methodology step-by-step foo :</font>

 - ###  <font color='#f77f00'>What data do we have ?</font>

   - IP Address: Client's IP Address
   - LoggedInFlag: Indicates whether the user has a profile on our website
   - ServerID: Belonging to the Treatment and Control group, 1: Treatment , 2-3: Control
   - VisitPageFlag: The status of the user clicking the download link
   
 - ### <font color='#f77f00'> Whats the Duration Of the Test</font> ? 
   - 1 Weak 
   
 - ### <font color='#f77f00'> What's our unit of analysis </font> 
    - IP Address: Client's IP Address 

 - ### <font color='#f77f00'>  What's our metric to measure success here </font> 
   - Number clicked in download  
   
- ### <font color='#f77f00'> The size of our treatment and control groups </font> 
  - 1/3 of the treatment units and 
  - 2/3 of control units.
  
 - ### <font color='#f77f00'>  What's our MDE (Minimum Detectable Effect) ? </font> 
   - MDE 1% 
   
-  ### <font color='#f77f00'> Apply hypothesis testing and check assumptions </font> 
      - Check Normality & Homogeneity
      - Apply tests (Shapiro, Levene Test, T-Test, Welch Test, Mann Whitney U Test)
      - Evaluate the results
      
 
 ### Libraries and Packages : 
 
 - [matplotlib](https://matplotlib.org/)
 - [seaborn](https://seaborn.pydata.org/#:~:text=Seaborn%20is%20a%20Python%20data,introductory%20notes%20or%20the%20paper.)
 - [pandas](https://pandas.pydata.org/)
 - [numpy](https://numpy.org/)
 - [scipy](https://scipy.org/)      
