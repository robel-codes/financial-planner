# Financial-Planner

This application contains two financial analysis tools. The first allows the user to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emerency fund click on a desired National Park and see the list of the campgrounds for that park, and some other useful information about the park.
The second tool is a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfoio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. You will then use the Monte Carlo data to calculate the expected portfolio returns given a specificc intial investment amount.

![GitHub last commit](https://img.shields.io/github/last-commit/robel-codes/financial-planner) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/robel-codes/financial-planner) ![GitHub watchers](https://img.shields.io/github/watchers/robel-codes/financial-planner?label=Watch&style=social) ![GitHub top language](https://img.shields.io/github/languages/top/robel-codes/financial-planner) ![GitHub license](https://img.shields.io/badge/license-MIT-blueyellow) <br>

## User Story

As a financial planner tool,
users will be able to use this tool to visualize teir current savings. The users can then determine if they have enough reserves for an emergency fund.
This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulation

## Table of Contents

1. [Project Links](#Project-Links)
1. [Screenshots](#Screenshot)
1. [Installation](#Installation)
1. [Contribution Guidelines](#Contribution-Guidelines)
1. [Project Team](#Project-Team)
1. [Questions](#Questions)
1. [License](#License)

## Project Links

[Repo Link](https://github.com/robel-codes/financial-planner) <br>

## Screenshots

#### Api Call Preview

![Api Calls Preview](/images/eth_api.png)

## Instructions

Add a .env file and add this code with your Alpaca credintals to make an API call via Alpaca SDK

```
 * ALPACA_API_KEY = "your-alpaca-api-key"
 * ALPACA_SECRET_KEY='your-alpaca-secret-key'
```

## Contribution Guidelines:

```
Feel free to contribute to this repo by creating issues or sending an email to any of the contributors in the list below.
```

## Project Team

[Robel Gebremeskel](https://github.com/robel-codes) <br>

## Questions

<details>
    <summary>Contact</summary>
    rofikre@yahoo.com <br>
</details>

## License

#### Distributed under the MIT License. See [Choose A License](https://choosealicense.com/) for more details.
