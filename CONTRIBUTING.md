# Contributing to `ramlegacy`

Thank you for any and all contributions! Following these guidelines will help streamline the process of contributing and make sure that we're all on the same page. While we ask that you read this guide and follow it to the best of your abilities, we welcome contributions from all, regardless of your level of experience.

By participating in this project, you agree to abide by the [code of conduct](https://github.com/ropensci/ramlegacy/blob/master/CONDUCT.md).

# Types of contributions 

Following types of contributions are always welcome:

- Identify areas for future development ([open an Issue](https://github.com//ramlegacy/issues))
- Identify issues/bugs ([open an Issue](https://github.com/ropensci/ramlegacy/issues))
- Write tutorials/vignettes ([open a Pull Request](https://github.com/ropensci/ramlegacy/pulls) to contribute to the ones here, or make your own elsewhere and send us a link)
- Add functionality ([open a Pull Request](https://github.com/ropensci/ramlegacy/pulls))
- Fix bugs ([open a Pull Request](https://github.com/ropensci/ramlegacy/pulls))


# How to contribute code

- Fork the repository
- Clone the repository from GitHub to your computer e.g,. `git clone https://github.com/ropensci/ramlegacy.git`
- Make sure to track progress upstream (i.e., on our version of `ramlegacy` at `ropensci/ramlegacy`)
  - `git remote add upstream https://github.com/ropensci/ramlegacy.git`
  - Before making changes make sure to pull changes in from upstream with `git pull upstream`
- Make your changes
  - For changes beyond minor typos, add an item to NEWS.md describing the changes and add yourself to the DESCRIPTION file as a contributor
- Push to your GitHub account
- Submit a pull request to home base (likely master branch, but check to make sure) at `ropensci/ramlegacy`

# Code formatting

- In general follow the convention of <https://r-pkgs.had.co.nz/r.html#style> (snake_case functions and argument names, etc.)
- Use explicit package imports (i.e. package_name::package_function) and avoid @import if at all possible
