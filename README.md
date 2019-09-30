The SLP GreenMiner uses an "eco-block mining" setup to emit a fixed number of SLP tokens at regular intervals similar to emulate how miners find blocks and mine a steady supply of coins. It does so by having a cron job invoke the SLP minting baton at scheduled intervals. These newly minted tokens will appear in the minting baton's wallet, just as if they were manually minted. From there, another job can optionally direct them to feeding a faucet with a steady drip of tokens, or direct them to any other place that the token creators decide.

As an alternative to a single "genesis block" emission of all tokens at once. The centralization and overwhelming upfront amount of tokens in the hands of an initial issuer has been a consistent criticism of many ERC20 token projects. The SLP GreenMiner solves this problem by instead introducing a linear, progressive, steady and predictable issuance of tokens; emulating how blocks are found by miners and thus gaining the benefit of a regular BTC/BCH/ETH/LTC issuance but without the high cost to the environment caused by the excessive electricity usage of mining.

A regular drip of tokens, as opposed to a single front-loading of the entire token supply in the "Genesis block", is beneficial to the value of the coin because it eliminates the problem of premining. Thus, scarcity can be predicted and a single dev/whale can not suddenly dump tokens on an exchange and crash the price because these tokens do not yet exist.

Parameters will include: Total coin supply, "block" time intervals, emission curve (linear or with halvings or with a progressive decline per "block"). Specific templates could be created to emulate the total coin supply and halvings of BTC/BCH, LTC or even XKR with its tail emission, among other coins.

Each emission will cost 546 sats BCH, so the issuing wallet with the mint baton must hold sufficient BCH to cover the cost of the total coin supply emission according to the selected variables. To lower the total cost, a block time of 10 minutes and for instance 50 tokens per block can be changed to an hourly emission of 300 tokens or a once-daily emission of 7200 tokens; thus saving BCH. Similarly, the cost can be lowered still further by invoking the minting baton only once a week or even less frequently. The ideal default would be a once-daily emission of coins that emulate a regular blocktime, as if minted.






This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
