# @WeRateDogs - Data Wrangling Project

The goal of the project is to wrangle all the data related to @WeRateDogs twitter archive details collected from various sources, so that meaningful insights can be inferred from the twitter data.



## Getting Started

1. Clone the git repository to your local machine
2. Create the Conda Environment to install the necessary packages for this project by using the command: conda env create --file environment.yml
3. Run 'jupyter notebook' to open 'wrangle_act.ipynb' file


### Prerequisites

- Anaconda
- Additionally you need twitter API tokens. Once you have them make sure, you have a file named 'twitter_secrets.txt' which contain the following details. *Make sure to replace &lt;value&gt; with your secret values*

```
{
"consumer_api_key":"<value>",
"consumer_api_secret":"<value>",
"access_token":"<value>",
"access_token_secret":"<value>"
}
```

### Installing

[Anaconda Installation Guide](https://conda.io/docs/user-guide/install/index.html)

## Authors

* **Karthick Mahalingam** - [KMPrep](https://github.com/KMPrep)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Udacity - Data Analyst Nanodegree
* To all folks, who have created awesome pandas documentation
