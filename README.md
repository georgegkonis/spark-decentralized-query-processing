# Spark Decentralized Query Processing & Optimization

This project is a part of the course "Distributed Data Processing Technologies" at the "University of Patras". The goal
of this project is to implement a decentralized query processing and optimization system on top of Apache Spark. The
system will be able to process queries in a decentralized manner, by distributing the query plan to multiple nodes and
executing the plan in parallel. The system will also be able to optimize the query plan by pushing down filters and
projections to the data sources.

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