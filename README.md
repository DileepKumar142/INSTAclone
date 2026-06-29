# INSTAclone
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Instagram Clone</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <!-- Left side image -->
    <div class="phone-image">
      <img src="https://www.instagram.com/static/images/homepage/home-phones.png/43cc71bb1b43.png" alt="Instagram phone preview">
    </div>

    <!-- Right side login form -->
    <div class="login-section">
      <div class="login-box">
        <h1>Instagram</h1>
        <form>
          <input type="text" placeholder="Phone number, username, or email">
          <input type="password" placeholder="Password">
          <button type="submit">Log In</button>
          <div class="divider">OR</div>
          <button class="fb-login">Log in with Facebook</button>
          <a href="#">Forgot password?</a>
        </form>
      </div>

      <div class="signup-box">
        <p>Don't have an account? <a href="#">Sign up</a></p>
      </div>

      <div class="app-links">
        <p>Get the app.</p>
        <div class="store-buttons">
          <img src="https://www.instagram.com/static/images/appstore-install-badges/badge_ios_english_en.png/9fc4bab7565b.png" alt="App Store">
          <img src="https://www.instagram.com/static/images/appstore-install-badges/badge_android_english_en.png/6071ff4c9f52.png" alt="Google Play">
        </div>
      </div>
    </div>
  </div>
</body>
</html> 
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #fafafa;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.container {
  display: flex;
  max-width: 900px;
  width: 100%;
}

.phone-image img {
  width: 400px;
  height: auto;
}

.login-section {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.login-box {
  background: #fff;
  border: 1px solid #dbdbdb;
  padding: 40px;
  margin-top: 20px;
  text-align: center;
  width: 350px;
}

.login-box h1 {
  font-family: 'Billabong', cursive;
  font-size: 48px;
  margin-bottom: 20px;
}

.login-box input {
  width: 100%;
  padding: 10px;
  margin: 5px 0;
  border: 1px solid #dbdbdb;
  border-radius: 3px;
  background: #fafafa;
}

.login-box button {
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  background: #3897f0;
  color: #fff;
  border: none;
  border-radius: 3px;
  font-weight: bold;
  cursor: pointer;
}

.divider {
  margin: 20px 0;
  font-size: 14px;
  color: #8e8e8e;
  position: relative;
}

.divider::before,
.divider::after {
  content: "";
  position: absolute;
  width: 40%;
  height: 1px;
  background: #dbdbdb;
  top: 50%;
}

.divider::before {
  left: 0;
}

.divider::after {
  right: 0;
}

.fb-login {
  background: none;
  color: #385185;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

.signup-box {
  background: #fff;
  border: 1px solid #dbdbdb;
  padding: 20px;
  margin-top: 10px;
  text-align: center;
  width: 350px;
}

.signup-box a {
  color: #3897f0;
  text-decoration: none;
}

.app-links {
  text-align: center;
  margin-top: 20px;
}

.store-buttons img {
  height: 40px;
  margin: 5px;
}

