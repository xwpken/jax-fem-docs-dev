## Installation

Create a conda environment from the given [`environment.yml`](https://github.com/deepmodeling/jax-fem/blob/main/environment.yml) file and activate it:

```bash
conda env create -f environment.yml
conda activate jax-fem-env
```

Install JAX
- See jax installation [instructions](https://github.com/jax-ml/jax?tab=readme-ov-file#installation). Depending on your hardware, you may install the CPU or GPU version of JAX. Both will work, while GPU version usually gives better performance.


Then there are two options to continue:

### Option 1

Clone the repository:

```bash
git clone https://github.com/deepmodeling/jax-fem.git
cd jax-fem
```

and install the package locally:

```bash

pip install -e .
```

### Option 2

Install the package from the [PyPI release](https://pypi.org/project/jax-fem/) directly:

```bash
pip install jax-fem
```
