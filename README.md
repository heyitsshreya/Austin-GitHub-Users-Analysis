# Austin GitHub Users Analysis

- The data was scraped using the GitHub API to gather users in Austin with over 100 followers and details on their repositories.
- A surprising insight from the analysis is that niche languages like Fennel have higher average star counts, despite low overall usage.
- Developers could consider exploring unique languages or frameworks to stand out and attract followers in specialized communities.

## Project Overview

This project analyzes GitHub users located in Austin who have more than 100 followers. Using the GitHub API, data was collected on user profiles and repository information, focusing on attributes such as bio length, follower count, and repository statistics.

### Files in This Repository
- **users.csv**: Contains details on each GitHub user from Austin with more than 100 followers, including username, bio, company, location, and follower count.
- **repositories.csv**: Lists the public repositories of these users, containing information like repository name, star count, programming language, and license type.
- **README.md**: Explains the project process, key findings, and recommendations.

### Data Collection Process
1. Used the GitHub API to identify users in Austin with over 100 followers.
2. Retrieved profile details for each user and compiled the data into `users.csv`.
3. Collected data on each user’s repositories (up to 500 per user) and saved it in `repositories.csv`.

### Key Findings
- **Bio Length and Follower Count**: A regression analysis suggests a small positive correlation between bio length and follower count. Developers with longer bios generally have more followers.
- **Popular Languages**: JavaScript is the most used language, with HTML ranking second among recent users, while niche languages like Fennel have notably high star averages.

### Recommendations for Developers
Based on the analysis, developers may benefit from crafting a well-written bio that highlights their skills and interests. Additionally, experimenting with less common languages could help attract followers in niche tech communities.
