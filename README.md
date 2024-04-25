# Project 2
Group Members

Gwen: https://github.com/gaw63800/Group-Project-2-4610

Caroline: https://github.com/carolinetcooper6/Group-Project-2/blob/main/README.md

Charlie: https://github.com/charles8888/Project2 

Hubah: https://github.com/hubahakhtar/Project2

Kishen: https://github.com/supersomeone03/Group-Project-2-4610/tree/main


# Data set:

Youth Tobacco Survey
https://catalog.data.gov/dataset/youth-tobacco-survey-yts-data

# Dataset Description:
The Youth Tobacco Survey (YTS) was developed to provide states with comprehensive data on both middle school and high school students regarding tobacco use, exposure to environmental tobacco smoke, smoking cessation, school curriculum, minors' ability to purchase or otherwise obtain tobacco products, knowledge and attitudes about tobacco, and familiarity with pro-tobacco and anti-tobacco media messages. The YTS uses a two-stage cluster sample design to produce representative samples of students in middle schools (grades 6–8) and high schools (grades 9–12). The data for the STATE System were extracted from Youth Tobacco Surveys from participating states. Tobacco topics included are cigarette smoking prevalence, cigarette smoking frequency, smokeless tobacco products prevalence, and quit attempts.

# Dataset Content(s):
Each row within our dataset is a youth tobacco survey entry conducted according to the recorded year. The important columns we have focused on within this dataset are the year the YTS was conducted (YEAR), the state in which it was conducted(LocationDesc), the topic type being “tobacco usage” for all data entries(TopicType), the detailed description of that topic (TopicDesc), the source of our data (DataSource), the responses from the YTS (Response), the data value(Data_Value) and its data type (Data_Value_Type), which genders were focused per survey (Gender), what races were observed (Race), the age group(s) observed (Age), and the education level of the student(s) (Education).

# Two meaningful questions and Importance:

1. How does education level affect the levels that survey respondents use tobacco over time?
   
→ This question is meaningful because it is a topic that is relatively frequently researched. It is known that education level from middle to high school shows a very distinct age range, and age is a strong indicator of brain development, therefore, this question is more so linking age and brain development and using tobacco products. This is also a question that can be very useful for parents with children around this age; Some parents are very oblivious to assume “No, my middle or high schooler does not use tobacco products.” This display clearly shows that that is not true for many children of that age from this data set. In light of many recent campaigns to encourage open conversations between parents and their children regarding drug/alcohol safety, a display such as this will encourage parents to bridge that gap and join this movement of more open conversations about safety, as this is undeniable that an increasing number of middle schooler over time as well and an even higher about of highschoolers over time have used tobacco products. 
![a](https://github.com/hubahakhtar/Project2/assets/165077668/db8e8c5e-6340-46f5-ba04-cb518cef0ac9)

2. How does the amount of people/density of people who frequently smoke change over time by state?
   
→ This question is meaningful because we can see the various influences of social, economic, and cultural changes directly impacting the data. High smoking prevalence correlated with increased healthcare costs due to smoking-related illnesses creates increasing healthcare costs. Also, states with stricter tobacco policies often experience declines in smoking rates which can aid in decreasing healthcare costs. We can track the data to use later to predict healthcare costs for the future. Analyzing smoking prevalence in certain southern states and constantly changing policies provides insights into the effectiveness of public health policies in place. The cultural norms continuously developing and “trends” coming and going reflects shifts in societal perceptions and behaviors. By integrating multiple data sources, researchers can uncover complex relationships between smoking behavior and economic factors, informing evidence-based policies and interventions to reduce smoking prevalence and its associated burdens.

Aggregate state data:
![b](https://github.com/hubahakhtar/Project2/assets/165077668/67e9a783-e8f3-459e-8b29-c84bb1265ded)
![c](https://github.com/hubahakhtar/Project2/assets/165077668/ea7b5d91-bca3-4456-b4c6-2a65f7607e88)

# Manipulation(s) during analysis:
To accurately display the density of frequent smokers across the different periods, we had to change the color legends to be consistent with each other. The colors on the map accurately show the range of .13% - 10.83%. That way our map would show the same colors. 
Tableau also helped us generate the longitude and latitude for each state based on the name. This allowed us to accurately plot on the map. 

# Analysis & Results:
According to our histogram data analysis comparing the education levels and their responses, the most saturated section appears to be high schoolers responding with “Ever”, specifically during the late 1990s being the peak. The general trend across all six histograms is a constant decline as time goes on from 1999 to 2017. When it comes to the level of education, high schoolers seem to have a higher rate of tobacco usage than middle schoolers. In terms of the response, “Ever” appears to be the highest frequency of response type. This is the preferred outcome, as this suggests that both high school and middle school students understand the potential consequences of tobacco usage. 

Based on the data analysis and results from our heat map, our team has concluded that tobacco usage among teenagers has overall been diminished across the United States as a whole. There are some outliers to the common pattern of decline in teenage tobacco usage, some of them being the states of Kentucky (KY), West Virginia(WV), and New Hampshire(NH). Looking solely at our data from 1999 to 2017, the states that appear to have little to no presence of teenage tobacco usage are California (CA), Utah (UT), Idaho (ID), Wyoming (WY), Colorado (CO), New Mexico (NM), Texas (TX), Iowa (IA), Virginia (VA), New York (NY), Maryland (MD), Vermont (VT), Massachusetts (MA), Rhode Island (RI), and Maine (ME). Specifically, we narrowed down our data analysis (line graph) to the Southern states of Alabama, Georgia, Louisiana, and South Carolina. Among the four states, Georgia appeared to have the highest in 1999 but by 2017 had the lowest frequent tobacco consumption by students. This can allow us to assume that anti-tobacco campaigns for young students have proved to be more successful and effective in Georgia than in Louisiana, Alabama, and South Carolina.




