# References
A repo of subject-collected references that I find useful.

Ultimately, this sort of thing is deeply personal, but maybe this is useful to someone else.



## General
* [Tutorialspoint](tutorials_point), a hub for many different resources



## Languages

### Ruby (version 2.1.5)
* [Ruby Standard Library](ruby_stdlib)
* [Ruby Core API](ruby_core)
* **Classes**
  * [Object](ruby_object): everything in ruby is an object.
  * [String](ruby_string)
  * [Enumerable](ruby_enumerable): a common mixin for enumerable objects.
  * [Array](ruby_array)
  * [Hash](ruby_hash)
  * [File](ruby_file) / [IO](ruby_io)
* [Ruby doc](ruby_doc), a central place for finding docs for `.gem`s
* [Ruby docs](ruby_docs), a searchable hub for ruby and rails API

### Testing (Rspec)
* [Rspec home](rspec_home)
* [Rspec matchers](rspec_matchers)
* [Rspec core](rspec_core)
* [Rspec expectations](rspec_expectations)
* [Rspec mocks](rspec_mocks)



## Web

### HTML
* [HTML 5 Semantics Tags](html5)
* [HTML tags](html_tags)

### CSS
* [CSS 2.1 Property Table](css2_1)
* [CSS 3](css3)
* [CSS Specificity](css_specificity) calculator

### JavaScript
* [Javascript Hub](javascript_main)
* [Underscore](underscore)

### JQuery
* [JQuery API](jquery)
* [JQuery UI API](jquery_ui)

### SQL
* [Use the Index, Luke](index_luke)



## Frameworks

### Rails
* [Rails API](rails_api)
* [Rails Guides](rails_guides), click the dropdown on the top right for more.

### Canvas



## Tools
* Homebrew
* rbenv
* Git
  * [Pro Git](pro_git)
  * [Git Ref](git_ref)
  * [Gitready](gitready), a reference of neat tasks/commands
  * [Git cheatsheet](git_cheatsheet), a really neat visual git reference
  * [Git immersion](git_immersion)
* rspec
  * [Guard](rspec_guard)
* [Postgres](postgres)
* [SQLite](sqlite)
  * [SQLite Command Line](sqlite_cli)
  * [SQL as understood by SQLite](sqlite_lang)
* [Foreigner](foreigner), for adding foreign key constraints to rails


## Style
* [Ruby style](ruby_style)
* [Better specs with Rspec](better_specs)
* [How I write SQL](sql_style)



## Environment

### Shell
* [readline](readline)



## Practice

### General/Math
* Project Euler

### Language specific
* Dr Eval, JS specific game

### Tools
* [Git "game"](git_game)
* [SQL zoo](sql_zoo)

### Books
* Code Complete
* Design Patterns

## Snippets
* Git reset authorship:  
`git filter-branch -f --env-filter "GIT_AUTHOR_NAME='your_full_name'; GIT_AUTHOR_EMAIL='your_email'; GIT_COMMITTER_NAME='your_full_name'; GIT_COMMITTER_EMAIL='your_email';" HEAD`



[jquery]: http://api.jquery.com
[jquery_ui]: http://api.jqueryui.com
[html5]: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/HTML5_element_list
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
