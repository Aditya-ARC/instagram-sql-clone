# Instagram-style SQL Data Warehouse Project

This project simulates a scaled-down **Instagram-like social media platform** backend using **SQL** and ER modeling. It implements core functionality like user management, posts, stories, messages, comments, hashtags, business accounts, ad campaigns, and engagement analytics.

## 📌 Schema Coverage
Designed conceptual, logical, and physical schemas covering:
- Users, Profiles, Followers
- Posts, Media, Likes, Comments, Stories
- Business Accounts, Ads, Campaigns, Promotions, Engagements
- Messaging (Chat), Reports, Blocklists, Locations
- Search History, Hashtags, Post Tags, Post Analytics

25+ interrelated tables with full **normalization**, **referential integrity**, and **realistic constraints** (e.g., `CHECK`, `FOREIGN KEY`, `UNIQUE`).

## 🧠 Features
- Multi-entity relationships: 1:1, 1:M, M:N (e.g., Tags, Saved_Posts, Post_Tags)
- Time-based data (e.g., `created_at`, `story_views`, `engagement_time`)
- OLTP + analytical design: modeled for **real-time operations** & **engagement insights**
- **Business logic ready**: supports queries like "who blocked/report whom", "likes per ad campaign", "user engagement trends", etc.

## 🔍 Sample Queries (from `Queries.docx`)
- User post details with media and hashtags
- Post engagement metrics: likes, comments, reach
- Campaign-wise ad engagement & budget tracking
- User-level engagement summaries and story activity
- Update analytics with real-time like counts

## ⚙️ Tech Stack
- SQL (Oracle syntax compatible)
- ER Modeling (Lucidchart / Draw.io)
- Documentation (PPT, PDF, SQL scripts)

## 📂 Repo Structure (suggested)
```
instagram-sql-clone/
├─ schema/
│  ├─ conceptual.png
│  ├─ logical.png
│  ├─ physical.png
│  └─ ORACLE_AWS_PROJ.sql
├─ queries/
│  └─ Queries.docx
├─ docs/
│  └─ SQL Project Report.pdf
├─ presentation/
│  └─ SQL_Instagramproj.pptx
├─ README.md
└─ .gitignore
```

