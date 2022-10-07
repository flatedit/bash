
## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/CONTRIBUTION.md)


Solutions for development:

### Install

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/flatedit/bash/main/flatedit.sh -o flatedit
echo "https://github.com/flatedit/bash.git flatedit" > "flatedit.dev.txt"
./flatedit install flatedit.dev.txt
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
 ./flatedit
```

### Config project file

The config file: **.flatedit** can be another, e.g. **flatedit.txt**

Just change the first line in  **.flatedit** on **flatedit.txt**
```bash
flatedit.txt
```


