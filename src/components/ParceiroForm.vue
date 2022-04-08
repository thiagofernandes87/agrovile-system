<template>
    <div>
        <div>
            <form id="fornecedor-form">
                <div class="input-container">
                    <label for="cnpj_cpf">CNPJ/CPF:</label>
                    <input type="text" id="cnpj" name="cnpj" v-model="cnpj" placeholder="Digite o CNPJ ou CPF">
                </div>
                <div class="input-container">
                    <label for="nome">Razão/Nome:</label>
                    <input type="text" id="nome" name="nome" v-model="cnpj" placeholder="Digite a Razão Social ou Nome">
                </div>
            </form>
        </div>
    </div>
</template>

<script>

export default{
    name: "ParceiroForm"
        
    }
    
</script>

<style scoped>
    #fornecedor-form{
        max-width: 400px;
        margin: 0 auto;
        }

    .input-container {
        display: flex;
        flex-direction: column;
        margin-bottom: 20px;
  }
    label {
        font-weight: bold;
        margin-bottom: 15px;
        color: #222;;
        padding: 5px 10px;
        border-left: 4px solid #1e6091;
  }

    input, select {
    padding: 5px 10px;
    width: 300px;
    
  }

</style>
