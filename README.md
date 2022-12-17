# dojima-hackathon

#### Setup genesis

Setup genesis whenever contracts get changed
### 1. Install dependencies and submodules
```bash
$ npm install

```

### 2. Compile contracts
```bash
#installation of npm v12.0.0 is required
$ npm run truffle:compile
```

### 3. Run Test Blockchain
```bash
$ npm run testrpc
$ npm test
```

### 4. Migrate Contracts to local chain
```bash
$ npm run truffle:migrate
```

### 5. Migrate Contracts to dojima chain
```bash
$ truffle migrate --network dojimachain
```