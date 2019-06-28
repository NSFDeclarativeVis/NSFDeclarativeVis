---
layout: project
color: "#6488BD"
logo: Logical Interaction
---

<div class="callout">
</div>


Data is a growing part of our culture, and visualizations of data are key to helping people understand and discuss the issues described by the data. Charts and graphs used to be associated with classrooms and laboratories; today they appear in mainstream coverage of weather, politics, sports, and other popular topics. This has happened in part because of advances in the technology for composing visualizations: it's much easier today to generate custom charts, thanks to a revolution in toolkits for data visualization driven by the academic research community. But it is still difficult to author interactive visualizations that allow users to manipulate charts. Research shows that interactivity helps people better understand and explore data visualizations. A number of interactive visualizations have appeared in popular online newspapers like the New York Times in recent years. Unfortunately, current interactive visualization toolkits are very technical and difficult to use, even for experts. The research funded by this grant attempts to make it far easier to build interactive visualizations. This should substantially simplify the task of specifying interaction, and broaden the population of users and organizations who can craft rich, interactive visualizations.

The research funded by this grant explores a declarative approach to specifying interactive data visualizations called Logical Interaction, realized in a new language called LIL. As a high level goal, LIL is intended to significantly simplify the specification of interactive visualizations, enabling more widespread use of interactive features in data visualizations. The dynamics of interaction introduce unique technical challenges and opportunities, including debugging and testing of asynchronous interaction handlers, and design tradeoffs between scaling up data and maintaining interface responsiveness. The hypothesis of the research is that Logical Interaction can make these challenges much more tractable, and that LIL can engage visualization designers in widespread, creative development of new interactive visualizations.

The work of the grant starts with exploring the fundamental modeling and language design issues in this domain, to develop techniques for composing and analyzing interaction code, and to deliver a prototype language, runtime, and analysis suite that demonstrates the benefits of our ideas. Results of the work will be embodied in a language runtime for Logical Interaction, which will be freely available as open source. The project will evaluate the effectiveness of Logical Interaction in terms of its interactivity and scale, the range of interactive visualizations it naturally supports, and the ability for users of varying skills to learn and use it. The researchers will also experiment with Logical Interaction in university courses on Big Data and Data Science, and share the curricula publicly along with the software. Research results will be published in the scientific literature.


## Principal Investigators

* Joseph Hellerstein, UC Berkeley [NSF 1564351](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1564351&HistoricalAwards=false)
* Jeffrey Heer, U. of Washington [NSF 1562182](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1562182&HistoricalAwards=false)
* Eugene Wu, Columbia University [NSF 1564049](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1564049&HistoricalAwards=false)

## Open Source Software

* [Vega-lite](https://vega.github.io/vega-lite/)
* [The DIEL project](https://logical-interactions.github.io/diel/)

## Galleries and Tutorials

* [DIEL Gallery](https://logical-interactions.github.io/diel-gallery/)
* [Interactive Notebooks for Visualization Curriculum](https://github.com/uwdata/visualization-curriculum)
* Relational Visualization Tutorial: [Short Paper](./files/tutorial-vis-sigmod19.pdf), [Slides](#)
