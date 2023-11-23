# Anti Money Laundering using Graph Neural Networks

## Description 
Money laundering is a significant problem involving billions of dollars. Detecting money laundering is challenging because automated algorithms often produce high false positive rates, flagging legitimate transactions as suspicious. Conversely, false negatives, where laundering transactions go undetected, are also a major issue. Criminals make efforts to conceal their illegal activities.

Access to actual financial transaction data is highly restricted due to proprietary and privacy concerns. Even when access is possible, accurately labeling each transaction as laundering or legitimate is problematic. The synthetic transaction data provided by IBM addresses these challenges.

This data is generated in a virtual world inhabited by individuals, companies, and banks. They engage in various financial interactions, such as purchasing goods and services, placing orders, paying salaries, repaying loans, and more, mostly conducted through banks.

A fraction of individuals and companies in this model engage in criminal activities like smuggling, illegal gambling, and extortion. Criminals obtain funds from these activities and attempt to disguise the source of these illicit funds through a series of financial transactions, constituting money laundering. Therefore, this data is labeled and can be used to train and test Anti Money Laundering (AML) models and other applications.

The data generator not only models illicit activities but also tracks funds derived from illegal activities through multiple transactions, allowing for labeling of laundering transactions even if they are several steps removed from the illicit source.

This IBM generator models the entire money laundering process, including placement (introducing illicit funds), layering (mixing funds in the financial system), and integration (spending illicit funds).

Unlike real financial institutions, which only see their own transactions, these synthetic transactions create an entire financial ecosystem. This allows for the development of laundering detection models that understand transactions across institutions but can apply their findings to transactions at a specific bank.

IBM has improved this data generator since its initial release, making it more realistic and resolving bugs.
