# XtGRL
Extended textual Goal-oriented Requirements Language is the extended edition of tGRL that is a domain specific language defined over DSL grammar in Xtext. Xtext is an open source Eclipse plugin. We have extended (also reduced) the tGRL grammar to enable only those features that allow enterprise architects to specify only the functional requirements and the corresponding non-functional requirements that are desired to be satisficed.
Extensions in the Grammar are described as follows.\
**1)** It also has the notion of a **_Softgoal_** that allows enterprise architects to only specify high level NFRs that
influence certain functional requirements.\
**2)** Notion of **_NFR Softgoals_**, **_Operationalization softgoals_** and **_Clain softgoals_** are introduced that are used to specify NFR catalogs.\
**3)** This extension allows the architect to specify the goal, task or resource that demands a certain specific softgoal. This requirement is represented by using new notation **_demands_**.

   ![](https://github.com/GRL2APK/XtGRL/blob/master/images/img1.PNG)\
In the above image a snapshot of the modified grammar is presented where we incorporated the notion of *_Softgoal_* by introducing  **_NFR Softgoals(NFR_SGoal)_**, **_Operationalization softgoals(Op_SGoal)_** and **_Clain softgoals_(Claim_SGoal)**
   ![](https://github.com/GRL2APK/XtGRL/blob/master/images/img2.PNG)\
In this snapshot of the grammar we incorporated the notion of demands for a specific Goal, Task or Resource using the notation **_demands_**.\
Some typical examples of represent your own Goal Model using xtGRL are presented in *_/examples/_* folder.\
The grammar for the XtGRL is given in *_/grammar/_* folder and a guide is given in that folder in order to integrate with the Eclipse platform.
   
      
