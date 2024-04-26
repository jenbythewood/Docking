#Docking Fullstack

# Requirements

- [x] User can create an account with an email address and password input field
- [x] User receives a success message after creating an account
- [x] After creating an account, email address or username appears in the top
    right corner
- [x] User can log in to an account with an email address/password or OAuth
- [x] User can log out of an account
- [x] User can deposit money
- [x] Total balance updates according to deposit amount
- [x] User can withdraw money
- [x] Total balance updates according to withdrawal amount
- [x] The total balance amount and any other user input persists through
    different user sessions
- [x] Logging out of the application does not reset the user data
- [x] A screenshot showing a data representation of user information and account
    balance is uploaded

## Data Representation

![Data Representation](./images/data-representation.png)

## Contributing

### Prerequisites

1. Install homebrew on macOS
2. Install mongodb with homebrew

    ```bash
    brew tap mongodb/brew
    brew install mongodb-community
    brew services start mongodb-community
    ## Use the following command to stop it
    #brew services stop mongodb-community
    ```

3. Install Heroku CLI with homebrew

    ```bash
    brew install heroku/brew/heroku
    ```

4. Install NVM

    ```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
    ```

5. Install Node.js with NVM

    ```bash
    nvm install lts/fermium
    nvm use lts/fermium
    ```

6. Upgrade npm to npm 8

    ```bash
    npm install --global npm@8
    ```

7. Install Docker Desktop Personal

### Run

- To run locally, execute:

    ```bash
    nvm use
    npm install
    npm run dev
    ```

    Then, open [http://localhost:3000](http://localhost:3000) with your browser
    to see the result

- To run inside docker, execute:

    ```bash
    nvm use
    npm install
    npm run docker:start
    ```

    Then, open [http://localhost:3000](http://localhost:3000) with your browser
    to see the result
