<template>
    <div>
        <b-jumbotron bg-variant="dark"
                     text-variant="white"
                     header="ERC20 Token Generator"
                     lead="The most used Smart Contract Generator for ERC20 Token"
                     class="mb-0 blue-gradient"
                     fluid>
            <hr class="my-5">
            <b-button to="create-token" size="lg" variant="outline-warning" class="py-3 px-5 text-uppercase">
                Create your Token
            </b-button>
            <a class="btn btn-lg btn-light py-3 px-5 text-uppercase"
               href="#features"
               v-smooth-scroll="{ duration: 1000, offset: 0, updateHistory: false }">
                Features
            </a>
        </b-jumbotron>
        <b-row id="how-it-works" class="mx-0">
            <b-col lg="8" offset-lg="2" class="mb-3">
                <h2 class="p-5 font-weight-lighter text-center text-dark">How it works</h2>
                <h4 class="text-center font-weight-light">
                    Create an ERC20 Token in less than a minute.
                </h4>
                <p class="text-center font-weight-light">
                    No login.
                    No setup.
                    No coding required.
                </p>
                <ui--how-it-works></ui--how-it-works>
            </b-col>
        </b-row>
        <b-row id="features" class="aqua-gradient mx-0">
            <b-col lg="10" offset-lg="1" class="mb-5">
                <h2 class="p-5 font-weight-lighter text-center text-light">Features</h2>
                <ui--pricing-table></ui--pricing-table>
            </b-col>
        </b-row>
        <b-row class="bg-dark text-white mx-0">
            <b-col lg="10" offset-lg="1" class="mb-3 text-center">
                <h2 class="pt-5 mb-4 font-weight-lighter text-light">Need a custom development?</h2>
                <p class="font-weight-light">
                    Open to getting in touch with awesome people and projects.
                </p>
                <a href="https://vittominacori.github.io/"
                   target="_blank"
                   class="btn btn-lg btn-outline-warning my-4 py-3 px-5 text-uppercase">
                    Contact me
                </a>
            </b-col>
        </b-row>
        <b-row id="details" class="mx-0">
            <b-col lg="12" class="px-0">
                <ui--details></ui--details>
            </b-col>
        </b-row>
    </div>
</template>

<script>
  export default {
    name: 'Home',
  };
</script>
