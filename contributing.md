# PeerToPeerLendingRecommender
A deep recommender system for investors in peer-to-peer lending platforms

## Target Market
Peer-to-Peer (P2P) lending (also known as social or crowd lending) is a financial technology that allows individuals to obtain loans directly from other individuals, without the need of an underwriter, such as a bank. This loans can be used for a variety of reasons, primarily to cover small expenses (e.g., a house renovation or a vacation) or sudden emergencies (e.g., a surgery/treatment). P2P lending offers individual investors the opportunity of higher interest rates compared to conventional investments, as a compensation for taking higher risk.

## Business Opportunities
Each investor can be broadly categorized as risk-averse, risk-neutral or risk neutral, according to the financial theory. P2P lending platforms often use this categorization as a basis for promoting investment opportunities to investors. Each individual investor is expected to select among some categories in order to specify how much risk they are willing to take and then select among grouped loans that represent that category. However, given the complexity of each individual loan, a better solution would be a recommender system that orders all available loans based on the preferences of an investor (risk/return factor), which would give each investor the freedom to construct their own portfolio.

## Roadmap
1. Training of a binary classifier that estimates the probability of default for an individual borrower.
2. Training of a regression model that predicts the annual return of a given loan.
3. Construction of relevant metrics that capture the risk and return dynamics of each individual loan.
4. Construction & deployment of the recommender system that orders all available loans based on the preferences of an investor.
5. (Bonus) Construct a Generative Adversarial Network (GAN) to create new loan data and test the system in real time.
