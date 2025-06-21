# User Story – Movie Search Functionality

## Description

**As a user**,  
I want to search for movies by name  
**so that** I can quickly find and watch the movies I am interested in.

---

## Background

Users of the streaming service should be able to search for movies by entering the name of the movie.  
The search functionality should be easy to use and provide relevant results based on the search query.

---

## Value / Why

- Easy and quick search in the movie database  
- Organized visibility of search results  
- The movie search technique is simple and intuitive

---

## What / Tech Steps

1. Implementing the search bar  
2. Applying black-box testing techniques to ensure full test coverage  
3. Testing scenarios using:
   - Valid and invalid inputs (numbers, letters)
   - Special characters (which should be rejected)

---

## Assumptions

- Voice search functionality exists

---

## Exclusions

- Voice search is excluded from this test scope

---

## Risks

- ⚠️ Inaccurate search results
- ⚠️ Search may be slow with large datasets
- ⚠️ Limited functionality for non-English or special characters

---

## Testing Context

Testing was done on a **streaming service application**, with focus on:
- Accessing and using the search feature via **side menu**
- Functional, usability, and compatibility testing

---

## Acceptance Criteria

- ✅ The user can see a search bar prominently placed on the main page  
- ✅ The search bar is responsive and accessible from desktop, tablet, and mobile devices  
- ✅ The search results display relevant movie titles with:
  - Thumbnail
  - Release year
  - Genre
  - Short description  
- ✅ The search works across major browsers (Chrome, Firefox, Safari, Opera)  
- ✅ The search is functional on Windows, Android, iOS, and Vidaa platforms
