# mern-ecommerce

> Frontend-> React JS

> Backend-> Node JS & Express JS

> Database-> MongoDB

## Installation process
1. #### clone the repo using this command
    ```bash
    git clone https://github.com/ashraf-kabir/mern-ecommerce.git
    ```
2. #### install npm packages
    1. install backend packages
    ```bash
    cd mern-ecommerce
    npm install
    ```
    2. install frontend packages
    ```bash
    cd client
    npm install
    ```
3. go to the parent folder of mern-ecommerce & create .env for connection, JWT_SECRET, BRAINTREE_MERCHANT_ID, BRAINTREE_PUBLIC_KEY and BRAINTREE_PRIVATE_KEY.

    ```bash
    cd mern-ecommerce
    sudo nano .env
    ```
    (ctrl+x to save & nano follow instruction there)
    
    ##### sample code for backend .env
    ```env
    MONGODB_URI=YOUR_MONGODB_URI
    JWT_SECRET=YOUR_JWT_SECRET
    BRAINTREE_MERCHANT_ID=YOUR_BRAINTREE_MERCHANT_ID
    BRAINTREE_PUBLIC_KEY=YOUR_BRAINTREE_PUBLIC_KEY
    BRAINTREE_PRIVATE_KEY=YOUR_BRAINTREE_PRIVATE_KEY
    ```
4.  create another .env file inside client directory for REACT_APP_API_URL.

    ```bash
    cd mern-ecommerce/client
    sudo nano .env
    ```
    ##### sample code for frontend .env
    ```env
    REACT_APP_API_URL=YOUR_API_URL
    ```
    
