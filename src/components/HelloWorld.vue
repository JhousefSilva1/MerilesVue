<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      El perro (Canis familiaris o Canis lupus familiaris, dependiendo de si se
      lo considera una especie por derecho propio o una subespecie del lobo),
      llamado perro doméstico o can, y en algunos lugares coloquialmente llamado
      chucho, tuso, choco, entre otros; es un mamífero carnívoro de la familia
      de los cánidos, que constituye una especie del género Canis.
    </p>

    <h3>La importancia de la esterilización</h3>
    <p>
     Ya sea si recién ha adoptado una mascota o si lo está considerando, una de las decisiones sanitarias más importantes que tomará es esterilizar o castrar a su gato o perro. Esterilización; remover los ovarios y útero de una mascota hembra, es un procedimiento de un veterinario que requiere hospitalización mínima y ofrece beneficios para la salud de por vida. Castrar; remover los testículos de su gato o perro macho, mejorará ampliamente la conducta de su mascota y lo mantendrá cerca de casa.
    </p>
    <li>
      <a
        href="https://es.wikipedia.org/wiki/Canis_familiaris#Castraci%C3%B3n_y_esterilizaci%C3%B3n"
        target="_blank"
        rel="noopener"
        >Esterilizacion</a
      >
    </li>

    <h3>¿Por que es importante la vacunación?</h3>
    <P>
      Las enfermedades infecciosas habitualmente asociadas con los perros
      incluyen la leptospirosis, el parvovirus canino y el moquillo. Para
      protegerlos de ellas, los perros deben ser vacunados, así como también
      contra la rabia, enfermedad que se transmite al ser humano y es altamente
      mortal.
    </P>
    <li>
      <a
        href="https://hvmajadahonda.com/vacunas-para-perros-obligatorias-y-su-calendario#:~:text=Las%20vacunas%20obligatorias%20para%20perros,tetravalente%20o%20bien%20la%20polivalente."
        target="_blank"
        rel="noopener"
        >vacunas</a
      >
    </li>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
