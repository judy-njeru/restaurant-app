<template>
    <div>
        <b-card title="ORDER FLOW BOX" class="order-flow-card">
            <b-link href="#" class="card-link order-flow-button" id="btnOrderFlow">order</b-link>
        </b-card>
    </div>
</template>

<script>
    export default {
        name: 'OrderFlowBox'
    }
</script>

<style lang="scss">

    div.order-flow-card { 
        height: 100%;
        
        div.card-body {
            padding: 15px 8px 8px 10px;
            text-align: left;
            display: flex;
            flex-direction: column;
            justify-content: space-between;

            h4.card-title {
                font-size: .8rem;
            }

            .order-flow-button {
                background-color: #bbb;
                display: block;
                margin: 10px 0;
                padding: 10px;
                width: 100%;
                text-transform: uppercase;
                color: #fff;
            }
        }
        
    }
    
</style>


