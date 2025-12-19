# Christmas Movie Picker Dashboard

## Project Overview
**Christmas Movie Picker** is an interactive **Power BI dashboard** designed to help users discover and filter Christmas-themed movies based on their preferences.
Using an intuitive set of slicers and visuals, users can explore movies by **genre**, **rating**, **IMDb score**, **runtime**, and **popularity (votes)** to quickly decide what to watch during the holiday season.

This project demonstrates end-to-end Power BI skills including data modeling, visualization design, slicers, and user-driven interactivity.

---

## Objective

The main goals of this project are to:
- Provide a **movie recommendation-style experience** using Power BI
- Allow users to dynamically filter Christmas movies based on personal preferences
- Showcase clean dashboard design and effective use of Power BI visuals
- Practice working with a real-world CSV dataset and transforming it into insights

---

## Dashboard Features
### Interactive Filters (Slicers):
The dashboard includes multiple slicers that allow real-time filtering.
- **Genre**: Filter movies by genre (Comedy, Family, Drama, Animation, etc.)
- **Rating**: Filter by movie certification/rating
- **IMDb Rating (Range)**: Adjustable slider to select movies within a rating range
- **Runtime (Minutes)**: Slider to control movie length (e.g., short films vs feature-length)

These slicers update all visuals simultaneously, enabling an interactive exploration experience.

### Movies Table:
A central table displays the filtered list of movies with the following details:
- Title
- Genre
- Director
- Release Year
- Number of Votes

This table updates dynamically based on slicer selections, allowing users to browse and compare movies easily.

### Top 5 Movies by Votes:

A bar chart highlights the **Top 5 most-voted Christmas movies**, helping users identify the most popular titles at a glance.
From the dashboard, examples of highly voted movies include:
- Die Hard
- Silver Linings Playbook
- Home Alone
- Love Actually
- Edward Scissorhands

This visual emphasizes popularity as a decision-making factor.

---
## Dataset Information

The project uses a CSV dataset: `christmas_moveis.csv`

The columns contain movie-level attributes such as:
- `Title` – Movie name
- `Genre` – Movie genre
- `Director` – Director name
- `Released` – Release year
- `Rating` – Movie certification
- `IMDB Rating` – IMDb score
- `Runtime` – Duration in minutes
- `Votes` – Number of user votes

---
