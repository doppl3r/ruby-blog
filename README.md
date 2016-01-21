# Ruby Blog
#### References
This was completely based off the Ruby on Rails 'Getting Started' guide. I did not write, nor do I clame any ownership to this code.
- Tutorial: [http://guides.rubyonrails.org/getting_started.html](http://guides.rubyonrails.org/getting_started.html)

#### Quick Installation (Windows)
- Install Ruby (I used the 2.1.7 installer): http://rubyinstaller.org/downloads/
- Install sqlite3: http://www.tutorialspoint.com/sqlite/sqlite_installation.htm

#### IDE - Sublime 3
- Settings: https://mattbrictson.com/sublime-text-3-recommendations
 
#### Issues I Ran Into & Resolved
- "TypeError: Object doesn't support this property or method" : [Windows Fix](http://stackoverflow.com/a/28317677)
- "ExecJS::ProgramError in Pages#home?" : [Windows Fix](http://stackoverflow.com/a/30460828)

#### Starting the server
- Open the Command Prompt (Window + r, then type 'cmd')
- Set current directory: cd your-directory\blog\
- Launch server: ruby bin\rails server
- Open browser and enter the address http://localhost:3000