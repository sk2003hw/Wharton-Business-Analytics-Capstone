# Wharton Business Analytics Capstone
Business Analytics Capstone from the Business Analytics Specialization from Wharton School, University of Pennsylvania, Coursera  
Applied the knowledge of analytics, marketing, human resources, finance, and operations to interpret a real-world data set and make appropriate business strategy recommendations as a part of the capstone project.  


## Optimization Model Scenario (as taken from Coursera)

GYF has a robust training program.  Two of its training programs are known as the “Hard Skills Program” and the “Soft Skills Program.”  Each of these trainings has two sub-programs: “External” (focusing on employee tasks mainly dealing with clients and customers outside GYF) and “Internal” (focusing on employee tasks mainly dealing with fellow GYF employees).    
As the leader of the DATA team, you can enroll your employees in these training programs, but you must decide how to best allocate your training budget of $65,000 among these four training options (Hard Skills/External, Hard Skills/Internal, Soft Skills/External, and Soft Skills/Internal).   

 You decide to base this decision on productivity return rates.  GYF’s management has calculated that the productivity return (i.e., the expected extra productivity in the next period, in the equivalent of U.S. dollars, that is achieved for each U.S. dollar spent on training, net of training cost) is proportional to the amount of money spent on training and can be expressed as follows:  

<img width="593" alt="image" src="https://github.com/sk2003hw/Wharton-Business-Analytics-Capstone/assets/71402153/f8f09bb7-353e-4abd-8301-2c9a989a8656">



This means that $10,000 spent on the Internal Hard Skills Program results in $2,000 worth of increased productivity in the next period.  This return is cumulative, meaning that if you spent $10,000 on the Internal Hard Skills Program and $10,000 on the External Soft Skills Program, your total dollar return in productivity increases would be 10000*.2+10000*.4.   

You need to decide how much of your budget to spend on each type of training to maximize the total productivity return.  But you can’t simply spend all your budget on the type of training with the highest return, because there are three requirements (in addition to staying within your budget) that management is requiring you to satisfy in allocating your training budget.  They are:   

The Hard Skills training program must achieve at least $20,000 in the total net productivity increase;   

The Soft Skills training program must achieve at least $12,000 in the total net productivity increase; and   

The Internal program should achieve at least 60% of the net productivity increase realized for the External program.   

Assume all these figures are “deterministic” – known, and non-random.   

Your task for this Application Exercise is to follow the steps outlined in Module 2 of the Operation Analytics course to:    

1.  Algebraically express the various relationships between the factors outlined above; and   

 2.  Use a spreadsheet application like Excel and a function like Solver to allocate your budget in a way that maximizes the productivity return (i.e., determine what amount of the budget, if any, should be spent on each of the four types of training to maximize productivity, subject to the constraints). 
