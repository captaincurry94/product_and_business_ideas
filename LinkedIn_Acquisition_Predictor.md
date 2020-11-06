# Problem
If investors new of certain acquisitions ahead of time, they could adapt their investment strategy respectively before the market reacts to the announcment of an acquisition.
Especially in the startup world, it is important to know what your competition and investment prospects are up to. 

# Solution
I remember having read that a hedge fund foresaw an acquisition because they tracked the movements of the corporate jet on a flight tracker application and observed multiple visits at airports close to a possible acquisition target. 
When I was working for a company that was planning a strategic acquisition, the public almost got to know about it too early because a significant number of employees from each company started connecting on platforms like LinkedIn in a short time span. I believe that this type of event might happen in other transactions as well. 

The solution would be to build a scraper bot that stores the LinkedIn contacts of every employee of a list of prospect companies in regular time intervals. When a significant amount of employees of a certain company now starts connecting with those of another company, you can expect some kind of partnership or acquisition to happen and might want to look deeper into it. 

The same algorithm might also be useful to observe the employee churn rate and hiring efforts of prospect companies.

# MVP
* Build a bot that can scrape all contacts and their respective employer from all people associated with one specific company from LinkedIn.
* Do this for multiple publicly listed companies and compare their publicly declared number of employees with how many you can find with the bot.
* Build network analysis where each company is a node and strength of each connection between company is determined by the number of employees that are connected on LinkedIn.
* Build outlier detection script and observe connections over time. When number of connections suddenly peak, something might be going on. 

# Customers
* Professional investors like family offices, hedge funds or venture capital firms
* M&A consultancies might also be interested in the reports

# Revenue model = subscription
* Sell weekly reportings on a monthly basis
* Adding prospect companies to the report increases the monthly fee
* For premium pricing, customers can get daily reportings and immediate urgency alerts when the algorithm detects increased activities.

# Pros
* Rather easy to maintain once built
* Little money required to start and run the project

# Cons
* Very small customer segment that is hard to reach and sell to
* How to determine fair pricing having so few customers
