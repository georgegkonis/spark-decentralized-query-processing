# Spark Decentralized Query Processing & Optimization

This project is part of the "Distributed Data Processing Technologies" course offered by
the [Department of Computer Engineering & Informatics](https://www.ceid.upatras.gr/) at
the [University of Patras](https://www.upatras.gr/). The objective of the project is to design and implement a
decentralized query processing and optimization system built on top of Apache Spark. The system will efficiently
distribute query plans across multiple nodes, enabling parallel execution and improving performance in a decentralized
manner. Additionally, the system will include query optimization capabilities by pushing down filters and projections to
data sources, thereby minimizing data transfer and enhancing overall query efficiency.

## Installation

To set up the environment for this project, follow these steps:

1. Ensure you have `conda` installed. If not, you can download and install it
   from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

2. Navigate to the project directory.

3. Create the environment using the `environment.yml` file:
    ```sh
    conda env create -f environment.yml
    ```

4. Activate the environment:
    ```sh
    conda activate spark-env
    ```

5. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

You should now be able to run the notebooks and scripts in this project.

## Contributing

Due to the academic nature of this project, contributions are not accepted.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Authors

- [George Gkonis](https://github.com/georgegkonis)