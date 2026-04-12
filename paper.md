# Console Applications for Mathematical Functions, EEG Signal Analysis, String Manipulation and Utilities. 

**Dietmar G. Schrausser**  
[orcid.org/0000-0002-4924-8280](https://orcid.org/0000-0002-4924-8280)

Karl-Franzens University, Graz, Austria

<br>

## Overview

Applications for calculating (1) *distribution* functions and
*bootstrap* estimators (s. Tab. 1; c.f. Schrausser,
[2023a](https://doi.org/10.5281/zenodo.7664141),
[2024a](https://doi.org/10.31234/osf.io/rvzxa)), (2) various parameters
within the framework of psycho-physiological *EEG* measurements (c.f.
Schrausser, [2024b](https://doi.org/10.5281/zenodo.10701349)), (3)
*integral* and *interpolation* (Schrausser,
[2023b](https://doi.org/10.5281/zenodo.7655056)) and (4) *matrix*
parameters (Schrausser,
[2023c](https://doi.org/10.5281/zenodo.7655046)), s. Tab. 2. Further
applications are (5) *string-* and *number-* *transformation tools*
(Schrausser, [2023d](https://doi.org/10.5281/zenodo.7653790)) and
finally (6) various *console tools* (Schrausser,
[2023e](https://doi.org/10.5281/zenodo.7655239)), see Tab. 3. For a full
*BibTeX* source of the reference list, see Schrausser
([2026](https://doi.org/10.5281/zenodo.19513238)).

The applications are written in *ANSI-C* (c.f. Gerlach,
[2019](https://doi.org/10.1007/978-3-662-59246-5_4); Joyce,
[2019](https://doi.org/10.1007/978-1-4842-5064-8); Gonzalez-Morris &
Horton, [2024](https://doi.org/10.1007/979-8-8688-0149-5)), executables
were com-piled for *MS-DOS* (c.f. Kaier,
[1990](https://doi.org/10.1007/978-3-322-89035-1_1); Herrmann,
[2001](https://doi.org/10.1007/978-3-322-94365-1_16)).

Certain applications are implemented in the Windows Tools (i)
*FunktionWin* (see Schrausser,
[2023f](https://doi.org/10.5281/zenodo.7651661),
[2025c](https://doi.org/10.5281/zenodo.17880113)), (ii) `ThetaWin` (see
Schrausser, [2009](https://www.academia.edu/81800920),
[2023g](https://doi.org/10.5281/zenodo.7659264),
[2025a](https://doi.org/10.5281/zenodo.17880113)) and (iii) *ATINA* (s.
Schrausser, [2006](https://doi.org/10.5281/zenodo.19422127)). For better
comparability, the *original* German-language terms are presented
comparatively in *italic* text.

## 1. ConsoleApp_DistributionFunctions

Console applications for *distribution* functions (c.f. Schrausser,
[2023a](https://doi.org/10.5281/zenodo.7664141),
[2024a](https://doi.org/10.31234/osf.io/rvzxa)) implemented in
`FunktionWin` (see Schrausser,
[2023f](https://doi.org/10.5281/zenodo.7651661),
[2025c](https://doi.org/10.5281/zenodo.17880113)).

The following functions are available:

(1.1.-1.2.) *Binomial* distribution (de Moivre,
[1711](https://doi.org/10.1098/rstl.1710.0018); Bernoulli,
[1713](https://www.e-rara.ch/zut/doi/10.3931/e-rara-9001)) as a discrete
distribution of probability values from fre-quency ratios of two groups,
c.f. Collani and Dräger
([2001](https://doi.org/10.1007/978-1-4612-0215-8)), Philippou and
Antzoulakos ([2025](https://doi.org/10.1007/978-3-662-69359-9_71)),
further e.g. Mulholland and Jones
([1968a](https://doi.org/10.1007/978-1-4899-6507-3_3)), Altham
([1978](http://www.jstor.org/stable/2346943)), Goel and Rodriguez
([1987](http://www.jstor.org/stable/2689344)), Vel-laisamy and Punnen
([2001](http://www.jstor.org/stable/3215739)), García-García et al.
([2022](https://doi.org/10.3390/math10152680)).

(1.3.) Effect size, *Cohen's* $d$ (Cohen,
[1977](https://doi.org/10.1016/C2013-0-10517-X),
[1988](https://doi.org/10.4324/9780203771587), p.20, p.49,
[1992](https://doi.org/10.1037/0033-2909.112.1.155)), an effect size
measure that represents the magnitude of the difference between two
group means in standard deviation units. Further works on this topic are
given by e.g. Wilcox ([2006](http://www.jstor.org/stable/20157436)),
Miller et al. ([2011](https://doi.org/10.1016/j.jval.2010.10.013)),
Fritz et al. ([2012](https://doi.org/10.1037/a0024338)), Janczyk and
Pfister ([2013](https://doi.org/10.1007/978-3-642-34825-9_7)), Peng and
Chen ([2014](https://www.jstor.org/stable/26594399)), Li
([2016](https://doi.org/10.3758/s13428-015-0667-z)), Schäfer and Schwarz
([2019](https://doi.org/10.3389/fpsyg.2019.00813)), Bowring et al.
([2021](https://doi.org/10.1016/j.neuroimage.2020.117477)), Groß and
Möller ([2023](https://doi.org/10.1007/s42519-023-00323-w),
[2024](https://doi.org/10.1007/s00362-023-01527-9)) and Brandmaier
([2025](https://doi.org/10.31234/osf.io/n9ta7_v1)).

(1.4.) Fisher-Snedecor $F$-distribution (Fisher,
[1924](https://repository.rothamsted.ac.uk/item/8w2q9/on-a-distribution-yielding-the-error-functions-of-several-well-known-statistics)),
a continu-ous probability distribution for determining significance
levels in multigroup and factorial designs, c.f. also David
([1949](http://www.jstor.org/stable/2332676)), Patnaik
([1949](http://www.jstor.org/stable/2332542)), Zinger
([1964](http://www.jstor.org/stable/2985223)), Cacoullos
([1965](http://www.jstor.org/stable/2282687)), Stange
([1970](https://doi.org/10.1007/978-3-642-85602-0_11)), Saunders and
Moran ([1978](https://doi.org/10.2307/3213414)), Herrmann
([1984](https://doi.org/10.1007/978-3-322-96320-8_21)), Selvin
([2014](https://doi.org/10.1002/9781118445112.stat05856)), Brereton
([2015](https://doi.org/10.1002/cem.2734)) or Chattamvelli and Shanmugam
([2021](https://doi.org/10.1007/978-3-031-02435-1_7)).

(1.5.) *Fisher's exact test* (Fisher,
[1922](https://doi.org/10.2307/2340521); s. Altham,
[1969](http://www.jstor.org/stable/2984209)), *[exact]{.underline}*
*hypergeometric* 4-field test, a non-parametric statistical proce-dure
for significance testing of frequency distributions in 2×2 de-signs, see
in this context e.g. Upton
([1992](http://www.jstor.org/stable/2982890)), Camilli
([1995](https://doi.org/10.1007/BF02301418)), Hersh-berger
([2014](https://doi.org/10.1002/9781118445112.stat06165)), Sprent
([2025](https://doi.org/10.1007/978-3-662-69359-9_693)).

(1.6.) *Fisher* $Z$-transformation (Fisher,
[1915](https://doi.org/10.2307/2331838)), to adjust the distri-bution of
*product moment* correlation coefficients $r$ to a *normal* distribution
in order to perform valid significance tests, inter-esting discussions
on the topic are given by Hjelm and Norris
([1962](http://www.jstor.org/stable/20156574)), Mendoza
([1993](https://doi.org/10.1007/BF02294830)), Bond and Richardson
([2004](https://doi.org/10.1007/BF02295945)), Carbonell et al.
([2009](https://doi.org/10.1016/j.spl.2008.11.007)) or Yang et al.
([2013](https://doi.org/10.1007/s12209-013-1978-8)).

(1.7.-1.8.) *Gamma* function $\Gamma$ (Bernoulli,
[1729](https://commons.m.wikimedia.org/wiki/File:DanielBernoulliLetterToGoldbach-1729-10-06.jpg))
to extend the fac-torial to non-integer arguments (c.f. Borwein &
Corless, [2018](https://www.jstor.org/stable/48663320)). The *gamma*
integral, or *gamma* value, is also a *[central]{.underline}* parame-ter
of the $F$, $t$, and $\chi ²$ distributions implemented here, s. e.g.
Gronwall ([1918](http://www.jstor.org/stable/1967180)), Rasch
([1931](http://www.jstor.org/stable/1968254)), Davis
([1959](http://www.jstor.org/stable/2309786)), Magnus et al.
([1966a](https://doi.org/10.1007/978-3-662-11761-3_1)), Saunders and
Moran ([1978](https://doi.org/10.2307/3213414)), Batir
([2008](https://doi.org/10.1016/j.exmath.2007.10.001)), Koepf
([2014](https://doi.org/10.1007/978-1-4471-6464-7_1)).

(1.9.) *Hypergeometric* distribution (Wallis,
[1656](https://books.google.com/books?id=Z5w_AAAAcAAJ)) for the
calcula-tion of significance levels for frequencies in 2×2 designs, see
*Fisher's* *exact* *test* above, c.f. Berggren et al.
([2000](https://doi.org/10.1007/978-1-4757-3240-5_11)) or Stedall
([2005](https://doi.org/10.1016/B978-044450871-3/50083-8)), s. further
e.g. Magnus et al.
([1966b](https://doi.org/10.1007/978-3-662-11761-3_2)), Dutka
([1984](http://www.jstor.org/stable/41133728)) or Shuster
([2014](https://doi.org/10.1002/9781118445112.stat04869))

(1.10.) *Geometric* distribution (de Montmort,
[1713](https://books.google.com/books?id=PII\_AAAAcAAJ)) calculates the
probability that event $A$ with probability $p_{A}$ occurs at least once
in $r + 1$ attempts, c.f. Sreehari
([1983](http://www.jstor.org/stable/3213738)), Zijlstra
([1983](https://doi.org/10.2307/3213595)) or Thomopoulos
([2017](https://doi.org/10.1007/978-3-319-65112-5_15)).

(1.11.) *Poisson* distribution (Poisson,
[1837](https://gallica.bnf.fr/ark:/12148/bpt6k110193z/f218.image)) is
generally right-skewed, but approaches with (i) increasing expected
number of events $\lambda$ the *normal* distribution (c.f. Chung,
[1974](https://doi.org/10.1007/978-1-4757-3973-2_7)), with (ii) large
$n$ and small $p$ the *binomial* distribution, a more detailed insight
into this method provide e.g. Rao and Chakravarti
([1956](http://www.jstor.org/stable/3001466)), Crow
([1958](http://www.jstor.org/stable/2333201)), Haight
([1967](https://books.google.com/books?id=l8Y-AAAAIAAJ)), Simonton
([1978](http://www.jstor.org/stable/284821)), Jolicoeur
([1999](https://doi.org/10.1007/978-1-4615-4777-8_19)), Finkel-shtein et
al. ([2025](https://doi.org/10.1007/s11009-025-10171-9)) or Zhang
([2025](https://doi.org/10.54254/2754-1169/2025.BJ24761)).

(1.12.) Student's $t$-distribution (Lüroth,
[1876](https://doi.org/10.1002/asna.18760871402); Gosset,
[1908](https://doi.org/10.2307/2331554)) to approximate significance
levels if sample sizes $n$ are small, it con-verges to the *normal*
distribution as $n$ increases (s. Wang,
[2011](https://doi.org/10.1016/j.spl.2011.03.037)), c.f. further
Cacoullos ([1965](http://www.jstor.org/stable/2282687)), Yang et al.
([2007](https://doi.org/10.1016/j.jmva.2006.11.003)), Fonseca et al.
([2008](http://www.jstor.org/stable/20441467)), Peña et al.
([2009](https://doi.org/10.1007/978-3-540-85636-8_15)), Grigelionis
([2012](https://doi.org/10.1007/978-3-642-31146-8)), Brereton
([2015](https://doi.org/10.1002/cem.2734)), Li and Nadarajah
([2020](https://doi.org/10.1007/s00181-018-1570-0)), Reyes et al.
([2021](https://doi.org/10.3390/sym13122444)), Kirkby et al.
([2024](https://doi.org/10.48550/arXiv.1912.01607)) and Edelman
([2025](https://doi.org/10.48550/arXiv.2508.13226)).

(1.13.) $\chi ²$-distribution (Helmert,
[1876](https://gdz.sub.uni-goettingen.de/id/PPN599415665_0021)) can be
derived from the *normal* distribution (c.f. Behnke & Behnke,
[2006](https://doi.org/10.1007/978-3-531-90003-2_26)) and provides
significance level determinations for frequency parameters, thus serving
as an *[approximation]{.underline}* *for exact* level determination
through probability distributions such as *binomial*, *multinomial* or
*hypergeometric* (c.f. Camilli,
[1995](https://doi.org/10.1007/BF02301418)), s. in this context Wilson
and Hilferty ([1931](http://www.jstor.org/stable/86022)), Patnaik
([1949](http://www.jstor.org/stable/2332542)), Molinari
([1977](http://www.jstor.org/stable/2335780)), Hafner
([1992](https://doi.org/10.1007/978-3-7091-3420-7_14)), Jolicoeur
([1999](https://doi.org/10.1007/978-1-4615-4777-8_8)), Canal
([2005](https://doi.org/10.1016/j.csda.2004.04.001)), Brereton
([2015](https://doi.org/10.1002/cem.2734)) and Das
([2025](https://arxiv.org/abs/2404.05062)).

(1.14.-1.15.) *Normal* distribution (de Moivre,
[1738](https://books.google.com/books?id=PII\_AAAAcAAJ)) or *Gaussian*
distribution is fundamental to the *central limit theorem*, which states
that the means of many independent, identically distri-buted random
variables tend to follow this *normal* distribution, the
*[basis]{.underline}* of *inferential statistics*. The
$z$-transformation with a mean of $\overline{x\ } = \ 0$ and a standard
deviation of $s = 1$ yields the *standard* *normal* distribution, c.f.
Behnke and Behnke
([2006](https://doi.org/10.1007/978-3-531-90003-2_26)). See moreover
David ([1949](http://www.jstor.org/stable/2332676)), Breitenberger
([1963](http://www.jstor.org/stable/2333749)), Mulholland and Jones
([1968b](https://doi.org/10.1007/978-1-4899-6507-3_8)), Chung
([1974](https://doi.org/10.1007/978-1-4757-3973-2_7)), Leaver and Thomas
([1974](https://doi.org/10.1007/978-1-349-01942-7_4)), Thome
([1990](http://www.jstor.org/stable/40986007)), Sachs
([1993](https://doi.org/10.1007/978-3-642-77717-2_4)), Massart et al.
([1998](https://doi.org/10.1016/S0922-3487(97)80033-0)), von Storch and
Zwiers ([1999](https://doi.org/10.1017/CBO9780511612336)), Stahl
([2006](http://www.jstor.org/stable/27642916)), Tóth
([2011](https://doi.org/10.1002/cem.1382)), Wang
([2011](https://doi.org/10.1016/j.spl.2011.03.037)), Brereton
([2014](https://doi.org/10.1002/cem.2655)), Lyon
([2014](https://doi.org/10.1093/bjps/axs046)), Bera et al.
([2016](http://www.jstor.org/stable/43948011)), Wesolowski and
Musselwhite Thompson
([2018](https://doi.org/10.4135/9781506326139.n476)), Benzon
([2021](https://doi.org/10.48188/so.2.6)) or Saneii and Doosti
([2024](https://doi.org/10.1007/978-981-97-3083-4_6)).

*Theta* applications (1.16.-1.23.) generating distributions and
*estimators* for several parameters $\theta$ (*theta*) within different
de-signs via *bootstrap* method (Efron,
[1979](https://doi.org/10.1214/aos/1176344552),
[1981](https://doi.org/10.1093/biomet/68.3.589),
[1982](https://doi.org/10.1137/1.9781611970319), res.), with given
number of resamples $B$, where *bootstrap* estimator

$${\widehat{\theta}}_{B} = B^{- 1} \cdot \sum_{i = 1}^{B}\theta_{i}^{*}.$$

Implemented in `ThetaWin` (see Schrausser,
[2009](https://www.academia.edu/81800920),
[2023g](https://doi.org/10.5281/zenodo.7659264),
[2025a](https://doi.org/10.5281/zenodo.17880113)); for a deeper and
current insight into the *bootstrap* method see e.g. Politis
([1998](https://doi.org/10.1109/79.647042)), Bickel and Ren
([2001](http://www.jstor.org/stable/4356107)), Horowitz
([2001](https://doi.org/10.1016/S1573-4412(01)05005-X)), Wilcox
([2001](https://doi.org/10.1007/978-1-4757-3522-2_6)), Machado and
Parente ([2005](http://www.jstor.org/stable/23114968)), Kleiner et al.
([2014](http://www.jstor.org/stable/24774569)), Kenett et al.
([2022](https://doi.org/10.1007/978-3-031-07566-7_3)) or Zuev
([2026](https://doi.org/10.1007/978-3-032-03848-7_6)); furthermore Hall
([2003](http://www.jstor.org/stable/3182845)), Politis
([2003](https://doi.org/10.1214/ss/1063994977)), Pewsey
([2018](https://doi.org/10.2307/2348962)), Khosravi et al.
([2021](https://doi.org/10.1016/j.seps.2020.100781)), Baíllo and Cárcamo
([2025](https://doi.org/10.1007/s11222-025-10762-z)), Eidous
([2025](https://doi.org/10.13140/RG.2.2.12238.11846)), Liu
([2025](https://doi.org/10.1007/s41237-025-00283-4)) or Zheng and Fan
([2025](https://doi.org/10.3390/math13182913)).

### 1.1. Binomial

---

$$f\left( X \leq k|n \right) = \sum_{i = 0}^{k}\frac{n!}{i! \cdot (n - i)!} \cdot p^{i} \cdot q^{(n - i)}.$$

Usage:

~~~
Binomial [p][k][n] [[1]]
[p] ............. Probability of event A
[k] ............. n of events A
[n] ............. n of trials
[1] ............. (1):full output
~~~

## 1.2. Binomial_T

---

$$f\left( X \leq b|b,c \right) = p = \sum_{i = 0}^{b}\frac{(b + c)!}{i! \cdot (b + c - i)!} \cdot 2^{- i} \cdot 2^{- (b + c - i)}.$$

Usage:

~~~
Binomial_T [b][c] [[1]]
[b] ............. Cell count b
[c] ............. Cell count c
[1] ............. (1):full output
~~~

### 1.3. Epsilon

---

$$\varepsilon = \frac{\mu_{1} - \mu_{0}}{\widehat{\sigma}}.$$

Usage:

~~~
epsilon [mode][Q0][s][n][e|Q1][p][df] [[x]]
[mode] .......... (1):Effect-size (2):Theta.1
[Q0] ............ Theta.0
[s] ............. Standard deviation
[n] ............. n of cases
[e|Q1] .......... Epsilon | Theta.1
[p] ............. Percent-level (0.00)
[df] ............ Degrees of freedom n - (.)
[x] ............. Test value
~~~

### 1.4. F_Function

---

$$F\left( F,df_{1},df_{2} \right) = 1 - p^{\alpha 2} = \int_{0}^{F}\frac{\Gamma_{\left( \frac{df_{1} + df_{2}}{2} \right)}}{\Gamma_{\left( \frac{df_{1}}{2} \right)} \cdot \Gamma_{\left( \frac{df_{2}}{2} \right)}} \cdot \left( \frac{df_{1}}{df_{2}} \right)^{\frac{df_{1}}{2}} \cdot F^{\frac{df_{1}}{2} - 1} \cdot \left( 1 + \frac{df_{1}}{df_{2}} \cdot F \right)^{- \frac{df_{1} + df_{2}}{2}}\ dF.$$

Usage:

~~~
F_Function [mode][x][n1][n2]
[mode] .......... (1):Fx=p->F (2):Fy=F->p
[x] ............. p-value/F-value
[n1] ............ n1
[n2] ............ n2
~~~

## 1.5. Fisher_Exact

---

$$f\left( X = a|a,b,c,d \right) = P0 = \frac{(a + b)! \cdot (c + d)! \cdot (a + c)! \cdot (b + d)!}{(a + b + c + d)! \cdot a! \cdot b! \cdot c! \cdot d!},$$

$$f\left( X \leq n|a,b,c,d \right) = p^{exact2} = \sum_{i = 0}^{n}Pi;\ Pi \leq P0.$$

Usage:

~~~
Fisher_Exact [a][b][c][d] [[1]]
[a][b][c][d] .... Cell counts a,b,c,d
[1] ............. (1):full output
~~~

## 1.6. Fisher_Z

---

$$Z = \frac{1}{2} \cdot log_{e}\left( \frac{1 + r}{1 - r} \right),$$
$$r = \frac{e^{2 \cdot Z} - 1}{e^{2 \cdot Z} + 1}.$$

Usage:

~~~
Fisher_Z [mode][x]
[mode] ......... (1):r->Z (2):Z->r
[x] ............ r-value/Z-value
~~~

## 1.7. GAMMA_Function

---

$$f(x,t) = \Gamma = \int_{0}^{\infty}t^{x - 1} \cdot e^{- t}\ dt + c.$$

Usage:

~~~
GAMMA_Function [mode][value]
[mode] ......... (1):F(x)->⌈ (2):F'(⌈)->x
[value] ........ x / ⌈
~~~


## 1.8. GAMMA

---

Usage:

~~~
GAMMA [n][input][output]
[n] ............ n of cases
[input] ........ Input file
[output] ....... Output file
~~~


## 1.9. Geometric

---

$$f\left( X \leq r|p \right) = \sum_{i = 0}^{r}{p \cdot q^{i}}.$$

Usage:

~~~
Geometric [p][r+1] [[1]]
[p] ............ Probability of event A
[r+1] .......... n of trials
[1] ............ (1):full output
~~~

## 1.10. Hypergeometric

---

$$f\left( X \leq k|n,K,N \right) = \sum_{i = 0}^{k}\frac{\binom{K}{i} \cdot \binom{N - K}{n - i}}{\binom{N}{n}}.$$

Usage:

~~~
Hypergeometric [k][n][N][K] [[1]]
[k] ............ n of events A in Sub-Population
[n] ............ Size of Sub-Population
[N] ............ Size of Population
[K] ............ n of events A in Population
[1] ............ (1):full output
~~~

## 1.11. Poisson

---

$$f\left( X \leq k|n,p \right) = \sum_{i = 0}^{k}\frac{(n \cdot p)^{i}}{e^{n \cdot p} \cdot i!}.$$

Usage:

~~~
Poisson [p][k][n] [[1]]
[p] ............ Probability of event A
[k] ............ n of events A
[n] ............ n of trials
[1] ............ (1):full output
~~~

## 1.12. t_Function

---

$$F(t,df) = p = \int_{- \infty}^{t}\frac{\Gamma_{\left( \frac{df - 1}{2} \right)}}{\Gamma_{\left( \frac{df}{2} \right)}} \cdot (df \cdot \pi)^{- \frac{1}{2}} \cdot \left( 1 + \frac{t^{2}}{df} \right)^{- \frac{df - 1}{2}}\ dt.$$

Usage:

~~~
t_Function [mode][x][n]
[mode] ......... (1):Fx=p->t (2):Fy=t->p
[x] ............ p-value/t-value
[n] ............ n of cases
~~~

## 1.13. x2_Function

---

$$F\left( \chi^{2},df \right) = 1 - p^{\alpha 2} = \int_{0}^{\chi^{2}}\frac{1}{2^{\frac{df}{2}} \cdot \Gamma_{\left( \frac{df}{2} \right)}} \cdot \left( \chi^{2} \right)^{\frac{df}{2} - 1} \cdot e^{- \frac{\chi^{2}}{2}}\ d\chi^{2}.$$

Usage:

~~~
x2_Function [mode][x][n]
[mode] ......... (1):Fx=p->x² (2):Fy=x²->p
[x] ............ p-value/x²-value
[n] ............ n of cases
~~~

## 1.14. z_Dichte

---

$$f(z) = \vartheta = \frac{1}{\sqrt{2 \cdot \pi}} \cdot e^{- \frac{z^{2}}{2}},$$
$$f^{- 1}(z) = f(\vartheta) = z = \sqrt{ln(\frac{\vartheta}{\sqrt{(2 \cdot \pi)^{- 1}}})^{- 2}},$$
$$F(z) = p = \int_{- \infty}^{z}\vartheta\ dz.$$

Usage:

~~~
z_Dichte [mode][value] [[f]]
[mode] ......... (1):fx=z->d (2):fy=d->z (3):∫x=z->p
                     (4):∫'p->z (5):∫'p->d (6):∫y=d->p
[value] ........ z-value/z-density/percent-rank p
[f] ............ (1):z-density function graph
~~~

## 1.15. z_Function

---

Usage:

~~~
z_Function [mode][x]
[mode] ......... (1):Fx=p->z (2):Fy=z->p
[x] ............ p-value/z-value
~~~

## 1.16. Theta

---

Usage:

~~~
Theta [sd][min][max][qq][q][v][s] [[x]] [[g]]
[sd]  .......... Seed: |0| Timevalue
[min] .......... R Minimum value
[max] .......... R Maximum value
[qq]  .......... Theta-Theta/
[q]   .......... Theta:
             |0| Harmonic mean (HM)
                 |1| Arithmetic mean (AM)
                 |2| Sum (SUM)
                 |3| Standard deviation (SD)
                 |4| Population variance estimation (VAR)
                 |5| Product sum (PSM)
                 |6| Geometric mean (GM)
                 |7| Schrausser's d (D)
                 |8| DvarO (DV)
[v]  ..........  n of Theta (v)
[s]  ..........  n Subpopulations (s)
[x]  ..........  Test value x
[g]  ..........  |1| Value range integer
~~~

## 1.17. Theta_Q

---

Usage:

~~~
Theta_Q [sd][min][max][qq][qp][qs1][qs2][qQ][v][m][n][s] [[x]] [[g]]
[sd]  ......................... Seed: |0| Timevalue
[min] ......................... R Minimum value
[max] ......................... R Maximum value
[qq]  ......................... Theta-Theta/
[qp]  ......................... Theta P/
[qs1] [qs2] ................... Theta S1, S2:
                                |0| Harmonic mean (HM)
                                |1| Arithmetic mean (AM)
                                |2| Sum (SUM)
                                |3| Standard deviation (SD)
                                |4| Population variance estm. (VAR)
                                |5| Product sum (PSM)
                                |6| Geometric mean (GM)
                                |7| Schrausser's d (D)
                                |8| DvarO (DV)
[qQ]  ......................... Theta Q:
                                |1| Difference
                                |2| Quotient
                                |3| Sum
                                |4| Product
[v]  .........................  n of Theta P (v)
[m]  .........................  n of Theta S1 (m)
[n]  .........................  n of Theta S2 (n)
[s]  .........................  n Subpopulations (s)
[x]  .........................  Test value x
[g]  .........................  |1| Value range integer
~~~

## 1.18. Theta_Qv

---

Usage:

~~~
Theta_Qv [sd][min][max][qq][qp][qs1][qs2][qQ][QQ][v][n][s] [[x]] [[g]]
[sd]  ......................... Seed: |0| Timevalue
[min] ......................... R Minimum value
[max] ......................... R Maximum value
[qq]  ......................... Theta-Theta/
[qp]  ......................... Theta P/
[qs1][qs2]..................... Theta S1, S2/
[qQ]  ......................... Theta Q:
                                |0| Harmonic mean (HM)
                                |1| Arithmetic mean (AM)
                                |2| Sum (SUM)
                                |3| Standard deviation (SD)
                                |4| Population variance estm. (VAR)
                                |5| Product sum (PSM)
                                |6| Geometric mean (GM)
                                |7| Schrausser's d (D)
                                |8| DvarO (DV)
[QQ]  ......................... Theta Theta Q:
                                |1| Difference
                                |2| Quotient
                                |3| Sum
                                |4| Product
                                |5| Correlation
                                |6| Covariance
                                |7| Coefficient of determination
                                |8| Redundancy
[v]  .......................... n of Theta P (v)
[n]  .......................... n of Theta S1,S2 (n)
[s]  .......................... n Subpopulations (s)
[x]  .......................... Test value x
[g]  .......................... |1| Value range integer
~~~

## 1.19. Theta_rQ

---

Usage:

~~~
Theta_rQ [sd][min][max][qq][qp][q11][q12][q21][q22][qr1][qr2][qQ][v]
[m][n][s] [[x]] [[g]]
[sd]  ......................... Seed: |0| Timevalue
[min] ......................... R Minimum value
[max] ......................... R Maximum value
[qq]  ......................... Theta-Theta/
[qp]  ......................... Theta P/
[q11][q12] .................... Theta S11, S12/
[q21][q22] .................... Theta S21, S22:
                                |0| Harmonic mean (HM)
                                |1| Arithmetic mean (AM)
                                |2| Sum (SUM)
                                |3| Standard deviation (SD)
                                |4| Population variance estm. (VAR)
                                |5| Product sum (PSM)
                                |6| Geometric mean (GM)
                                |7| Schrausser's d (D)
                                |8| DvarO (DV)
[qr1][qr2] .................... Theta Regressions 1,2/
                                |1| Correlation (kor)
                                |2| Covariance (cov)
                                |3| Coeff. of determination (det)
                                |4| Redundancy (red)
[qQ]  ......................... Theta Q:
                                |1| Difference (Diff)
                                |2| Quotient (Quot)
                                |3| Sum (Summ)
                                |4| Product (Prod)
[v]  .......................... n of Theta P (v)
[m]  .......................... n of Theta S11,S12 (m)
[n]  .......................... n of Theta S21,S22 (n)
[s]  .......................... n Subpopulations (s)
[x]  .......................... Test value x
[g]  .......................... |1| Value range integer
~~~

## 1.20. Theta_S

---

Usage:

~~~
Theta_S [sd][min][max][qq][qp][qs][v][m][s] [[x]] [[g]]
[sd]  ......................... Seed: |0| Timevalue
[min] ......................... R Minimum value
[max] ......................... R Maximum value
[qq]  ......................... Theta-Theta:
[qp]  ......................... Theta P/
[qs]  ......................... Theta S/
                                |0| Harmonic mean (HM)
                                |1| Arithmetic mean (AM)
                                |2| Sum (SUM)
                                |3| Standard deviation (SD)
                                |4| Population variance estm. (VAR)
                                |5| Product sum (PSM)
                                |6| Geometric mean (GM)
                                |7| Schrausser's d (D)
                                |8| DvarO (DV)
 [v]  ......................... n of Theta P (v)
 [m]  ......................... n of Theta S (m)
 [s]  ......................... n Subpopulations (s)
 [x]  ......................... Test value x
 [g]  ......................... |1| Value range integer
~~~

## 1.21. Verteilungsform

---

Usage:

~~~
Verteilungsform [min][max][n][s]
[min] ......................... Minimum value
[max] ......................... Maximum value
[n] ............. n of parameter Theta=sum(x)
[s] ........................ n Subpopulations
~~~

## 1.22. Verteilungsform_2u

---

Usage:

~~~
Verteilungsform_2u [min][max][q][n1][n2][s] [[xd]] [[g]]
[min] ......................... Minimum value
[max] ......................... Maximum value
[q] ........................... Theta:
                                |0| Harmonic mean
                                |1| Arithmetic mean
                                |2| Sum
                                |3| Standard deviation 
                                |4| Population variance estm.
                                |5| Product sum 
                                |6| Geometric mean
                                |7| Schrausser's d
                                |8| DvarO
[n1] .......................... n1 of Theta
[n2] .......................... n2 of Theta
[s] ........................... n Subpopulations
[xd] .......................... Difference test value
[g] ........................... |1| Value range integer
~~~

## 1.23. Verteilungsform_kor

---

Usage:

~~~
Verteilungsform_kor [min][max][q][n][s] [[x]] [[g]]
[min] ......................... Minimum value
[max] ......................... Maximum value
[q] ........................... Theta:
                                |1| Pearson Correlation
                                |2| Covariance
                                |3| Coeff. of determination
                                |4| Redundancy
                                |5| Regression coefficient ayx
                                |6| Regression coefficient byx
                                |7| Regression coefficient axy
                                |8| Regression coefficient bxy
[n] ........................... n of Theta
[s] ........................... n Subpopulations
[x] ........................... Test value x
[g] ........................... |1| Value range integer
~~~


**Table** 1. *ConsoleApp* *distribution* functions and *bootstrap* overview with corresponding functions in *SCHRAUSSER-MAT* and *HP_Prime_MATH* (Schrausser, [2022](https://doi.org/10.17605/OSF.IO/8XE42), [2025a](https://doi.org/10.5281/zenodo.15713317), res.)*.*

~~~
nr.		Function		
		ConsoleApp				SCHRAUSSER-MAT					HP_Prime_MATH

1		Binomial¹				BNP, BNW	
2		Binomial_T¹				BN1, BN2						ABT1, BINOM, pzBN, zBN, E01
3		Epsilon¹				EFG, ANI, BNI, IMB, EFS, OPP	EPSILON, EFG, EFR, E01
4		F_Function¹				FPW, PFW, PFD					FVTLG, F02, F03Z
5		Fisher_Exact¹			FX0, FX1, FX2					FX_, z4F, pz4F
6		Fisher_Z¹				FZR, RFZ						Zcor, rZ, Zr
7		GAMMA_Function¹			GAMMA, AGAM	
8		GAMMA¹					IGM	F01z, F04
9		Geometric¹				GMP, GMW						GMVTLG
10		Hypergeometric¹			HGP, HGW	
11		Poisson¹				PNP, PNW	
12		t_Function¹				TPW, PTW, PTD					tVTLG, F06_, F02, F06, F03Z
13		x2_Function¹			XPW, PXW, PXD					ch2VTLG, F07_, F02, F07, F03Z
14		z_Dichte¹				DZW, ZDW	
15		z_Function¹				ZPW, PZW, PZD					NVTLG, E01, F02, F03
16		Theta²		
17		Theta_Q²		
18		Theta_Qv²		
19		Theta_rQ²		
20		Theta_S²		
21		Verteilungsform		
22		Verteilungsform_2u		
23		Verteilungsform_kor
~~~	

¹) implemented in *FunktionWin* (Schrausser, [2023f](https://doi.org/10.5281/zenodo.7651661),
[2025c](https://doi.org/10.5281/zenodo.17880113)).  
²) implemented in *ThetaWin* (Schrausser,
[2023g](https://doi.org/10.5281/zenodo.7659264), [2025a](https://doi.org/10.5281/zenodo.17880113)).

<br>

## 2. ConsoleApp_EEG

Console applications (c.f. Schrausser,
[2024b](https://doi.org/10.5281/zenodo.10701349)) for *EEG* (s. Galvani,
[1791](https://doi.org/10.5479/sil.324681.39088000932442); Caton,
[1875](https://journals.lww.com/jonmd/fulltext/1875/10000/electrical_currents_of_the_brain.13.aspx);
Beck,
[1890](https://scholar.google.com/scholar_lookup?&title=Die%20Str%C3%B6me%20der%20Nervenzentren&journal=Zbl%20Physiol&volume=4&pages=572-573&publication_year=1890&author=Beck%2CA)
and Berger, [1929](https://doi.org/10.1007/BF01797193)) parameters
im-plemented in *ATINA* (Schrausser,
[[2006](https://github.com/Schrausser/ATINA)](https://doi.org/10.5281/zenodo.19422127)),
calculating *coherence* (2.1.; c.f. French & Graham,
[1984](https://doi.org/10.1016/0167-8760(84)90044-8); Schrausser et al.,
[2001](https://doi.org/10.5281/zenodo.13738772); Gueva-ra et al.,
[2011](https://doi.org/10.4236/jbise.2011.412096); Puthanmadam
Subramaniyam & Thiagarajan,
[2025](https://doi.org/10.1038/s41598-025-94076-0)), *cross*
*correlation* (2.2.) and *focus* parameters (2.3.-2.6.; s. Schrausser,
[2000a](https://doi.org/10.13140/RG.2.2.32114.17601),
[b](http://doi.org/10.13140/RG.2.2.28637.90083)) from
*[Fourier-analyzed]{.underline}* data (c.f. Fourier,
[1822](https://archive.org/details/bub_gb_TDQJAAAAIAAJ/mode/1up)). More
profound insight into the methods is provided by e.g. Gerthsen
([1966](https://doi.org/10.1007/978-3-662-30201-9)), Kumar and
Bhuvaneswari ([2012](https://doi.org/10.1016/j.proeng.2012.06.298)),
Siuly et al. ([2017](https://doi.org/10.1007/978-3-319-47653-7)), Panov
([2024](https://doi.org/10.1007/978-1-0716-3230-7_5)), Grafakos
([2024](https://doi.org/10.1007/978-3-031-56500-7)), Panitz et al.
([2024](https://doi.org/10.1017/9781009000796.024)), Brigola
([2025](https://doi.org/10.1007/978-3-031-81311-5)) or Meschede et al.
([2026](https://doi.org/10.1007/978-3-662-30201-9)).

For the implementation of the methods in the fields of neuro-psychology
or psychobiology see e.g. Neubauer et al.
([2002](https://doi.org/10.1016/S0160-2896(02)00091-0)), Neubauer et al.
([2005](https://doi.org/10.1016/j.cogbrainres.2005.05.011)),
Micheloyannis et al.
([2006](https://doi.org/10.1016/j.neulet.2006.04.006)), Neubauer and
Fink ([2009](https://doi.org/10.1016/j.neubiorev.2009.04.001)),
Chiarionet al. ([2023](https://doi.org/10.3390/bioengineering10030372)),
Zhang et al. ([2023](https://doi.org/10.1186/s40779-023-00502-7)) or
Nguyen et al.
([2025](https://doi.org/10.1161/circ.152.suppl/_3.4373687)), c.f.
further Adrian ([2016](https://doi.org/10.9783/9781512809794)),
Tassinari ([2019](https://doi.org/10.1016/j.clinph.2019.10.010)) and
Rossini et al. ([2025](https://doi.org/10.1016/j.clinph.2024.11.021)).

### 2.1. ERC, ERCX

---

Calculates *event related* *coherence* $ERC$, where *coherence*

$$Coh_{xy}^{2} = \frac{P_{xy}^{2}(f)}{P_{xx}(f) \cdot P_{yy}(f)},$$

with *cross power* $P_{xy}$ within given frequency $f$ in $\mathbb{C}$
defined by

$$P_{xy}(f)\mathfrak{= R}\left( a_{xy} \right)^{2}\mathfrak{+ I}\left( a_{xy} \right)^{2},$$

c.f. Schrausser ([2000b](http://doi.org/10.13140/RG.2.2.28637.90083)).

Usage:

~~~
erc [input][output][nCoh][nX][refs][refe][acts][acte][typ]
[input] ................. Input File, Format ASCII tab. (e.g. coh.asc)
[output] ................ Output File
[nCOH] .................. Number of coherence values 
[nX] .................... Number of channel combinations
[refs] .................. Number of reference start value 
[refe] .................. Number of reference end value
[acts] .................. Number of active start value
[acte] .................. Number of active end value
[typ] ................... Type of output (0):individual (1):append
~~~

### 2.2. XCOR

---

Calculates *cross correlation* $xCOR$.

Usage:

~~~
xcor [input][output][n][k]
[input] ..... Input File, Format ASCII tab. (e.g. data.dat)
[output] .... Output File
[n] ......... Number of cases
[k] ......... Number of variables
~~~

### 2.3. FOC

---

Calculates *focus* parameter $yf$, where

$$yf = \sum_{i = 1}^{k}{1 - \frac{\frac{x_{i} - x_{\min}}{d}}{k - 1}},$$

with

$$d = x_{\max} - x_{\min}.$$

Usage:

~~~
foc [input][output][n][k]
[input] ..... Input File, Format ASCII tab. (e.g. data.dat)
[output] .... Output File
[n] ......... Number of cases
[k] ......... Number of leads
~~~

### 2.4. DIS

---

Reading in *distance* values $d_{ij}$ for $x_{i}$, $x_{j}$ and
calculates *wights* $g_{ij}$ defined by

$$g_{ij} = \frac{\frac{1}{d_{ij}}}{\sum_{j = 1}^{n}\frac{1}{d_{ij}}}.$$

Usage:

~~~
dis [input][output][n][k]
[input] ..... Input File, Format ASCII tab. 
[output] .... Output File
[n] ......... Number of cases
[k] ......... Number of leads
~~~

### 2.5. FLOC

---

Calculates *spatial* *focus* parameter $yloc$, where

$$yloc = \frac{\sum_{i = 1}^{k}{\sum_{j = 1}^{k - 1}{\frac{1}{G_{i}} \cdot \left\lbrack \left( 1 - \frac{x_{i} - x_{\min}}{d} \right) \cdot w_{G_{ij}} \right\rbrack}}}{k - 2},$$

with

$$G_{i} = \sum_{j = 1}^{k - 1}g_{ij},$$
$$w_{G_{ij}} = g_{ij} \cdot \left( 1 - \frac{x_{j} - x_{\min}}{d} \right).$$

Usage:

~~~
floc [input][output][n][k][distance]
[input] ..... Input File, Format ASCII tab. (e.g. data.dat)
[output] .... Output File
[n] ......... Number of cases
[k] ......... Number of leads
[distance] .. Distance Matrix File
~~~

### 2.6. OUT

---

Generates output file.

Usage:

~~~
out [input][n][k][start][end] 
[input] ..... Input File, Format ASCII tab. (e.g. coh.asc)
[n] ......... Number of values / cases / rows
[k] ......... Number of variables / columns 
[start] ..... Number of block start value 
[end] ....... Number of block end value
~~~

<br>

## 3. ConsoleApp_Integral

Console applications for *integral* and *interpolation* (see
Schraus-ser, [2023b](https://doi.org/10.5281/zenodo.7655056)). For the
basic concept of *[Riemann sums]{.underline}* (Riemann,
[1868](http://eudml.org/doc/135759)), see Lewis et al.
([1978](https://doi.org/10.1007/978-3-0348-5563-1_25.)), Hassler
([2007](https://doi.org/10.1007/978-3-540-73568-7_7)), Truc
([2019](https://www.jstor.org/stable/48662056)), Torchinsky
([2022](https://doi.org/10.1007/978-3-031-11799-2)), Forster and
Lindemann ([2023](https://doi.org/10.1007/978-3-658-40130-6_18)),
further Goel and Rodriguez
([1987](http://www.jstor.org/stable/2689344)), Guillemin and Stroock
([2008](https://doi.org/10.1007/978-0-8176-4683-7_1)), Büchter and Henn
([2010](https://doi.org/10.1007/978-3-8274-2680-2_6)), for *integral
calculus* in general see Schwarz
([1997](https://doi.org/10.1007/978-3-663-01227-6_8)), Meyberg and
Vachenauer ([2001a](https://doi.org/10.1007/978-3-642-56654-7_4)), Allen
and Isaacson ([2019](https://doi.org/10.1002/9781119245476.ch7)) or
Neher ([2024](https://doi.org/10.1007/978-3-662-68815-1_7)).

The included methods are as follows:

(3.1.-3.2.) *Romberg's method* (Romberg,
[1955](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://web.eng.fiu.edu/LEVY/images/EGM5346/romberg%2520textbook%2520example.pdf&ved=2ahUKEwiSxr-u846SAxVFQvEDHd83Bj8QFnoECHMQAQ&usg=AOvVaw3vtOkKCF8WeDkOB49i_03i))
as an analytical method for achieving higher approximation accuracy for
inte-grals, based on the *Richardson extrapolation* (Richardson,
[1911](https://doi.org/10.1098/rsta.1911.0009); s. Rannacher,
[1987](https://doi.org/10.1007/978-3-322-85997-6_9); Bickel & Yahav,
[1988](http://www.jstor.org/stable/2288854); Sidi,
[1988](https://doi.org/10.1007/978-3-0348-6398-8_22),
[2003](https://doi.org/10.1017/CBO9780511546815); Du-beau,
[2019](https://doi.org/10.1016/j.jcpx.2019.100017); Bach,
[2021](https://doi.org/10.1137/21M1397349)) or the *trapezoidal rule*
(c.f. Luke et al.,
[1969](https://doi.org/10.1016/S0076-5392(09)60075-8); Abdulhameed &
Memon, [2021](https://doi.org/10.1088/1742-6596/2090/1/012104); Izzo et
al., [2022](https://doi.org/10.1016/j.jcp.2022.111193); Bujang,
[2025](https://doi.org/10.1063/5.0294833)), respectively. The
*Richardson extrapolation* is further used, for example, in machine
learning and other fields to *ac-celerate* convergences. In this context
c.f. Herrmann ([1983](https://doi.org/10.1007/978-3-322-96321-5_27)),
Jetter ([1984](https://doi.org/10.1007/BF01389471)), Talay and Tubaro
([1990](https://doi.org/10.1016/0167-4730(90)90036-O)), von Petersdorff
([1993](http://www.jstor.org/stable/2324787)) or Meyberg and Vachenauer
([2001b](https://doi.org/10.1007/978-3-642-56654-7_4), p. 209).

(3.3.-3.4.) the *Cubic spline* interpolation (Schoenberg,
[1946](https://doi.org/10.1090/qam/15914); c.f. Rabut,
[1992](https://doi.org/10.1016/0898-1221(92)90177-J); Agarwal & Wong,
[1993](https://doi.org/10.1007/978-94-011-2026-5_6); Farin,
[1994](https://doi.org/10.1007/978-3-663-10602-9_9)) as a method for
*polynomial* *curve fitting* and precise interpolation of *em-pirical*
data points, where the rate of change corresponds to the slope,
resulting in smooth, continuous function curves. See in this context
Cheng and Barsky ([1991](https://doi.org/10.1016/0010-4485(91)90023-P)),
Fredenhagen et al. ([1999](https://doi.org/10.1006/jath.1998.3247)),
Jiang and Zhao ([2009](https://doi.org/10.1109/FSKD.2009.591)), Moon
([2001](https://doi.org/10.1016/S0096-3003(99)00178-2)), Sarfraz
([2008](https://doi.org/10.1007/978-1-84628-871-5_8)), Sun et al.
([2023](https://doi.org/10.1016/j.cam.2022.115039)), Török et al.
([2025](https://doi.org/10.1016/j.amc.2025.129411)), Jarre
([2025](https://doi.org/10.48550/arXiv.2507.05083),
[2026](https://doi.org/10.1016/j.cam.2025.117240)). For application in
*EEG* examination and psychophysiology, see e.g. Perrin et al.
([1987](https://doi.org/10.1016/0013-4694(87)90141-6)), Soufflet et al.
([1991](https://doi.org/10.1016/0013-4694(91)90204-H)), Congedo et al.
([2002](https://doi.org/10.1300/J184v06n04_08)), Roy and Shukla
([2017](https://doi.org/10.1007/s11277-017-4846-3)), Abduganiev et al.
([2023](https://doi.org/10.1007/978-3-031-27199-1_3)) or Schulter et al.
([2023](https://doi.org/10.1038/s41598-023-49307-7), p. 5).

(3.5.-3.6.) the *Newton* interpolation (Cardano,
[1545](https://web.archive.org/web/20220201093634/http:/www.filosofia.unimi.it/cardano/testi/operaomnia/vol_4_s_4.pdf);
Newton,
[1687](https://books.google.at/books?id=XJwx0lnKvOgC&pg=PP2&redir_esc=y#v=onepage&q&f=false))
as a further method for *curve fitting* which is easier to calculate,
however, has lower accuracy and stability compared to interpolation via
*cubic splines*, calculates a significantly less smooth curve and is
therefore better suited for *smaller* datasets and lower accuracy
requirements. For an overview c.f. Rutis-hauser
([1990](https://doi.org/10.1007/978-1-4612-3468-5_6)), Scherer
([2010](https://doi.org/10.1007/978-3-642-13990-1_2)) or Epperson
([2021](https://doi.org/10.1002/9781119604570.ch4)), further in-sight
give e.g. Tsao ([1977](https://doi.org/10.1007/BF01389317)) and Zou et
al. ([2020](https://doi.org/10.1155/2020/9020541)).

### 3.1. ROMI

---

Approximates (i) *surface* or (ii) *curve integrals \[Approximiert (i)
Flächen- oder (ii) Kurven-Integrale\]*

$$\int_{a}^{b}f(x)dx$$

by means of the *Romberg method*, if applicable including file output to
***romi.txt*** from the function *matrix \[mittels Romberg Methode,
dabei ggf. Dateiausgabe nach romi.txt von Funkti-onsmatrix\]*

$$\mathbf{F =}\left( \mathbf{x|y} \right),$$

where *\[bei\]*

$$x = \frac{x + d}{2},y = \int_{a}^{b}{f(x)dx}.$$

-   Execution of ***ROMI.bat***:
-   Definition of $f(x)$ in ***ROMI.h***;
-   Compiling ***ROMI.c***;
-   Execution of ***ROMI.exe***.

-   *\[Ausführung von ROMI.bat:\]*
-   *\[Definition von* $f(x)$ *in ROMI.h;\]*
-   *\[Compilieren von ROMI.c;\]*
-   *\[Ausführung von ROMI.exe.\]*

Usage *\[Handhabung\]*:

~~~
ROMI [a][b][d][m][F]
[a] ......... Integration Minimum a
[b] ......... Integration Maximum b
[d] ......... Delta d
[m] ......... Mode (0):Area.I (1):Curve.I
[F] ......... Function matrix (0):none (1):romi.txt
~~~

Example *\[Bsp.\]*:

~~~
ROMI.bat
ROMI 1 10 0.0001 0 0
ROMI -9 0 0.5 0 1
~~~

### 3.2. ROME

---

Approximates $\int_{a}^{b}f(x)dx$ using *Romberg extrapolation*
*\[Appro-ximiert* $\int_{a}^{b}f(x)dx$ *mittels Romberg-Extrapolation\]*
(see. Mey-berg & Vachenauer,
[2001b](https://doi.org/10.1007/978-3-642-56654-7_4), p. 209).

-   Execution of ***ROME.bat***:
-   Definition of $f(x)$ in ***ROME.h***
-   Compiling ***ROME.c***;
-   Execution of ***ROME.exe***.

-   *\[Ausführung von ROME.bat:\]*
-   *\[Definition von* $f(x)$ *in ROME.h;\]*
-   *\[Compilieren von ROME.c;\]*
-   *\[Ausführung von ROME.exe.\]*

Usage *\[Handhabung\]*:

~~~
ROME [a][b]
[a] ......... Integration Minimum a
[b] ......... Integration Maximum b
~~~

Example *\[Bsp.\]*:

~~~
ROME.bat
ROME 1 10
ROME -14 1
~~~

### 3.3. KUSI

---

*Cubic spline* interpolation: Calculation of the
*[coefficient]{.underline}* *matrix*
$\mathbf{A =}\left( \mathbf{b}\left| \mathbf{c} \right|\mathbf{d} \right)\ $and
$\mathbf{s}\left( \mathbf{x} \right)$ for an (empirical) function
*matrix* $\mathbf{F =}\left( \mathbf{x|y} \right)$, where *\[Kubische
Spline Interpolation: Berechnung der [Koeffizienten]{.underline}-matrix*
$\mathbf{A =}\left( \mathbf{b}\left| \mathbf{c} \right|\mathbf{d} \right)$
*sowie* $\mathbf{s}\left( \mathbf{x} \right)$ *zu einer (empiri-schen)
Funktionsmatrix* $\mathbf{F =}\left( \mathbf{x|y} \right)$*, wobei\]*

$$s_{i}(x) = y_{i} + b_{i} \cdot \left( x - x_{i} \right) + c_{i} \cdot \left( x - x_{i} \right)^{2} + d_{i} \cdot \left( x - x_{i} \right)^{3};i = 0,1,...,n - 1.$$

-   Import of an *ASCII* function *matrix* file $\mathbf{F}$;
-   Output of the *ASCII* coefficient *matrix* file $\mathbf{A}$
    (***KUSI.txt***);
-   Calculation of $\mathbf{s}\left( \mathbf{x} \right)$ via the
    interpolation function.

-   *\[Übernahme einer ASCII Funktionsmatrix Datei* $\mathbf{F}$*;\]*
-   *\[Ausgabe der ASCII Koeffizientenmatrix Datei* $\mathbf{A}$
    *(KUSI.txt);\]*
-   *\[Berechnung von* $\mathbf{s}\left( \mathbf{x} \right)$ *über die
    Interpolations-Funktion.\]*

Usage *\[Handhabung\]*:

~~~
KUSI [f][x]
[f] ......... Function matrix file (F)
[x] ......... Function value x
~~~

Example *\[Bsp.\]*:

~~~
KUSI in.txt 0.5
~~~

### 3.4. KUSF

---

*Cubic spline* function: Calculation of a [function]{.underline}
*matrix*
$\mathbf{S =}\left( \mathbf{x|s}\left( \mathbf{x} \right) \right)$
corresponding to coefficient *matrix*
$\mathbf{A =}\left( \mathbf{b}\left| \mathbf{c} \right|\mathbf{d} \right)$,
where *\[Kubische Spline Funktion: Berechnung einer
[Funktions]{.underline}-matrix*
$\mathbf{S =}\left( \mathbf{x|s}\left( \mathbf{x} \right) \right)$ *zu
Koeffizientenmatrix*
$\mathbf{A =}\left( \mathbf{b}\left| \mathbf{c} \right|\mathbf{d} \right)$*,
wobei\]*

$$s_{i}(x) = y_{i} + b_{i} \cdot \left( x - x_{i} \right) + c_{i} \cdot \left( x - x_{i} \right)^{2} + d_{i} \cdot \left( x - x_{i} \right)^{3};i = 0,1,...,n - 1.$$

-   Import of an *ASCII* function *matrix* file $\mathbf{F}$;
-   Import of the *ASCII* coefficient *matrix* file $\mathbf{A}$
    (***KUSI.txt***);
-   Output of the *ASCII* function *matrix* file $\mathbf{S}$
    (***KUSF.txt***).

-   *\[Übernahme einer ASCII Funktionsmatrix Datei* $\mathbf{F}$*;\]*
-   *\[Übernahme der ASCII Koeffizientenmatrix Datei* $\mathbf{A}$
    *(KUSI.txt);\]*
-   *\[Ausgabe der ASCII Funktionsmatrix Datei* $\mathbf{S}$
    *(KUSF.txt).\]*

Usage *\[Handhabung\]*:

~~~
KUSF [f][a][b][d] 
[f] ......... Function matrix file (F)
[a] ......... (x) Minimum
[b] ......... (x) Maximum
[d] ......... Interval d
~~~

Example *\[Bsp.\]*:

~~~
KUSF in.txt 1 10 0.1
~~~

### 3.5. NWTI

*Newton* interpolation: Calculation of the [coefficient]{.underline}
*vector* $\mathbf{a}$ as well as $\mathbf{p}\left( \mathbf{x} \right)$
for an (empirical) function *matrix*
$\mathbf{F =}\left( \mathbf{x|y} \right)$, where *\[Newton
Interpolation: Berechnung des [Koeffizientenvektors]{.underline}*
$\mathbf{a}$ *sowie* $\mathbf{p}\left( \mathbf{x} \right)$ *zu einer
(empirischen) Funktionsmatrix*
$\mathbf{F =}\left( \mathbf{x|y} \right)$*, wobei\]*

$$p(x) = a_{0} + a_{1} \cdot (x - 1) + a_{2} \cdot (x - 1) \cdot (x - 2)...a_{n} \cdot (x - 1) \cdot (x - 2) \cdot ... \cdot (x - n).$$

-   Import of an *ASCII* function *matrix* file $\mathbf{F}$;
-   Output of the *ASCII* coefficient *vector* file $\mathbf{a}$
    (***nwti.txt***);
-   Calculation of $\mathbf{p}\left( \mathbf{x} \right)$ using the
    interpolation polynomial.

-   *\[Übernahme einer ASCII Funktionsmatrix Datei* $\mathbf{F}$*;\]*
-   *\[Ausgabe einer ASCII Koeffizientenvektor Datei* $\mathbf{a}$
    *(nwti.txt);\]*
-   *\[Berechnung von* $\mathbf{p}\left( \mathbf{x} \right)$ *über das
    Interpolations-Polynom.\]*

Usage *\[Handhabung\]*:

~~~
NWTI [f][x]
[f] ......... Function matrix file (F)
[x] ......... Function value x
~~~

Example *\[Bsp.\]*:

~~~
NWTI in.txt 3
~~~

### 3.6. NWTP

*Newton* Interpolation Polynomial: Calculation of a
[function]{.underline} *ma-trix*
$\mathbf{F =}\left( \mathbf{x|p}\left( \mathbf{x} \right) \right)$
corresponding to coefficient *vector* $\mathbf{a}$, where *\[Newton
Interpolations Polynom: Berechnung einer
[Funk]{.underline}-[tionsmatrix]{.underline}*
$\mathbf{F =}\left( \mathbf{x|p}\left( \mathbf{x} \right) \right)$ *zu
Koeffizientenvektor* $\mathbf{a}$*, wobei\]*

$$p(x) = a_{0} + a_{1} \cdot (x - 1) + a_{2} \cdot (x - 1) \cdot (x - 2)...a_{n} \cdot (x - 1) \cdot (x - 2) \cdot ... \cdot (x - n).$$

-   Import of the *ASCII* coefficient *vector* file $\mathbf{a}$
    (***nwti.txt***);
-   Output of the *ASCII* function *matrix* file $\mathbf{F}$
    (***nwtp.txt***).

-   *\[Übernahme der ASCII Koeffizientenvektor Datei* $\mathbf{a}$
    *(nwti.txt);\]*
-   *\[Ausgabe der ASCII Funktionsmatrix Datei* $\mathbf{F}$
    *(nwtp.txt).\]*

Usage *\[Handhabung\]*:

~~~
NWTP [a][b][d]
[a] ......... (x) Minimum
[b] ......... (x) Maximum
[d] ......... Interval d
~~~

Example *\[Bsp.\]*:

~~~
NWTP 1 10 0.1
~~~

<br>

## 4. ConsoleApp_Matrix

Console applications for (4.1.-4.9.) *matrix* calculation (Cayley,
[1858](http://www.jstor.org/stable/108649); c.f. Cardano,
[1545](https://web.archive.org/web/20220201093634/http:/www.filosofia.unimi.it/cardano/testi/operaomnia/vol_4_s_4.pdf);
Heisenberg, [1925](https://doi.org/10.1007/BF01328377); Turing,
[1948](https://turing.academicwebsite.com/publications/20-rounding-off-errors-in-matrix-processes)
or Crilly, [1986](https://doi.org/10.1016/0315-0860(86)90091-1)) and
(4.10.-4.21.) *tools*, s. Schrausser
([2023c](https://doi.org/10.5281/zenodo.7655046)); on the topic in
general c.f. Meyberg and Vachenauer
([2001](https://doi.org/10.1007/978-3-642-56654-7)), Grcar
([2011](https://doi.org/10.1016/j.hm.2010.06.003)), Karpfinger
([2022a](https://doi.org/10.1007/978-3-662-65458-3_10),
[b](https://doi.org/10.1007/978-3-662-63305-2_11)), Shores
([2018](https://doi.org/10.1007/978-3-319-74748-4_2)), Gentle
([2024](https://doi.org/10.1007/978-3-031-42144-0)) or Saff and Snider
([2025](https://doi.org/10.1007/978-3-031-97222-5)).

### 4.1. AMA

---

Adds or subtracts 2 *matrices*, with given *\[Addiert oder subtra-hiert
2 Matrizen\]*,

$$k_{1} = k_{2}\text{,\ }n_{1} = n_{2}.$$

*\[wird vorausgesetzt\]*.

-   Import of 2 *ASCII matrix* files.
-   Output of an *ASCII matrix* file.

-   *\[Übernahme 2er ASCII Matrixdateien.\]*
-   *\[Ausgabe einer ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
AMA [matrix1][matrix2][output][mode] 
[matrix1] ... Input file 1 
[matrix2] ... Input file 2 
[output] .... Output file 
[mode] ...... (0):Addition (1):Subtraction
~~~

Example *\[Bsp.\]*:

~~~
AMA in1.txt in2.txt out.txt 0
~~~

### 4.2. IMA

---

Calculates the inverse $\mathbf{A}^{- 1}$ of $\mathbf{A}$ using the
*chained* form of *Gaus-sian elimination \[Berechnet die inverse*
$\mathbf{A}^{- 1}$ *von* $\mathbf{A}$ *über die ver-kettete Form des
Gaussschen Algorithmus\]*,

$$k_{\max} = n_{\max} = 200,a_{11} \neq 0.$$

This results in two triangular *matrices* $\mathbf{B}$ and $\mathbf{C}$,
as well as the *matrix* $\mathbf{T}$ to the generated identity *matrix*
$\mathbf{E}$; $\mathbf{A}^{- 1}$ is obtained by its transpose *\[Es
resultieren 2 Dreiecksmatrizen* $\mathbf{B}$ *und* $\mathbf{C}$*, sowie
die Matrix* $\mathbf{T}$ *zur erzeugten Einheitsmatrix* $\mathbf{E}$*,*
$\mathbf{A}^{- 1}$ *entsteht trans-poniert\]:*

~~~
. . .  A   1 0 0  E
. . .      0 1 0
. . .      0 0 1

. . .  B   . . .  T
  . .      . . .
    .      . . .
.      C
. .

. . . (1/A)'
. . .
. . .
~~~

-   Import of a square *ASCII matrix* file.
-   Output of a square *ASCII matrix* file.

-   *\[Übernahme einer quadratischen ASCII Matrixdatei.\]*
-   *\[Ausgabe einer quadratischen ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
IMA [matrix][output] 
[matrix] ....... Input file 
[output] ....... Output file
~~~

Example *\[Bsp.\]*:

~~~
IMA in.txt out.txt
~~~

### 4.3. MMA

---

Multiplies two *matrices* ($k_{1} = n_{2}$ is assumed). The
result is a *matrix* with *\[Multipliziert 2 Matrizen (*$k_{1} = n_{2}$
*wird voraus-gesetzt). Es resultiert eine Matrix mit\]*

$$n = n_{1},\text{\ }k = k_{2}:$$

~~~
       *          =
 o . .   o o         o o
 o . .   . .         o .
         . .
 
 
 o . .   o o         o o
 o . .   . .         o .
 o . .   . .         o .    
 o . .               o .
 o . .               o .
~~~

-   Import of 2 *ASCII* *matrix* files.
-   Output of an *ASCII matrix* file.

-   *\[Übernahme 2er ASCII Matrixdateien.\]*
-   *\[Ausgabe einer ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
MMA [matrix1][matrix2][output] 
[matrix1] ...... Input file 1 
[matrix2] ...... Input file 2 
[output] ....... Output file
~~~

Example *\[Bsp.\]*:

~~~
MMA m1.txt m2.txt m3.txt
~~~

### 4.4. QMA

---

Squaring a square *matrix \[Quadriert eine quadratische Matrix\]*:

~~~
        *       =
 o .   o o      o o
 o .   . .      o .
~~~

-   Import of a square *ASCII matrix* file.
-   Output of a square *ASCII matrix* file.

-   *\[Übernahme einer quadratischen ASCII Matrixdateien.\]*
-   *\[Ausgabe einer quadratischen ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
QMA [matrix][output] 
[matrix] ....... Input file 
[output] ....... Output file
~~~

Example *\[Bsp.\]*:

~~~
QMA a.txt b.txt
~~~

### 4.5. SMA

---

Selects a *submatrix* (or *vector*) from a *matrix* *\[Selegiert eine
Sub Matrix (oder einen Vektor) aus einer Matrix\]*.

-   Importing an *ASCII matrix* file.
-   Output of an *ASCII* (*matrix*) file.

-   *\[Übernahme einer ASCII Matrixdatei.\]*
-   *\[Ausgabe einer ASCII (Matrix-)Datei.\]*

Usage *\[Handhabung\]*:

~~~
SMA [matrix][output][i0][i1][j0][j1] 
[matrix] ...... Matrix file 
[output] ...... Matrix output file 
[i0] .......... From line 
[i1] .......... To line 
[j0] .......... From column 
[j1] .......... To column
~~~

Example *\[Bsp.\]*:

~~~
SMA in.txt out1.txt 1 5 2 2 //Columnvector j2
SMA in.txt out2.txt 2 2 1 5 //Linevector i2
SMA in.txt out3.txt 2 4 2 4 //Submatrix
SMA in.txt out4.txt 3 3 3 3 //Single number
~~~

### 4.6. SPUR

---

Calculates the trace (*sp*) of a square *matrix* $\mathbf{A}$
*\[Berechnet die Spur (sp) einer quadratischen Matrix* $\mathbf{A}$*\]*:

~~~
o . .  A
. o .  
. . o
       sp A
~~~

-   Import of a square *ASCII matrix* file.
-   Output of *sp* $\mathbf{A}$ in file ***SPUR.txt***.

-   *\[Übernahme einer quadratischen ASCII Matrixdatei.\]*
-   *\[Ausgabe von sp* $\mathbf{A}$ *in die Datei SPUR.txt.\]*

Usage *\[Handhabung\]*:

~~~
SPUR [matrix][mode] 
[matrix] ...... Input file 
[mode] ........ Mode of trace calculation: 
                (0):Addition (Standard) 
                (1):Multiplication (s. VMA.exe)
                (2):Subtraction
                (3):Division
~~~

Example *\[Bsp.\]*:

~~~
SPUR in.txt 0
~~~

### 4.7. TRP

---

Transposes a data *matrix* *\[Transponiert eine Datenmatrix\]*,

$$n_{\max} = k_{\max} = 1299.$$

Column separator, input file: tab or space. Column separator, output
file: 1 space *\[Spaltentrennzeichen, Eingabedatei: Tabula-tor oder
Leerzeichen. Spaltentrennzeichen, Ausgabedatei: 1 Leerzeichen\].*

-   Importing an *ASCII* data *matrix* file.
-   Output of a transposed *ASCII* data *matrix* file.

-   *\[Übernahme einer ASCII Datenmatrixdatei.\]*
-   *\[Ausgabe einer transponierten ASCII Datenmatrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
TRP [input][output] 
[input] ....... Input file 
[output] ...... Output file
~~~

Example *\[Bsp.\]*:

~~~
TRP in.txt out.txt
~~~

### 4.8. VMA

---

Calculates the *chained* form of *Gaussian elimination* of a square
*matrix* $\mathbf{A}$, with *\[Berechnet die verkettete Form des
Gaussschen Algorithmus einer quadratischen Matrix* $\mathbf{A}$*, mit\]*

$$k_{\max} = n_{\max} = 250,a_{11} \neq 0.$$

This results in two triangular matrices $\mathbf{B}$ and $\mathbf{C}$
*\[Es resultieren 2 Dreiecksmatrizen* $\mathbf{B}$ *und*
$\mathbf{C}$*\]*:

~~~
. . .  A
. . .  
. . .

. . .  B
  . .
    .
.      C
. .
~~~

The determinant of $\mathbf{A}$ (det $\mathbf{A}$) is the product of the
elements in the main diagonal of $\mathbf{B}$ ($\mathbf{TT}b_{ii}$)
*\[Die Determinante von* $\mathbf{A}$ *(det* $\mathbf{A})$ *ist das
Produkt der Elemente in der Hauptdiagonale von* $\mathbf{B}$
*(*$\mathbf{TT}b_{ii}$*)\]*.

-   Import of a square *ASCII matrix* file.
-   Output of a square *ASCII matrix* file.

-   *\[Übernahme einer quadratischen ASCII Matrixdatei.\]*
-   *\[Ausgabe einer quadratischen ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
VMA [matrix][output] 
[matrix] ...... Input file 
[output] ...... Output file
~~~

Example *\[Bsp.\]*:

~~~
VMA in.txt out.txt
~~~

### 4.9. ZMA

---

Multiplies a *matrix* by a real number *\[Multipliziert eine Matrix mit
einer reellen Zahl\]*.

-   Import of an *ASCII matrix* file.
-   Output of an *ASCII matrix* file.

-   *\[Übernahme einer ASCII Matrixdatei.\]*
-   *\[Ausgabe einer ASCII Matrixdatei.\]*

Usage *\[Handhabung\]*:

~~~
ZMA [matrix][output][wert] 
[matrix] ...... Input file 
[output] ...... Output file 
[wert] ........ Real number
~~~

Example *\[Bsp.\]*:

~~~
ZMA in.txt out.txt 3
~~~

### 4.10. ENT

---

Performs a symmetrical interlaced split of a data *vector* file
$\mathbf{x}_{0}$ *\[Führt eine symmetrische entwobene Aufteilung einer
Datenvek-tordatei* $\mathbf{x}_{0}$ *durch\]*:

~~~
x0
--
1
2
3
4

x1 x2
-- --
1
   2
3
   4
~~~

-   Importing a single-column *ASCII* file.
-   Output of 2 single-column *ASCII* files.

-   *\[Übernahme einer einspaltigen ASCII Datei.\]*
-   *\[Ausgabe von 2 einspaltigen ASCII Dateien.\]*

Usage *\[Handhabung\]*:

~~~
ENT [input][output1][output2] 
[input] ...... Input file  
[output1] .... Output file 1 
[output2] .... Output file 2
~~~

Example *\[Bsp.\]*:

~~~
ENT in.txt out1.txt out2.txt
~~~

### 4.11. KTF

---

Reduces or increases the size of a *perfectly* linear data *vector*. The
data adjustment up to $n'$ is iteratively performed by *\[Verrin-gert
oder vergrössert den Umfang eines perfekt linearen Daten-vektors. Die
bis* $n'$ *iterative Datenanpassung erfolgt über\]*

$$x_{i}\lbrack n\rbrack = x_{i}\lbrack n + 1\rbrack \cdot \frac{n}{n - 1};n' < n,$$
$$x_{i}\lbrack n\rbrack = x_{i}\lbrack n - 1\rbrack \cdot \frac{n - 2}{n - 1};n' > n.$$

-   Import of a single-column, ascendingly ordered *ASCII* data *vector*
    file of size $n$.
-   Output of a single-column, ascendingly ordered *ASCII* data *vector*
    file of size $n'$.

-   *\[Übernahme einer einspaltigen, aufsteigend geordneten ASCII
    Datenvektordatei im Umfang* $n.$*\]*
-   *\[Ausgabe einer einspaltigen, aufsteigend geordneten ASCII
    Datenvektordatei im Umfang* $n^{'}.$*\]*

Usage *\[Handhabung\]*:

~~~
ktf [input][output][n] 
[input] ....... Input file  
[output] ...... Output file 
[n] ........... Vector size n’
~~~

Example *\[Bsp.\]*:

~~~
ktf data_in.txt data_out.txt 30
~~~

### 4.12. KTF2

---

Reduces or increases the size of a data *vector* *\[Verringert oder
vergrössert den Umfang eines Datenvektors\]*
($n_{\max} = n'_{\max} = 33000$).

-   Import of a single-column, ascendingly ordered *ASCII* data *vector*
    file of size $n$.
-   Output of a single-column, ascendingly ordered *ASCII* data *vector*
    file of size $n'$.

-   *\[Übernahme einer einspaltigen, aufsteigend geordneten ASCII
    Datenvektordatei im Umfang* $n.$*\]*
-   *\[Ausgabe einer einspaltigen, aufsteigend geordneten ASCII
    Datenvektordatei im Umfang* $n^{'}.$*\]*

Usage *\[Handhabung\]*:

~~~
ktf2 [input][output][n] 
[input] ....... Input file 
[output] ...... Output file 
[n] ........... Vector size n’
~~~

Example *\[Bsp.\]*:

~~~
ktf2 in.txt out.txt 12
ktf2 in.txt out.txt 110
~~~

### 4.13. KTF3

---

Adapts a data *vector* to a target coordinate system. The data
adaptation is performed by *\[Passt einen Datenvektor an ein
Ziel-Koordinatensystem an. Die Datenanpassung erfolgt über\]*

$$x_{i}' = min_{x} + \{\lbrack\left( min_{x} - x_{\min} \right) - \left( min_{x} - x_{i} \right)\rbrack \cdot \frac{max_{x} - min_{x}}{\left( min_{x} - x_{\min} \right) - \left( min_{x} - x_{\max} \right)}\}$$

When inverting a value, $x''_{i}$ is calculated as *\[bei einer
Wertinver-tierung errechnet man* $x''_{i}$ *über\]*

$$x''_{i} = \left( min_{x} + max_{x} \right) - x'_{i},$$

where *\[mit\]*

$min_{x}$ ..... Value of the minimum point in the target coordinate
system\
$max_{x}$ .... Value of the maximum point in the target coordinate
system\
$x_{\min}$ ....... *Vector* minimum value\
$x_{\max}$ ...\... *Vector* maximum value

$min_{x}$ ..... *[Wert des Minimalpunktes im Ziel-Koordinatensystem]*  
$max_{x}$ ....*[Wert des Maximalpunktes im Ziel-Koordinatensystem]*  
$x_{\min}$ ....... *[Vektor Minimalwert]*  
$x_{\max}$ ...... *[Vektor Maximalwert]*

-   Import of a single-column, ascendingly ordered *ASCII* data *vector*
    file.
-   Output of a two-column, ascendingly ordered *ASCII* data *matrix*
    file containing:

-   *\[Übernahme einer einspaltigen, aufsteigend geordneten ASCII
    Datenvektordatei.\]*
-   *\[Ausgabe einer zweispaltigen, aufsteigend geordneten ASCII
    Datenmatrixdatei beinhaltend:\]*

The data *vector* adapted to the target coordinate system;
the initial data *vector* *\[Den an das Ziel-Koordinatensystem
angepassten Datenvektor; den ursprünglichen Datenvektor\]*.

Usage *\[Handhabung\]*:

~~~
ktf3 [input][output][minx][maxx][inv] 
[input] ....... Input file 
[output] ...... Output file 
[minx] ........ Val. of the min. point in the target coordinate system
[maxx] ........ Val. of the max. point in the target coordinate system
[inv] ......... (1):Value inversion (0):No Value inversion
~~~

Example *\[Bsp.\]*:

~~~
**ktf3** data_in.txt data_out.txt 1 100 1
**ktf3** data_in.txt data_out.txt 371 51 0
~~~

### 4.14. NTF

---

Generates an ascending linear data *vector* and fits it to a target
coordinate system. The data fitting is performed by *\[Erzeugt einen
aufsteigend geordneten linearen Datenvektor und passt diesen an ein
Ziel-Koordinatensystem an. Die Datenanpassung erfolgt über\]*

$$x_{i}' = min_{x} + \{\lbrack\left( min_{x} - x_{\min} \right) - \left( min_{x} - x_{i} \right)\rbrack \cdot \frac{max_{x} - min_{x}}{\left( min_{x} - x_{\min} \right) - \left( min_{x} - x_{\max} \right)}\}$$

When inverting a value, $x_{i}''$ is calculated as *\[bei einer
Wertinver-tierung errechnet man* $x_{i}''$ *über\]*

$$x''_{i} = \left( min_{x} + max_{x} \right) - x'_{i},$$

where *\[mit\]*

$min_{x}$ ..... Value of the minimum point in the target coordinate
system\
$max_{x}$ .... Value of the maximum point in the target coordinate
system\
$x_{\min}$ ....... *Vector* minimum value\
$x_{\max}$ ...... *Vector* maximum value

$min_{x}$ ..... *[Wert des Minimalpunktes im Ziel-Koordinatensystem]*  
$max_{x}$ .... *[Wert des Maximalpunktes im Ziel-Koordinatensystem\]*  
$x_{\min}$ ....... *[Vektor Minimalwert]*  
$x_{\max}$ ...... *[Vektor Maximalwert]*

-   Output of a single-column, ascending linear *ASCII* data *vector*
    file.
-   *\[Ausgabe einer einspaltigen, aufsteigend geordneten linearen ASCII
    Datenvektordatei.\]*

Usage *\[Handhabung\]*:

~~~
ntf [output][minn][maxn][min][max][inv] 
[output] ...... Output file
[minn] ........ n Minimum value 
[maxn] ........ n Maximum value 
[min] ......... Coordinates Minimum Position Value 
[max] ......... Coordinates Maximum Position Value 
[inv] ......... (1):inverted (0):not inverted
~~~

Example *\[Bsp.\]*:

~~~
ntf data_out.txt 1 30000 1 30000 0
ntf data_out.txt 1 30000 372 50 1
~~~

### 4.15. SEL

---

Selects a data *vector* from a data *matrix* *\[Selegiert einen
Daten-vektor aus einer Datenmatrix\]*,

$$n_{\max} = 33000.$$

-   Import of an *ASCII* data *matrix* file.
-   Output of a single-column *ASCII* data *vector* file.

-   *\[Übernahme einer ASCII Datenmatrixdatei.\]*
-   *\[Ausgabe einer einspaltigen ASCII Datenvektordatei.\]*

Usage *\[Handhabung\]*:

~~~
sel [input][output][a][k] 
[input] ....... Input file 
[output] ...... Output file 
[a] ........... Vector number 
[k] ........... Number of vectors
~~~

Example *\[Bsp.\]*:

~~~
sel in.txt out.asc 3 5
~~~

### 4.16. SRT

---

Sorts a data *vector* *\[Sortiert einen Datenvektor\]*,

$$n_{\max} = 33000,$$

16-digit output *\[16 stellige Ausgabe\]*.

-   Import of a single-column *ASCII* data *vector* file.
-   Output of a sorted single-column *ASCII* data *vector* file.

-   *\[Übernahme einer einspaltigen ASCII Datenvektordatei.\]*
-   *\[Ausgabe einer sortierten einspaltigen ASCII Datenvek-tordatei.\]*

Usage *\[Handhabung\]*:

~~~
srt [input][output] [[d]] 
[input] ...... Input file 
[output] ..... Output file 
[d] .......... optional (1):descending sorting
~~~

Example *\[Bsp.\]*:

~~~
srt in.txt out.txt
srt in.txt out.txt 1
~~~

### 4.17. SRT1

---

Concatenates two sorted data *vectors* using filestream proces-sing
*\[Verkettet 2 sortierte Datenvektoren mit Filestream Verar-beitung\]*,

$n_{\max} \rightarrow \infty$.

-   Import of two ascendingly sorted single-column *ASCII* data *vector*
    files.
-   Output of a sorted single-column *ASCII* file *vector* file.

-   *\[Übernahme von zwei aufsteigend sortierten einspalti-gen ASCII
    Datenvektordateien.\]*
-   *\[Ausgabe einer sortierten einspaltigen ASCII Datenvek-tordatei.\]*

Usage *\[Handhabung\]*:

~~~
srt1 [input1][input2][output] 
[input1] ...... Input file 1 
[input2] ...... Input file 2 
[output] ...... Output file
~~~

Example *\[Bsp.\]*:

~~~
srt1 in1.asc in2.asc out.asc
~~~

### 4.18. SRT2

---

Sorts a data *vector \[Sortiert einen Datenvektor\]*,

$$n_{\max} = 33000.$$

Data sorting is performed via iterative pairwise comparison *\[Die
Datensortierung erfolgt über iterativen Paarvergleich\]*

$$i\text{\ vs.\ }i + 1$$

and pairwise exchange *\[und Paartausch\]*

$$i > i + 1.$$

(slower than ***SRT.EXE***) *\[(langsamer als SRT.EXE)\]*.

-   Import of a single-column *ASCII* data *vector* file.
-   Output of a sorted single-column *ASCII* data *vector* file.

-   *\[Übernahme einer einspaltigen ASCII Datenvektordatei.\]*
-   *\[Ausgabe einer sortierten einspaltigen ASCII Datenvek-tordatei.\]*

Usage *\[Handhabung\]*:

~~~
srt2 [input][output] [[d]] 
[input] ...... Input file 
[output] ..... Output file
[d] .......... optional (1):descending sorting
~~~

Example *\[Bsp.\]*:

~~~
srt2 in.txt out.txt
srt2 in.txt out.txt 1
~~~

### 4.19. SRT3

Sorts a data *vector* *\[Sortiert einen Datenvektor\]*,

$$n_{\max} = 33000,$$

max. 8 digits *\[max. 8-Stellen\]*.

Very fast calculation through implementation of the *C*-function
***Qsort*** *\[Sehr schnelle Berechnung durch Umsetzung der C-eigenen
Qsort Funktion\]*.

-   Import of a single-column *ASCII* data *vector* file.
-   Output of a sorted single-column *ASCII* data *vector* file.

-   *\[Übernahme einer einspaltigen ASCII Datenvektordatei.\]*
-   *\[Ausgabe einer sortierten einspaltigen ASCII Datenvek-tordatei.\]*

Usage *\[Handhabung\]*:

~~~
srt3 [input][output] [[d]] 
[input] ...... Input file 
[output] ..... Output file 
[d] .......... optional (1):descending sorting
~~~

Example *\[Bsp.\]*:

~~~
srt3 in.txt out.txt
srt3 in.txt out.txt 1
~~~

### 4.20. V2V

---

Concatenates two single-column *ASCII* files ($n_{1} = n_{2}\ $required)
*\[Fügt 2 einspaltige ASCII Dateien aneinander (*$n_{1} = n_{2}$ *wird
vor-ausgesetzt)\]*.

-   Import of 2 single-column *ASCII* files.
-   Output of a two-column *ASCII* file.

-   *\[Übernahme von 2 einspaltigen ASCII Dateien.\]*
-   *\[Ausgabe einer zweispaltigen ASCII Datei.\]*

Usage *\[Handhabung\]*:

~~~
V2V [input1][input2][output][tab] 
[input1] ...... Input file 1 
[input2] ...... Input file 2 
[output] ...... Output file 
[tab] ......... Column separator
(0):Tabulator 
(1):Blank 
(*):String
~~~

Example *\[Bsp.\]*:

~~~
V2V in1.txt in2.txt out.txt 1
V2V in1.txt in2.txt out.txt <---->
~~~

###4.21. Z2Z

---

Concatenates two *ASCII* files *\[Fügt zwei ASCII Dateien
aneinan-der\]*.

-   Import of two *ASCII* files.
-   Output of an *ASCII* file.

-   *\[Übernahme zweier ASCII Dateien.\]*
-   *\[Ausgabe einer ASCII Datei.\]*

Usage *\[Handhabung\]*:

~~~
Z2Z [input1][input2][output] 
[input1] ...... Input file 1 
[input2] ...... Input file 2 
[output] ...... Output file 
~~~

Example *\[Bsp.\]*:

~~~
Z2Z in1.txt in2.txt out.txt
~~~

**Table 2**. *ConsoleApp* functions overview with corresponding
functions in *SCHRAUSSER-MAT* (Schrausser,
[2022](https://doi.org/10.17605/OSF.IO/8XE42)).

~~~
Category					chpt.	nr.		Function	
											ConsoleApp		SCHRAUSSER-MAT

EEG/ Focus parameters		2		1		ERC, ERCX	
							2		2		XCOR	
							2		3		FOC¹	
							2		4		DIS¹	
							2		5		FLOC¹	
							2		6		OUT¹	

Integral/ Interpolation		3		1		ROMI	
							3		2		ROME	
							3		3		KUSI	
							3		4		KUSF	
							3		5		NWTI	
							3		6		NWTP	

Matrix/ Data manipulation	4		1		AMA				MXA, MXS
							4		2		IMA				MXI
							4		3		MMA				MXM
							4		4		QMA				MXQ
							4		5		SMA	
							4		6		SPUR			MSP
							4		7		TRP				MXT
							4		8		VMA				MXV
							4		9		ZMA	
							4		10		ENT	
							4		11		KTF	
							4		12		KTF2	
							4		13		KTF3	
							4		14		NTF	
							4		15		SEL	
							4		16		SRT	
							4		17		SRT1	
							4		18		SRT2	
							4		19		SRT3	
							4		20		V2V	
							4		21		Z2Z	     
~~~
                                                                                                        
¹) implemented in *ATINA* (Schrausser, [2006](https://doi.org/10.5281/zenodo.19422127)).

<br>

## 5. ConsoleApp_String

Console applications for *string-* and *number-transformation*, see
Schrausser ([2023d](https://doi.org/10.5281/zenodo.7653790)).

### 5.1. 2DEC

---

Converts the argument to a decimal *number* *\[Argument in
Dezi-malzahl\]*.

Usage *\[Handhabung\]*:

~~~
2DEC [x] 
[x] .......... Argument
~~~

### 5.2. DEC2

---

Decimal *number* conversion *\[Dezimalzahl Umwandlung\]*.

Usage *\[Handhabung\]*:

~~~
DEC2 [d]
[d] .......... Decimal number
~~~

### 5.3. BIN2DEC

---

Binary *number* converted to decimal *number* *\[Binärzahl in
Dezimalzahl\]*.

Usage *\[Handhabung\]*:

~~~
BIN2DEC [b]
[b] .......... Binary number
~~~

### 5.4. DEC2BIN

---

Binary *number* converted to decimal *number* *\[Dezimalzahl in
Binärzahl\]*.

Usage *\[Handhabung\]*:

~~~
DEC2BIN [d]
[d] .......... Decimal number
~~~

### 5.5. ABCD

---

Modifies or deletes *strings* in an *ASCII* file *\[Ändert oder löscht
Strings einer ASCII Datei\].*

-   Import of an *ASCII* file.
-   Output of a modified *ASCII* file.

-   *\[Übernahme einer ASCII Datei.\]*
-   *\[Ausgabe einer modifizierten ASCII Datei.\]*

Usage *\[Handhabung\]*:

~~~
ABCD [input][output][ab][cd][sw]
[input] ...... Input file
[output] ..... Output file 
[ab] ......... String to be modified
[cd] ......... String to be inserted
[sw] ......... (0):modifies 
               (1):deletes (2):inserts a space
~~~

Example *\[Bsp.\]*:

~~~
ABCD input.txt output.txt .txt .asc 0
ABCD input.txt output.txt REM 0 1
~~~

### 5.6. AZUBE

---

Changing individual characters in an *ASCII* file *\[Änderung einzelner
Zeichen einer ASCII Datei\].*

Usage *\[Handhabung\]*:

~~~
AZUBE [input][output][a][b] 
[input] ...... Input file
[output] ..... Output file
[a] .......... Character
[b] .......... Modify 
~~~

Example *\[Bsp.\]*:

~~~
AZUBE input.txt output.txt , .
~~~

### 5.7. TEZUTE

---

Changing individual *strings* in a file *\[Änderung einzelner Strings
einer Datei\].*

Usage *\[Handhabung\]*:

~~~
TEZUTE [input][output][a][b] 
[input] ...... Input file
[output] ..... Output file 
[a] .......... String
[b] .......... Modify 
~~~

Example *\[Bsp.\]*:

~~~
78 00
67 8
null 00
9 null
~~~

~~~
TEZUTE input.txt output.txt null 00
~~~

~~~
78
00
67
8
00
00
9
00
~~~

Edit source code for formatted output *\[Zur formatierten Ausga-be
Quellcode bearbeiten\]*.

### 5.8. AB_L

---

Inserts a *string* (i) before and/or a *string* (ii) after each line of
a file *\[Fügt einen String (i) vor und/oder einen String (ii) nach
jeder Zeile einer Datei ein\]*.

-   Import of a single-column *ASCII* file.
-   Output of a (one-,) two- or three-column *ASCII* file.

-   *\[Übernahme einer einspaltigen ASCII Datei.\]*
-   *\[Ausgabe einer (ein-,) zwei- oder dreispaltigen ASCII Datei.\]*

Usage *\[Handhabung\]*:

~~~
AB_L [input][output][a][sw][z][sw]
[input] ...... Input file 
[output] ..... Output file
[a] .......... String inserted before each line of input file
[sw] ......... (0):no insert before each line 
[z] .......... String inserted after each line of input file
[sw] ......... (0):no insert after each line
~~~

Example *\[Bsp.\]*:

~~~
**AB_L** in.txt out.txt move 1 verzeichnis 1\
**AB_L** in.txt out.txt del 1 0 0
~~~

### 5.9. BIIA

---

Encodes a file into an *[ASCII]{.underline}* file (recoding via
***AIIB.EXE***) *\[Encodiert eine Datei in eine [ASCII]{.underline}
Datei (Recodierung via AIIB.EXE)\]*.

-   Import of a file.
-   Output of an encoded *ASCII* file (***\*.bii***).

-   *\[Übernahme einer Datei.\]*
-   *\[Ausgabe einer* *encodierten ASCII Datei (\*.bii).\]*

Usage *\[Handhabung\]*:

~~~
BIIA [input][output][mode][form]
[input] ...... Input file
[output] ..... Output file in ASCII format (*.bii)
[mode] ....... (1):cd01 SCHRAUSSER CODE, uppercase letter combination (2 characters, e.g. AA, FD, ..., good readability – unambiguous, for archiving)
               (2):cd02 SCHRAUSSER CODE, keyboard character comb. (1 or 2 characters, e.g. a, 1A, ..., small file) 
               (3):cd03 SCHRAUSSER CODE, number combination (3 characters, e.g. 001, 123, ..., optimal readability)
               (4):cd04 SCHRAUSSER CODE, ASCII-combination (1 or 2 characters, e.g. -, #+, ..., minimum file size) 
               (5):HEX Hexadecimal value - No AIIB recoding
               (6):DEZ Decimal value
               (7):OKT Octal value – No AIIB recoding
               (8):ASCII characters directly - No AIIB recoding
[form] ....... (1):1-column ASCII output 
               (2):1-line ASCII output in block format without breaks

~~~

Example *\[Bsp.\]*:

~~~
BIIA bild.jpg bild.bii 4 2
~~~

### 5.10. AIIB

---

Recodes a *SCHRAUSSER CODE* or decimal encoded file (encoding via
***BIIA.EXE***) *\[Recodiert eine SCHRAUSSER CODE oder dezimal
encodierte Datei (Encodierung via BIIA.EXE)\]*.

-   Importing a *SCHRAUSSER CODE* file (***\*.bii***).
-   Output of the recoded original file.

-   *\[Übernahme einer SCHRAUSSER CODE Datei (\*.bii).\]*
-   *\[Ausgabe der recodierten Ursprungsdatei.\]*

Usage *\[Handhabung\]*:

~~~
AIIB [input]
[input] ...... SCHRAUSSER CODE file
~~~

Example *\[Bsp.\]*:

~~~
AIIB bild.bii
~~~

### 5.11. STGERSETZ

---

Modification of one or more *substrings* (single characters or
*strings*) in a contiguous *string* (without spaces), read as a line of
an *ASCII* file *\[Änderung ein oder mehrerer Substrings (Einzelzei-chen
oder Zeichenketten) in einem zusammenhängenden String (ohne
Leerzeichen), eingelesen als Zeile einer ASCII Datei\]*.

-   Importing a line from an *ASCII* file.
-   *\[Übernahme einer Zeile aus einem ASCII-File.\]*

Example *\[Bsp.\]*:

~~~
12345678
abcdefghijk
ABCDEFG
1234567890
~~~

-   Line-by-line processing of the *strings* and output to an *ASCII*
    file.
-   *\[zeilenweise Bearbeitung der Strings und Ausgabe in ein
    ASCII-File.\]*

The processing steps are logged in ***stgersetz_log.txt*** *\[Die
Bear-beitungsschritte werden in stgersetz_log.txt protokolliert\]*.

Usage *\[Handhabung\]*:

~~~
STGERSETZ [input][output][typ][alt][neu]
[input] ...... Input file (strings line by line)
[output] ..... Output file (strings line by line)
[typ] ........ (0):deletes
               (1):modifies
               (2):insert a space
[alt] ........ String to be modified
[neu] ........ Change to string
~~~

The type of argument \[neu\] has no effect on \[typ\] (0) *delete* and
(2) *insert a space*, but must be specified as character (e.g. '-'). A
space in the input file splits the *string* and results in a new line in
the output file. Some special characters are ignored *\[Die Art des
Arguments \[neu\] hat für \[typ\] (0) löschen und (2) ein Leerzeichen
einfügen keine Auswirkung, muss aber als beliebiges Zeichen angegeben
werden (iuF. '-'). Ein Leerzeichen in der Eingabedatei trennt die
Zeichenkette und führt zu einer neuen Zeile in der Ausgabedatei. Manche
Sonderzeichen bleiben unberücksichtigt\].*

Example *\[Bsp.\]*:

~~~
STGERSETZ input.txt output.txt 0 8 - //deletes 8
~~~

~~~
1234567
abcdefghijk
ABCDEFG
123456790
~~~

~~~
STGERSETZ input.txt output.txt 1 def DEF //changes def to DEF
~~~

~~~
12345678
abcDEFghijk
ABCDEFG
1234567890
~~~

~~~
STGERSETZ input.txt output.txt 2 234 - //inserts a space for 234
~~~
~~~
1 5678
abcdefghijk
ABCDEFG
1 567890
~~~

<br>

### 6. ConsoleApp_Tools

---

Console *tool* applications, see Schrausser
([2023e](https://doi.org/10.5281/zenodo.7655239)).

### 6.1. AUTO

---

Creates a *C*-source file and directory structure.

-   Declaration of parmeters (*name*, *filestreams*, *loops*).
-   Creation of framework-file ***NAME.c*** as specified.
-   Creation of *ASCII* framework-file ***NOTE_NAME.txt***.

Directory structure:

~~~
\_NAME\_\\NAME.c\
\_NAME\_\\debug\\NOTE_NAME.txt\
 DOSCOM.exe
~~~

Usage:

~~~
AUTO [name][input][output][nl][L]
[name] ....... C projekt mame 
[input] ...... ASCII input filename
[output] ..... ASCII output filename
[nl] ......... Number of loop-shells to implement
[L] .......... Language (0):English (1):German
~~~

Example:

~~~
AUTO TEST 0 0 0 0
AUTO PRO1 input.txt output.txt 3 1
AUTO PRO2 0 output.txt 1 0
~~~

### 6.2. DLS

---

Writes a file to the console *\[Schreibt eine Datei zur Konsole\]*.

Usage *\[Handhabung\]*:

~~~
DLS [input] [ [i][m1][m2] ]
[input] ...... Input file 
optional:
[i] .......... (1):displays file name, n, k, m1, m2, i, j 
               (0):displays no additional information
[m1] ......... Start line of text output 
[m2] ......... End line of text output
~~~

Example *\[Bsp.\]*:

~~~
DLS NOTIZ_DLS.txt
DLS NOTIZ_DLS.txt 1
DLS NOTIZ_DLS.txt 1 1
DLS NOTIZ_DLS.txt 0 3 10
DLS NOTIZ_DLS.txt 1 10 10
~~~

### 6.3. FIL

---

Writes a list of all specified files in the current directory to an
*ASCII* file *\[Schreibt eine Liste aller spezifizierten Dateien des
aktu-ellen Verzeichnisses in eine ASCII Datei\]*.

Usage *\[Handhabung\]*:

~~~
FIL [output][*] 
[output] ..... Output file 
[*] .......... File specification
~~~

Example *\[Bsp.\]*:

~~~
FIL dir.txt *.*
~~~

**6.4. KOPIE** Copies a file *\[Kopiert eine Datei\]*.

-   Import of a file.
-   Output of a copy of a file (if applicable modified).

-   *\[Übernahme einer Datei.\]*
-   *\[Ausgabe einer (ggf. modifizierten) Dateikopie.\]*

Usage *\[Handhabung\]*:

~~~
KOPIE [input][output] ([switch]) 
[input] ...... Input file 
[output] ..... Output file 
~~~

Example *\[Bsp.\]*:

~~~
KOPIE DTREN.BAT DTRENA.BAT
~~~

### 6.5. SRC

---

Writes the command-line argument to an *ASCII* file *\[Schreibt das
Kommandozeilenargument in eine ASCII Datei\]*.

Usage *\[Handhabung\]*:

~~~
SRC [output][typ][arg][sw]
[output] ..... Output file
[typ] ........ (0):attach (1):create 
[arg] ........ Argument
[sw] ......... (0):line break (1):space (2):no character
~~~

Example *\[Bsp.\]*:

~~~
SRC out.bat 1 lsn 1
SRC out.bat 0 nul.txt 0
~~~

### 6.6. T

---

Inserts the command-line arguments into the *ASCII* file ***T.txt***.
The arguments are separated by a space *\[Fügt die
Kommandozeilen-argumente in die ASCII Datei T.txt ein. Die Argumente
werden in der Datei durch ein Leerzeichen getrennt\]*.

Usage *\[Handhabung\]*:

~~~
T [argi]…[argn]
[argi] ....... String
~~~

Example *\[Bsp.\]*:

~~~
T This is a very simple program
T for fast text input into a file
T Das ist ein sehr einfaches Programm
T zur schnellen Texteingabe in eine Datei.
~~~

### 6.7. DOSCOM

---

Starts a *DOS* *shell* in the current directory. Copies itself to the
di-rectory ***\[\_DOSCOM\]***, which is linked to the desktop. Renames
to *nil* after use in the current directory *\[Startet eine DOS-Shell im
aktuellen Verzeichnis. Kopiert sich selbst in das mit dem Desktop
verknüfte Verzeichis \[\_DOSCOM\]. Umbenennung in nil nach Ge-brauch im
aktuellen Verzeichis\]*.

Usage *\[Handhabung\]*:

*Drag* the desktop shortcut ***\[\_DOSCOM\]*** to any directory, run it
there, and delete it after use *\[Aus der Desktopverknüpfung
\[\_DOSCOM\] in ein beliebiges Verzeichnis ziehen, dort ausführen und
nach Gebrauch löschen\]*.

### 6.8. FINDE

---

Search and *find* files *\[Dateien suchen und finden\]*.

Usage *\[Handhabung\]*:

~~~
FINDE [file]
[file] ....... File to be found
~~~

### 6.9. LSN

---

Deletes a file *\[Löscht eine Datei\]*.

-   Input the name of a file to be deleted.
-   *\[Übernahme des Namens einer zu löschenden Datei.\]*

Usage *\[Handhabung\]*:

~~~
LSN [file] 
[file] ....... Filename 
~~~

Example *\[Bsp.\]*:

~~~
LSN oo
~~~

### 6.10. CMND, CMNDw

---

Executes *console* commands with arguments *\[Führt Consolenbe-fehle mit
Argumenten aus\]*.

Usage *\[Handhabung\]*:

~~~
CMND [cmd]
[cmd] ........ Command

CMNDw [cmd][argc]
[cmd] ........ Command
[argc] ....... n of Arguments
~~~

**Table 3**. *ConsoleApp* tools overview.

~~~
Category		chpt.	nr.		Function

String/ Number	5		1		2DEC
				5		2		DEC2
				5		3		BIN2DEC
				5		4		DEC2BIN
				5		5		ABCD
				5		6		AZUBE
				5		7		TEZUTE
				5		8		AB_L
				5		9		BIIA
				5		10		AIIB
				5		11		STGERSETZ

Tools			6		1		AUTO
				6		2		DLS
				6		3		FIL
				6		4		KOPIE
				6		5		SRC
				6		6		T
				6		7		DOSCOM
				6		8		FINDE
				6		9		LSN
				6		10		CMND, CMNDw           
~~~
                                                            
<br>

## References
