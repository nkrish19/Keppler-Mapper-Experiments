# Keppler Mapper Experiments

**Note:**

You might need to install git lfs to succesfully download the mnist_x_processed_10_10 file since it exceeds 100mb size limit. Head here for more details:

https://git-lfs.github.com/

https://github.com/git-lfs/git-lfs/blob/main/docs/man/git-lfs-migrate.1.ronn?utm_source=gitlfs_site&utm_medium=doc_man_migrate_link&utm_campaign=gitlfs


## Running the Project

1. Clone or download this repository.

2. If you find that some files in your working directory have been replaced with Git LFS pointers, then the working copies of these files can be repopulated with their full expected contents by using the below mentioned command or you can simply download [mnist_x_processed_10_10](https://github.com/nkrish19/Keppler-Mapper-Experiments/files/7524581/mnist_x_processed_10_10.zip) instead.

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

Our code is a further experimentation on the work done by [Kim _et al._](https://arxiv.org/abs/2002.02778) 

https://github.com/jisuk1/pllay
