<template>
    <div class="center">    
        <v-row>
            <v-col cols="10" sm="6" offset-sm="3" md="4" offset-md="4" offset="1">
                <v-avatar size="295" tile>
                    <v-img src="@/assets/istockphoto-826736292-612x612.jpg"></v-img>
                </v-avatar>
                <v-text-field label="Username" v-model="username"></v-text-field>
                <v-text-field label="Password" v-model="password" type="password"></v-text-field>
                <v-btn block elevation="2">Login</v-btn>
            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {
    name: 'Login',
    data() {
        return {
            username: "",
            password: "",
        }
    },
    methods: {
        authenticate: function(){

        }
    }
}
</script>


<style lang="scss" scoped>
</style>>
