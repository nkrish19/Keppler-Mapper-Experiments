# Keppler Mapper Experiments

**Note:**

You might need to install git lfs. Head here for more details:

https://git-lfs.github.com/

https://github.com/git-lfs/git-lfs/blob/main/docs/man/git-lfs-migrate.1.ronn?utm_source=gitlfs_site&utm_medium=doc_man_migrate_link&utm_campaign=gitlfs


## Running the Project

1. Clone or download this repository.

2. If you find that some files in your working directory have been replaced with Git LFS pointers, then the working copies of these files can be repopulated with their full expected contents by using

```
git lfs checkout
```

3. Create a virtual environment.

```
virtualenv env
```

4. Activate the environment.
```
source env/bin/activate
```
* For Windows:
```
env\Scripts\activate
```

5. Install project dependencies.
```
pip3 install -r requirements.txt
```

