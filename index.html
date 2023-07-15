<!DOCTYPE html>
<html>
  <head>
    <title>Instagram Clone - Login/Signup</title>
    <style>
      .container {
        max-width: 300px;
        margin: 0 auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 4px;
      }

      h1 {
        text-align: center;
      }

      input[type="text"],
      input[type="email"],
      input[type="password"],
      button {
        display: block;
        width: 100%;
        margin-bottom: 10px;
        padding: 10px;
      }

      button {
        background-color: #4caf50;
        color: white;
        border: none;
      }

      button:hover {
        opacity: 0.8;
      }

      .divider {
        margin: 20px 0;
        border-top: 1px solid #ccc;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Login</h1>
      <form id="login-form">
        <input type="email" name="email" placeholder="Email" required />
        <input
          type="password"
          name="password"
          placeholder="Password"
          required
        />
        <button type="submit">Login</button>
      </form>
      <div class="divider"></div>
      <h1>Signup</h1>
      <form id="signup-form">
        <input type="text" name="name" placeholder="Full Name" required />
        <input type="text" name="username" placeholder="Username" required />
        <input type="email" name="email" placeholder="Email" required />
        <input
          type="password"
          name="password"
          placeholder="Password"
          required
        />
        <input type="text" name="bio" placeholder="Bio" required />
        <button type="submit">Signup</button>
      </form>
    </div>

    <script>
      document
        .getElementById("login-form")
        .addEventListener("submit", async (e) => {
          e.preventDefault();
          let profileData;
          const form = e.target;
          const formData = new FormData(form);
          const data = Object.fromEntries(formData.entries());

          try {
            const response = await fetch(
              "http://localhost:3000/v1/user/login",
              {
                method: "POST",
                headers: {
                  "Content-Type": "application/json",
                },
                body: JSON.stringify(data),
              }
            );

            if (response.ok) {
              const result = await response.json();
              alert(result.msg);
              // Perform any desired actions for successful login
            } else {
              const error = await response.json();
              alert(error.msg);
              // Display error message to the user
            }
          } catch (error) {
            alert("An error occurred:", error);
            // Handle any network or server errors
          }
        });

      document
        .getElementById("signup-form")
        .addEventListener("submit", async (e) => {
          e.preventDefault();

          const form = e.target;
          const formData = new FormData(form);
          const data = Object.fromEntries(formData.entries());

          try {
            const response = await fetch(
              "http://localhost:3000/v1/user/signup",
              {
                method: "POST",
                headers: {
                  "Content-Type": "application/json",
                },
                body: JSON.stringify(data),
              }
            );

            if (response.ok) {
              const result = await response.json();
              alert(result.msg);
              // Perform any desired actions for successful signup
            } else {
              const error = await response.json();
              alert(error.msg);
              // Display error message to the user
            }
          } catch (error) {
            alert("An error occurred:", error);
            // Handle any network or server errors
          }
        });
    </script>
  </body>
</html>
