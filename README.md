# Team Problem Set

This is the repository for designing the team problem set. It contains the same binder setup branches and notebook templates as the repo for your individual problem sets and you can use any of them as you see fit.

# Designing the problem set

When designing the problem set, be mindful that you are now working together with multiple people and it is especially important to work in branches, push your changes regularly to GitHub and merge branches regularly into the master branch. If you are working in Jupyter, make sure to clear all output **before** committing changes to git.

# Testing

Make sure to test your problem set on binder to make sure it will be possible to use in a classroom context. For this, adjust/delete the example links below to fit the language(s) and platforms you are using. Make sure to replace all instances of the word `2020-ps-team-geol2001` (the name of the template repo) with the name of your own repository.

create_binder_link(
  create_binder_url(
    org = "CUB-Computational-Tools", # change if your repo lives elsewhere
    repo = "2020-ps-team-geol2001", # change to the name of your repository
    binder_branch = "binder-python", # use the python binder configuration
    content_branch = "drafts", # change if you want to use a different content branch
    ide = "lab", # use the jupyter lab IDE
    file = "example_python_in_jupyter.ipynb" # specify which file to load initially
  ),
  create_badge_url(
    left = "launch", # change to adjust link text
    right = "planet earth", # change to adjust link text
    color = "green" # change to adjust link color
  )
)

# Cleanup

Generally, it is good to clean up the repo once ready for student usage by deleting all unused files in the master branch. None of the files initially in the master branch (examples and blank templates from the template repo) are necessary and all can be deleted (although keeping the `.gitignore` is generally a good idea).
