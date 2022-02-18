<template>
  <h1>¿Quién es éste Pokémon?</h1>
  <pokemon-picture :pokemonId="4" :showPokemon="true"/>
  <pokemon-options/>
</template>

<script>

import PokemonPicture from '@/components/PokemonPicture'
import PokemonOptions from '@/components/PokemonOptions'

export default {
  components:{
    PokemonPicture,
    PokemonOptions
  }
}
</script>
