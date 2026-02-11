Create a comprehensive news aggregator system that:

1. **Sources**: Scrape key websites and RSS feeds covering AI, VibeCoding, Tech, and Finance
2. **Curation**: Use AI to analyze and select the 20 most important articles from each collection cycle
3. **Scheduling**: Run twice daily (6am and 5pm) on weekdays only
4. **Storage**: Maintain files in a `News/` directory:
   - `sources.md` - List of monitored websites/RSS feeds
   - Daily HTML files with curated articles (newest first)
   - Article tracking to prevent duplicates
5. **Format**: Each article entry includes title, summary, description, and source link
6. **Delivery**: Generate clean HTML output suitable for viewing/sharing

The system will:
- Build a comprehensive list of AI/tech/finance news sources
- Implement duplicate detection across days
- Create an intelligent scoring system to identify "important" articles
- Generate clean, readable HTML output
- Set up the twice-daily cron schedule (6am/5pm weekdays)
- Handle edge cases (fewer than 20 articles, source failures, etc.)