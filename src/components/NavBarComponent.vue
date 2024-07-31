<template>
    <nav class="navbar">
      <div class="container">
        <a href="#" class="brand">MyWebsite</a>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavBarComponent'
  };
  </script>
  
  <style scoped>
  .navbar {
    background-color: #333;
    color: white;
    padding: 1rem;
  }
  
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .brand {
    font-size: 1.5rem;
    color: white;
    text-decoration: none;
  }
  
  .nav-links {
    list-style: none;
    display: flex;
    gap: 1rem;
  }
  
  .nav-links a {
    color: white;
    text-decoration: none;
  }
  </style>
  