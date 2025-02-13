<script setup>


</script>

<template>
    <h3>Add a new Transaction</h3>
    <form id="form" @submit.prevent="onSubmit">
        <div class="form-control">
            <label for="text">Enter Transaction</label>
            <input type="text" id="text" v-model="text" placeholder="Enter Transaction...">
        </div>
        <div class="form-control">
            <label for="amount">Enter Transaction</label>
            <input type="text" id="text" v-model="amount" placeholder="Enter Negative Value for Expenses">
        </div>


    </form>

</template>