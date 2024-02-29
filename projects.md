---
layout: page
title: Projects & Research
permalink: /work/
---

Several major academic and professional projects throughout my career are broadly summarized as,

- <a class="smoothscroll" data-link="theoretic" href="#theoretic">Learning/Game Theoretic</a> work focuses on **core mathematical** aspects in learning systems, often involving advanced **optimization, probability theory, and graph theory**.
- <a class="smoothscroll" data-link="analytics" href="#analytics">Predictive Analytics</a> entails applicative data-driven strategic decision making for front-office operations, involving **statistical modeling** in **Python using Big Data tools**.
- <a class="smoothscroll" data-link="dev" href="#dev">Software Dev for Algo Trading</a> specializes in **C/C++ based system design** for crucial **low-latency** performance.
- <a class="smoothscroll" data-link="vision" href="#vision">Vision/Recognition</a> projects primarily focus on **novel models or applications** driven by **images as the sole mode** of data.
- <a class="smoothscroll" data-link="nlp" href="#nlp">Language Modeling/Understanding</a> involves projects pertaining to **lingustic/sequential** data dealing with **abstract** notions of **sentiment** and **semantic** understanding.
- <a class="smoothscroll" data-link="social" href="#social">Social Impact</a> projects revolve around product development intended to solve specific social issues.
- <a class="smoothscroll" data-link="signals" href="#signals">Signal Processing</a> projects specialize in **mathematical modeling** for low-level hardware and **signal development**.

<br><br/>
<div align="right">
<a href='#expall' id='expAll'>Expand All</a> &nbsp; <a href='#expnone' id='collAll'>Collapse All<br></a>
</div>

<div id="theoretic">
    <button type="button" class="collapsible">Learning/Game Theoretic</button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Exploring approximation regrets in Online Learning from adversarial feed<sup>[\[ppt\]](https://drive.google.com/file/d/1FnzyRf-5VqmS0vbFMwf2xlPwhHmleMz4/view?usp=sharing)[\[paper\]](https://drive.google.com/file/d/1qe3ZfIv0KNTm0BMKK53Aosp-EUeZFghc/view)<sup/>
*Course Project under [Dr. Gil Kur](https://scholar.google.com/citations?user=yDkAhccAAAAJ&hl=en), [Prof. Dr. Fanny Yang](https://sml.inf.ethz.ch/group/fannyy/) at [SML Group](https://sml.inf.ethz.ch/), 2023* <br><br/>
<img src="/assets/thumbnail_OL.png" class="expimg" align="left" alt="Adversarial Online Learning" width="200px" height=auto/> Learning complex functions is fairly mainstream when data points are available offline. _What learning mechanism (with guarantees) work when the data is only available in an online sequentially adversarial fashion?_ We dig deeper into [Smoothed Online Learning Guarantees for non-parametric functions](https://arxiv.org/abs/2202.04690) and establish adaptive $\sigma_t$-smooth regret bounds in adversarial online learning, extending results from this study. Additionally, we identify limitations of Improper Learning algorithm proposed by the authors, and highlight improvements. 

### Exploring Mechanism-Aware Cooperation Intent<sup>[\[pre-poster\]](https://drive.google.com/file/d/1RoveJYYztqy_8Yt82_7kO6jNiw5jap_g/view?usp=sharing)[\[paper\]](https://drive.google.com/file/d/1HZA_IkKm7508LSu-rAzns41mu_8FfeUK/view)<sup/>
*Course Project supervised by [Vinzenz Thoma](https://scholar.google.com/citations?user=2ZT371MAAAAJ&hl=en), [Dr. Zebang Shen](https://scholar.google.com/citations?user=klqzFvgAAAAJ&hl=en), [Prof. Dr. Niao He](https://scholar.google.com/citations?user=iNcA81MAAAAJ&hl=en) at [Optimization & Decision Intelligence Group](https://odi.inf.ethz.ch/), 2023* <br><br/>
<img src="/assets/MG.jpg" class="expimg" align="right" alt="Prisoner's Dilemma Game" width="200px" height=auto/> In a repeated Matrix Game between two optimal agents, mutual defection strategy is often an undesirable, yet the only outcome. We propose an improved learning mechanism that enforces moral conduct in these perceptive agents by promoting mutual co-operation and joint reward maximization. <br><br/>

### Optimal Transport for Social Influence Maximization<sup>[\[report\]](https://drive.google.com/file/d/1gd6yv50lifP72L3zIxAK5I0cQC7OJb39/view)<sup/>
*Research Project supervised by [Nicolas Lanzetti](https://scholar.google.ch/citations?user=gWJV1rQAAAAJ&hl=en), [Prof. Dr. Giulia De Pasquale](https://scholar.google.com/citations?user=61JYIhYAAAAJ&hl=it), [Prof. Dr. Florian Dörfler](https://scholar.google.com/citations?user=P2kxZ3MAAAAJ&hl=en), [Prof. Dr. Andreas Krause](https://scholar.google.com/citations?user=eDHv58AAAAAJ&hl=en) at [Automatic Control Laboratory](https://control.ee.ethz.ch/), 2023*  <br><br/>
<img src="/assets/sim.png" class="expimg" align="left" alt="OT SIM Pipeline" width="200px" height=auto/> Information propagation in complex social networks often leads to its disproportionate access across different groups within the network. To ensure fairness in information access across groups while maximizing its outreach, we propose an iterative metric characterized by Optimal Transport cost between information distribution across groups.

### Priors from Deep Networks for Bayesian Deep Learning<sup>[\[paper\]](https://drive.google.com/file/d/1_6mhUEmLygu4_a83CFNAgNNbZz0bKJpj/view)<sup/>
*Course Project supervised by [Lorenzo Noci](https://scholar.google.com/citations?user=VZ__1r0AAAAJ&hl=en), [Prof. Dr. Thomas Hofmann](https://scholar.google.co.uk/citations?user=T3hAyLkAAAAJ&hl=en) at [Data Analytics Lab](https://da.inf.ethz.ch/), 2022*  <br><br/>
<img src="/assets/TILDA.png" class="expimg" align="right" alt="TILDA Model" width="200px" height=auto/> While deep neural networks are fundamental architectures for learning tasks, their lack of uncertainty estimation motivated us to design TILDA: a mechanism to encode information from deep networks as dirichlet priors for improved uncertainty quantification and performance in Bayesian Neural Networks. <br><br/>



</div>
</div>


<div id="analytics">
    <button type="button" class="collapsible">Predictive Analytics<sup>[proprietary]</sup></button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Market Data Inferences
*Analyst at [Tower Research Capital](https://www.tower-research.com/), 2021-2022*
<!-- <br><br/> -->
- Continued from [low-latency role](/work/#dev), 2018-2020
- Periodic trade statistic and market sentiment characterization of instruments using NEWS feed, facilitating insightful long-term strategies
- Top of book estimate & trade prediction with early book adjustment for specific instruments based on recent trade-history and book-activity of correlated symbols, enabling strategic order placement for US equities during rush trade hours
- Inhouse trade book level construction, gauging correlation between book levels, during communication failure with exchanges
- Lossy book (modeled as a matrix) compression and reconstruction for low-cost and fast transport between colocation and strategy boxes worldwide
- Regrouping instruments on volatility based on initial incoming trades from basis instruments
- Live strategy monitoring and performance evaluation on deviation from historical sim metrics
- Managing a team of 3 in MD analysis


### Digital Aquisition via Fractional Attribution
*Data Analysis at [AmEx](https://www.americanexpress.com/en-us/careers/career-areas/risk-and-data-analytics/) Market Research, 2017* <br><br/>
Probability of conversion of a potential customer in influence from social media, customer targetting, and referral from acquaintances, is jointly modeled under a time-decaying impact of such influence, to optimally allocate constrained funds for a *+8% in regional customer acquisition.*

</div>
</div>



<div id="dev">
<button type="button" class="collapsible">Software Dev in Algo Trading<sup>[proprietary]</sup></button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Low Latency Infrastructure
*Owner Mid Freq./Co-owner High Freq. for Market Data at [Tower Research Capital](https://www.tower-research.com/), 2018-2022*
<!-- <br><br/> -->
- Live market data split service for separate trading instruments, facilitating containerized strategy run in Crypto and US equity exchanges
- Trade book recovery service enabling strategy runs at adhoc trading hours
- Live data inconsistency monitoring and alert service on ELK Stack
- Automated code and API documentation hosting service using Sphynx and Doxygen, enabling seamless usage of trading library
- Automated development-to-deployment pipeline to keep up with mandatory exchange protocol updates
- Continued in [Python role](/work/#analytics), 2021-2022

</div>
</div>



<div id="vision">
<button type="button" class="collapsible">Vision/Recognition</button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Aerial Road Segmentation<sup>[\[paper\]](https://drive.google.com/file/d/1a83sBnwbgoQDz1DxAJxISNfGlZVq9g5e/view?usp=sharing)<sup/>
*Course Kaggle Contest at [Data Analytics Lab](https://da.inf.ethz.ch/), 2023* <br><br/>
<img src="/assets/passivBlock.png" class="expimg" align="left" alt="PaSSIV Model Block" width="200px" height=auto/> <img src="/assets/passivModel.png" class="expimg" align="right" alt="PaSSIV Model" width="200px" height=auto/> Given, identification of roads from aerial satelite-view images is far from completely solved, we achieved the 3<sup>rd</sup> highest Kaggle score for it in ETH history. Additionally, I formulated a novel neural operator (Section D.4) that enables Transformers to better identify complex graph-like road geometry even in data scarcity.<br><br/>

### Handwriting recognition in unconstrained and haphazard writeups
*Industry Project under [Prof. Dr. Indra Gupta](https://ee.iitr.ac.in/~EE/indrafee), 2017* <br><br/>
Implemented a robust handwriting recognition android app, using data augmentation from transformed characters, to automate remittance processing at local banks.

</div>
</div>



<div id="nlp">
<button type="button" class="collapsible">Language Modeling/Understanding</button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### If you know what it means..., Sent-ribute: Understanding sentiment subtleties<sup>[\[paper\]](https://drive.google.com/file/d/1iQdQxG8M0ztbKFwQGOxqeE0vxmiznMYJ/view)<sup/>
*Course Project supervised by [Prof. Dr. Christopher Potts](https://web.stanford.edu/~cgpotts/) at [Stanford](https://online.stanford.edu/programs/artificial-intelligence-professional-program), 2021* <br><br/>
<img src="/assets/sentribute.png" class="expimg" align="left" alt="Sentribute Model" width="200px" height=auto/> Amidst several generic discrete sentiment classifiers that often could not differentiate between neutral and conflicting sentiments, Sentribute represents a gaussian mixture of basic polar sentiments resulting in a much more interpretable representation of complex sentiments. <br><br/><br><br/>

### Describe unnamed colors in a language game<sup>[\[code\]](https://github.com/codeViser/color-describe)<sup/>
*Course Project supervised by [Prof. Dr. Christopher Potts](https://web.stanford.edu/~cgpotts/) at [Stanford](https://online.stanford.edu/programs/artificial-intelligence-professional-program), 2021* <br><br/>
How would one describe a color that has no universally accepted name? The trick is to convert the task into a conversation between 2 agents mutually trying to conclude on a unique description of the target color differentiating it from the rest. I improve on this idea via generative cooperative games between listener and speaker agents.<br><br/>

### Sentiment Analysis in unseen domain<sup>[\[code\]](https://github.com/codeViser/sentiment-analysis)<sup/>
*Course Project supervised by [Prof. Dr. Christopher Potts](https://web.stanford.edu/~cgpotts/) at [Stanford](https://online.stanford.edu/programs/artificial-intelligence-professional-program), 2021* <br><br/>
Sentiment identification models predict poorly when they process text from a domain different from their training data. I present a robust sentiment classification module that suppresses sentiment signals from idiosyncratic phrases of a domain limiting the effects of domain-shift, producing 2<sup>nd</sup> highest leaderboard score in the university contest.<br><br/>

### Char-level Neural Machine Translation<sup>[\[code\]](https://github.com/codeViser/esp-en-char-nmt)<sup/>
*Course Project supervised by [Prof. Dr. Christopher Manning](https://nlp.stanford.edu/~manning/) at [Stanford](https://online.stanford.edu/programs/artificial-intelligence-professional-program), 2020* <br><br/>
Neural Machine Translation is a popular method for translation across languages. *But how big of a vocabulary in both languages suffice acceptable translation between them?* To address this practical issue, I implement [Loung & Manning (2016)](https://arxiv.org/abs/1604.00788), a translation engine for even unknown words.<br><br/>

</div>
</div>


<div id="social">
<button type="button" class="collapsible">Social Impact</button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Violence Detect
*Hackathon at [SDS Labs](https://sdslabs.co/), [IITR](https://new.iitr.ac.in/Main/pages/_en_Indian_Institute_of_Technology_Roorkee__en_.html), 2018* <br><br/>
Built a intelligent video surveillence system using [clarifai API](https://www.clarifai.com/), that alerts authorities on detecting perceptible physical violence from camera feed. The detection is based on confidence inferred from bag of words generated by API on sampled images.<br><br/>

### Military training in simulation
*Student Project funded by [Artificial Intelligence and Electronics Society (ArIES)](https://www.linkedin.com/company/aries-iitr/?originalSubdomain=in) at [IITR](https://new.iitr.ac.in/Main/pages/_en_Indian_Institute_of_Technology_Roorkee__en_.html), 2015-2017* <br><br/>
To help military personnel practice strategic manoeuvring and skilled shooting, we created a functional augmented reality environment using Microsoft Kinect, limb sensors, Oculus, and an LED gun. The spawned enemies followed adversarial path planning to make their elimination non-trivial.<br><br/>


</div>
</div>



<div id="signals">
<button type="button" class="collapsible">Signal Processing</button>

<div class="content" markdown="1">
<!-- <br><br/> -->

### Real-time anomaly detection in sinusoidal grid system via modeling z-transform frequency filters<sup>[\[paper\]](https://ieeexplore.ieee.org/document/8944848)<sup/>
*Bachlers Project supervised by [Prof. Dr. Vishal Kumar](https://ee.iitr.ac.in/~EE/vksaxfee) at [Electrical Department, IITR](https://ee.iitr.ac.in/), 2018*  <br><br/>
To detect real-time faults in electrical grid, we implemented a signal processing system that digitally samples sinusoidal waves, breaks it into basic components, and actively monitors anomaly from their characteristics. <br><br/>

</div>
</div>
