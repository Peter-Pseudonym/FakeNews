# FakeNews
A three part program, using a web scraper, a python-firebase API and deep learning networks, to gauge the "truthiness" of articles in any genre

STEP ONE:

1. BeautifulSoup Web scraper fetches online articles under specific search guidelines -- every time this happens, make firebase create a new section for article genres. If it already exists, update.

STEP TWO:

1. Firebase API to query specific articles, organize based on different genres
2. Initialize group of articles with truth rating -- standardize across multiple articles

STEP THREE:

1. Feed specific batches of the data into a keras network
2. Use different metrics to analyze
3. Group, categorize and rate articles according to their determined trustworthiness
