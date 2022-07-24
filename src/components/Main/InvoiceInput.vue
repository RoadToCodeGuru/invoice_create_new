<template>
    <div class="card" style="width: 100%; height: 100%;">
        <div class="card-body">
            <div class="mb-3 row">
                <div class="col-6">
                    <input type="text" class="form-control" id="customer_name" placeholder="Customer Name">
                </div>
                 <div class="col-6">
                    <input type="date" class="form-control" id="customer_name" placeholder="Customer Name">
                </div>
            </div>
            <div class="mb-3 row">
                <div class="col-6">
                    <input type="text" class="form-control" id="customer_name" placeholder="Sale Person Name">
                </div>
                 <div class="col-6">
                    <input type="text" class="form-control" id="customer_name" placeholder="Note (Optional)">
                </div>
            </div>
            <hr/>
            <div class="mb-3 row">
                <div class="col-6">
                    <!-- <input type="text" class="form-control" id="customer_name" placeholder="Search Product Name"> -->
                </div>
                <div class="col-3">
                    <input type="number" class="form-control" id="customer_name" placeholder="Qty" value="1">
                </div>
                <div class="col-3">
                    <button style="width:100%" type="button" class="btn btn-sm btn-info float-right">Add Product</button>
                </div>
            </div>
            <hr/>
            <div class="mb-3 row px-3">
               <ProductTable/>
            </div>
        </div>
    </div>
</template>

<script>
import ProductTable from './ProductTable.vue'

export default {
    name: 'InvoiceInput',
    components: {
        ProductTable,
    },
    data() {
        return {
            products: [
                {id: 1, name: 'Splashing Melody', picture: '1.png', stock: 100, price: 4200},
                {id: 2, name: 'In A Ville', picture: '2.png', stock: 100, price: 4000},
                {id: 3, name: 'Red Attraction', picture: '3.png', stock: 100, price: 3900},
                {id: 4, name: 'Damn Fresh!', picture: '4.png', stock: 100, price: 4200},
                {id: 5, name: 'True Beauty', picture: '5.png', stock: 100, price: 4100}
            ]
        }
    }
}
</script>

<style scoped>
input {
    font-size: 12px
}
</style>