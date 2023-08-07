# WhatsApp Group Chat Analyzer

This is a Python script that helps you analyze your WhatsApp group chat export file. The script processes the chat data, extracts useful information, and presents it in a readable format, including active users, activity by hour, most used words, and most used emojis. Additionally, it creates a bar chart to visualize the activity by hour using Plotly.

## Prerequisites

To run this script, you need to have the following installed:

- Python 3.x
- pandas
- emoji
- plotly

You can install the required dependencies using the following command:

```bash
pip install pandas emoji plotly
```

## How to Use

1. Export your WhatsApp group chat:
   - Open the WhatsApp group chat you want to analyze.
   - Go to the three dots menu in the top-right corner.
   - Select "More" > "Export chat".
   - Choose "Without Media" to get a text file with the chat data only.

2. Save the exported chat file to a convenient location on your computer.

3. Replace 'chat.txt' in the script with the path to your WhatsApp chat export file:

   ```python
   chat_file_path = 'path_to_your_chat_file.txt'
   ```

4. Run the script:

   ```bash
   python chat_analyzer.py
   ```

   The script will process the data and display the following information:

   - Active Users: A count of messages sent by each user in the chat.
   - Activity by Hour: A bar chart showing the number of messages sent during each hour of the day.
   - Most Used Words: The top 10 most frequently used words in the chat.
   - Most Used Emojis: The top 10 most frequently used emojis in the chat.



