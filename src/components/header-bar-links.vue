<template>
  <div class="navbar-menu">
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a :href="github" target="_blank" rel="noopener noreferrer">
           <label class="label" for="github">Github</label>
            <input type="text" id="github" class="input" v-model="github">
             {{ github }}
            <i class="fab fa-github fa-2x" aria-hidden="true"></i>
            <div class="field">
            
             </div>
          </a>
          <a :href="twitter" target="_blank" rel="noopener noreferrer">
            <i class="fab fa-twitter fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      github: 'https://github.com',
      twitter: 'https://twitter.com',
    };
  },
};
</script>
