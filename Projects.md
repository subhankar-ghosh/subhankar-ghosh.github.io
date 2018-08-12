## Projects

I was extremely blessed to be part of the following projects through which I have learnt a lot. I would like to take this opportunity to thank all those people who have helped me in doing the following projects and whet my skills.

### Curb Domestic Violence
*Feb 2016 – Dec 2016*

We had given a **poster presentation based on this project in  Microsoft Machine Learning, Analytics & Data Science Conference, Redmond, 2015.** You can find the **complete paper [here](MLADS%202016-CurbDomesticViolence.pdf).**

Domestic Violence is a big issue in our society. Everyday thousands of men and women suffer from domestic violence and majority of these cases do not come out in the open due to various reasons. The victims are generally scared to talk about it and ask for help.

In this project we aimed to detect domestic violence automatically using an app which recorded sound and after analysis of the the sound signals our algorithm predicted domestic violence in real time. The sound signals were transmitted to an algorithm hosted in AzureML that detected domestic violence. If domestic violence was detected immediate help was sent. This project is still being researched by the Microsoft Research, India.
  
  Factors taken into account were analysis of text extracted from the speech using speech to text APIs in Cortana Analytics. Text classification was done using a LSTM(Long Short Term Memory) neural network. 
  
  Another factor was the decibel level of the sound that was recorded, a simple regression model was trained using decibel levels.
  
  An ensemble of the two models gave a recall value of 0.47. The main reason of a low performance is the lack of proper training data.
  
  Models were trained on movie subtitles, in which the violent scenes are manually marked as domestic violence. Hopefully the ongoing research on this problem would lead to better performance.

We had used: Python, Azure Stream Analytics, Azure ML, Text mining and classification, Speech to text in Cortana analytics suite.


### Let's Envisage
*Aug 2015 – Jun 2016*

  **A patent [EFFICIENT TASK PLANNING USING PAST PERFORMANCE (Patent number: US20180150786A1)](https://patents.google.com/patent/US20180150786A1/en?q=EFFICIENT&q=TASK&q=PLANNING&q=USING&q=PAST&q=PERFORMANCE&oq=EFFICIENT+TASK+PLANNING+USING+PAST+PERFORMANCE) has been published under the United States Patent and Trademark Office.**


In a developer environment, utilizing the developers efficiently is the key to improve their productivity and team's overall performance. Presently, senior members assign work items to developers mostly based on intuition. Hence, the estimated time set by senior members within which the work item needs to be completed, may be inaccurate resulting in either overloading or under-utilizing the developer. 

Our tool makes sprint planning a lot simpler by guiding the senior member to allocate task to the correct developer and to provide better time estimates for work items, thereby efficiently managing the available resources. The tool also takes a list of work items planned for a particular Sprint and efficiently assigns those work items to members of the team depending on the difficulty of the work item, experience and time availability of the members of the team. Made use of: Python, C#, SQL, Azure Machine Learning Suite.

### Azure Virtual Architect
*Mar 2016 – Jun 2016*

Azure provides multiple solutions for each problem. So many architectures can be built on azure with different cost,efficiency and performance. This virtual architecture takes the requirement as different input parameters and recommends the most optimum solution. Input was given as raw text and we used nltk to parse the input. 

   We crawled azure docs and using text mining we built the training dataset. The input features are now mapped to output design via cosine similarly and euclidean distance. This project was done when I was a part of Microsoft R&D India with team mates Swaraj Khadanga and Anubhav Panda.
   

### Characterization of mammograms using classification techniques for breast cancer detection
*Aug 2014 – Mar 2015*

This was my research project in NIT Rourkela while my B Tech. Breast cancer is one of the most rapidly spreading cancers in the world today and so an efficient and accurate method for detecting it is necessary. This project aims at designing and implementing a computer aided model for efficiently and accurately determining from a given mammogram(xray images of women breasts) if it has cancer or not, if yes then its extent accurately.

   In this project my role is that of a research assistant where my work is for devising an appropriate data preprocessing technique and classification technique which will classify the mammograms accurately.
Skill Used: MATLAB, WEKA, programming, datamining techniques, classification.
