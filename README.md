# Semester Project
## Using Yelp Fusion and demographic data to draw conclusions about zip codes in Harris County

A collection of code and files for my semester project on pulling Houston restaurant data from Yelp and integrating with census information by zip code. 

A report of this project is available as 'final_report.pdf' and was created at the time of its most recent commit.
 
# Disclaimers
This code is not without its issues! For one, the method I use to pull restaurants potentially underrepresents zip codes with large amounts of restaurants. While I believe we'll still be able to draw significant conclusions about each zip code, any such conclusions must be treated with a healthy amount of skepticism.

# Know before you knit!
- Make sure all of the required packages are installed
- Some version of LaTeX is required to knit to pdf
- Run using R version 4.0.5
- Register for a Yelp Fusion API key at https://www.yelp.com/fusion

# Reproducibility:
I've found that over the course of running the semester_project.Rmd file, on occasion the API request fails and I'm left with incomplete data. (A good indicator of this is that the price choropleth map will be full of black (NAs)). For now, the solution to reproduce the results of the experiment seems to be just re-running the code until this works.
