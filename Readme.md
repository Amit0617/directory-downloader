# directory-downloader
An extension to gh CLI for a very trivial but missing feature.

### Installation
One liner installation:
```shell
git clone https://github.com/Amit0617/directory-downloader.git; cd directory-downloader; chmod u+x gh-down.sh; sudo ln -s -T $(pwd)/gh-down.sh /usr/bin/gh-down
```

### Usage
```shell
gh-down username/repositoryname path/to/directory
```

##### Example
Let say you want to download `ABAP` directory which is in `samples` in https://github.com/octocat/linguist

```shell
gh-down octocat/linguist samples/ABAP
```

That's it!

Note: It will download the files inside the given directory in your current directory and to keep it minimal it downloads files only and should be skipping if it contains more directory inside the given directory.