
# Crowdfunding app setup
An Ethereum-based crowdfunding app allows anyone to create a campaign to raise funds for their project or cause to cover their story. The app uses smart contracts on the Ethereum blockchain to securely handle all transactions and ensure that funds are distributed only to the intended recipients.

To create a campaign, users simply create a smart contract with the details of their project and fundraising goal. They can set rewards for different contribution levels, such as early access to the product or special perks. Contributors can then send ETH (Ethereum's cryptocurrency) directly to the smart contract to fund the campaign.

## How to locally deploy the project?
You firstly need to download or clone the repo.

Secondly, make sure that you currently are in the root directory. 

On Windows, verify by using the command:
```bash
  cd
```

On Linux, verify by using the command:
```bash
  pwd
```

The address should appear as something that will end with 'crowdfunding-master' similar to this:

/media/rohan/New Volume/crowdfunding-master

After this step change your directory to web3 by using the command
```bash
  cd web3
```

Install all the dependencies using the command
```bash
  npm install
```

It should fetch the dependencies from package.json file in the directory.

Change your directory to 'client' by using the below commands:
```bash
  cd ..
  cd client
```

Once you are in the client directory install the dependencies by the same process you followed as in the case of web3 directory.

```bash
  npm install
```

After successful installation of the dependencies use the following dev script:
```bash
  npm run dev
```

That's it! You'll now have the localhost address of the site. Copy that and paste it in the browser, use the website and raise some campaigns!



