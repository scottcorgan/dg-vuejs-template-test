<template>
  <footer class="container">
    <div class="content">
      <div>
        <p>
          God is most glorified in us
          when we are most satisfied in him
        </p>
        <p>
          Learn more about Desiring God ->
        </p>
      </div>
      <div class="dgsocial">
        Social Stuff
      </div>
      <div>
        Social stuff
      </div>
      <!-- <form onSubmit={onSubmit}> -->
      <div v-if="submitted"> || Submitted!</div>
      <form v-else v-on:submit.prevent="handleSubmit">
        <label>
          Email Updates
          <input type='text' /><button>Subscribe</button>
        </label>
      </form>
    </div>

    <ul class="meta">
      <li>Permissions</li>
      <li>Privacy</li>
      <li>Careers</li>
      <li>Donate</li>
    </ul>
  </footer>
</template>

<script>
export default {
  data () {
    return {
      submitted: false
    }
  },
  methods: {
    handleSubmit () {
      this.submitted = true
    }
  }
}
</script>

<style scoped>
.container {
  border-top: 1px solid #eee;
}

.content {
  display: flex;
  align-items: center;
  padding: 60px;
}

.dgsocial {
  flex: 2;
}

.jpsocial {
  flex: 2;
}

.meta {
  text-align: right;
  border-top:1px solid #eee;
  padding: 25px 60px;
}

.meta li {
  border-bottom:1px solid #eee;
  display: inline-block;
}

</style>
