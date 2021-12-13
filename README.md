# Rock, Paper, and Scissors dAPP

Code for the tutorial https://docs.reach.sh/tut.html

This tutorial walks through the creation of a simple decentralized application. It contains everything you need to know to build and test this application and assumes no prior experience with DApp/blockchain development of any kind

## Compile

```
npm run compile
```

## Run

### Algorand

```
npm start
```
### Ethereum

```
npm run start-eth
```

### React

- Creare account MetaMask e selezionare la net in locale (es: Localhost 8545)
- `npm run react-eth` (or `npm run` per Algorand, al momento non funzionante)

## Background

# **Background**

Before starting this tutorial, we will need to install and make sure Reach is configured for Algorand Blockchain Development. For those using Unix based systems make sure the following commands run without error.

 **`$ make --version
 $ docker --version
 $ docker-compose --version`**

**Tip**

If you are using Windows, consult [Reach SDK Installtion Windows]

Once you have confirmed that the above is installed, we can choose a directory for our sample AlgoReach project.

**`mkdir -p ~/reach/AlgoReach && cd ~/reach/AlgoReach`**

Next, we can install Reach from [GitHub] in our console lets run the following command in our terminal.

 **`curl https://raw.githubusercontent.com/reach-sh/reach-lang/master/reach -o reach ; chmod +x reach`**

Now, we can check and see if everything worked by running the following command in our terminal.

**`./reach version`**

Reach is Docker Container, when we first use it, you will need to download the images it uses. You can get these by running the following command in your terminal.

**`./reach update`**

Congratulations, if you have made it this far without any error run the folowing command in your terminal

**`./reach compile --help`**
