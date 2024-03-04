# Processing MEA Data LMOS

This document provides instructions on how to run the `processing_mea_data_lmos.ipynb` notebook, which is used for processing MEA (Multi-Electrode Array) data in the LMOS (Local Multi-Unit Spiking) format.

## Prerequisites

Before running the notebook, make sure you have the following prerequisites installed:

- Python 3.x
- Jupyter Notebook

## Installation

To install the necessary dependencies, you can use the following command:
Apologies for the confusion. Here's a more specific outline based on your requirements:

1. **Create a Conda Environment**: Use the `environment.yaml` file to create a conda environment named `neural_analysis_env`. This file should list all the dependencies for your project.

```bash
conda env create -f environment.yaml
```

2. **Activate the Conda Environment**: Once the environment is created, activate it.

```bash
conda activate neural_analysis_env
```

3. **Check the Environment's Dependencies**: After activating the environment, check its dependencies to ensure everything is installed correctly.

```bash
conda list
```

4. **Navigate to the Directory Containing `setup.py`**: Change your current directory to the one containing the `setup.py` file. Let's assume the directory is `neural_analysis`.

```bash
cd neural_analysis
```

5. **Run `setup.py`**: Install the Python package into your active environment.

```bash
python setup.py install
```

6. **Verify Installation**: Check that the package was installed correctly. You should see `neural_analysis` in the list of installed packages.

```bash
conda list
```

7. **Use the Environment**: Now you can start using this environment for your project. Any Python scripts you run will use the Python interpreter and packages from this environment.

Remember to replace `environment.yaml` with your actual yaml file's name and `neural_analysis` with the actual path to the directory containing your `setup.py` file.



## Usage

1. Open a terminal and navigate to the `src` directory:

    ```bash
    cd /path/to/mua_analysis/src
    ```

2. Start the Jupyter Notebook server:

    ```bash
    jupyter notebook
    ```

3. In your web browser, open the notebook `processing_mea_data_lmos.ipynb`.

4. Follow the instructions in the notebook to process the MEA data.

## Troubleshooting

If you encounter any issues while running the notebook, try the following:

- Make sure you have the latest version of Python and Jupyter Notebook installed.
- Check that all the required dependencies are installed by running `pip list`.
- Verify that the MEA data files are in the correct format and located in the specified directory.

## Conclusion

By following these instructions, you should be able to run the `processing_mea_data_lmos.ipynb` notebook and process MEA data in the LMOS format.

For any further assistance, please refer to the documentation or reach out to the project maintainers.