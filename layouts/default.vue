<template>
  <div>
    <NavbarAdmin />
      <div class="row">
        <div class="sidebar col-md-3">
            <SidebarAdmin />
        </div>
        <main class="col-md-9">
            <slot></slot>
        </main>
    </div>
    <FooterAdmin />
  </div>
</template>



