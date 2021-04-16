## Lauren Pendo Data Scientist

Data Scientist with experience in statistics, machine learning and analytics. Current Master's Student at Stanford's Institute of Computational and Mathematical Engineering, Data Science. 

## Projects

### Causal Inference: Do Gender Quotas Really Reduce Bias? Evidence from a Policy Experiment in Southern Africa" - A Causal Re-analysis

We questioned much we could rely on the random quota assignment at the ED level holding at the individual level; to this end, we leveraged a number of analysis techniques from the observational study literature in order to better understand how much the study depended on the consequences of a completely randomized experimental design. 

Through our exploratory data analysis, we verified that the covariates observed in the Afro-Barometer survey do tend to be balanced across treatments as supposed by Clayton in her supplemental analysis. Then, we analyzed her initial, direct testing through Clayton's own Neymanian lens, as well as from the Fisherian perspective. Here, we found that her results for political and traditional bias held even in the absence of normality assumptions, while her result for education bias did change in the Fisherian scheme.

Viewing the quota dataset an an observational study, we used matching on age and gender in order to possess potential counfounding at the individual level that may not have been evident in the original analysis. Here, we saw that the results for each outcome generally became more significant, although none of the results crossed the threshold into actual statistical significance. As an extension, we also performed a sensitivity analysis to see how much this increase in significance held under increased devations from ignorability; here we found that the results are in fact quite sensitive, with the $p$-values increasing quite dramatically even for $\Gamma = 1.2$. 


As a final check on the assumptions from an observational point of view, we turned to subclassification on propensity score as an alternative to matching and to return to a Neymanian paradigm. Again, we found that the results were not significant. 


In conclusion, it was quite informative to view the randomized quota experiment from an observational lens given how we were able to assess deviations from the properties of a completely randomized experiment - in the observational study paradigm, these are instead seen as assumptions. While we performed a fairly detailed analysis on the explicit bias experiment, there are still numerous observational techniques that can be applied to the remaining covariates, and the potential to apply the same analysis to the experiment on implicit bias. Overall, we view the amount of information gleaned from this causal re-analysis as a vindication of the techniques that have come from the field in recent years, and see numerous opportunities for rich re-analysis on this dataset.


[Final Deliverable](MSE327_Final_Project__Gender_Bias.pdf)

### NLP: Improving QA System Out of Domain Performance Using Data Augmentation

We investigated the effectiveness of different data augmentation and sampling techniques to improve the robustness of the pre-trained DistilBERT question answering system on out of domain data. We trained the DistilBERT model on the in domain data and then experimented with fine-tuning using augmented versions of the out of domain data. To generate the additional data-points we performed random word deletion, synonym replacement, and random swapping. We found that all the fine-tuned models performed better than the baseline model. Additionally, we found that our optimal synonym replacement model performed the best on the out of domain test set, and that the combination model of synonym replacement and deletion also led to increased performance over the baseline. Overall, we conclude that data augmentation does increase the ability of our question answering system to generalize to out of domain data and suggest that future work could look further into applying combinations of these data augmentation techniques.

[Final Deliverable](CS224N_Project_Milestone.pdf)

