<template>
    <div >
      <h1>{{ msg }}</h1>
      <h2>Book Table</h2>
      <table class="table table-striped">
  <thead>
    <br>
    <br>
    <div class="input-group">
    <input type="search" class="form-control rounded" placeholder="Search" aria-label="Search" aria-describedby="search-addon" />
    <br><button type="button" class="btn btn-outline-primary">Search Book</button>
    </div>

    <br>
    <tr>
      <th scope="col">ID</th>
      <th scope="col">Book First Name</th>
      <th scope="col">Book Last Name</th>
      <th scope="col">ISBN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>

    </div>
  </template>
  
  <script>
  export default {
    name: 'EmployeeView',
    data () {
      return {
        msg: 'Welcome to Online Library System'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h1, h2 {
    font-weight: normal;
  }
  input{

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
  