# youngilkim0818.github.io
Install Git

Github Page started
1. Create a new repository
2. git clone <repo_name> <path>
3. Create a file # index.html
4. git status, git add, git commit -m "message"
5. Create Personal Access Token
6. git push origin main

Install Jekyll

1. jekyll -v # Check jekyll
2. jekyll new . --force # Install Jekyll on current directory
3. bundle exec jekyll serve # Start Jekyll
4. bundle exec webrick # webrick(LoadError)
5. localhost:4000
6. Change file _config.yml
7. bundle exec jekyll serve #Restart jekyll
8. git rm index.html, git add *, git commit -m "message", git push origin main
9. Check <username>.github.io

Post Upload
1. Create a new file
2. git add, git commit, git push
3. Check result

New theme for our blog
1. Go http://jekyllthemes.org/ and find theme
2. git clone
3. Overwrite them carefully
4. git add / git commit / git push

Customize blog - add comments
1. Sign up Disqus and complete setup
2. add lines on _config.yml
3. Add and fix lines on _layouts/post.html
4. Check src
5. Add line comments: true on _posts if you want to allow comments

Analytic blog
1. Sign up Google Analytics
2. Add lines on _includes/head.html
3. Add tracking code on files
4. git add, git commit, git push 
