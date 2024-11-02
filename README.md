# Build & Publish Your Own Go Package

- Brian Morrison's tutorial: [Build & Publish Your Own Go Package](https://youtu.be/KNHEXOoV-H4?si=a0V8kvurhyZmQW6Z)

- create and go to folder for new package

- create go.mod file:  ```go mod init github.com/user-name/package-name```

- create main.go with new package name and desired content

- create new GitHub repository named as package-name

- copy the URL of new repository

- git init

- git add .

- git commit -m "first commit"

- git branch -M main

- git remote add origin https://github.com/user-name/colored.git

- git push -u origin main

- add annotated tag locally: ```git tag -a v1.0.0 -m "my version 1.0.0"```

- upload a single tag to GitHub: ```git push origin "v1.0.0"```

- upload all tags to GitHub: ```git push origin --tags```

# Utilising new Package

- create and go into new directory

- go mod init ```package-name```

- go get -u github.com/user-name/package-name

- create main.go and

- import "github.com/username/package-name"


