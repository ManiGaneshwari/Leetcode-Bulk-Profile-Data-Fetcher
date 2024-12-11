
# LeetCode Bulk Profile Data Fetcher

## Problem Statement
**==>**Create a tool that fetches LeetCode profile data for a list of up to 100 usernames. 
**==>**The tool should efficiently retrieve profile information for each user, including their username, rating/ranking, the number of problems solved, and badges (if any).
**==>**The retrieved data should be presented in a table-like format and optionally saved as a CSV or JSON file.
**==>**The program should handle invalid profiles or issues during data retrieval gracefully, providing meaningful error messages without crashing.
## Input
The user will provide a list of up to 100 LeetCode usernames. The usernames can be given either as:
- A comma-separated list
- A file containing one username per line

## Output
The retrieved data should be displayed in a table-like format. Each row will contain:
- Username
- Rating
- Problems Solved
- Badges
Example Output:

| Username | Rating | Problems Solved | Badges         |
|----------|--------|-----------------|----------------|
| Team     | 1400   | 200             | Gold, Silver   |

Optionally, the program should generate a CSV or JSON file with the retrieved data.



**==>**Here we are giving an excel file which contains about 50 leetcode profiles (you can customize it to your own choice).
**==>**The output will be given in **table format (which contains details about the given profiles ,they are arranged rank wise)**
**==>**It also gives a **HTML file** and **CSV file** as an output
