Lego is a household name across the world, supported by a diverse toy line, hit movies, and a series of successful video games.
In this project, we are going to explore a key development in the history of Lego: the introduction of licensed sets such as Star Wars, Super Heroes, and Harry Potter.
In the late 90s Lego was only able to survive due to a successful internal brand (Bionicle) and the introduction of its first licensed series: Star Wars.
Although Star Wars was critical to the survival of the brand, Lego has since introduced a wide variety of licensed sets over subsequent years.
Two questions are as follows:

1. What percentage of all licensed sets ever released were Star Wars themed? Save your answer as a variable (called "the_force") in the form of an integer (e.g. 25).
2. In which year was Star Wars not the most popular licensed theme (in terms of number of sets released that year)? 
   Save your answer as a variable (called "new_era") in the form of an integer (e.g. 2012).

Datasets description:

datasets/lego_sets.csv
  1. set_num: A code that is unique to each set in the dataset. This column is critical, and a missing value indicates the set is a duplicate or invalid!
  2. set_name: A name for every set in the dataset (note that this can be the same for different sets).
  3. year: The date the set was released.
  4. num_parts: The number of parts contained in the set. This column is not central to our analyses, so missing values are acceptable.
  5. theme_name: The name of the sub-theme of the set.
  6. parent_theme: The name of the parent theme the set belongs to. Matches the name column of the parent_themes csv file.

datasets/parent_themes.csv
  1. id: A code that is unique to every theme.
  2. name: The name of the parent theme.
  3. is_licensed: A Boolean column specifying whether the theme is a licensed theme.

The datasets are not necessarily clean, and may require the removal rows where there are values missing from critical columns.
