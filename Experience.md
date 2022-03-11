## Experience

### Deep Learning Engineer at NVIDIA
*July 2019 - Present*

I have worked on multiple deep learning solutions in Computer vision and graph neural networks. Currently, I am actively involved in Conversational AI research.

### Research Assistant at Cline Center for Advanced Social Research (UIUC)
*January 2017 - May 2019* 

I worked on the [ResTeCo](https://clinecenter.illinois.edu/project/NewsAnalytics/responsible-terrorism-coverage-resteco) project. The aim of this project is to identify ways of reporting terror news that will be informative but will not instill fear and panic among the public. Also the news reports should not help the terrorists in achieving what they want like fame, importance etc. 

For this we are working with a huge corpus of New York Times news articles. 
In the Spring 2017 I have worked on two major tasks:
   
   -  Devising an algorithm that automatically corrects any spelling mistakes in the corpus. This involves OCR-post correction as well as spelling correction in digital text. I experimented with rule based methods as well as a more sophisticated [n-grams language model](https://easyintuitions.wordpress.com/2018/07/27/statistical-language-model/) with [interpolation smoothing](https://easyintuitions.wordpress.com/2018/07/27/smoothing-in-n-gram-model/) to incorporate context based methods of spell-checking. I have built an n-gram model from cleaned Wikipedia n-gram data and am using it for context based spelling correction.
   
   -  OCR-post correction using Machine Translation. If we consider OCR as one language and corrected english as another then this boils down to a machine translation task. I have used an character level [encoder-decoder neural network](http://aclweb.org/anthology/I17-1101) to transform OCR data to corrected english text. I have used a bi-LSTM layer with 512 hidden units as encoder as well as decoder. Experimented with multiple encoder-decoder architectures and performed extensive literature survey in machine translation. Currently performing more experimentations for further improving the performance of the model. Trained model on single Tesla k80 GPU.
   
   -  Used topic modelling techniques to identify articles of interest (articles talking about terrorist activities) and also analyze how a topic of interest as developed over time ([Dynamic Topic Models](https://mimno.infosci.cornell.edu/info6150/readings/dynamic_topic_models.pdf)). I am currently conducting research on the important topic modelling methods which have worked well with OCR text. Used LDA for topic models and [LDA2Vec](https://arxiv.org/abs/1605.02019) for extracting topic specific features.
   

### Researcher at University of Illinois at Urbana-Champaign
*September 2017 - December 2017*

[Detailed Report](Readme-style.pdf) and [Code](https://github.com/subhankar-ghosh/UIUC/tree/master/Fall17/Research).

In this project I worked under Prof. Vetle Torvik in Torvik Research Group on stylometry. Trying to determine style of every author and the age group or the ethnicity of the author of the research paper. I came up with a mathematical model for style of writing of different authors. 

   I used standard NLP techniques along with statistical analysis in this project.

### Software Engineer at Microsoft R&D India Ltd
*June 2015 - July 2017*

Worked closely with business and IT partners during early SDLC phases to understand the business capabilities and goals for the program Develop engineering artifacts such as Logical Data Model, System Conceptual model, Component Interaction Model etc. Created windows and web services based on the Microsoft platform. Understood the existing systems, while analyzing upstream and downstream system impacts. Adept at working cross-group with other teams, as our development projects are often coordinated with other teams around the world. Used C#, SQL, javascript, Azure cloud technologies.

   Created a system to predict the rewards of employees based on the feedback from teammates and managers automatically. Used NLP and deeplearning techniques to mine the huge amount of employee feedback and come up with a technique that would predict the rewards with 87% accuracy. Used Python, TensorFlow, RNN.

### Software Engineer Intern at Microsoft R&D India Ltd
*May 2014 - July 2014*

I worked as a Software Developer Engineer intern during my internship with Microsoft. Developed an app completely by my own that helped new employees to onboard to the company easily.
