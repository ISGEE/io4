---
# Define Jekyll collections
collections:
  # Define a collection named "docs", its documents reside in the "_docs" directory
  Games:
    permalink: "/_games/"
    output: true

just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "docs" collection
    Games:
      # Give the collection a name
      name: Serious Games
      # Exclude the collection from the navigation
      # Supports true or false (default)
      nav_exclude: false
      # Exclude the collection from the search
      # Supports true or false (default)
      search_exclude: false
---


* Dummy Serious Game