
## Homework Git, part 1
**1. Create a new repository on your personal account and call it JSON.**

**2. Clone this repository to create a local copy on your computer.**
```
$ git clone git@github.com:AnDerova/JSON.git
```

**3. Create a new file "new.json" into your local repository.**
```
$ touch new.json
```

**4. Stage a "new.json" for commit.**
```
$ git add new.json
```
**5. Commit a file that you've staged.**
```
$ git commit -m 'Create new.json'
```
**6. Push a file in your remote repository on GitHub.**
```
$ git push -u origin main
```
**7. Edit a "new.json", to add information about yourself (name, age, number of pets, desired salary).**
```
$ vim new.json

$ cat new.json
{
        "first name": "Anastasiia",
        "last name": "Derova",
        "age": 38,
        "pets": 0,
        "salary": 10000
}
```
**8. Push the changes in your remote repository to GitHub.com.**
```
$ git commit -a -m 'Add info about person into new.json'
$ git push
```
**9. Create a new file "preferences.json" into your local repository.**
```
$ touch preferences.json
```
**10. Edit a "preferences.json", to add information about your preferences (favorite movie, TV shows, food, season, country you'd like to visit).**
```
$ vim preferences.json

$ cat preferences.json
{
        "favorite movie": "Forrest Gump",
        "favorite TV shows": "Rick and Morty",
        "favorite food": "Mango",
        "favorite season": "Spring",
        "country": "Iceland"
}
```
**11. Create a new file "sklls.json" into your local repository, add information about your skills**
```
$ touch skills.json
$ vim skills.json
$ cat skills.json
{
        "1": "Terminal",
        "2": "GitHub",
        "3": "Postman",
        "4": "SQL",
        "5": "DevTools",
        "6": "Mobile testing"
}
```
**12. Push the modified files in your remote repository to GitHub.com.**
```
$ git add . && git commit -m 'Create preferences.json and skills.json' && git push
```
**13. Create a new file "bug_report.json" directly on GitHub.**

**14. Click Commit changes.**

**15. Edit a file "bug_report.json" directly on GitHub in your repository, add bug report.** 
```
{
        "id": 1,
        "severity": "Major",
        "environment": "Win 10 Chrome 107 108 109 110 111 112 113 114",
        "title": "The English version of the page 'Privacy Policy' in 'Sign up' form is linked to the link 'Privacy Policy' from any language except EN, DE",
        "steps":
                {
                "1": "Navigate to capital.com",
                "2": "Select any language exсept EN, DE",
                "3": "Click button 'Trade'",
                "4": "Click link 'Privacy policy'"
                }

        "ER": "The 'Privacy policy' page is opened in selected language",
        "AR": "The 'Privacy policy' page is opened in English",
        "attach": "Link",
        "comments": "Null"
}
```

**16. Save changes in your remote repository.**

**17. Keep your local repository in sync with your remote repository.**
```
$ git pull
$ ls -la
```
