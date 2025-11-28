# FEDF Lab End Sem Project

question
->Create two branches and merge them to main branch

Code:-
1     mkdir FEDF-lab-endsem
2     cd FEDF-lab-endsem
3     git init
4     git remote add origin https://github.com/Madhu696969/FEDF-lab-endsem.git
5     git branch -M main
6     git push -u origin main
7     git checkout -b Course-Registration
8     echo "This is Course Registration feature" >> course.txt
9     git add .
10    git commit -m "Add Course Registration feature"
11    git checkout main
12    git merge Course-Registration
13    git push
14    git checkout -b Event-Calendar
15    echo "This is Event Calendar feature" >> event.txt
16    git add .
17    git commit -m "Add Event Calendar feature"
18    git checkout main
19    git merge Event-Calendar
20    git push



