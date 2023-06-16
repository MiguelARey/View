<template>
    <HeaderComponent />
    <section class="mainPage">
        <nav class="navbar navbar-dark bg-dark">
            <div class="container-fluid">
                <p class="navbar-brand">Category</p>
                <button
                    class="navbar-toggler"
                    type="button"
                    data-bs-toggle="offcanvas"
                    data-bs-target="#offcanvasDarkNavbar"
                    aria-controls="offcanvasDarkNavbar"
                    aria-label="Toggle navigation"
                >
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div
                    class="offcanvas offcanvas-end text-bg-dark"
                    tabindex="-1"
                    id="offcanvasDarkNavbar"
                    aria-labelledby="offcanvasDarkNavbarLabel"
                >
                    <div class="offcanvas-header">
                        <h5
                            class="offcanvas-title"
                            id="offcanvasDarkNavbarLabel"
                        >
                            Category
                        </h5>
                        <button
                            type="button"
                            class="btn-close btn-close-white"
                            data-bs-dismiss="offcanvas"
                            aria-label="Close"
                        ></button>
                    </div>
                    <div class="offcanvas-body">
                        <ul
                            class="navbar-nav justify-content-end flex-grow-1 pe-3"
                        >
                            <li class="nav-item">
                                <a
                                    class="nav-link active"
                                    href="#"
                                    >Women's clothing</a
                                >
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Men's clothing</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Shoes</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Bag / Purse</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Clock</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Jewelry</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Fashion Accessories</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Digital</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Home Appliances</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Sports / Leisure</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Vehicle / Motorcycle</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Art / Rare / Collectible</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Record / Instrument</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">
                                    Books / Tickets / Stationery
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Beauty</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Furniture</a>
                            </li>
                        </ul>
                        <form class="d-flex mt-3" role="search">
                            <input
                                class="form-control me-2"
                                type="search"
                                placeholder="Search"
                                aria-label="Search"
                            />
                            <button class="btn btn-success" type="submit">
                                Search
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </nav>
        <NavComponent />
    </section>

</template>

<script>
import HeaderComponent from "../HeaderComponent.vue";
import NavComponent from "../NavComponent.vue";

export default {
    name: "MainPageComponent",
    components: {
        HeaderComponent,
        NavComponent,
    },
};
</script>
