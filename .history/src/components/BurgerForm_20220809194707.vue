<template>
  <div>
    <p>Componente de Mensagem</p>
    <div>
        <form id="burger-form">
            <div class="input-container">
                <label for="nome">Nome do Cliente</label>
                <input type="text" id="nome" name="nome" v-model="nome" placeholder="Digite seu nome.">
            </div>
        </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BurgerForm',
}
</script>

<style scoped></style>
