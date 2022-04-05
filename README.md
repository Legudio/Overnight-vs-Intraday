# Overnight-vs-Intraday

Project inspired by this link: https://bruceknuteson.github.io/spy-day-and-night/ and the paper within titled "They Still Haven't Told You" (2022). Reading the paper, I didn't believe the main conclusion: that most major stock indices experience the majority of their growth overnight. Though I realized this hypothesis would be fairly straight forward to test. 24 hours later, I had my answer: the SPY index did indeed have a negative return intraday, and a large return overnight. In fact, more than half of the components (270) had greater returns overnight than intraday.

This is my first major project, and as such there is room for improvement: first, I must find a better way to obtain financial data. The current solution takes over 20 minutes to download all the data for just over 12 years. The original paper analyzed data going back to 1990. Second, it would make sense to define functions to call to complete the analysis, in the interest of neatness and perhaps efficiency.

I am a novice coder, so alternative methods for the two aforementioned problems are welcome. Also welcome are insights into other areas of improvement which I may have missed.
