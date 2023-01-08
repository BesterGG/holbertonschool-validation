## Prerequisites

Requisites to build an hugo website:

- Hugo
- git
- Homebrew
- curl

### Before to start

Update all the dependences with the command line

```
apt-get update
```

You can start to install:

### Curl

```
apt-get install curl
```

### Git

```
apt-get install git
```

### Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Hugo

execute the next command:

```
brew install hugo
```

## Lifecycle

There are diferents steps:

- Clean the build
- Create posts
- Make a new build
- Help

### Clean

```
make clean
```

### Create posts

```
make POST_NAME=file_name_of_post POST_TITLE="Title of the new post" post
```

### Make a new build

```
make build
```

### Help
```
make help
```
