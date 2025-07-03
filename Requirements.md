# 🧰 Project Requirements  
**YouTube Power BI Dashboard Suite**

This document details all prerequisites and setup requirements for running, editing, or extending the dashboards in this project.


## 💻 System Requirements

| Component | Minimum Requirement |
|-----------|---------------------|
| Operating System | Windows 10/11 (64-bit) |
| RAM | 8 GB (16 GB recommended for large datasets) |
| Disk Space | 1 GB (for project files and visuals) |
| Power BI Version | Power BI Desktop (May 2023 or later) |
| Processor | 2.0 GHz Dual-Core (i5/i7/i9 preferred) |
| Internet | Required for Power BI updates and optional web visuals |



## 🔧 Software Requirements

- ✅ **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/en-us/downloads/))
- ✅ [DAX Studio (optional)](https://daxstudio.org/) for DAX performance testing
- ✅ Excel or Notepad++ for quick data inspection
- ✅ Git (if cloning the repository)



## 📦 Dataset Requirements

| Dataset | Description | Required? |
|---------|-------------|-----------|
| `YouTube Trending Dataset` | Contains video metadata, engagement metrics, timestamps, tags, and errors | ✅ |
| Enriched Columns | Added during preprocessing: `days_to_trend`, `hour`, `category_name`, `publish_day_of_week`, etc. | ✅ |

### 📁 Columns Used:
- `video_id`, `title`, `channel_title`, `views`, `likes`, `dislikes`, `comment_count`
- `publish_date`, `trending_date`, `days_to_trend`, `published_day_of_week`
- `publish_country`, `category_id`, `category_name`, `tags`, `hour`
- `comments_disabled`, `ratings_disabled`, `video_error_or_remove`

> Note: A cleaned/enriched `.csv` or `.xlsx` version is used as input in each `.pbix` file.



## 📊 Power BI Features Required

The dashboards use advanced Power BI capabilities:
- ✅ **Slicers**: country, hour, category, date ranges
- ✅ **Tooltips & Drillthrough**
- ✅ **Bookmarks (for dynamic pages)**
- ✅ **Custom Measures & DAX Expressions**
- ✅ **Time Series Charts, Heatmaps, and Matrix Visuals**

---

## 📚 Required Skills to Modify

| Skill | Level |
|-------|-------|
| Power BI Navigation | Beginner |
| DAX (Data Analysis Expressions) | Intermediate |
| Power Query (M) | Beginner |
| Data Modeling Concepts | Intermediate |
| Git/GitHub (optional) | Beginner |


