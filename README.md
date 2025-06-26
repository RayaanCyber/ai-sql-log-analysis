# AI + SQL Log Analysis Tool

This project uses generative AI and manual SQL queries to analyze login logs for cybersecurity use cases. It’s part of my learning journey into cybersecurity, where I’m combining hands-on experience with tools like SQL, ChatGPT, and system log simulation.

The goal is to detect suspicious behavior, such as failed logins and admin access attempts, by writing SQL queries manually and generating them using AI prompts.

## Objective

- Learn how to structure and query real-world system logs
- Practice writing SQL statements used in threat detection
- Explore how AI can generate useful SQL queries from natural language
- Build a clean, organized portfolio project for employers

- 
## Log File Overview

The log file simulates basic login activity. It includes:

- `user_id` – The username attempting login
- `ip_address` – Source IP of the login
- `action` – Either `login_attempt` or `admin_access`
- `status` – Either `success` or `failed_login`
- `timestamp` – When the event happened

This log structure is based on real-world system logging used in security operations.

## Key Skills Demonstrated

- Writing SQL queries for failed login detection, admin access tracking, and activity summaries
- Designing clear, structured AI prompts to generate SQL commands
- Explaining what each query does and why it matters in security
- Using markdown and file structure to organize a real-world project

## Tools Used

- SQL (manual queries + AI-generated)
- ChatGPT (LLM-based query generation)
- Markdown (for clear documentation)
- GitHub (version control and publishing)
- SQLite (to test queries using sample data)

## Status

- Sample data created and documented
- Manual queries written and explained
- Prompt tests complete (with screenshots)
- Reflection and learning summary included

## Next Steps

- Add more prompt variations (e.g., geo-based logins, login spikes)
- Compare performance and accuracy of AI-generated queries
- Possibly build a basic web interface to test queries interactively

## Author

Created by [Rayaan Mourad](https://www.linkedin.com/in/rayaanmourad)  
GitHub: [github.com/RayaanCyber](https://github.com/RayaanCyber)
