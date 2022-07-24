<template>
    <table class="table">
        <thead>
            <tr>
            <th scope="col">#</th>
            <th scope="col">Product</th>
            <th scope="col">Qty</th>
            <th scope="col">Unit.P</th>
            <th scope="col">Price</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <th scope="row">1</th>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            </tr>
        </tbody>
    </table>
</template>

<script>
export default {
    name: 'ProductTable',
}
</script>

<style scoped>
table {
    font-size: 12px
}
thead{
    background-color: black;
    color: white
}
</style>