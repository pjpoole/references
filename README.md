<!-- Up through W5D1 -->

# References
A repo of subject-collected references that I find useful.

Ultimately, this sort of thing is deeply personal, but maybe this is useful to someone else.



## General
* [Tutorialspoint][tutorials_point], a hub for many different resources



## Languages

### Ruby (version 2.1.5)
* [Ruby Standard Library][ruby_stdlib]
* [Ruby Core API][ruby_core]
* **Classes**
  * [Object][ruby_object]: everything in ruby is an object.
  * [String][ruby_string]
  * [Enumerable][ruby_enumerable]: a common mixin for enumerable objects.
  * [Array][ruby_array]
  * [Hash][ruby_hash]
  * [File][ruby_file] / [IO][ruby_io]
* [Ruby doc][ruby_doc], a central place for finding `.gem`s and their associated documentation
* [Ruby docs][ruby_docs], a searchable hub for ruby and rails API

### Testing
* **Rspec**
  * [home][rspec_home]
  * [matchers][rspec_matchers]
  * [core][rspec_core]
  * [expectations][rspec_expectations]
  * [mocks][rspec_mocks]
  * [...and Rails][rspec_rails]
* [Capybara API][capybara_api]
* [FactoryGirl][factory_girl]
* [Faker API][faker_api]



## Web

### HTML
* [HTML 5 Semantics Tags][html5]
* [HTML elements][html_elements]
* [HTML tags][html_tags]
* [DOM events][dom_events]

### CSS
* [CSS 2.1 Property Table][css2_1]
* [CSS 3][css3], but you should probably stick with 2.1 mostly
* [CSS Specificity Calculator][css_specificity]
* [SASS][sass]


### JavaScript
* [Javascript Hub][javascript_main] on MDN
* [Underscore][underscore], utility functions for JS

### JQuery
* [JQuery API][jquery]
* [JQuery UI API][jquery_ui]

### Backbone
* [Backbone API][backbone_api]
* [Backbone annotated source][backbone_source]
* [Underscore API][underscore_api]


### SQL
* [Use the Index, Luke][index_luke], how to make effective use of SQL indices

### HTTP
* [HTTP methods][http_methods]: GET, POST, PATCH, etc.



## Frameworks

### Rails
* [Rails API][rails_api]
* [Rails Guides][rails_guides], click the dropdown on the top right for more.
  * There are a couple that are really good and merit reading all the way through.
* [Rails status codes][rails_status], semantic HTTP Status Codes

### Canvas
* [Canvas hub][canvas_hub], MDN
* [Intro to Canvas][canvas_book], an excellent book


## Tools
* [Homebrew][homebrew], painless compilation and updates
* [rbenv][], ruby environment manager
* Git
  * [Pro Git][pro_git]
  * [Git Ref][git_ref]
  * [Gitready][gitready], a reference of neat tasks/commands
  * [Git cheatsheet][git_cheatsheet], a really neat visual git reference
  * [Git immersion][git_immersion]
* rspec/testing
  * [Guard][rspec_guard]
  * [Faker][faker]
  * [Capybara][capybara]
  * [Shoulda matchers][shoulda]
* SQL
  * [Postgres][postgres]
  * [SQLite][sqlite]
    * [SQLite Command Line][sqlite_cli]
    * [SQL as understood by SQLite][sqlite_lang]
* Rails
  * [Foreigner][foreigner], for adding foreign key constraints to rails
  * [Draper][draper], for decorating model objects
* HTTP
  * [Postman][postman], a chrome extension for making HTTP requests
* HTML
  * [The SASS Way][sass_way], readings about using SASS
* [Bootstrap][bootstrap]
* [Chrome dev tools][chrome_dev]




## Style
* [Ruby style][ruby_style]
* [Better specs with Rspec][better_spec]
* [How I write SQL][sql_style]
* Rails conventions: model, view: singular; database, controller: plural
* [Crockford JavaScript][crockford]
* [JQuery Style Guide][jquery_style]



## Environment

### Shell
* [readline][readline]
* [bash programming][bash_prog]
* [advanced bash][bash_adv]
* unix shell



## Practice

### General/Math
* [Project Euler][project_euler]
* Coding challenges (several)

### Language specific
* [Dr Eval][dr_eval], JS specific game
* [SQL zoo][sql_zoo]
* [Ruby Warrior][ruby_warrior], AI practice in ruby
* [CSS Diner][css_diner], selector practice
* [jQuery Fundamentals][jquery_fun]

### Tools
* [Git "game"][git_game]

### Books
* Code Complete
* Design Patterns
* Effective Javascript



## Snippets
* Git reset authorship:  
`git filter-branch -f --env-filter "GIT_AUTHOR_NAME='your_full_name'; GIT_AUTHOR_EMAIL='your_email'; GIT_COMMITTER_NAME='your_full_name'; GIT_COMMITTER_EMAIL='your_email';" HEAD`
* create new rails project:
`rails new project_name --database postgresql`
* rails initial config (can probably be automated)
  * database.yml
  * Gemfile



[jquery]: http://api.jquery.com
[jquery_ui]: http://api.jqueryui.com
[html5]: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/HTML5_element_list
[html_elements]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element
[html_tags]: https://simon.html5.org/html-elements
[css2_1]: http://www.w3.org/TR/CSS21/propidx.html
[css3]: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
[css_specificity]: http://specificity.keegan.st/
[ruby_stdlib]: http://ruby-doc.org/stdlib-2.1.5/
[ruby_core]: http://ruby-doc.org/core-2.1.5/
[ruby_object]: http://ruby-doc.org/core-2.1.5/Object.html
[ruby_string]: http://ruby-doc.org/core-2.1.1/String.html
[ruby_enumerable]: http://ruby-doc.org/core-2.1.1/Enumerable.html
[ruby_array]: http://ruby-doc.org/core-2.1.1/Array.html
[ruby_hash]: http://ruby-doc.org/core-2.1.1/Hash.html
[rspec_matchers]: https://www.relishapp.com/rspec/rspec-expectations/v/2-14/docs/built-in-matchers
[rails_api]: http://api.rubyonrails.org/
[rails_guides]: http://guides.rubyonrails.org/
[javascript_main]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[underscore]: http://underscorejs.org/
[readline]: http://cnswww.cns.cwru.edu/php/chet/readline/readline.html
[ruby_doc]: http://www.rubydoc.info/
[ruby_docs]: https://rubydocs.org/
[tutorials_point]: http://www.tutorialspoint.com/index.htm
[ruby_io]: http://ruby-doc.org/core-2.1.5/IO.html
[ruby_file]: http://ruby-doc.org/core-2.1.5/File.html
[ruby_style]: https://github.com/bbatsov/ruby-style-guide
[pro_git]: http://git-scm.com/book/en/v2
[git_ref]: http://gitref.org/
[gitready]: http://gitready.com/
[git_cheatsheet]: http://www.ndpsoftware.com/git-cheatsheet.html
[git_immersion]: http://gitimmersion.com/
[git_game]: http://pcottle.github.io/learnGitBranching/?NODEMO
[rspec_home]: https://www.relishapp.com/rspec
[better_spec]: http://betterspecs.org/
[rspec_core]: https://github.com/rspec/rspec-core
[rspec_expectations]: https://github.com/rspec/rspec-expectations
[rspec_mocks]: https://github.com/rspec/rspec-mocks
[rspec_guard]: https://github.com/guard/guard-rspec
[sql_style]: http://www.craigkerstiens.com/2012/11/17/how-i-write-sql
[postgres]: http://postgresapp.com/
[sql_zoo]: http://sqlzoo.net/wiki/Main_Page
[index_luke]: http://use-the-index-luke.com/
[sqlite]: http://www.sqlite.org/
[sqlite_cli]: http://www.sqlite.org/cli.html
[sqlite_lang]: http://www.sqlite.org/lang.html
[foreigner]: https://github.com/matthuhiggins/foreigner
[http_methods]: http://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html
[postman]: https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm?hl=en
[draper]: https://github.com/drapergem/draper
[bootstrap]: http://getbootstrap.com/
[sass_way]: http://thesassway.com/
[sass]: http://sass-lang.com/guide
[rspec_rails]: http://everydayrails.com/2012/03/12/testing-series-rspec-setup.html
[rails_status]: http://guides.rubyonrails.org/layouts_and_rendering.html#the-status-option
[capybara]: https://github.com/jnicklas/capybara
[factory_girl]: https://github.com/thoughtbot/factory_girl
[faker]: https://github.com/stympy/faker
[backbone_api]: http://backbonejs.org
[backbone_source]: http://backbonejs.org/docs/backbone.html
[underscore_api]: http://underscorejs.org
[dr_eval]: http://alexnisnevich.github.io/untrusted/
[ruby_warrior]: https://www.bloc.io/ruby-warrior/
[project_euler]: https://projecteuler.net
[homebrew]: http://brew.sh
[rbenv]: https://github.com/sstephenson/rbenv
[faker_api]: http://www.rubydoc.info/github/stympy/faker/master/frames
[capybara_api]: http://www.rubydoc.info/github/jnicklas/capybara#The_DSL
[shoulda]: https://github.com/thoughtbot/shoulda-matchers
[crockford]: http://javascript.crockford.com/code.html
[jquery_style]: http://contribute.jquery.org/style-guide/js/
[css_diner]: http://flukeout.github.io/
[chrome_dev]: https://developer.chrome.com/devtools
[canvas_book]: http://joshondesign.com/p/books/canvasdeepdive/chapter01.html
[dom_events]: https://developer.mozilla.org/en-US/docs/Web/Events
[jquery_fun]: http://jqfundamentals.com/
[bash_prog]: http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html
[bash_adv]: http://www.tldp.org/LDP/abs/html/
[canvas_hub]: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API
