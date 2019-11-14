# ml-tests

### Use virtual environment (optional)

Create virtual environment

```shell
$ python3 -m venv myenv
```

Activate your virtual environment

```shell
$ source myenv/bin/activate
```

### Install dependencies

```shell
pip3 install -r requirements
```

### Create a new ipython kernel to use Jupyter Notebook inside your virtual environment

```shell
python3 -m ipykernel install --user --name=myenv
```

### Launch the Notebook

```shell
jupyter notebook pca_test.ipynb
```

**Note**:  
If you are using a virtual environment you have to change kernel inside the notebook by clicking *Kernel* in the top navbar, then *Change kernel*, then choose the kernel you created before
