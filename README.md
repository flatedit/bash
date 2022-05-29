
![logo.flatedit.com](https://logo.flatedit.com/1/cover.png)

# [bash.flatedit.com](https://bash.flatedit.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/bash/edit/main/DOCS/MENU.md) 

+ [Strona informacyjna: www.flatedit.com](https://www.flatedit.com/)
+ [Dokumentacja - docs.flatedit.com](https://docs.flatedit.com/)
+ [Logotyp: logo.flatedit.com](https://logo.flatedit.com/)
+ [Przykłady - examples.flatedit.com](http://examples.flatedit.com)

+ [LICENSE](../LICENSE)



## About flatedit [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/bash/edit/main/DOCS/ABOUT.md)

creating documentation is not easy in hundreds of small projects, where are dependencies
we need some simple tool to manage the documentation from the terminal, during programming

this is the FlatEdit:
+ file of projects list: readme.txt



## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/CONTRIBUTION.md)


Solutions for development:

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```


Install package list after created project
```bash
curl https://raw.githubusercontent.com/apipackage/bash/main/apipackage.sh -o apipackage
echo "https://github.com/letwhois/bash apidsl/apidsl/bash letwhois" >> "apipackage.txt"
./apipackage install
```

Edit documentation with flatedit
```bash
echo "#!/bin/bash" > "readme"
echo "./flatedit/readme.sh readme.txt" > "readme"
echo "./DOCS/MENU.md" >> "readme.txt"
echo "./DOCS/ABOUT.md" >> "readme.txt"
echo "./DOCS/FOOT.md" >> "readme.txt"
```

### Update documentation

```bash
 ./readme
```

### Config project file

The config file: **.apifork** can be another, e.g. **apifork.txt**

Just change the first line in  **.apifork** on **apifork.txt**
```bash
apifork.txt
```



### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```

### update

```bash
./apifork update
```


### remove

```bash
./apifork remove
```


## Documentation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/DOCS.md)

creating documentation is not easy in hundreds of small projects, where are dpendencies
we need some simple tool to manage the documentation from the terminal, during programming

this is the frlatedit:
+ file of projects list: readme.txt

### Dependencies

projects list [**readme1.txt**](readme1.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme1.txt
```

### Comments

With comments not to load this file

projects list [**readme2.txt**](readme2.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme2.txt
```


### Logs 

Show not- & working/existing files


projects list [**readme3.txt**](readme3.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme3.txt
```


# Tags

+ scripts
+ language

---

+ [edit](https://github.com/flatedit/bash/edit/main/README.md)
+ [flatedit/bash](https://github.com/flatedit/bash)
