# practiceprojects
I recently started my transition into the tech space as a data scientist.
This repo contains my first completed beginner project detailing what I had learnt at the time.
My training started off with learning how to navigate spreadhseets, and then I moved on to databases, specifically MYSQL.
This was followed by data visualisation and storytelling in Power BI. 
In between the training and at the end, there was an ongoing practice project that required application of SQL and visualisation skills. 
It involved analysing data on water sources in a fictional town called Maji Ndogo to determine the population of the town that has access to water and also rejuvenate the sources to cater for those without.

Summary Report

The insights from the data include:

Most water sources are rural in Maji Ndogo.
43% of people are using shared taps. 2000 people often share one tap.
31% of population has water infrastructure in their homes, but within that group, 45% face non-functional systems due to issues with pipes, pumps, and reservoirs. Towns like Amina, the rural parts of Amanzi, and a couple of towns across Akatsi and Hawassa have broken infrastructure.
18% of people are using wells of which, but within that, only 28% are clean. These are mostly in Hawassa, Kilimani and Akatsi.
Citizens often face long wait times for water, averaging more than 120 minutes: • Queues are very long on Saturdays. • Queues are longer in the mornings and evenings. • Wednesdays and Sundays have the shortest queues.

Plan of action

We want to focus our efforts on improving the water sources that affect the most people. • Most people will benefit if we improve the shared taps first.
Wells are a good source of water, but many are contaminated. Fixing this will benefit a lot of people.
Fixing existing infrastructure will help many people. If they have running water again, they won't have to queue, thereby shorting queue times for others. So we can solve two problems at once.
Installing taps in homes will stretch our resources too thin, so for now if the queue times are low, we won't improve that source.
Most water sources are in rural areas. We need to ensure our teams know this as this means they will have to make these repairs/upgrades in rural areas where road conditions, supplies, and labour are harder challenges to overcome.

Practical solutions:

If communities are using rivers, we will dispatch trucks to those regions to provide water temporarily in the short term, while we send out crews to drill for wells, providing a more permanent solution. Sokoto is the first province we will target.
If communities are using wells, we will install filters to purify the water. For chemically polluted wells, we can install reverse osmosis (RO) filters, and for wells with biological contamination, we can install UV filters that kill microorganisms - but we should install RO filters too. In the long term, we must figure out why these sources are polluted.
For shared taps, in the short term, we can send additional water tankers to the busiest taps, on the busiest days. We can use the queue time pivot table we made to send tankers at the busiest times. Meanwhile, we can start the work on installing extra taps where they are needed. According to UN standards, the maximum acceptable wait time for water is 30 minutes. With this in mind, our aim is to install taps to get queue times below 30 min. Towns like Bello, Abidjan and Zuri have a lot of people using shared taps, so we will send out teams to those towns first.
Shared taps with short queue times (< 30 min) represent a logistical challenge to further reduce waiting times. The most effective solution, installing taps in homes, is resource-intensive and better suited as a long-term goal.
Addressing broken infrastructure offers a significant impact even with just a single intervention. It is expensive to fix, but so many people can benefit from repairing one facility. For example, fixing a reservoir or pipe that multiple taps are connected to. We identified towns like Amina, Lusaka, Zuri, Djenne and rural parts of Amanzi seem to be good places to start.

Visualisations of the data was also done using Power BI. Hence, the repository contains pdf's showing these viusalisations. It has two dashboards; one detailing the types of sources of water available nationally and in each province and the required amount of money needed to upgrade the sources. The other dashboard serves as a monitor for the improvements to be done or have been done and how much money has been spent on which improvements.
