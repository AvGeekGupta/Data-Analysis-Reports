# Reddit r/developersindia Community Posts Raw Dataset

<img src="https://www.redditstatic.com/desktop2x/img/favicon/android-icon-192x192.png" width=100><img src="https://styles.redditmedia.com/t5_2dfnk0/styles/communityIcon_uli9r9wy5lba1.png?width=256&s=7d293bdc1f306bce5ec9a495652c2a60706c4e1c" width=100 align="right">


## Overview

This raw dataset contains every possible information about posts from the r/developersindia subreddit on Reddit. It covers posts starting from July 8, 2023, and goes back in time. The dataset aims to provide insights into the discussions and activities within the r/developersindia community.


## Columns

This dataset contains a comprehensive set of features associated with Reddit posts, offering insights into various aspects of each post. Below is a description of each feature:

1. `approved_at_utc`: Timestamp of post approval in Coordinated Universal Time (UTC).
2. `subreddit`: The name of the subreddit where the post was published.
3. `selftext`: The text content of the post (if it's a self-post).
4. `author_fullname`: Unique identifier for the post's author.
5. `saved`: Indicates if the post has been saved by users.
6. `mod_reason_title`: Title of the moderation reason for the post.
7. `gilded`: The number of awards or gildings received by the post.
8. `clicked`: Indicates if the post has been clicked.
9. `title`: The title of the post.
10. `link_flair_richtext`: Rich text associated with the post's link flair.
11. `subreddit_name_prefixed`: The subreddit name with a prefix (e.g., "r/AskReddit").
12. `hidden`: Indicates if the post is hidden.
13. `pwls`: "Post When Less than Score" threshold for the post.
14. `link_flair_css_class`: CSS class associated with the post's link flair.
15. `downs`: The number of downvotes received by the post.
16. `thumbnail_height`: The height of the post's thumbnail image.
17. `top_awarded_type`: The type of the top award received.
18. `hide_score`: Indicates if the post's score is hidden.
19. `media_metadata`: Metadata associated with media content within the post.
20. `name`: Unique identifier for the post.
21. `quarantine`: Indicates if the post is in quarantine.
22. `link_flair_text_color`: The color of the link flair text.
23. `upvote_ratio`: The ratio of upvotes to total votes on the post.
24. `author_flair_background_color`: Background color of the author's flair.
25. `ups`: The number of upvotes received by the post.
26. `total_awards_received`: The total number of awards or gildings received.
27. `media_embed`: Embedded media content associated with the post.
28. `thumbnail_width`: The width of the post's thumbnail image.
29. `author_flair_template_id`: Template ID of the author's flair.
30. `is_original_content`: Indicates if the post is original content.
31. `user_reports`: Reports filed by users about the post.
32. `secure_media`: Secure media content associated with the post.
33. `is_reddit_media_domain`: Indicates if the post is hosted on Reddit's media domain.
34. `is_meta`: Indicates if the post is meta-content.
35. `category`: The category of the post.
36. `secure_media_embed`: Embedded secure media content associated with the post.
37. `link_flair_text`: The text of the link flair.
38. `can_mod_post`: Indicates if the post can be moderated by a moderator.
39. `score`: The score (upvotes minus downvotes) of the post.
40. `approved_by`: Username of the user who approved the post.
41. `is_created_from_ads_ui`: Indicates if the post was created through the ads UI.
42. `author_premium`: Indicates if the author has a premium account.
43. `thumbnail`: URL of the post's thumbnail image.
44. `edited`: Indicates if the post has been edited.
45. `author_flair_css_class`: CSS class associated with the author's flair.
46. `author_flair_richtext`: Rich text associated with the author's flair.
47. `gildings`: Information about the gildings (awards) received by the post.
48. `post_hint`: A hint about the type of content in the post.
49. `content_categories`: Categories associated with the post's content.
50. `is_self`: Indicates if the post is a self-post.
51. `subreddit_type`: The type of subreddit.
52. `created`: Timestamp when the post was created.
53. `link_flair_type`: The type of link flair.
54. `wls`: Whitelist status.
55. `removed_by_category`: Category of the reason for post removal.
56. `banned_by`: Username of the user who banned the post.
57. `author_flair_type`: The type of author flair.
58. `domain`: The domain of the post's URL.
59. `allow_live_comments`: Indicates if live comments are allowed on the post.
60. `selftext_html`: HTML representation of the selftext content.
61. `likes`: Indicates if the post is liked by the user.
62. `suggested_sort`: Suggested sorting method for comments.
63. `banned_at_utc`: Timestamp when the post was banned in UTC.
64. `view_count`: The number of views the post has received.
65. `archived`: Indicates if the post is archived.
66. `no_follow`: Indicates if the post is marked as "no follow."
67. `is_crosspostable`: Indicates if the post can be crossposted.
68. `pinned`: Indicates if the post is pinned.
69. `over_18`: Indicates if the post is marked as "over 18."
70. `preview`: Preview information for the post's content.
71. `all_awardings`: Information about all the awards/gildings received by the post.
72. `awarders`: Users who have given awards to the post.
73. `media_only`: Indicates if the post contains only media content.
74. `link_flair_template_id`: Template ID of the link flair.
75. `can_gild`: Indicates if the post can be gilded.
76. `spoiler`: Indicates if the post is marked as a spoiler.
77. `locked`: Indicates if the post is locked.
78. `author_flair_text`: The text of the author's flair.
79. `treatment_tags`: Tags associated with how the post is treated.
80. `visited`: Indicates if the user has visited the post.
81. `removed_by`: Username of the user who removed the post.
82. `mod_note`: Notes left by moderators about the post.
83. `distinguished`: Indicates if the post has been distinguished (e.g., by a moderator).
84. `subreddit_id`: Unique identifier of the subreddit.
85. `author_is_blocked`: Indicates if the author is blocked.
86. `mod_reason_by`: Username of the moderator who provided the reason for post removal.
87. `num_reports`: The number of reports filed for the post.
88. `removal_reason`: The reason for post removal.
89. `link_flair_background_color`: Background color of the link flair.
90. `id`: Unique identifier of the post.
91. `is_robot_indexable`: Indicates if the post is indexable by search engines.
92. `report_reasons`: Reasons provided when reporting the post.
93. `author`: The username of the post's author.
94. `discussion_type`: The type of discussion associated with the post.
95. `num_comments`: The number of comments on the post.
96. `send_replies`: Indicates whether to send replies to the post.
97. `whitelist_status`: The whitelist status of the post.
98. `contest_mode`: Indicates if the post is in contest mode.
99. `mod_reports`: Reports filed by moderators about the post.
100. `author_patreon_flair`: Indicates if the author has Patreon flair.
101. `author_flair_text_color`: The color of the author's flair text.
102. `permalink`: The URL permalink of the post.
103. `parent_whitelist_status`: The whitelist status of the parent post (if applicable).
104. `stickied`: Indicates if the post is stickied.
105. `url`: The URL associated with the post.
106. `subreddit_subscribers`: The number of subscribers to the subreddit.
107. `created_utc`: Timestamp when the post was created in UTC.
108. `num_crossposts`: The number of times the post has been crossposted.
109. `media`: Media content associated with the post.
110. `is_video`: Indicates if the post contains video content.
111. `url_overridden_by_dest`: Overridden URL destination (if applicable).
112. `gallery_data`: Data associated with post galleries.
113. `is_gallery`: Indicates if the post is a gallery.
114. `author_cakeday`: Indicates if it's the author's cakeday.

These features collectively provide valuable information for analyzing and understanding Reddit post data in various research and machine learning applications.


## Potential Use Cases

This dataset can be valuable for various data analysis and machine learning tasks, including:

- Sentiment analysis of posts within the r/developersindia community.
- Topic modeling to identify common discussion topics.
- User behavior analysis, such as post frequency and engagement.
- Exploring trends and patterns in posts and comments.
- Investigating the impact of upvotes, downvotes, and crossposts.


## Data Collection

The data was collected using a Python script from the [RedditScraper GitHub repository](https://github.com/AvGeekGupta/RedditScraper) authored by [AvGeekGupta](https://github.com/AvGeekGupta). The script uses the `requests` library to scrape data from Reddit. Please make sure to review the script and its associated license on the GitHub repository for more details on the data collection process.


## Licensing

Please note that this dataset is intended for research and analysis purposes only. Ensure that you comply with Reddit's terms of service and any applicable licenses when using this data.

## Acknowledgments

We would like to express our gratitude to [AvGeekGupta](https://github.com/AvGeekGupta) for creating the Python script and making this dataset available.

## Citation

If you use this dataset in your work or research, please consider citing it as follows:

[AvGeekGupta. "Reddit r/developersindia Community Posts Raw." Kaggle, 2023.](https://www.kaggle.com/avgeekgupta/reddit-rdevelopersindia-community-posts-raw)

## Feedback and Contact

If you have any questions, feedback, or need further assistance regarding this dataset, please feel free to contact [AvGeekGupta](https://github.com/AvGeekGupta) on GitHub.

Happy analyzing!
