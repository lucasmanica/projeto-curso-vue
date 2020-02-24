<template>
    <v-container fluid>
        <v-row justify="center">
            <v-col cols="12"
            md="3"
            class="text-center">
                <h6 class="headline">Login</h6>
                <v-text-field
                    label="Token"
                    />
                <v-btn depressed color="green" dark block>
                Login
                </v-btn>
                <v-btn text>
                Entrar como visitante
                </v-btn>
            </v-col>
        </v-row>
    </v-container>
</template>
<script>
export default {
    name: 'LoginPage',
};
</script>
<style lang="stylus" scoped>

</style>