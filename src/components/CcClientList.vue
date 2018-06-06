<template>
    <table class="table">
        <thead class="thead-light">
            <tr>
            <th scope="col">#Código</th>
            <th scope="col">Nome</th>
            <th scope="col">Cargo</th>
            <th scope="col">Endereço</th>
            <th scope="col">Cidade</th>
            <th scope="col">CEP</th>
            <th scope="col">País</th>
            <th scope="col">Telefone</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <th scope="row">{{codigo}}</th>
            <td>{{nome}}</td>
            <td>{{cargo}}</td>
            <td>{{endereco}}</td>
            <td>{{cidade}}</td>
            <td>{{cep}}</td>
            <td>{{pais}}</td>
            <td>{{telefone}}</td>
            </tr>
            <tr></tr>
            <tr></tr>
            
        </tbody>
    </table>      
</template>

<script>
export default {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
