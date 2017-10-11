# wec-ruby1011
## 実行ログ
iso1:~/workspace $ mkdir wec-ruby1011
iso1:~/workspace $ mkdir wec-ruby1011
iso1:~/workspace $ cd wec-ruby1011/iso1:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >    > README.md
iso1:~/workspace/wec-ruby1011 $ git initInitialized empty Git repository in /home/ubuntu/worksp    ace/wec-ruby1011/.git/
iso1:~/workspace/wec-ruby1011 (master) $ git add README.md
iso1:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) 73c34ab] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
iso1:~/workspace/wec-ruby1011 (master) $ git remote add origin git@github.com:iso-1/wec-ruby1011.git
iso1:~/workspace/wec-ruby1011 (master) $ git remote add origin git@github.com:iso-1/wec-ruby1011.git
fatal: remote origin already exists.
iso1:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of known hosts.
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
iso1:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
iso1:~/workspace/wec-ruby1011 (master) $ git status
iso1:~/workspace/wec-ruby1011 (master) $ git add README.md
iso1:~/workspace/wec-ruby1011 (master) $ git add READMisiiso1:~/workspace/wec-ruby1011 (master) $ git init
Reinitialized existing Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
iso1:~/workspace/wec-ruby1011 (master) $ git add README.md
iso1:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
iso1:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> 
iso1:~/workspace/wec-ruby1011 (master) $ sudo gem installbundler
ERROR:  While executing gem ... (Gem::CommandLineError)
    Unknown command installbundler
iso1:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installed
iso1:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
iso1:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Resolving dependencies...
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
iso1:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> require "nokogiri"
LoadError: cannot load such file -- nokogiri
from /usr/local/rvm/rubies/ruby-2.4.0/lib/ruby/2.4.0/rubygems/core_ext/kernel_require.rb:55:in `require'
[2] pry(main)> 
iso1:~/workspace/wec-ruby1011 (master) $ bundle install
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
iso1:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rbiso1:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rbnokogiri.rb:2:in `<main>': undefined method `repuire' for main:Object (NoMethodError)
Did you mean?  require
iso1:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲーム クリエイターに強い専門学校"
iso1:~/workspace/wec-ruby1011 (master) $ 