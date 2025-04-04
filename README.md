# Whatsapp-chat-analysis
A Streamlit app that analyzes exported WhatsApp chats. Shows message stats, active users, timelines, word clouds, emoji usage, and activity heatmaps. Supports user-specific or group-level insights with interactive visualizations. Built with Python, Pandas, and Matplotlib.

# Key Features
Message Statistics:
1. Total messages, words, media shared, and links shared
2. User-specific or overall group analysis

User Activity Analysis:
1. Most active users in the group
2. Percentage contribution of each user
3. Daily, weekly, and monthly activity patterns

Temporal Analysis:
1. Monthly and daily message timelines
2. Activity heatmap showing message frequency by day and hour
3. Busiest days and months visualization

Content Analysis:
1. Word cloud generation (with stopword removal)
2. Most common words used in chat
3. Emoji usage analysis with frequency distribution

Interactive Interface:
1. User-friendly sidebar for file upload and user selection
2. Responsive layout with multiple visualization columns
3. Clean, modern presentation of analytics

# Technical Implementation
Built with Python using Streamlit for the web interface
Utilizes pandas for data manipulation and preprocessing
Employs matplotlib and seaborn for visualizations
Includes advanced text processing with:
  1. Regular expressions for chat parsing
  2. Stopword filtering
  3. URL extraction
  4. Emoji detection and analysis

# How It Works
1. Users upload an exported WhatsApp chat text file
2. The application preprocesses the data, extracting:
  Message timestamps
  Sender information
  Message content
3. Various analytics are computed and displayed through interactive visualizations
4. Users can filter analysis by specific group members or view overall statistics

# Ideal For
1. Group admins wanting to understand chat dynamics
2. Individuals analyzing their messaging patterns
3. Researchers studying communication behaviors
4. Anyone curious about their WhatsApp usage statistics
