# Marketing Budget Allocation

Marketing budgets now comprise 11 percent of total company budgets, based on a CMO survey sponsored by the Fuqua School of Business at Duke University, Deloitte LLP, and the American Marketing Association. However, the effectiveness of marketing varies significantly: on the one hand, P&G cut more than $100 million in digital marketing spending because their digital ads were largely ineffective; on the other hand, Netflix plans a 54% boost in ad spending because they got very positive feedback in international markets.

One potential reason for such variation is the way of making marketing budget allocations. Namely, how much to invest in each advertisement platform. As stated in the Handbook of Marketing Analytics:
...budget decisions are often based on gut feelings or on the negotiation skills of individual managers. Consequently, politics and individual opinions tend to shape the decision process instead of fact-based discussions. Obviously, these rules and practices bear the risk of results far away from the optimal, profit-maximizing budget.

Indeed, the marketing strategy of Netflix seems to be steered by data.

In this project, we use linear programming to build a simple marketing budget allocation strategy.

The marketing department is tasked with recommending the allocation of a $10 million budget across various marketing mediums based on estimated Return on Investment (ROI) data provided by two consulting firms. The goal is to find an optimal budget allocation while adhering to specific constraints set by the Chief Marketing Officer.
The problem involves formulating this budget allocation as a linear program and using Gurobi to find the optimal solution based on both sets of ROI data.
