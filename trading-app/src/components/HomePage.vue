<template>
    <div>
        <nav>
            <router-link to="/place-order">Place Order</router-link> |
            <router-link to="/view-transactions">View Transactions</router-link>
            |
            <router-link to="/cancel-transaction"
                >Cancel Transaction</router-link
            >| <router-link to="/create-stock">Create Stock</router-link> |
            <router-link to="/add-stock">Add Stock</router-link> |
            <router-link to="/portfolio">Portfolio</router-link> |
            <router-link to="/add-money">Add Money</router-link> |
            <router-link to="/wallet-balance">Wallet Balance</router-link>
            |
            <router-link @click="logout" to="#">Logout</router-link>
        </nav>
        <router-view />
    </div>
</template>

<script>
export default {
    methods: {
        logout() {
            // Clear authentication token or session data
            localStorage.removeItem("token");
            this.$router.push("/");
        },
    },
};
</script>
