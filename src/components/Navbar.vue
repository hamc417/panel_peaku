<template>
    <div class="w-100 bg-primary d-flex justify-content-between p-2">
      <b-nav pills class="w-100 bg-primary d-flex justify-content-around p-2">
        <b-nav-form>
          <b-form-input aria-label="Input" class="mr-1"></b-form-input>
        </b-nav-form>
        <div class="d-flex">
          <div>
            <b-button-group>
              <b-dropdown right text="Area" variant="primary" class="badge rounded-pill text-bg-primary">
                <b-dropdown-item>Item 1</b-dropdown-item>
                <b-dropdown-item>Item 2</b-dropdown-item>
                <b-dropdown-divider></b-dropdown-divider>
                <b-dropdown-item>Item 3</b-dropdown-item>
              </b-dropdown>
  
              <b-dropdown right text="Cargo" variant="primary">
                <b-dropdown-item>Item 1</b-dropdown-item>
                <b-dropdown-item>Item 2</b-dropdown-item>
                <b-dropdown-divider></b-dropdown-divider>
                <b-dropdown-item>Item 3</b-dropdown-item>
              </b-dropdown>
  
              <b-dropdown right text="Salario" variant="primary">
                <b-dropdown-item>Item 1</b-dropdown-item>
                <b-dropdown-item>Item 2</b-dropdown-item>
                <b-dropdown-divider></b-dropdown-divider>
                <b-dropdown-item>Item 3</b-dropdown-item>
              </b-dropdown>
  
              <b-dropdown right text="Ubicación" variant="primary">
                <b-dropdown-item>Item 1</b-dropdown-item>
                <b-dropdown-item>Item 2</b-dropdown-item>
                <b-dropdown-divider></b-dropdown-divider>
                <b-dropdown-item>Item 3</b-dropdown-item>
              </b-dropdown>
            </b-button-group>
          </div>
        </div>
      </b-nav>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AppNavbar',
  }
  </script>
  