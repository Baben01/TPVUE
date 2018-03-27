<template>
    <p>TEEEST</p>
    <li v-for="personne in personnes">{{personne.nom}} {{personne.prenom}}</li>
</template>

<script>
    export default {
        data: function () {
            {
                return {
                    personnes: [
                        {nom: "Durand", prenom: "Jacques"},
                        {nom: "Dupont", prenom: "Albert"},
                        {nom: "Martin", prenom: "Denis"},
                    ]
                }
            }
        }
    }
</script>

<style scoped>

</style>