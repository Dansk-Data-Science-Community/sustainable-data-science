# DDSC's Sustainable Data Science Guide

This is the [Danish Data Science Community](https://ddsc.io/)'s guide to resources on sustainable data science. In this context, <em>sustainable data science</em> refers to the sustainability of data science as a field from a climate and environmental perspective, i.e. how to make the data science field more sustainable for instance by reducing the energy consumption of machine learning model training. Thus, this is <em>not</em> a guide to resources on data science applied to sustainability use cases. By "data science" we mean a broad field encompassing machine learning, statistics, operations research etc, but also data engineering and other related disciplines.

Feel free to create an issue or make a PR if you want to contribute.

## Sustainable data science tools

Tools for measuring energy consumption and/or CO2e from computational procedures

1. [carbontracker](https://pypi.org/project/carbontracker/): A Python package for tracking and predicting the energy consumption and carbon footprint of training deep learning models as described in [Anthony et al. (2020)](https://arxiv.org/abs/2007.03051)
2. [codecarbon](https://codecarbon.io/): A Python package that estimates the amount of carbon dioxide (CO2) produced by the cloud or personal computing resources used to execute code. It shows developers how they can lessen emissions by optimizing their code or by hosting their cloud infrastructure in geographical regions that use renewable energy sources. It is similar to carbontracker, but is actively maintained and developed as opposed to carbontracker which was last updated in 2021.
3. [ML CO2 Impact](https://mlco2.github.io/impact/#compute): In this web application, you choose your hardware, runtime and cloud provider to estimate the carbon impact of your model training. This calculator will give you 2 numbers: the raw carbon emissions produced and the approximate offset carbon emissions. The latter number depends on the grid used by the cloud provider.
4. [AWS Customer Carbon Footprint Tool](https://aws.amazon.com/aws-cost-management/aws-customer-carbon-footprint-tool/): Track, measure, review, and forecast the carbon emissions generated from your AWS usage
5. [GCP Carbon Footprint](https://cloud.google.com/carbon-footprint): Measure, report, and reduce your cloud carbon emissions.
6. [Azure Emissions Impact Dashboard](https://www.microsoft.com/en-us/sustainability/emissions-impact-dashboard?rtc=1&activetab=pivot_2:primaryr12): Estimate your carbon emissions related to using Microsoft cloud services—including Azure and Microsoft 365
7. [ThoughtWorks Cloud Carbon Footprint](https://www.cloudcarbonfootprint.org/): Free and open source cloud carbon emissions measurement and analysis tool from ThoughtWorks. 
8. [Green Algorithms calculator](http://www.green-algorithms.org/): Similar to ML CO2 Impact

## Sustainable data science papers

Academic and industry papers about the environmental / climate impact of data science, machine learning and related topics.

1. [Green AI](https://arxiv.org/abs/1907.10597)
2. [Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning](https://arxiv.org/abs/2002.05651)
3. [Carbon Emissions and Large Neural Network Training](https://arxiv.org/abs/2104.10350)
4. [Hyperparameter Power Impact in Transformer Language Model Training](https://stromberg.ai/publication/transformerpower/)
5. [The carbon impact of artificial intelligence](https://www.nature.com/articles/s42256-020-0219-9?proof=t)
6. [Towards Power Efficiency in Deep Learning on Data Center Hardware](https://ieeexplore.ieee.org/document/9005632)
7. [Quantifying the Carbon Emissions of Machine Learning](https://arxiv.org/abs/1910.09700)
8. [Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning](https://arxiv.org/abs/2002.05651)
9. [Power Consumption Variation over Activation Functions](https://stromberg.ai/publication/powerconsumptionvariationoveractivationfunctions/)
10. [Impacts of software and its engineering on the carbon footprint of ICT](https://www.sciencedirect.com/science/article/abs/pii/S0195925514000687?via%3Dihub)
11. [Energy Efficiency across Programming Languages](https://greenlab.di.uminho.pt/wp-content/uploads/2017/09/paperSLE.pdf)
12. [Energy and Policy Considerations for Deep Learning in NLP](https://arxiv.org/abs/1906.02243)
13. [Green Algorithms: Quantifying the carbon footprint of computation](https://arxiv.org/abs/2007.07610)
14. [MEASURING THE ENVIRONMENTAL IMPACTS OF ARTIFICIAL INTELLIGENCE COMPUTE AND APPLICATIONS](https://www.oecd-ilibrary.org/docserver/7babf571-en.pdf?expires=1669740588&id=id&accname=guest&checksum=73E109E3AEEA9B5438E0E483E40E61AA)

## Sustainable data science journals

A list of scientific journals related to sustainable data science and related topics

1. [Sustainable Computing: Informatics and Systems](https://www.sciencedirect.com/journal/sustainable-computing-informatics-and-systems)

## Sustainable data science talks

Talks, presentations, debates etc. about sustainable data science and the environmental / climate impact of machine learning.

## Sustainable data science podcasts

Podcast shows and episodes about sustainable data science, the environmental impact of machine learning and related topics.

1. [Sustainable data science / GreenAI podcasts](https://open.spotify.com/playlist/2ojcoox4YyeAXxJaS2bufh?si=6b14fae7e0a5441f) - a Spotify playlists with some podcast episodes on the topic
2. [Environment Variable](https://open.spotify.com/show/4gynCMPIRC49vcO0hA8PGi?si=a933761d221c42c3) - A show by The Green Software FOundation: "Each episode we discuss the latest news regarding how to reduce the emissions of software and how the industry is dealing with its own environmental impact"

## Sustainable data science news and blogs

News, blogs and other written material (excluding published papers) about the environmental / climate impact of data science, machine learning and software engineering.

1. [Accenture, GitHub, Microsoft and ThoughtWorks Launch the Green Software Foundation with the Linux Foundation to Put Sustainability at the Core of Software Engineering](https://newsroom.accenture.com/news/accenture-github-microsoft-and-thoughtworks-launch-the-green-software-foundation-with-the-linux-foundation-to-put-sustainability-at-the-core-of-software-engineering.htm)
2. [Sustainable Software Engineering (SSE) and the role and responsibilities of a Sustainable Software Engineer](https://devblogs.microsoft.com/sustainable-software/sustainable-software-engineering-sse-and-the-role-and-responsibilities-of-a-sustainable-software-engineer/)
3. [The current state of affairs and a roadmap for effective carbon-accounting tooling in AI](https://devblogs.microsoft.com/sustainable-software/the-current-state-of-affairs-and-a-roadmap-for-effective-carbon-accounting-tooling-in-ai/)
4. [Carbon proxies: Measuring the greenness of your application](https://devblogs.microsoft.com/sustainable-software/carbon-proxies-measuring-the-greenness-of-your-application/)
5. [How to measure the energy consumption of your apps](https://devblogs.microsoft.com/sustainable-software/how-to-measure-the-energy-consumption-of-your-apps/)
6. [A.I.’s carbon footprint is big, but easy to reduce, Google researchers say](https://fortune.com/2021/04/21/ai-carbon-footprint-reduce-environmental-impact-of-tech-google-research-study/)
7. [A Practical Guide to Quantifying Carbon Emissions for Machine Learning researchers and practitioners](https://hal.archives-ouvertes.fr/hal-03376391/document)
8. [How Green Is Your Software?](https://hbr.org/2020/09/how-green-is-your-software)
9. [Most of computing’s carbon emissions are coming from manufacturing and infrastructure](https://tech.fb.com/uncategorized/2021/03/sustainable-computing/)
10. [Your Software’s Carbon Footprint](https://medium.com/@john.m.murray786/your-softwares-carbon-footprint-98d6dc2ff6d6)
11. [Evaluating the carbon footprint of a software platform hosted in the cloud](https://medium.com/teads-engineering/evaluating-the-carbon-footprint-of-a-software-platform-hosted-in-the-cloud-e716e14e060c)
12. [The 10 most energy efficient programming languages](https://kaspergroesludvigsen.medium.com/the-10-most-energy-efficient-programming-languages-6a4165126670)
13. [8 great podcast episodes on the climate impact of machine learning](https://medium.com/towards-data-science/8-podcast-episodes-on-the-climate-impact-of-machine-learning-54f1c19f52d)
14. [BEYOND SINGLE-DIMENSIONAL METRICS FOR DIGITAL SUSTAINABILITY](<https://greensoftware.foundation/articles/beyond-single-dimensional-metrics-for-digital-sustainability?ct=t(EMAIL_CAMPAIGN_1_6_2022_14_35_COPY_01)>)
15. [GPS-UP: A BETTER METRIC FOR COMPARING SOFTWARE ENERGY EFFICIENCY](<https://greensoftware.foundation/articles/gps-up-a-better-metric-for-comparing-software-energy-efficiency?ct=t(EMAIL_CAMPAIGN_1_6_2022_14_35_COPY_01)>)
16. [Towards a Fossil-Free Internet: The Fog of Enactment - Priority areas for research in digital sustainability](https://www.thegreenwebfoundation.org/publications/report-fog-of-enactment/)
17. [Sustain - Sustainable AI in practice](https://algorithmwatch.org/en/wp-content/uploads/2022/06/SustAIn_Magazine_2022_EN.pdf)
18. [How to estimate and reduce the carbon footprint of machine learning models](https://towardsdatascience.com/how-to-estimate-and-reduce-the-carbon-footprint-of-machine-learning-models-49f24510880)

## Carbon footprint reporting methodology in data science and software engineering

1. [Carbon Footprint reporting methodology](https://cloud.google.com/carbon-footprint/docs/methodology)
2. [Software Carbon Intensity (SCI) Specification](https://github.com/Green-Software-Foundation/software_carbon_intensity)
