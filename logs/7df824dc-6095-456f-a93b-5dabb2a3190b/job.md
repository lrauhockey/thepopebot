Create a comprehensive news aggregation system with the following specifications:

1. **Directory Structure**: Create a News/ directory with:
   - sources.md - List of websites and RSS feeds being monitored
   - Daily HTML files with curated articles

2. **News Sources**: Monitor key websites covering:
   - AI (OpenAI blog, Anthropic, Google AI, etc.)
   - VibeCoding (relevant coding/development sites)
   - Tech (TechCrunch, Ars Technica, Hacker News, etc.)
   - Finance (tech finance, startup funding news)

3. **Article Curation**: 
   - Fetch up to 20 important articles per run
   - Generate title, summary, and description for each
   - Sort with newest articles on top
   - Implement duplicate detection to prevent repeating articles

4. **Scheduling**: Set up cron jobs for:
   - 6:00 AM weekdays (Monday-Friday)
   - 5:00 PM weekdays (Monday-Friday)

5. **Output Format**: 
   - Save as HTML files in News/ directory
   - Include date, article titles, summaries, descriptions, and source links
   - Send daily digest via Telegram notifications

6. **Duplicate Prevention**: Track previously sent articles to ensure no repeats between 6am and 5pm runs, or across different days

7. **Test Run**: After setting up the system, run it once immediately as a test for today to verify everything works properly

The system will automatically start running twice daily once implemented, delivering curated news directly to your Telegram.