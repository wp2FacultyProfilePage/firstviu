<!-- <template>
  <div class="login-page">
    <h2>Login</h2>
    <form @submit.prevent="login">
      <label for="username">Username:</label>
      <input type="text" v-model="username" required />

      <label for="password">Password:</label>
      <input type="password" v-model="password" required />

      <button type="submit">Login</button>
    </form>

    <div v-if="error" class="error-message">{{ error }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: '',
      password: '',
      error: ''
    };
  },
  methods: {
    login() {
      // Simulate authentication (replace with actual authentication logic)
      if (this.username === 'user' && this.password === 'password') {
        // Successful login
        // You can redirect to another page or perform other actions here
        console.log('Login successful');
      } else {
        // Failed login
        this.error = 'Invalid username or password';
      }
    }
  }
};
</script>

<style scoped>
.login-page {
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
}

form {
  display: flex;
  flex-direction: column;
}

label {
  margin-bottom: 6px;
}

input {
  padding: 8px;
  margin-bottom: 12px;
}

button {
  padding: 10px;
  background-color: #007bff;
  color: #fff;
  cursor: pointer;
  border: none;
  border-radius: 4px;
}

.error-message {
  color: red;
  margin-top: 10px;
}
</style> -->
