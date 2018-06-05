<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
             <span class="navbar-toggler-icon"></span>
        </button>         
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Cadastros</a>
                          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#">Cliente</a>
                            <a class="dropdown-item" href="#">Categoria</a>
                            <a class="dropdown-item" href="#">Produto</a>
                            <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Pedido</a>
                          </div>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link disabled" href="#">Disabled</a>
                        </li>
             </ul>
         </div>
    </nav>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
