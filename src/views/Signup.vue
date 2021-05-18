<template>
    <body id="inscription" class="inscription">
        <h1>Inscrivez-vous</h1>
        <form method="POST" @click="sendForm">
            <label for="nom">Nom : </label>
            <br>
            <input type="text">
            <br>
            <label for="prenom">Prénom : </label>
            <br>
            <input type="text">
            <br>
            <label for="Adresse mail">Adresse mail : </label>
            <br>
            <input type="email">
            <br>
            <label for="password">Mot de passe : </label>
            <br>
            <input type="password">
        </form>
    </body>
  
</template>

<script>
export default {
    name : "Signup",
}
</script>

<style>

</style>