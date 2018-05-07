<template>
  <div >
        <div >
          <div >Login</div>
        </div>
        <div >
          <div >Other Documentation</div>
          <div>
              <label>用户名: </label> <label><input></input></label>
            </div>
          <div>
              <label>密码:    </label> <label><input></input></label>
            </div>
        </div>
        <div><button @click="login()">登录</button></div>
      </div>
</template>

<script>

export default {
  name: 'login',
  components: {},
  methods: {
    async login () {
      console.log('hello world')
    }
  }
}
</script>

<style>
</style>
