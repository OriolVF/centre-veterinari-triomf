<template>
  <navbar position="fixed" type="primary" menu-classes="ml-auto">
    <template>
      <router-link v-popover:popover1 class="navbar-brand" to="/presentation">
        Centre Veterinari Triomf
      </router-link>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <a class="nav-link" href="#">
          <p>Inici</p>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <p>Serveis</p>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <p>Contacte</p>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <p>Sobre Nosaltres</p>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">
          <p>Novetats</p>
        </a>
      </li>
    </template>
    <template slot="navbar-menu">
      <drop-down tag="li" title="Català">
        <nav-link class="dropdown-item">
          Català
        </nav-link>
        <nav-link class="dropdown-item">
           Castellano
        </nav-link>
      </drop-down>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';

export default {
  name: 'main-navbar',
  components: {
    DropDown,
    Navbar,
    NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>
