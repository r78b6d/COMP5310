java c
COMP5310 Project Stage 2
Develop and evaluate a predictive model
Due: 11:59PM on 17th of October 2024 (Week 11)
This assignment is worth 20% of the ﬁnal mark of the unit of study.
GROUPSThis stage is usually done with the same group members you worked with for Stage 1. However, under excep?onal circumstances, an alternative group may be created by the tutor when a group is reduced in size due to members discon?nuing this unit. If this applies to you, please email the unit  coordinator maryam.khaniannajafabadi@sydney.edu.au or the TA: ssri4213@uni.sydney.edu.au, with copy to your tutor to discuss this.Note: Each member of the group is required to complete individual tasks, but the project will be submi@ed as a combined effort. The final project will be marked as a whole, with both individual and group components contribuEng to the final grade. All assessments will be based on the single, submi@ed document.
Dispute ResolutionIf, during the course of the assignment work, there is a dispute among group members that you can’t resolve or that will impact your group’s capacity to complete the task well, you need to inform. the unit coordinator maryam.khaniannajafabadi@sydney.edu.au or the   TA ssri4213@uni.sydney.edu.au. Make sure that your email speciﬁes the lab session and group name and is explicit about the diﬃculty; also  make sure this email  is copied to all group members (including anyone you are complaining about) and your lab tutor.We need to know about problems in Eme to help ﬁx them, so set early deadlines for group members, and deal with non-performance promptly (don’t waittill a few days before the work is due to complain that someone is not delivering on their tasks). If necessary, the coordinator will split a group and leave anyone who didn’t par?cipate eﬀectively in a group by themselves (they will need to achieve all the outcomes on their own). This opEon is only available up unEl Thursday Week 9, which is the last day with ?me to resolve the issue before the due date. For any group issues that arise aSer this time, you will need to try to resolve the problem on your own, and you will continue to be treated as a single group. If someone doesn’t provide the material required for the report, or their material is not of the agreed standard, you should still have the report show what that person did. Their section of the report may be empty if they don’t produce anything, or it may have material but not enough. In such cases, please put a “Note to marker” on the front page of the report, which describes the circumstances. That way, we can consider how best to apply the marking scheme. Note that it is not expected or sensible for other members to do the work that someone failed to deliver.
PROJECT
OverviewThe objective of Stage 2 of the project is to build a robust predictive model using the clean dataset obtained in Stage 1. This stage will involve advanced predictive modeling techniques, as well as thorough model evalua?on and optimization processes.
Important Notes:1. You MUST use the dataset you chose in Stage 1. Changing to another dataset is not allowed.
2. You MUST work in the same groups you worked on during Stage 1.
3.   Further  cleaning  of  the  dataset,  addi?on  of  previously  dropped  columns,  and  or removal of columns are permiYed if you wish.
4.   Changing  of  target  variable  and  research  ques?on  is  also  permiYed,  if  the  group chooses to do so.
5. Each member must use a diﬀerent predicEve modelling technique to develop their predic?ve model.
6. Each student must designate their secEon or component both in the report and the code ﬁle using their Unikey (THIS IS A UNIKEY: ABCD1234). DO NOT provide Student ID or the name of the student.
7. Only 1 submission per group is required. In other words, only 1 member from the group must submit the assignment.
8. In total, 2 items are to be submi@ed: 1 zipfolder which contains python code and ﬁnal clean dataset, and 1 report in pdf format.
9. You MUST ONLY use Jupyter Notebook for your code. You are NOT PERMITTED to use any other IDE, such as Google Colab, Spyder, etc for your code file. MARKS WILL BE DEDUCTED if students require the markers to run the code file in any IDE other than Jupyter Notebook.
10. Students must follow the report format exactly as given in the assignment guide. DO NOT add your own sec?ons or sub-sec?ons to the report. Simply follow the report format men?oned in the guide.
DELIVERABLES
ReportThe report must have a maximum of 3 pages for each individual sec?on and maximum 3 pages for the group sec?on (including both group sec?ons) for a group of 2, and 4 pages for a group of 3. You must use the high-level headings, as provided below, to indicate the diﬀerent sec?ons and sub-sec?ons of the report. You must use line spacing of at least 1.15pt, margins of at least 1.8cm, and body font size of at least  10pt. The goal is to convey the problem clearly and concisely.
Key Notes:1. The diﬀerent report secEons and sub-secEons are aligned with the marking rubric.Therefore, please include only the requested contents and do not mix or merge the secEons, as this will interfere with the marking process. If you fail to do so, this won’t be considered for the marking.2.   The report must have a front page that gives: the group number, acEvity code, and
the list of each group member’s Unikey and Student ID (DO NOT PROVIDE NAMES).3. DO NOT INCLUDE a Content’s Page at the beginning of your report. It is not required.
The body of the report must have a structure as follows:
Group Component 1
The report must begin with a group sec?on including:
1.   Topic   and    research    ques9on:  Describe   the    research    problem   comprehensively, emphasizing its signiﬁcance in the domain. Clearly ar?culate the research ques?on and highlight its implica?ons for various stakeholders. Discuss how addressing this ques?on could lead to ac?onable insights or improvements in decision-making for the stakeholders.
2.   Dataset: Provide  a  detailed  overview  of  the  dataset  and  discuss  any  challenges,  class imbalances, and or biases present in the data and how they might impact the modeling process.
3. Setup
3.1. Modelling agreements: Iden?fy an aYribute that you will all make predic?ons about and agree on at least two measures of success for the predic?ve models you will be producing. These measures should go beyond standard accuracy metrics and may include area under the receiver opera?ng characteris?c curve (AUC-ROC), F1-score, precision-recall curves, etc. Explain the ra?onale behind these measures and their suitability for the research ques?on.
3.2. Data  division: Describe  the  process  of  how  you  divided  your  data  into  training, valida?on (if applicable), and test sets. Explain the ra?onale behind the data 代 写COMP5310 Project Stage 2 Develop and evaluate a predictive modelPython
代做程序编程语言division, considering strategies like temporal valida?on or stra?ﬁed sampling.
Individual Component
The report must include a dedicated secEon for each group member. Each secEon should clearly state the member's Unikey to idenEfy their individual secEons in the report (THIS IS A UNIKEY: ABCD1234).
Each individual sec?on must include:
1. Predic9ve modelNote: Each member must choose a different predicEve modelling technique.
1.1.  Model  descrip9on: Name  and  describe  your  technique,  discuss  the  assump?ons underlying this technique and cri?cally evaluate their validity in the context of the dataset. Highlight the strengths and limita?ons of the chosen technique and jus?fy its suitability for the research ques?on and dataset characteris?cs.
1.2.  Model  algorithm: Provide  a  detailed explana?on of the algorithm  powering your chosen technique,  including  its  underlying  principles,  such as  (but  not  limited to) mathema?cal    equa?ons,    hyperparameters,     and    poten?al    varia?ons.     Using pseudocode  or  ﬂowchart  diagrams,  provide  the  step-by-step  execu?on  of  the algorithm. (You can type the pseudocode in Jupyter Notebook and put the screenshot of the pseudocode here.  You cannot put the screenshot of the pseudocode in the appendix. If you do, it will not be marked). If you choose to draw a ﬂowchart, you can create it on any online tool or sofware and a@achits screenshot here. You must put the screenshot of the ﬂowchart diagram here, in the main report. If you put it in the appendix, it will not be marked.
1.3. Model development: Describe the process of building the predic?ve model, including advanced  data  preprocessing  techniques  such  as  feature  scaling,  dimensionality reduc?on (e.g., Principal Component Analysis), or feature engineering. Discuss the selec?on  of  model-speciﬁc  func?ons  and  hyperparameters,  providing  theore?cal jus?ﬁca?on and empirical valida?on. Also, you will iden?fy the Python func?ons and chosen parameters you selected and what they mean.Note: You don’t have to include the code in the report, as you will submit it separately
2. Model evalua9on and op9miza9on
2.1. Model evalua9on: Perform. a comprehensive evalua?on of your model's performance using the agreed-upon measures of success. Interpret the results in the context of the research  ques?on  and  dataset  characteris?cs,   considering  factors  such   as  class imbalance,  noise,  and  interpretability.  Discuss  the  implica?ons  of  the  evalua?on metrics and iden?fy poten?al areas for improvement.
2.2. Model op9miza9on: Explore advanced op?miza?on techniques to further enhance your   model's   performance,   explaining   your   choices   clearly.   This   may   involve hyperparameter tuning using techniques like grid search.
Group Component 2
Finally, a second group sec?on at the end of the report, including:
1.   Discussion: Engage  in  a  cri?cal  discussion  on  the  strengths  and   limita?ons  of  each modeling   technique    employed   by   group    members.    Compare   and    contrast    the performance of various models quan?ta?vely and qualita?vely. Reﬂect on the broader implica?ons of model selec?on for addressing the research ques?on eﬀec?vely.
2.   Conclusion: Synthesize  the  ﬁndings  from  individual  model  evalua?ons  and  provide  a recommenda?on  on  the  most  eﬀec?ve  predic?ve  model  for  answering  the  research ques?on.   Jus?fy   your   recommenda?on   based   on   empirical   evidence,   theore?cal considera?ons, and domain knowledge. Propose poten?al avenues for future research, including data collec?on strategies, model reﬁnement techniques, and interdisciplinary collabora?ons.
Code and Dataset
Along with the report, you must submit the Python code and the final clean dataset used in this assignment as a single zip or tar.gz folder and that folder must be named using the following convenEon: “GroupX_AcEvityY_A2”.
The python ﬁle must contain the following:
- Group Component 1:
o The beginning of this sec9on must be clearly marked and labelled.
o Preliminary Changes to Data: all steps used to ingest the data and further process the  data,  such  as  adding   previously  dropped  features,   removal  of  exis?ng aYributes, conversion of data type of aYributes to a more suitable data type.
o Data split for train/valida9on/test sets: all the steps required to split the data into training, valida?on (if required), and tes?ng sets, including (but  not  limited to) strategies like temporal valida?on or stra?ﬁed sampling.
o The end of this group component sec9on must be clearly marked and labelled.
- Individual Component:
o Title and Unikey Markdown: Before starEng the code for the individual component, you must create a markdown cell and provide the Etle which states the model name and the Unikey of the student who will work on that model.
o Data  Processing: provide all  relevant  data  processing techniques  implemented, such as PCA, feature scaling, etc.
o Ini9al Model Development and Evalua9on: all the model building steps required to successfully construct and train the predic?ve model.
o Model  Op9miza9on: all  the  hyperparameter  tuning  steps,  the  results  of  each hyperparameter  test  run,  and  the  decision  of  the  op?mal  hyperparameter conﬁgura?on that will be used by the student.
o Model Results: all the results, including relevant graphs (curves), plots, accuracy percentages,  and  other  relevant  metrics  of  model  performance  that  show  the performance behavior. for the op?mal model must clearly be depicted.
o The end of each of the individual sec9on must be clearly marked and labelled.
- Group Component 2:o The  beginning  of this group  component  sec9on  must  be  clearly  marked  and labelled.o Op9mal  Model  Comparison: all  the  op?mal   models  must   be  compared  and contrasted with each other.
o Final Model Recommenda9on: once all the models have been compared, the ﬁnal recommenda?on of the most appropriate model must be men?oned including its performance metrics and scores obtained aSer tes?ng.
o The end of this group sec9on must be clearly marked and labelled.
This compressed / zip folder must contain the following:
1.   1 Jupyter notebook (the python ﬁle), with all the code men?oned above, which must be named using the following conven?on: “GroupX_AcEvityY_A2_Code.ipynb”
2.   The ﬁnal cleaned version of the data in CSV format must be named using the following conven?on: “GroupX_AcEvityY_FinalCleanData.csv”.DO NOT INCLUDE THE REPORT IN THE ZIPfolder. The submission portal for the report is separate from the submission  portal of the ﬁnal clean dataset and code. The  naming conven?on for the report (in pdf format) is: “GroupX_AcEvityY_A2_Report.pdf”



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
