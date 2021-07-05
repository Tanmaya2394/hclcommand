# hclcommand 
jenkins installing:
    1  vi /etc/cloud/cloud.cfg
    2  adduser hcladmin
    3  passwd hcladmin
    4  usermod –aG wheel hcladmin
    5  usermod -aG wheel hcladmin
    6  exit
    7  cd branchingproject/
    8  history
    9  touch secretfile
   10  git status
   11  ls
   12  git add .
   13  git status
   14  git commit -m "secret file by mistake added"
   15  git log
   16  git reset
   17  git status
   18  git commit --amend
   19  git log
   20  history
   21  echo "this is an README file" > Readme.md
   22  cat Readme.md
   23  git add Readme.md
   24  git commit -m "README file added"
   25  git status
   26  git checkout -b "branch_to_create_merge_conflict"
   27  git branch
   28  vi Readme.md
   29  git add Readme.md
   30  git commit -m "Edit made to readme on master branch"
   31  git branch
   32  git merge
   33  git checkout master
   34  vi Readme.md
   35  git add .
   36  git commit -m "Edit made on the readme on master branch"
   37  history
   38  git commit -m "README file added"
   39  git status
   40  git checkout -b "branch_to_create_merge_conflict"
   41  git branch
   42  git checkout master
   43  git branch
   44  history
   45  cat Readme.md
   46  vi Readme.md
   47  git status
   48  git merge --abort
   49  git status
   50  history
   51  ls -la
   52  ~git -version
   53  yum install git
   54  git --version
   55  history
   56  mkdir branchingproject
   57  cd nranchingproject/
   58  cd branchingproject/
   59  touch DS_Store
   60  touch Calcy.py
   61  git init
   62  git add .
   63  git commit -m "framework for calcy project"
   64  git log
   65  vi Calcy.py
   66  git add.
   67  git add .
   68  git commit -m "Branching project started"
   69  git log
   70  history
   71  clear
   72  git branch
   73  git branch calc-divide
   74  git branch
   75  git checkout calc-divide
   76  git branch
   77  vi Calcy.py
   78  git checkout calc-divide
   79  git add .
   80  git commit -m "added divide functionality"
   81  git branch
   82  git log
   83  git branch -a
   84  history
   85  git remote add origin https://github.com/Tanmaya2394/hclbranchinge                                                                                              xcercise.git
   86  git checkout master
   87  git push -u origin master
   88  git checkout calc-divide
   89  git push origin calc-divide
   90  history
   91  git branch -a
   92  git branch
   93  git checkout master
   94  git branch
   95  git merge calc-divide
   96  git push -u origin master
   97  git branch -a
   98  git pull
   99  git branch -d calc-divide
  100  git branch -a
  101  git pull
  102  git push origin -delete calc-divide
  103   git push origin --delete calc-divide
  104  git branch -a
  105  history
  106  git reflog
  107  yum install java
  108  javac
  109  yum install jre
  110  yum install wget -y
  111  wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/r                                                                                              edhat-stable/jenkins.repo
  112  rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
  113  yum install jenkins java-11-openjdk-devel
  114  systemctl daemon-reload
  115  jenkins --version
  116  systemctl start jenkins
  117  systemctl enable jenkins
  118  systemctl status jenkins
  119  history
