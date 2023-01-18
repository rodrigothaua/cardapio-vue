<template>
  <header id="cabecalho">
        <div class="menu-icon">
            <a data-bs-toggle="offcanvas" href="#offcanvasExample" role="button" aria-controls="offcanvasExample">
                <i class="bi bi-list"></i>
            </a>
        </div>

        <div class="menu-logo">
            LOGO
        </div>

        <div class="menu-right">
            <a href="login.html">
                <i class="bi bi-person"></i>
            </a>
        </div>

    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>
    
<style>
    #cabecalho{
        height: 6rem;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        box-shadow: rgb(0 0 0 / 10%) 0px 4px 16px 0px;
        background: rgb(248, 248, 248);
        width: 100%;
        padding: 0 1.8rem 0 1.8rem;
    }

    .menu-logo{
        justify-content: center;
        font-size: 30px;
    }

    .menu-right{
        justify-content: flex-end;
    }

    .offcanvas-body{
        background-color: #000;
    }
</style>