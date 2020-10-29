<template>
    <div class="faq-table">
        <b-row>
            <b-col lg="8" offset-lg="2">
                <b-card bg-variant="light" class="mb-4">
                    <h3 class="font-weight-light">The ERC20 Standard</h3>
                    <p class="font-weight-light">
                        ERC20 provides basic functionality to transfer tokens, as well as allow tokens to be approved so
                        they can be spent by another on-chain third party.
                    </p>
                    <hr class="my-4">
                    <p class="font-weight-light">
                        There are many libraries and tools that provide implementations of standards like ERC20 which
                        you can deploy as-is or extend to suit your needs, as well as Solidity components to build
                        custom contracts and more complex decentralized systems.<br>
                        But you need to learn Solidity, you need to setup your own environment and code and deploy your
                        Token using an Ethereum node.
                        They are a lot of skills and configurations.<br><br>
                        <b>ERC20 Token Generator</b> allows people to think about how their projects can be
                        decentralized (if blockchain would apply to their projects) and not bothering about why
                        node is not syncing, or if Smart Contract is secure and many other blockchain related issues.
                        All of what you have to do is to fill in a simple form and complete the transaction
                        with MetaMask.
                        Nothing else. No login. No setup. No coding required.
                    </p>
                </b-card>
            </b-col>
        </b-row>
    </div>
</template>

<script>
  export default {
    name: 'Faq',
  };
</script>
