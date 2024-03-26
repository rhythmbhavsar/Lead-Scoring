# Lead Scoring 

## Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

There are a lot of leads generated in the initial stage, but only a few of them come out as paying customers. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

## Goal of the Study
- To build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads.
- A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
- We will also try to check if certain adjustments or recommendations can be made to ensure that we are suggesting the right business solutions to tackle future problems as well.

## Recommendation
- Initiatives should be taken to get more leads from Lead Add Form as their conversion rate is above par.
- The website can be made more interactive to engage customers and increase the overall time spent on the website, which will indeed increase the conversion as observed in the EDA.
- Working Professionals can be targeted more, as they have the spending capacity and willingness to upskill themselves which can also be seen in the analysis.
- Students can be avoided as they are already enrolled in a course and might not purchase a course for industry professionals this early in their careers.
- Loyalty programs can be initiated for our existing customers to get more references from them as the conversion rate is very high.
- Similarly, leads whose last Notable Activity was SMS and who visit the website repeatedly on a regular basis can be nudged towards conversion.

## Conclusion
- Our model development process involved several crucial steps to ensure accuracy and reliability. Initially, we applied one hot encoding to convert categorical variables into a suitable format for modeling.
- Subsequently, we utilized Recursive Feature Elimination (RFE) to identify the most significant features, enhancing our model's predictive capability.
- Building on this foundation, we constructed logistic regression models and refined them iteratively based on improving p-values. This iterative process enabled us to fine-tune the models for optimal performance.
- This approach led to an impressive accuracy rate of around 80% and a precision rate of around 75%, showcasing the effectiveness of our method in predicting lead conversions.
- To validate our model's performance, we rigorously tested it on unseen data, confirming its reliability and applicability in real-world scenarios.
- Overall, our systematic approach and meticulous attention to detail have yielded a robust predictive model capable of providing valuable insights for enhancing lead conversion rates and optimizing resource allocation strategies.
