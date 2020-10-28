<template>
    <b-jumbotron bg-variant="dark"
                 text-variant="white"
                 class="mb-0 blue-gradient"
                 fluid>
        <h3 class="font-weight-light">The ERC20 Standard</h3>
        <p class="font-weight-light">
            ERC20 provides basic functionality to transfer tokens, as well as allow tokens to be approved so
            they can be spent by another on-chain third party.
        </p>
        <hr class="my-4">
        <p class="font-weight-light">
            There are many libraries and tools that provide implementations of standards like ERC20 which
            you can deploy as-is or extend to suit your needs, as well as Solidity components to build
            custom
            contracts and more complex decentralized systems.<br>
            But you need to learn Solidity, you need to setup your own environment and code and deploy your
            token
            using an Ethereum node.
            They are a lot of skills and configurations.<br><br>
            <b>ERC20 Token Generator</b> allows people to think about how their projects can be
            decentralized
            (if blockchain would apply to their projects) and not bothering about why node is not syncing,
            or
            if Smart Contract is secure and many other blockchain related issues. All of what you have to do
            is
            to fill in a simple form and complete the transaction with MetaMask.
            Nothing else. No login. No setup. No coding required.
        </p>
        <p class="font-weight-light">
            <b>What will you deploy?</b><br>
            Depending on the Token you choose you will have a:
        </p>
        <ul class="font-weight-light">
            <li>
                <b>Detailed ERC20</b>: your token will be fully compliant with the ERC20 definition and
                compatible with any ERC20 wallet all around the world.
                It will have a name, a symbol and a decimals amount.
            </li>
            <li>
                <b>Capped ERC20</b>: you can’t be able to mint more than the defined max token supply.
                This ensure people that you will not generate more tokens than declared.
            </li>
            <li>
                <b>Mintable ERC20</b>: you will be able to generate tokens by minting them.
                Only token owner will be able to do that.
                You can also disable minting if you don’t want to generate anymore.
            </li>
            <li>
                <b>Burnable ERC20</b>: your token can be burnt.
                It means that you can choose to reduce the circulating supply by destroying some of your
                tokens.
            </li>
            <li>
                <b>ERC1363 Payable Token</b>: the ERC1363 is an ERC20 compatible token that can make a
                callback
                on the receiver contract to notify token transfers or token approvals.
                It can be used to create a token payable crowdsale, selling services for tokens, paying
                invoices,
                making subscriptions, use them for a specific utility and many other purposes.
                <a href="https://eips.ethereum.org/EIPS/eip-1363" target="_blank" class="text-warning">
                    <b>Discover more</b>
                </a>.
            </li>
            <li>
                <b>Token Recover</b>: it allows the contract owner to recover any ERC20 token sent into the
                contract for error.
                <a href="https://vittominacori.github.io/eth-token-recover/" target="_blank"
                   class="text-warning">
                    <b>Discover more</b>
                </a>.
            </li>
        </ul>
    </b-jumbotron>
</template>

<script>
  export default {
    name: 'Details',
  };
</script>
