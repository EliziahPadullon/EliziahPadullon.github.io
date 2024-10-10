<script>
    import "../app.css";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300..900;1,300..900&display=swap" rel="stylesheet">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</svelte:head>

<Navbar  >
    <NavBrand href="/"  >
      <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Eliziah P.</span>
    </NavBrand>
    <NavHamburger  />
    <NavUl >
      <NavLi href="/about" class="hover:text-red-500">About</NavLi>
      <NavLi href="/portfolio" class="hover:text-red-500">Portfolio</NavLi>
      <NavLi href="/contact" class="hover:text-red-500">Contact</NavLi>
    </NavUl>
  </Navbar>

<slot></slot>

