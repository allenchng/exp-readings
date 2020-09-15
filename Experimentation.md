# Experimentation Resources

This is a list of resources that I found useful when studying for experimentation based data science roles. It is by no means an exhaustive list, please feel free to message me or submit a PR if you think the organization could be improved or I've omitted any outstanding examples.

Inspired by [Dustin Tran's ML Video repo](https://github.com/dustinvtran/ml-videos) and PhD qual's lists.

## General Overview

-   [Kohavi et al., 2020 - Online randomized controlled experiments at scale: lessons and extensions to medicine](https://link.springer.com/article/10.1186/s13063-020-4084-y)

- [Kohavi & Longbotham, 2017 - Online Controlled Experiments and A/B Testing](https://www.researchgate.net/profile/Ron_Kohavi/publication/316116834_Online_Controlled_Experiments_and_AB_Testing/links/59b7583b458515c212b3cd46/Online-Controlled-Experiments-and-A-B-Testing.pdf)

- [Kohavi et al., 2009 - Controlled experiments on the web: survey and practical guide](http://www.robotics.stanford.edu/~ronnyk/2009controlledExperimentsOnTheWebSurvey.pdf)

- [Alex Deng - Trustworthy Analysis of Online A/B Tests: Pitfalls, Challenges and Solutions](https://alexdeng.github.io/public/files/ExpediaTestSummit.pdf)

-   [Trustworthy Online Controlled Experiments: Five Puzzling Outcomes Explained](https://exp-platform.com/Documents/puzzlingOutcomesInControlledExperiments.pdf)

-   [Twitch - A/B Testing using Google’s Staged Rollouts](https://blog.twitch.tv/en/2017/01/12/a-b-testing-using-googles-staged-rollouts-ea860727f8b2/#.tkg2qw9a4)

## Measuring Treatment Effects

-   [Facebook - A Comparison of Approaches to Advertising Measurement: Evidence from Big Field Experiments at Facebook](https://www.kellogg.northwestern.edu/faculty/gordon_b/files/kellogg_fb_whitepaper.pdf)

-   [Google - Inferring causal impact using Bayesian structural time-series models](https://research.google/pubs/pub41854/)

-   [Twitch - Two-Stage Least Squares For A/B Tests](https://blog.twitch.tv/en/2017/06/30/two-stage-least-squares-for-a-b-tests-669d07f904f7/)

- [Booking.com - Understanding Mechanisms of Change in Online Experiments at Booking.com](https://booking.ai/understanding-mechanisms-of-change-in-online-experiments-at-booking-com-629201ec74ee)

- [Wayfair - Wayfair DS Explains It All: Jerry Chen on A/B Test Measurement Validation](https://tech.wayfair.com/data-science/2019/07/wayfair-ds-explains-it-all-jerry-chen-on-a-b-test-measurement-validation/)

- [Wayfair - Modeling Uplift Directly: Uplift Decision Tree with KL Divergence and Euclidean Distance as Splitting Criteria](https://tech.wayfair.com/data-science/2019/10/modeling-uplift-directly-uplift-decision-tree-with-kl-divergence-and-euclidean-distance-as-splitting-criteria/)


## Statistical Testing

- [VK Tech - Practitioner’s Guide to Statistical Tests](https://medium.com/@vktech/practitioners-guide-to-statistical-tests-ed2d580ef04f)

-   [Netflix - Streaming Video Experimentation at Netflix:  
Visualizing Practical and Statistical Significance](https://netflixtechblog.com/streaming-video-experimentation-at-netflix-visualizing-practical-and-statistical-significance-7117420f4e9a)

- [Ellery Wulczyn - AB Testing and the Importance of Independent Observations](https://ewulczyn.github.io/ab_testing_and_independence/)

- [Ellery Wulczyn - How to do AB Testing with Discrete Rewards?](https://ewulczyn.github.io/ab_testing_with_multinomial_data/)

- [Simon Jackson - Recreating Netflix’s quantile bootstrapping in R](https://towardsdatascience.com/recreating-netflixs-quantile-bootstrapping-in-r-a4739a69adb6)

- [Cross Validated - What is difference-in-differences?](https://stats.stackexchange.com/questions/564/what-is-difference-in-differences)

- [Wolfram - Quantile Regression—Theory, Implementations, and Applications](https://www.youtube.com/watch?v=GddvdXMJV9Y)

## Power / Stopping Rules

- [Booking - How Booking.com increases the power of online experiments with CUPED](https://booking.ai/how-booking-com-increases-the-power-of-online-experiments-with-cuped-995d186fff1d)

-  [Improving the Sensitivity of Online Controlled Experiments by Utilizing Pre-Experiment Data](https://www.researchgate.net/publication/237838291_Improving_the_Sensitivity_of_Online_Controlled_Experiments_by_Utilizing_Pre-Experiment_Data)

- [Analytics Toolkit - What does "Sequential Testing" mean?](https://www.analytics-toolkit.com/glossary/sequential-testing/#:~:text=Sequential%20testing%20is%20the%20practice,error%20rate%20of%20the%20procedure.)

- [Microsoft - Sequential Estimation of Quantiles with Applications to A/B-testing and Best-arm Identification](https://www.youtube.com/watch?v=CRSiyYCTCp8)

- [Simon Jackson - The 4-step Refresher of Statistical Power](https://towardsdatascience.com/a-quick-refresher-of-statistical-power-fe8ae5e0c317)

## Bayesian A/B Testing

- [John Krushke - Optional stopping in data collection: p values, Bayes factors, credible intervals, precision](http://doingbayesiandataanalysis.blogspot.com/2013/11/optional-stopping-in-data-collection-p.html)

- [Analytics Toolkit - Bayesian A/B Testing Is Not Immune To Optional Stopping Issues](http://blog.analytics-toolkit.com/2017/bayesian-ab-testing-not-immune-to-optional-stopping-issues/)

- [Chris Stucchio - Easy Evaluation of Decision Rules in Bayesian A/B Testing](https://www.chrisstucchio.com/blog/2014/bayesian_ab_decision_rule.html)

- [Clauido Bellei - Bayesian A/B Testing: a step-by-step guide](http://www.claudiobellei.com/2017/11/02/bayesian-AB-testing/)

- [David Robinson - Is Bayesian A/B Testing Immune To Peeking? Not Exactly](http://varianceexplained.org/r/bayesian-ab-testing/)

## Multivariate Testing

- [Analytics Toolkit - Multivariate Testing – Best Practices & Tools for MVT (A/B/n) Tests](http://blog.analytics-toolkit.com/2017/multivariate-testing-practices-tools-mvt-abn-tests/)

- [Nielsen-Norman Group - Multivariate vs. A/B Testing: Incremental vs. Radical Changes](https://www.nngroup.com/articles/multivariate-testing/)

## Bandits

- [Stitch Fix - Your Client Engagement Program Isn't Doing What You Think It Is.](https://multithreaded.stitchfix.com/blog/2018/11/08/bandits/)

- [Stitch Fix - Multi-Armed Bandits and the Stitch Fix Experimentation Platform](https://multithreaded.stitchfix.com/blog/2020/08/05/bandits/)

## Case Studies

#### Quality of Experience

-   [Netflix: A/B Testing and Beyond: Improving the Netflix Streaming Experience with Experimentation and Data Science](https://netflixtechblog.com/a-b-testing-and-beyond-improving-the-netflix-streaming-experience-with-experimentation-and-data-5b0ae9295bdf)

#### Billing
-   [SecurionPay - Payment Gateway A/B Testing Guide – How to effectively test different payment providers and methods](https://securionpay.com/blog/payment-gateway-ab-testing/)

- [Recurly - Predicting Recurring Transaction Success](https://blog.recurly.com/predicting-recurring-transaction-success)

#### Marketing

- [Wayfair - Uplift Modeling in Display Remarketing](https://tech.wayfair.com/data-science/2018/05/uplift-modeling-in-display-remarketing/)

#### Pricing
- [Wayfair - Wayfair DS Explains It All: Lin Jia on Measuring Price Effects](https://tech.wayfair.com/data-science/2019/09/wayfair-ds-explains-it-all-lin-jia-on-measuring-price-effects/)

#### Product Analytics

- [StellarPeers - How would you find the cause of a 15% drop in Facebook Groups usage?](https://stellarpeers.com/how-would-you-find-the-cause-of-a-15-drop-in-facebook-groups-usage/)

- [StellarPeers - How do you decide between displaying Facebook’s ‘People You May Know’ feature or an Advertisement?](https://stellarpeers.com/decide-between-facebooks-people-you-may-know-feature-or-advertisement/)

## Experimentation Platforms

- [Wayfair - Gemini: Wayfair’s advanced marketing test design and measurement platform](https://tech.wayfair.com/data-science/2019/07/gemini-wayfairs-advanced-marketing-test-design-and-measurement-platform/)

- [LinkedIn - Building a Scalable Experimentation Platform by LinkedIn](https://www.youtube.com/watch?v=LY1aeOdr9jU)

- [Uber - Building an Experimentation Platform at Uber](https://www.youtube.com/watch?v=9bl7SPSqbX0)

- [Spotify - Building a scalable experimentation platform at Spotify by Karina Bunyik](https://www.youtube.com/watch?v=RPyriHfNblE)

- [Pinterest - AB Testing At Pinterest: Building A Culture Of Experimentation](https://www.youtube.com/watch?v=MZTHghbPjbE)

## Software

- [Wayfair - Pylift: A Fast Python Package for Uplift Modeling](https://tech.wayfair.com/data-science/2018/10/pylift-a-fast-python-package-for-uplift-modeling/)


<!--stackedit_data:
eyJoaXN0b3J5IjpbNzgxNzgyMDYyLDIwNzI4MTA5MjJdfQ==
-->