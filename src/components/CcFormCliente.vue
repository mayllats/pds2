<template>
    <form>
         <div class="col-md-12">
            <div class="form-group col-md-2">
                <label for="inputCodigo">Código:</label>
                <input type="text" class="form-control" ng-model="cliente.codigo" id="inputCodigo" placeholder="Código">
            </div>
             <div class="form-group col-md-6">
                <label for="inputNome">Nome:</label>
                <input type="text" class="form-control" ng-model="cliente.nome" id="inputNome" placeholder="Nome">
            </div>                   
            <div class="form-group col-md-4">
                <label for="inputCargo">Cargo:</label>
                <input type="text" class="form-control" ng-model="cliente.cargo" id="inputCargo" placeholder="Cargo">
            </div>
         </div>
            <div class="form-group col-md-6">
                <label for="inputEndereco">Endereço:</label>
                <input type="text" class="form-control" ng-model="cliente.endereco" id="inputEndereco" placeholder="Endereço">
            </div>
            <div class="form-group col-md-4">
                <label for="inputCidade">Cidade:</label>
                <input type="text" class="form-control" ng-model="cliente.cidade" id="inputCidade" placeholder="Cidade">
            </div>
             <div class="form-group col-md-2">
                <label for="inputCEP">CEP:</label>
                <input type="text" class="form-control" ng-model="cliente.cep" id="inputCEP" placeholder="CEP">
            </div>
            <div class="form-group col-md-4">
                <label for="inputPais">País:</label>
                <input type="text" class="form-control" ng-model="cliente.pais" id="inputPais" placeholder="País">
            </div>
            <div class="form-group col-md-3">
                <label for="inputTelefone">Telefone:</label>
                <input type="text" class="form-control" ng-model="cliente.telefone" id="inputTelefone" placeholder="Telefone">
            </div>    
            </form>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
