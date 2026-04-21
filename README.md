🚀 Just deployed my latest full-stack AI application to the cloud: an Intelligent YouTube Summarizer!

I set out to build a tool that could instantly convert long YouTube videos into beautifully structured, highly readable articles and downloadable PDF reports, and I just pushed it live to production!

Here is the tech stack and architecture I used to pull it off: 🔹 Frontend UI: Designed a sleek,
responsive Glassmorphic interface with reactive CSS gradients.
🔹 Backend Engine: Built using a Python Flask server to orchestrate the heavy lifting.
🔹 Data Extraction Pipeline: Engineered a robust pipeline using the youtube-transcript-api to pull native caption data,
coupled with a BeautifulSoup fallback scraper that seamlessly grabs video metadata whenever transcripts are disabled. 
🔹 Generative AI Integration: Hooked the raw data directly into the powerful Google Gemini 2.5 API,
programming it with a custom system prompt to intelligently synthesize the context into a formatted Markdown article.
🔹 PDF Generation: Implemented fpdf2 with custom text sanitization logic to weave the AI's Markdown dynamically into an elegant, downloadable PDF report. 
🔹 Cloud Deployment: Wrapped the entire application in a Docker container running a production Gunicorn WSGI server, and
securely deployed it live to an AWS EC2 instance!

This project was an incredible deep-dive into managing complex API lifecycles, debugging stubborn encoding issues within PDF generators, and configuring secure containerized environments moving from localhost to the cloud.

The app is currently live right here! Check it out: http://98.88.249.72
