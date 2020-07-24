# Northern Change Lab Repo

Add whatever code you think is useful for remote sensing data analysis and misc. coding.

## Using git submodeles

We are experimenting with git submodules to link working repos with this one so that changes can be synchronized without having to create copies of working scripts here. A better solution might be github project boards.

### To add a sub-repository:
``` 
$ git submodule add https://github.com/example/url.git
```
Then push as normal.

### To clone from a repository with sub-repositories:

Either use
``` 
$ git clone https://github.com/example/url.git
& git submodule update --init
```
or
```
$ git clone --recurse-submodules https://github.com/example/url.git
```

If you clone as normally, the subrepos will show up as empty directories, so if you want to actually have the scripts, you will need to follow the commands above.

Minute details on git submodule available [here](https://git-scm.com/book/en/v2/Git-Tools-Submodules).