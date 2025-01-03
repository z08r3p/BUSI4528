java c
BUSI4528-E1 
A LEVEL 4 MODULE, AUTUMN SEMESTER   2018-2019 
QUANTITATIVE RESEARCH METHODS FOR FINANCE AND ACCOUNTING
1.          a)   A researcher is interested in the factors that affect women’s decision to participate   in the   labour force.   He   interviews a total of 753 women in   2000   and   collects   data   on   a   number   of variables as described   below:
fempart                      : Variable taking value   1   if a woman   participated   in the   labour   force,   0 otherwise 
faminc                            : Gross family   income   in the year   2000,   measured   in   US   $
educ                                    : years of schooling,   in   years
age                                          : age,   in   years
exper                               :   years   of working   experience,   in   years
urban                               : Variable taking value   1   if the woman   lives   in   the   urban   area,   0 otherwise
kidsunder6         :   number of kids   under   6 years   old
(i)          Explain   how the   Logit   model   is   set   up   and   how the   researcher   should   use   it   to   calculate   the   probability   of   participating   in   the   labour   force   for   each   individual   in the   data   set.       [30   marks]
(ii)       The actual estimation of the Logit   model reveals   the   following   output.   Calculate   the   probability of participating   in the   labour force for   a   woman   who   is   36 years   old and   lives   in the urban area. She   has   completed   14   years   of schooling   and   5   years working experience. She currently has   2   kids   under 6   years   old.   It   is   also   known   that   her   total   family   income   is   US$   60,000   per   annum.   Show   all   your   workings.    [10   marks]
Iteration   0:         log   likelihood   = -514 .8732 
Iteration   1:       log   likelihood   =-411 .62085 
Iteration   2:       log   likelihood   =-407 .17257 
Iteration   3:         log   likelihood   = -407 .1063 
Iteration   4:         log   likelihood   =-407 .10628 Logistic regression Number of obs   LR chi2(6) Prob > chi2 = = = 753 215 .53 0 .0000 Log likelihood = -407 .10628 Pseudo R2 = 0 .2093 fempart Coef . Std . Err . z P>|z| [95% Conf . Interval] faminc .0000169 8 .06e-06 2 .10 0 .035 1 .16e-06 .0000327 educ .1596136 .0429795 3 .71 0 .000 .0753753 .243852 age - .1017045 .0134487 -7 .56 0 .000 - .1280634 - .0753456 exper .126727 .0133507 9 .49 0 .000 .1005601 .152894 urban - .1671848 .1881382 -0 .89 0 .374 - .5359288 .2015592 kidsunder6 -1 .421205 .1974545 -7 .20 0 .000 -1 .808209 -1 .034201 _cons 1 .431475 .7389594 1 .94 0 .053 - .0168589 2 .879809 
(iii)      Using information contained   in part (ii) calculate   the   effect   on   the   probability   of   participating in the labour force if a woman lives in the rural area. Show   all your   workings.       [15   marks]
b)   Explain two ways of evaluating the goodness of fit   of the   Logit   regression   model?       [20   marks]
c)    Discuss the consequences of Heteroskedasticity for   the   OLS   estimator.       [25   marks]Total [100 marks] 
2.    a)   i)    Discuss,   using    basic   mathematical   notations,   the   assumptions   for   a   simple    linear   regression   model  代 写BUSI4528 QUANTITATIVE RESEARCH METHODS FOR FINANCE AND ACCOUNTING AUTUMN SEMESTER 2018-2019Matlab
代做程序编程语言 : y   = β1    + β2x       +    e.       [30   marks]
ii)   Briefly outline the Gauss-Markov Theorem and the Central   Limit Theorem.       [20   marks]
b)   What   are   the   likely   consequences   of   using   non-stationary   time   series   data   in   a   linear   regression?       [15   marks]
c)    Consider the following AR(1)   model with drift:
yt      =   μ   + Pyt−1    + vt   , with   |P|   < 1
what   is the de-meaned series of the AR(1)   model? What   is the   mean   of the   de-meaned   series?       [15   marks]
d)   Explain the circumstances   under which the Augmented   Dickey-   Fuller (ADF) test   is   used   instead of the standard   Dickey-Fuller   (DF) test.       [20   marks]Total [100 marks] 
3.    a)   What   are   the   main   limitations   of the   Linear   Probability   Model   (LPM)   as   compared   to   the   Logit   model?       [20   marks]
b)   Consider the following time series   model with serially correlated   error term   :
yt      = α + βxt      + εt,      with εt       =   P1 εt−1    + P2 εt−2      + vt       where var(vt   )   = σv(2),    and    Cov   (vt,   vs   )   =   0      for      t    ≠   S
show the above   model can   be   rewritten   into a   new   model   that   has an   error term   uncorrelated over time.   Discuss on the   merits of doing   so.       [30   marks]
c)   Explain the term “Heteroskedasticity” in cross-sectional   multivariate   regression.       [15   marks]
d)   How   might   Heteroskedasticity   be detected and addressed in   regression analysis?       [35   marks]Total [100 marks] 
4.    a)   Discuss   how   the   fixed-effects   model   might   be   adopted   to   reduce   endogeneity   concerns   resulting from the   unobserved   heterogeneity associated with firms and years   in   a   panel   dataset. Specify the   regression   model in your   discussions.       [50   marks]
b)   What   is   meant   by   saying   that   a   time   series   is   stationary?      Is   the   following   time   series   stationary or   non-stationary?
yt      =   yt−1 + vtwhere   error   terms vt      are   i.i.d.   with   mean   zero   and   variance σv(2)   ,   and t denotes   the t-th time   period Justify your answer.       [25   marks]
c)    Explain   the   Engle-Granger   test   for   cointegration   and   write   down   the   steps   involved   in   the test.       [25   marks]Total [100 marks] 
5.    a)   Discuss   how   the   difference-in-difference   (DID)   estimator   (specify   the   DID   regression   model)   might   be   used to test for   a   potential treatment effect   of a   policy   reform.   Outline   the   key assumptions for the   DID estimation. Use   graphs where   necessary.       [75   marks]
b)   Consider the following time series   model   :
yt      =    β0    + β1xt      + β2xt−1 + yyt−1 + εt
It   is   suspected   that   the   model   suffers   from   serial   correlation   in   the   error   term   of   the   form.
εt      =   Pεt−1    + utwhere ut       is   an   identically   independently   distributed   error   term   and t denotes   the t-th   time   period.   Describe in detail a   test to detect serial correlation   in   the   above   form   of the   model. [25   marks] Total [100 marks] 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
