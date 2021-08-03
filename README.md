# SpockTunes

Hey,
This repo is kinda ambitious or probably too good to be true, but hey we've gotta start from somewhere!

So, this will mainly contain ML and Deep learning algos for smart intra-day trading (Opinions are mine!) 

Road map planning to follow:
- Read about algorithmic trading and start to fork some of the cool repos lying around to clone and implement them. If it gives fruitful results, then
- Include a list of stocks (refinieres) and run the algo on them to predict the stock value:
For example: I need to check for Amazon (pretty giant huh!?) and let's say I have just 500 quids to spend, so the algo will take the 
  - Input: Amazon, 500 (starting_amount_willing_to_trade)(TODO: Do we need this? Have to think about it, if fractional trading is allowed), date (for which intraday you wanna reap the benefit)
  - Output: Time when the stock value would be highest for the particular date (How about returning top 3 time keys for maximum stock values)

To think about: Should we add API keys for brokers like Zerodha/ Angel Broking to put an order automatically for the given output, Also how about, making an order in fractions for the given amount(Let's say, I have 500 quids to spend and the top 3 stock values for Amazon for 15th August is [3500, 3490, 3480], so we can also try splitting 500 bucks in [60%, 20%, 20%] trading anount to reduce risk probably.

Let's try this first

Then after that: 
- We will try to combine neural nodes to pick both fundamental and technical trading features to make more accurate judgement, probably using Quantum Entanglement based approaches.
- Using NLP and text analysis, we can try crawling through news for a particular stock and track the behaviour/pattern of the stock value for such news in the past and could serve this as a third feature set
