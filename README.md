# Network-Analysis for Risk Assessment

---

The world is moving at a very fast pace, increasingly being dominated by new technology and emerging business models, while Risk is getting more interconnected like never before. As a result of this rapid growth in technology, the past can no longer be solely relied on as a guide to the future. Risks are evolving, they combine, they spill over into each other and do not manifest in isolation. Thus, dealing with risks discretely is no longer sufficient in the Enterprise Risk Assessment process.
Traditional Risk Assessment may be insufficient, without considering Risks that trigger other Risks (Contagious Risks) and to what extent (Velocity). Two-dimensional Risk Management methodologies that focus on single points of risk by measuring the high likelihood and severity, may provide only limited value and insights in increasingly complex and globally interconnected organizations. Instead, we need to consider these additional dimensions of risks, by asking questions about how risks are interconnected, the strength of these interconnections, how risks potentially cluster together, as well as the potential cumulative impact of such clusters.
For example, a risk identified during an initial risk assessment workshop may be Liquidity Risk. While stakeholders may agree that this is a medium Risk, there is a need to go a step further and establish what other risks could be triggered by the manifestation of this risk, and possibly, what other risks could those risks trigger.
This gets complicated using the traditional analytics approach, especially when you have a large pool of risks to analyze. The top ten (10) risks, in this case, should not just be limited to severity and impact, but also include the third and fourth dimensions of contagion and velocity.
Risks such as Natural Disasters, Infectious Diseases, Critical Infrastructure failure, and Climate Change are likely to be regarded as low likelihood risks, due to the very low probability that the risks could crystalize. They could, however, have a devastating effect on an organisation in the short and long term, should they crystalize. The effects could even be more devastating if they trigger other critical high-risk areas. Organisations, therefore, need to be adequately equipped to respond to these Risks.
For example, the recent COVID-19 pandemic has triggered certain unanticipated risks, which organisations are struggling to mitigate. An outbreak of Infectious Diseases like this could trigger operational risks, sourcing risks, working capital risks, etc. in ways that the organisation could not have anticipated. However, having an understanding of which risks could be triggered by a sudden outbreak, and to what extent it can devastate the operations will enable organisations better plan for eventualities.


---

Graph Network Algorithms and Risk Assessment
Traditional analytics techniques are not sophisticated enough to perform a multidimensional relation analysis, which is where graph networks come in.
A graph network is a collection of interconnected nodes. The nodes represent entities and the properties of the entities are embedded within these nodes, while the connections with other nodes represent the relationships. For Risk Assessment purposes, we can represent the risks as a node within the network, each node (risk) will have properties such as likelihood and impact. Risk Interconnectedness will be depicted by creating connections between the risks that affect/ trigger each other, while the strength of this connection will be represented by the thickness of the connection.
We can then deploy algorithms to analyze the graph networks, obtain valuable insights about the network properties, and also to rank the risks based on their interconnectedness, as a more analytical approach to deriving top risks which an organisation should focus its limited resources to mitigate.
Additionally, we can use advanced algorithms to create risk clusters within our network, that provide information on how risks are interrelated and which risks are likely to trigger each other.
An example of graph network applied in risk assessment can be seen in the World Economic Forum Report on The Global Risks Interconnections 2020, where the traditional approach was taken a step further and survey respondents were asked to select up to six pairs of global risks they believe to be most interconnected. 


---

In the section below, we will attempt a basic example of how graph network algorithms can be deployed during risk assessment to help analyze and categorize risks in python. The section requires basic understanding of python programming language, however if you don't write python code, you can still follow along to understand the intuition behind the analysis
