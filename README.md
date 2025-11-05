# ai-assisted-sentiment-data-analysis
Sentiment Analysis of customer reviews with LLM integration for reporting and insight generation on common product issues, common service issues, frequency of reported issues.

## Tools Used:

- Jupyter AI
- OpenAI API
- GPT4.1-mini
- Pandas

## Analysis Carried out:

- Created sentiment categories based on numeric rating
- Grouped product and services by category and sentiment, aggregating key metrics
- Calculated percentage of negative reviews safely
- Used OpenAI’s gpt-4.1-mini model to summarize the content in the reviews, with the goal of outputing a summary of product and service issues.
- Saved a copy of the summary generated in .md format

## Analysis Results:

1. **Common Product Issues**: List of main problems customers reported about the product itself (quality, functionality, features, etc.)
2. **Common Service Issues**: List of main problems customers reported about the service (shipping, customer support, packaging, etc.)
3. **Frequency**: For each issue, the estimate of how often it appears (e.g., "mentioned frequently", "occasional complaint", "rare issue")

## Insights Generated

See [insight generated here](outputs/customer_reviews.md)