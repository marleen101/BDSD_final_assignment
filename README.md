# BDSD final assignment
<img src="Reddit_photo.png" width="400" height="400">    

This is the Github repository of the Final Assignment of the _Big Data, Small Data_ course of the Master's program _Social sciences for a Digital Society_. This assignment is about the usage of neutralization techniques by Reddit users posting on the subreddits r/climate, r/climatechange and r/environment. Neutralization techniques are techniques used to justify certain behaviour. There are five techniques:

- _Denial of responsibility_: the deviant negates personal responsibility by arguing that the act was accidental or beyond their control (e.g. unloving parents, slum neighbourhood).
- _Denial of Injury_: the deviant argues his behaviour does not really cause any harm by qualifying this behaviour as an extension of a common practice. According to McKie (2018) the deviant may also assert their behaviour has a positive impact.
- _Denial of the victim_: the deviant positions himself as an avenger, whereas the victim is changed into a wrong-doer. Injury is a form of rightful retaliation or punishment, which means the deviant does not see a victim or sees the victim as deserving.
- _Condemnation of the condemner_: the deviant shifts attention away from the norm violation by attacking the legitimacy, motives, or integrity of those making the claim.
- _Appeal to higher loyalties_: the deviant justifies the act as a necessary trade-off in resolving a dilemma. The violation of the law is framed as unfortunate but acceptable as it serves a greater obligation.

For this assignment, data was downloaded, via arctic shift[^1]. The data are Reddit posts on these subreddit, which were posted from January 1<sup>st</sup> 2020 to November 30<sup>th</sup> 2025. Structural Topic Model (STM) and Critical Discourse Analysis (CDA) were used for the analysis. 

## Overview of the repository
- `Analysis`: This is the map containing information about the analysis. There are two maps and a PDF file within Analysis:
    - `R Analysis`: QDM file of the code used for the analyses. The analyses were done using R. 
    - `Topic modelling interpretation`: Containign a MD and Pdf file containing the top 20 most prominent posts of each topic of the model. These were used for interpreting the topics.
    - `Annotation guidelines`: these are the guidelines created for annotating
- `Data`: This is the map containing information about the data used for the analysis.
  - `Annotation`: Contain data of the two annotators in and RDS file, along with the sample of posts used for the annotation (also RDS file).
  - `Data climate change`: has the CSV file used within the QMD file for the analyses. Furthermore, the CSV files of the separate subreddits are added. 
  - `Topic model`: This map contains a RSD file of the model used to estimate the amount of topics and a RDS file of the final topic model.
## Summary of the results of the assignment
> **The full assignment can be read in the pdf file `Final assignment.pdf`**
 
This study examines the use of neutralisation techniques in climate change discussions on Reddit. Drawing on prior research on climate change countermovements, the study explored which neutralisation strategies appear most frequently in Reddit posts and whether policy-oriented techniques occur more often than science denial techniques. While the findings do not provide definitive support for the initial hypotheses, they offer important insights into how climate inaction and scepticism are discursively justified online.  
&nbsp;&nbsp;&nbsp;&nbsp;The analysis shows that climate science is often framed as unreliable, particularly through critiques of climate models and forecasting practices. In several posts, climate models were portrayed as inherently inaccurate, and climate scientists were depicted as untrustworthy for relying on them. This framing mirrors established countermovement strategies that aim to cast doubt on the scientific basis of climate change. Similarly, some users attributed climate change to natural processes rather than human activity, presenting the issue as scientifically uncertain and contested.  
&nbsp;&nbsp;&nbsp;&nbsp;Policy-oriented neutralisation techniques were also prevalent. Appeals to higher loyalties emerged in arguments suggesting that economic growth, political stability, or existing social systems take precedence over climate action. Although climate action was often acknowledged as desirable, it was framed as subordinate to competing collective priorities.  
&nbsp;&nbsp;&nbsp;&nbsp;Beyond established neutralisation categories, the study identified additional discursive patterns. Climate change was frequently depicted as an overwhelmingly complex and unsolvable problem, which served to justify inaction. Feelings of hopelessness and anxiety about the future were also prominent. Topic modelling indicated that a substantial share of posts expressed scepticism, despair, or “doom” perspectives. These expressions can be understood as forms of climate anxiety, which may contribute to passivity and inaction by reinforcing perceptions of powerlessness.  
&nbsp;&nbsp;&nbsp;&nbsp;Together, these findings highlight how Reddit users employ a range of neutralisation strategies, both established and emergent, to manage responsibility, uncertainty, and emotional responses in climate change discussions.


## Information Authors
This project was done as part of the MSc Social Sciences for a Digital Society at Vrije Universiteit Amsterdam.
For questions or discussion regarding this assignment, please open an issue in this repository.

[^1]:https://arctic-shift.photon-reddit.com/download-tool/
