Customizing Webpage

# Change profile image
  assets -> cropped.png (swap image and keep the same name, make sure to delete the previous one)
  can adjust image height through _layouts -> home.html -> .profile-picture (Look for "margin-top:")

# Change contents on website
  For About Me section
    -> index.md (to modify About Me section)

  All other sections
  _includes folder
    -> positions.md
    -> current-research.md
    -> publications.md
    -> teaching.md
    -> talks-and-links.md
    -> contact-info.md

  To change layout of homepage
  _layouts -> home.html
  can change the layout of the entire home page including the formats for each section
# Change © placeholder
  _includes -> footer.html
  edit code next to ©

# Updating new tabs
  _data -> nav.yml
  can delete tabs or create new ones, follow the formating for the previous examples

  changing the format, navigate to nav.html to find html format code
