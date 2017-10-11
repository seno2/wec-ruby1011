# wec-ruby1011
## 実行ログ
seno2:~/workspace $ mkdir wec-ruby1011
seno2:~/workspace $ cd wec-ruby1011
seno2:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
seno2:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
seno2:~/workspace/wec-ruby1011 (master) $ git add README.md
seno2:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) b8beb36] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
seno2:~/workspace/wec-ruby1011 (master) $ git remote add origin https://github.com/seno2/wec-ruby1011.git
seno2:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com':  
Password for 'https://github.com': 
remote: Anonymous access to seno2/wec-ruby1011.git denied.
fatal: Authentication failed for 'https://github.com/seno2/wec-ruby1011.git/'
seno2:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com':      
Password for 'https://github.com': 
remote: Anonymous access to seno2/wec-ruby1011.git denied.
fatal: Authentication failed for 'https://github.com/seno2/wec-ruby1011.git/'
seno2:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
seno2:~/workspace/wec-ruby1011 (master) $  pry
[1] pry(main)> 
seno2:~/workspace/wec-ruby1011 (master) $  sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installed
seno2:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
seno2:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Resolving dependencies...
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
seno2:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
seno2:~/workspace/wec-ruby1011 (master) $ bundle install
Fetching gem metadata from https://rubygems.org/.............
Fetching version metadata from https://rubygems.org/.
Resolving dependencies...
Using bundler 1.15.4
Fetching mini_portile2 2.3.0
Installing mini_portile2 2.3.0
Fetching nokogiri 1.8.1
Installing nokogiri 1.8.1 with native extensions
Bundle complete! 1 Gemfile dependency, 3 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
seno2:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに強い専門