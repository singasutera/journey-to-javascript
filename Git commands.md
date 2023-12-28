# Git commands

Initializing new repository.
Username and e-mail will be visible in commit history.

```sh
git init
git config user.name "Sonora"
git config user.email "supernaturalsonora@gmail.com"

git remote add origin {link_to_repository}
```

Daily commit and push.

```sh
git add .
git commit -m "Message to accompany your commit."
git push -u origin master
```

It's "master" because you put "master" as "main" in this specific repo.

## Notes from dearest trainer Mas Franklin

Initiate Git local repository

```sh
git init
```

Add remote repository

```sh
git remote add origin {remote_repository}
```

Example

```sh
git remote add origin github.com/tamboto2000/hello-world.git
```

Identity configuration for defining the author of this repository

```sh
git config user.name "Franklin Collin Tamboto"
git config user.email "tamboto2000@gmail.com"
```

Add changes

```sh
git add {folder/files}
```

Example to add all folder and files

```sh
git add .
```

Example to add specific files

```sh
git add ./main.go
```

or for multiple specific files

```sh
git add ./hello-world.go ./main.go ./config.json
// etc.
```

Example to add specific directory

```sh
git add ./configs/
```

or

```sh
git add ./configs
```

Example to add files from inside a folder

```sh
git add ./configs/dev.json
```

Git commit for storing changes on local repository

```sh
git commit -m {message}
```

Example

```sh
git commit -m "Call method fmt.Println()"
```

Git push for storing changes on remote repository

```sh
git push
```

or with ```-u``` option

```sh
git push -u {remote_repository} {branch}
```

Example

```sh
git push -u origin main
```
