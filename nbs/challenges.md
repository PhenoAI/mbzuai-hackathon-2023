# Competition Challenges

Aging leads to molecular and physiological changes throughout the body's tissues, increasing vulnerability to various illnesses. Identifying unique aging markers is vital, as each individual's aging trajectory is shaped by a blend of genetic and environmental factors. Phenotypic age, determined by molecular and physiological markers, is deemed to more accurately depict human aging compared to merely tallying years. Deep phenotype longitudinal cohorts are powerful tools for advancing healthy aging research by providing detailed information on an individual's physical and medical characteristics over time. This data enables researchers to pinpoint risk factors for age-related diseases, develop personalized interventions, and inform clinical trial design, resulting in more effective treatments and improved health outcomes for older adults.

## 1. Predictive Challenge - Phenotypic Age Prediction
Your objective is to forecast an individual's actual chronological age by leveraging all available phenotype datasets. Your performance will be assessed empirically using a withheld test set, with the mean absolute error (MAE) serving as the evaluation criterion. Throughout the event, two leaderboard test sets will be distributed, allowing teams to monitor their progress and compare results. Upon the hackathon's conclusion, a final test set will be used to establish the ultimate leaderboard.

Submission instructions and format can be found in the `example_notebooks\prediction_example.ipynb` notebook on the platform.

The final score will be composed of:  
- 80%: Leaderboard **rank** on empirical MAE on the test set.  
- 20%: Model novelty and usage of unstructured datasets. This is presented by the groups and **ranked** by the judges.  

Examples for model novelty:  
- Simple: Vanilla scikit-learn and gradient boosting trees (CatBoost, XGBoost, LightGBM)  
- Complex: Custom models, bespoke probabilistic models, leveraging domain expertise  

Examples of unstructured datasets:  
- Simple: All tabular features  
- Complex: Images (fundus), time series (sleep monitor, CGM, ECG, diet logging)  

## 2. Creative Challenge
This challenge is an open challenge to find the best application of deep phenotype longitudinal cohorts to promote healthy aging. The output of this challenge is a presentation of a proof-of-concept of such an application using the available data at hand.

User the following template for your presentation: [Presentation template slides]()

The presentation should briefly cover:  
1. Scientific or clinical background and rationale for the application.  
2. Main idea  
3. Proof-of-concept of the application on the HPP dataset  
4. Future directions  

Example use cases may include (but not limited to):  
1. Identifying risk factors  
2. Personalized interventions  
3. Precision medicine  
4. Biomarker discovery  
5. Assisting clinical trial design  

Specific examples (feel free to be creative and come up with your own):  
1. Omics-mediated glucose-diet personalized response with respect to age. Utilize microbiome, serum metabolomics, and genetics datasets. See for example: [Personalized Nutrition by Prediction of Glycemic Responses](https://www.sciencedirect.com/science/article/pii/S0092867415014816).  
2. Predict _cardiovascular age_ from wearable devices data (such as sleep monitoring PAT signal or ECG).  
3. _Fragility scores_ using bone density and body composition data.  
4. Utilize the retinal microvasculature found in fundus images as _a window to the heart_. See [Deep Learning of the Retina Enables Phenome- and Genome-Wide Analyses of the Microvasculature](https://www.ahajournals.org/doi/10.1161/CIRCULATIONAHA.121.057709).  
5. Genetics and interaction with aging. See for example: [Longitudinal fundus imaging and its genome-wide association analysis provide evidence for a human retinal aging clock](https://elifesciences.org/articles/82364).  
6. Semi-supervised learning on large cohorts for enhancing small cohort data. See [Self-supervised learning in medicine and healthcare and Self-supervised Learning for Human Activity Recognition Using 700,000 Person-days of Wearable Data](https://www.nature.com/articles/s41551-022-00914-1).  
7. Sleep architecture (sleep stage patterns) and associations with health and disease.  
8. Clinical trial design - smart matching of healthy individuals to a smaller cohort.  

Please do come up with your own ideas!  


## Challenges deadlines:

### Day 1 (2/5)
| Time   | Event                                              |
|--------|----------------------------------------------------|
| 11:30  | Kickoff teamwork begins                            |
| 17:30  | Leaderboard submission #1 (Predictive Challenge)   |

### Day 2 (3/5)
| Time   | Event                                              |
|--------|----------------------------------------------------|
| 07:30  | Leaderboard submission #2 (Predictive Challenge)   |
| 10:30  | Predictive + Creative final submission deadline    |
| 11:00  | Team presentations (Predictive + Creative)         |


## General notes  
1. You are one of the first to use the platform and unique datasets. Be patient with issues and we will help you overcome them.  
2. Platform resource usage - please limit yourself to 1 workspace per user.
3. Keep the compettiton clean. None of us want to win the wrong way. If you come across something that would seem unfair (target data leakage, ability to observe other teams shared folder) - please let us know.
4. Support available througoput the event.
5. Have fun! Build great applications with the data.  
