<template>
    <table class="table">
        <thead>
            <tr>
            <th scope="col">Array</th>
            <th scope="col">Boolean</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="(item) in array" :key="item">
                <td>{{item}}</td>
                <td>{{boolean}}</td>
            </tr>
           <!-- <tr>
                <td>Hola</td>
            <tr/>-->
        </tbody>
    </table>
</template>

<script>
    export default{
        name:'MiTabla',
        props:['array','MyStyle','boolean']
    }
</script>