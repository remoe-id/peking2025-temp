---
layout: ../layouts/MarkdownLayout.astro
title: Description
---
# Project Description

#### The Infectious Ringleader of Chronic Gastropathies

*Helicobacter pylori* (*H. pylori*, Hp) infection has been reported worldwide (Fig. 1) and is believed to affect more than half of the world’s population<sup>1</sup>. What makes it a trouble are the related gastropathies including chronic gastritis, peptic ulcer disease (PUD) and gastric cancer, resulting in discomfort, pains and even death. Worse yet, once individuals acquire *H. pylori* infection, the pathogen usually persists throughout their lifetime<sup>2</sup>, which gives their quality of life an overtime cut.

![Fig. 1](https://static.igem.wiki/teams/5870/description/fig1.webp)
<p class="figure-caption">
  Fig. 1 Global prevalence of <i>H. pylori</i> choropleth map. Certain regions are magnified to better display the smaller countries. (Hooi et al., 2017)
</p>

*H. pylori* exhibits clear infectivity and is primarily transmitted through the vomitus–oral and gastro–oral pathways, and faecal–oral transmission is also considered possible<sup>3,4</sup>. Direct person-to-person contact within families appears to be the predominant route of transmission, with infection clustering in households and stronger associations observed between infected children and close caregivers such as mothers and siblings<sup>5,6</sup>. Additional indirect sources of infection include contaminated food or animal products, especially milk, and occupational exposure in agricultural, fishery, or healthcare settings<sup>7</sup>.

*H. pylori* is Gram-negative, microaerophilic bacteria that are highly motile due to a unipolar bundle of sheathed flagella<sup>3</sup>. It is highly adapted to the colonization in the deep gastric mucus layer<sup>8</sup>, the features of which are represented by motility, urease production, adhesion, etc. Such a living habitat is inaccessible to most of the existing medicines due to the acidity of gastric juice and the thick barrier namely mucus layer<sup>9</sup> (Fig. 2).

![Fig. 2](https://static.igem.wiki/teams/5870/description/fig2-width.webp)
<p class="figure-caption">
  Fig. 2 Distribution of <i>H. pylori</i> in the mucus layer of Mongolian gerbils. (A) The tissue surface of the <i>H. pylori</i>-infected gerbil depicted from the luminal side of the antrum. <i>H. pylori</i> is highlighted in red. (B) Schematic cross section showing the distribution of <i>H. pylori</i> through the gastric mucosa of infected gerbil. (Schreiber et al., 2004.)  
</p>

#### Common Therapies

The first-line and most widely used treatments are the triple and quadruple therapies that are mainly based on metabolic disturbing and antibiotic intervention, giving an eradication efficacy of around 90%<sup>8</sup>. In other therapies, though cocktailed with probiotic components, antibiotics are still unavoidable. However, not only the increasing resistance to antibiotics leads to declines in the eradication rate, but the individuals also suffer from the destructive effect of the antibiotics on the intestine flora<sup>10</sup>. One of the reasons for drug resistance is the formation of biofilm<sup>11</sup>, possibly by enhancing structural protection and increasing genetic exchange across microorganisms, especially the resistance genes. Consequently, a substitute for the traditional antibiotic therapies is badly needed.

#### New Approaches

Probiotic microorganisms have been used as auxiliaries to reduce adverse effects<sup>12</sup>, beyond which researches are underway to select specific strains for pure-biological treatment. Several studies have confirmed the efficacy of probiotics as monotherapy for *H. pylori* eradication<sup>13,14,15,16</sup>. Nevertheless, probiotic-only therapies usually give an eradication rate less than 30%<sup>17</sup>, possibly due to the low specificity and, critically, the difficulty for the whole cells to arrive at the nidi through the gastric mucus layer.

#### Our Solutions

##### 1. Probiotic-based engineering

We expect to equip a probiotic microorganism, *Saccharomyces boulardii* (*S. boulardii*) CNCM Ⅰ-745 with targeting and expelling ability specific for *H. pylori*. *S. boulardii* has been in widely use in the treatment for *H. pylori*, either as an auxiliary to reduce adverse effects or as part of monotherapies to cure the infection individually<sup>15</sup>. As to improve its specificity to *H. pylori*, we expect to introduce a chimeric G protein-coupled receptor (GPCR) to sense the biomarker of *H. pylori* and trigger the expression of downstream genes. Thus, we gain an engineered cell with anti-Hp activity, short-term (specific) and long-term (probiotic & unspecific) both.

##### 2. Genetic circuits

We choose N<sup>α</sup>-methylhistamine (NAMH) as the biomarker for Hp infection. A chimeric GPCR is designed for sensing by the combination of human histamine receptor 3 (hH<sub>3</sub>R) and Ste2 from yeast mating pathway. The chimeric GPCR is hoped to trigger the secretion of AiiA, and to enhance the adhesion to *H. pylori* by the expression of C1ND (Fig. 3).

![Fig. 3](https://static.igem.wiki/teams/5870/description/fig3.webp)
<p class="figure-caption">
  Fig. 3 Engineering logic from sensing to reacting. 
</p>

- Therapy Branch: AiiA is a kind of acyl-homoserine lactonase from Pseudomonas aeruginosa, which is believed to effectively inhibit biofilm formation and likely to block the virulence proteins on *H. pylori*<sup>18</sup>. In our yeast, AiiA is designed to be secreted after sensing the biomarker of H. pylori as the main destructor against Hp biofilm.
- Adhesion Branch: C1ND is derived from a human gastric protein CEACEM1, which targets the surface antigen HopQ of *H. pylori*<sup>19</sup>. In our project, C1ND is displayed on the surface of our yeast to adhere to *H. pylori*. By constructing C1ND as the adhesion part in our yeast, we aim to achieve specific colonization at the infection nidi of *H. pylori*, facilitating our therapy branch in terms of efficiency.

##### 3. Motor Delivery

Our engineered yeast will be cladded in pH-responsive gels as microgels, which are stable in the acidic gastric juice (pH < 4) and disintegrate to release the yeast after reaching the gastric mucosa, where the pH is 6~7. A Mg-based micromotor will be loaded on the microgels to provide driving force through the mucus layer. It was demonstrated that the micromotor-driven microgels can adhere efficiently to the ulcer-region in the stomach and release drugs, exhibiting desirable curing effect<sup>20</sup>. In our project, the micromotor-based delivery will be examined with cell-level loading as a possible solution to delivery difficulties.

#### Conclusion

In conclusion, the Peking 2025 project aims to avoid the disadvantages of traditional therapies and draw the advantage of probiotic therapies, thus providing a comfortable and short-term therapeutic alternative for Hp-infected patients. We hope our research and work will contribute to the battle against the global infection of *Helicobacter pylori*.

![Fig. 4](https://static.igem.wiki/teams/5870/description/fig4-2.webp)
<p class="figure-caption">
  Fig. 4 The overall system diagram of the project.
</p>

##### Reference
---
<ol style="font-size: 0.85em;">
    <li>1. Hooi, J. K. Y. et al. Global prevalence of Helicobacter pylori infection: systematic review and meta-analysis. Gastroenterology 153, 420–429 (2017).</li>
    <li>2. Suerbaum, S. & Michetti, P. Helicobacter pylori infection. N. Engl. J. Med. 347, 1175–1186 (2002).</li>
    <li>3. Kheyre H, Morais S, Ferro A, Costa AR, Norton P, Lunet N, Peleteiro B. The occupational risk of Helicobacter pylori infection: a systematic review. Int Arch Occup Environ Health. 2018 Aug;91(6):657-674.</li>
    <li>4. De Schryver A, Van Winckel M, Cornelis K, Moens G, Devlies G, De Backer G. Helicobacter pylori infection: further evidence for the role of feco-oral transmission. Helicobacter. 2006 Dec;11(6):523-8.</li>
    <li>5. Eusebi LH, Zagari RM, Bazzoli F. Epidemiology of Helicobacter pylori infection. Helicobacter. 2014 Sep;19 Suppl 1:1-5.</li>
    <li>6. Mentis A, Lehours P, Mégraud F. Epidemiology and Diagnosis of Helicobacter pylori infection. Helicobacter. 2015 Sep;20 Suppl 1:1-7.</li>
    <li>7. Krueger WS, Hilborn ED, Converse RR, Wade TJ. Environmental risk factors associated with Helicobacter pylori seroprevalence in the United States: a cross-sectional analysis of NHANES data. Epidemiol Infect. 2015 Sep;143(12):2520-31.</li>
    <li>8. Nyssen, O. P. et al. European Registry on Helicobacter pylori management (Hp-EuReg): patterns and trends in first-line empirical eradication prescription and outcomes of 5 years and 21 533 patients. Gut 70, 40–54 (2021).</li>
    <li>9. S. Schreiber, M. Konradt, C. Groll, P. Scheid, G. Hanauer, H. Werling, C. Josenhans & S. Suerbaum, The spatial orientation of Helicobacter pylori in the gastric mucus, Proc. Natl. Acad. Sci. U.S.A. 101 (14), 5024-5029, 2004.</li>
    <li>10. Malfertheiner, P., Camargo, M.C., El-Omar, E. et al. Helicobacter pylori infection. Nat Rev Dis Primers 9, 19 (2023). </li>
    <li>11. Elshenawi, Y., Hu, S., & Hathroubi, S. (2023). Biofilm of Helicobacter pylori: Life Cycle, Features, and Treatment Options. Antibiotics, 12(8), 1260.</li>
    <li>12. Malfertheiner, P. et al. Management of Helicobacter pylori infection — the Maastricht V/Florence consensus report. Gut 66, 6–30 (2017).</li>
    <li>13. Goderska K, Agudo Pena S, Alarcon T. Helicobacter pylori treatment: antibiotics or probiotics. Appl Microbiol Biotechnol. 2018;102:1–7.</li>
    <li>14. Canducci F, Cremonini F, Armuzzi A, Di Caro S, Gabrielli M, Santarelli L, Nista E, Lupascu A, De Martini D, Gasbarrini A. Probiotics and Helicobacter pylori eradication. Dig Liver Dis. 2002;34 Suppl 2:S81–S83.</li>
    <li>15. Uspenskiy Y, Baryshnikova N. Lactobacillus reuteri against Helicobacter pylori: efficacy in vitro и in vivo. Vrach. 2019;12:37–42.</li>
    <li>16. Vandenplas Y, Veereman-Wauters G, De Greef E, Peeters S, Casteels A, Mahler T, Devreker T, Hauser B. Probiotics and prebiotics in prevention and treatment of diseases in infants and children. J Pediatr (Rio J) 2011;87:292–300.</li>
    <li>17. Baryshnikova NV, Ilina AS, Ermolenko EI, Uspenskiy YP, Suvorov AN. Probiotics and autoprobiotics for treatment of Helicobacter pylori infection. World J Clin Cases. 2023;11(20):4740-4751.</li>
    <li>18. Gopalakrishnan, V., Saravanan, V., Mahendran, M. I. M. S., & Kumar, M. P. N. (2024). Helicobacter pylori biofilm interference by N-acyl homoserine lactonases: in vitro and in silico approaches. Molecular Biology Reports, 51(1).</li>
    <li>19. Javaheri, A., Kruse, T., Moonens, K. et al. Helicobacter pylori adhesin HopQ engages in a virulence-enhancing interaction with human CEACAMs. Nat Microbiol 2, 16189 (2017).</li>
    <li>20. L. Cai, C. Zhao, H. Chen, L. Fan, Y. Zhao, X. Qian, R. Chai, Suction-Cup-Inspired Adhesive Micromotors for Drug Delivery. Adv. Sci. 2022, 9, 2103384.</li>
</ol>

<style>
    .figure-caption {
  font-size: 0.875rem;
  max-width: 800px;
  margin: 0.5rem auto 1rem auto;
  line-height: 1.5;
  color: #6c757d;
  text-align: center;
  font-style: normal;
}
</style>