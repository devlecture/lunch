<pre>
…or create a new repository on the command line
echo "# lunch" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/devlecture/lunch.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/devlecture/lunch.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

…github 의 프로젝트를 로컬로 처음 가져올때
git clone https://github.com/devlecture/lunch.git


…pull
git pull https://github.com/devlecture/lunch.git


…로컬의 프로젝트를 github에 올릴때
git add .
git commit -m "test"
git push -u origin main




</pre>