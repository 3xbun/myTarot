<template>
  <div>
    <h1>Card of the Day</h1> <br>
    <div class="card">
      <div class="card-img">
        <img src="https://m.media-amazon.com/images/I/71mXrxkcOHL._SL1415_.jpg" alt="">
      </div>
      <div class="card-info">
        <div class="title">
          <h1>The Fool</h1>
        </div>
        <hr>
        <ul class="keywords">
          <li>unified love</li>
          <li>partnership</li>
          <li>mutual attraction</li>
        </ul>
        <p class="desc">The Fool depicts a youth walking joyfully into the world. He is taking his first steps, and he
          is exuberant, joyful, excited. He carries nothing with him except a small sack, caring nothing for the
          possible dangers that lie in his path...</p>
        <button>View</button>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
hr {
  width: 100%;
  margin: .5em auto;
}

h1 {
  text-align: center;
}

.card-img {
  height: 30vh;
  width: 100%;
  text-align: center;
}

img {
  margin: auto;
  width: auto;
  height: 100%;
  border-radius: .5em;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
}

.card {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.card-info {
  width: 100%;
  display: flex;
  flex-direction: column;
}

p {
  width: 100%;
  text-align: center;
}

.keywords {
  display: flex;
  gap: .5em;
  flex-wrap: wrap;
  justify-content: center;
  margin-bottom: .5em;
}

li {
  background-color: var(--primary-accent);
  padding: .25em;
  border-radius: .5em;
}

button {
  background-color: var(--highlight-color);
  border: none;
  border-radius: .5em;
  font-family: inherit;
  color: var(--text-primary);
  margin-top: 1em;
}
</style>