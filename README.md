# ANOVA_ANALYSIS
This study investigates the impact of different treatments on psychopathic deviant T scores among subjects from Central Prison in Raleigh, NC. The goal is to identify a treatment that effectively reduces the subjects' need for control or their rebellion against control, as measured by the Minnesota Multiphasic Personality Inventory (MMPI) test. The experiment comprises three treatment groups involving sensory restriction, each with a unique accompanying tape. The findings aim to contribute valuable insights into potential therapeutic approaches for individuals with elevated psychopathic deviant T scores. The statistical analysis employs a one-way analysis of variance (ANOVA) to determine if there are significant differences in the mean scores among the treatment groups.

THEORY
The Minnesota Multiphasic Personality Inventory (MMPI) is a widely used psychological test designed to assess various mental health conditions and personality traits. The psychopathic deviant T score specifically focuses on a person's inclination towards control or rebellion against it. A higher score indicates a greater need for control or a more rebellious nature.

The experiment employs three distinct treatments to explore their influence on psychopathic deviant T scores:

Sensory Restriction + Therapeutic Tape: This group undergoes four hours of sensory restriction coupled with a 15-minute "therapeutic" tape emphasizing the availability of professional help. The hypothesis posits that exposure to therapeutic content might positively impact psychopathic deviant T scores.

Sensory Restriction + Emotionally Neutral Tape: Subjects in this group experience four hours of sensory restriction along with a 15-minute "emotionally neutral" tape related to training hunting dogs. This group serves as a comparative measure to assess whether exposure to emotionally neutral content has an effect on psychopathic deviant T scores.

Sensory Restriction (No Taped Message): The third group undergoes four hours of sensory restriction without any accompanying taped message. This condition serves as a control to isolate the impact of sensory restriction itself on psychopathic deviant T scores. By analyzing the MMPI test results from these groups using one-way ANOVA, this study aims to determine which treatment, if any, is associated with a significant reduction in psychopathic deviant T scores. The findings will provide valuable information for designing targeted interventions to address specific personality traits related to control and rebellion.

CHECKING CONDITIONS OF OUR DATA FOR ANOVA ANALYSIS
-INDEPENDENCE
42 Volunteers were randomly distributed intro groups so this condition is satisfied

-NORMALITY CHECK
NORMALITY We check this using QQ-plots,HISTOGRAMS and SHAPIRO WILK TEST

HOMOGENEITY IN VARIABILITY CHECK
This is checked with boxplots,levine and barlet test

In summary, the Tukey HSD test is identifying which specific pairwise comparisons are statistically different after finding a significant result in the ANOVA. In this case, it suggests that there is a significant difference between treatdiff_1 and treatdiff_3, but not between the other pairs.

Conclusion
Null Hypothesis (H0): The null hypothesis assumes that there is no significant difference in means among the groups. Alternative Hypothesis (H1): The alternative hypothesis suggests that there is a significant difference in means among the groups. p-value (PR(>F)): If the p-value is less than the chosen significance level (commonly 0.05), you would reject the null hypothesis. In this case, the p-value is 0.046069, which is less than 0.05. Therefore, you would reject the null hypothesis. Conclusion: There is evidence to suggest that there are statistically significant differences in means among the treatment groups.
