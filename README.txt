//setup
cd projectName
npm init --yes
npm install --save-dev hardhat
npx hardhat
//start local node
npx hardhat node
//compile/deploy contract
npx hardhat run --network localhost scripts/sample-script.js
