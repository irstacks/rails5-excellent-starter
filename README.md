## The stack.
- __Rails 5.0.0.rc2__
- __Ruby 2.3.1 (x86_64-darwin15)__ Note the file `.rvmrc`. It specifies this ruby version at a gemset named `r5`. If you want to use a different gemset name, or a different ruby version, just change this file and check the RVM docs for installing your preferred ruby with your preferred gemset. 
- __Postgres__ 
- __Bootstrap 4 Alpha__

## Excellent gems
A big part of the objective for me for making this starter is keeping a running list of gems I find myself installing repeatedly in new projects.  Except for Bootstrap and Font Awesome, these gems are commented by default. Go through and turn on the ones you want. These gems include but are not limited to...

##### Front end gems
- Bootstrap 4 (and Font Awesome)
- Gon
- D3 and Chartkick
- Angular (with templates)
- Statistics stuff

##### Middle end gems
- Devise (user auth)
- Nokogiri (doc parsing)
- Carrierwave (file uploads)

##### Behind the scenes gems
- Query Diet (mind n+1 queries)
- Table_print (intuitive table view for rails console)
- Figaro (manage secrets)
- Rails 12Factor (happier deploys)


### Make it your own.
When you clone the starter, you'll clone an existing app named _RbRails5Pg_, which I'm guessing isn't what you want to name your app.  Globally find and replace `RbRails5Pg` and `rb-rails5-pg`. Excepting `README.md`, there should be 1 occurence in 1 file (`application.rb`) and 7 occurrences in 3 files, respectively.  

### Set it up.
Once you've swapped the name, you're ready to install and run. 
- `$ bundle install` (you may need to install `Bundler` gem first in your gemset)
- `$ rails db:create `
- `$ rails db:migrate`
- `$ rails s` 
- `$ guard -P livereload` in separate terminal adjacent to server (you'll need to `$ quit` to exit the livereload process)

### Look around. 
Once alive, check out `application.html.erb`. You'll find some goodies in there which you can make use of our turn off as you like. 
- `gon` init helper
- `query diet` widget
- flash messages partial (with helper method in `application_helper.rb`)
- a __getResponsiveBreakpoints()__ helper function is made available to your JS by a partial
- a little JS to make Rails errors css Bootstrappier&trade;
- `debug(params)` for development

