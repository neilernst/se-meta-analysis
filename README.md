A meta-analysis is a research study that looks at previous empirical work and uses the underlying data to generate statsitical inferences from the collective results.

This is often done in medicine and biology to summarize research studies and look for trends. E.g., of these 10 studies on diabetic ulcers, is there evidence from all of them for treatment A?

A related type of study is a systematic literature review. The difference is that an SLR does not conduct statistical inference testing, rather it is a qualitative summary of different studies.

This repository collects research papers claiming to do meta-analysis in software engineering. Where possible, I link to a free PDF. 

Spawned from this tweet and responses thereto: https://twitter.com/neilernst/status/932758799458246656

# Papers
1. Jo E. Hannay, Tore Dybå, Erik Arisholm, Dag I.K. Sjøberg, The effectiveness of pair programming: A meta-analysis, In Information and Software Technology, Volume 51, Issue 7,  **2009**, Pages 1110-1122, https://doi.org/10.1016/j.infsof.2009.02.001. 

[Free PDF](http://ai2-s2-pdfs.s3.amazonaws.com/f6b9/0bdffbf1b00bdc3e24b8cd679df1009c5bec.pdf)

> Several experiments on the effects of pair versus solo programming have been reported in the literature. We present a meta-analysis of these studies. The analysis shows a small significant positive overall effect of pair programming on quality, a medium significant positive overall effect on duration, and a medium significant negative overall effect on effort. However, between-study variance is significant, and there are signs of publication bias among published studies on pair programming. A more detailed examination of the evidence suggests that pair programming is faster than solo programming when programming task complexity is low and yields code solutions of higher quality when task complexity is high. The higher quality for complex tasks comes at a price of considerably greater effort, while the reduced completion time for the simpler tasks comes at a price of noticeably lower quality. We conclude that greater attention should be given to moderating factors on the effects of pair programming.

2. M. Shepperd, D. Bowes and T. Hall, "Researcher Bias: The Use of Machine Learning in Software Defect Prediction," in IEEE Transactions on Software Engineering, vol. 40, no. 6, pp. 603-616, **June 1 2014**. doi: 10.1109/TSE.2014.2322358

[Free PDF](http://bura.brunel.ac.uk/bitstream/2438/8784/2/Fulltext.pdf)

> Abstract: Background. The ability to predict defect-prone software components would be valuable. Consequently, there have been many empirical studies to evaluate the performance of different techniques endeavouring to accomplish this effectively. However no one technique dominates and so designing a reliable defect prediction model remains problematic. Objective. We seek to make sense of the many conflicting experimental results and understand which factors have the largest effect on predictive performance. Method. We conduct a meta-analysis of all relevant, high quality primary studies of defect prediction to determine what factors influence predictive performance. This is based on 42 primary studies that satisfy our inclusion criteria that collectively report 600 sets of empirical prediction results. By reverse engineering a common response variable we build a random effects ANOVA model to examine the relative contribution of four model building factors (classifier, data set, input metrics and researcher group) to model prediction performance. Results. Surprisingly we find that the choice of classifier has little impact upon performance (1.3 percent) and in contrast the major (31 percent) explanatory factor is the researcher group. It matters more who does the work than what is done. Conclusion. To overcome this high level of researcher bias, defect prediction researchers should (i) conduct blind analysis, (ii) improve reporting protocols and (iii) conduct more intergroup studies in order to alleviate expertise issues. Lastly, research is required to determine whether this bias is prevalent in other applications domains.

3. Lutz Prechelt, "The 28: 1 Grant-Sackman Legend is Misleading, Or: how Large is Interpersonal Variation Really", December **1999**, Universität Karlsruhe, Technical Report 1999-18. 

[Free PDF](http://page.mi.fu-berlin.de/prechelt/Biblio/varianceTR.pdf)

> How long do different programmers take to solve the same task? In 1967, Grant and Sackman published their now famous number of 28:1 interpersonal performance differences, which is both incorrect and misleading.
This report presents the analysis of a much larger dataset of software engineering work time data with respect to the same question. It corrects the false 28:1 value, proposes more appropriate metrics, presents the results for the larger dataset, and presents results of several further analyses: distribution shapes, effect sizes, and the performance of various significance tests.

# Meta-meta analyses

1. Lesley M. Pickard, Barbara A. Kitchenham, Peter W. Jones, "Combining empirical results in software engineering", In Information and Software Technology, Volume 40, Issue 14, 1998, Pages 811-821, doi:10.1016/S0950-5849(98)00101-3.

> Abstract
In this paper we investigate the techniques used in medical research to combine results from independent empirical studies of a particular phenomenon: meta-analysis and vote-counting. We use an example to illustrate the benefits and limitations of each technique and to indicate the criteria that should be used to guide your choice of technique. Meta-analysis is appropriate for homogeneous studies when raw data or quantitative summary information, e.g. correlation coefficient, are available. It can also be used for heterogeneous studies where the cause of the heterogeneity is due to well-understood partitions in the subject population. In other circumstances, meta-analysis is usually invalid. Although intuitively appealing, vote-counting has a number of serious limitations and should usually be avoided. We suggest that combining study results is unlikely to solve all the problems encountered in empirical software engineering studies, but some of the infrastructure and controls used by medical researchers to improve the quality of their empirical studies would be useful in the field of software engineering.

2. Hayes, Will. "Research synthesis in software engineering: a case for meta-analysis." Sixth International Software Metrics Symposium, 1999.

[PDF](https://pdfs.semanticscholar.org/9599/aa996302c3ece477edc4122f0dee5e78f0ca.pdf)

> The use of meta-analytic techniques to summarize empirical software engineering research results is illustrated using a set of 5 published experiments from the literature. The intent of the analysis is to guide future work in this area through objective summarization of the literature to date. A focus on effect magnitude, in addition to statistical significance is championed, and the reader is provided with an illustration of simple methods for computing effect magnitudes.

3. Brooks, Andy. "Meta analysis—a silver bullet—for meta-analysts." Empirical Software Engineering 2.4 (1997): 333-338. DOI: 10.1023/A:1009793700999

[Free PDF](http://faculty.ksu.edu.sa/ghazy/Documents/Emp%20SWE%2097/Meta%20Analysis—A%20Silver%20Bullet—for%20Meta-Analysts.pdf)

>Many of those who recognize that software engineering problems are people problems, and who engage in subject-based empirical software engineering, will have formed the view by now that their research paradigm is broadly similar to that employed by psychologists. Null hypotheses are framed, experiments are designed, subjects are found (from somewhere), and the resulting data are analyzed by statistical means, interpretations of the data are bound up very much in the null hypothesis and the statistical test of significance. The null hypothesis states that there is no difference between treatment and control group means i.e., the data are all drawn from the same population. The intention, of course, is to reject the null hypothesis and make a claim that something (the treatment) has been found that makes a difference e.g., that software engineers using tool or technique A can deliver in less time and with fewer errors than those using tool or technique B. But what lessons have psychologists learnt in conducting research along these lines for a good few decades now?
> 
