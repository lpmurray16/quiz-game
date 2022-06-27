<header>
    <div class="logo" on:click={() => (window.location.href = "/")}>
        <img src="/controller2.svg" alt="Quiz Game" />
        <span>Quiz Game</span>
    </div>
    <div class="nav__reg">
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/add">+Question</a></li>
            </ul>
        </nav>
        <div class="nav__right">
            <a
                href="https://logan-murray.dev"
                target="_blank"
                rel="noreferrer noopener">More</a
            >
        </div>
    </div>
</header>

<style>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem;
        background-color: #fafafa;
        border-bottom: 1px solid #eaeaea;
    }
    .nav__reg {
        display: flex;
        align-items: center;
    }
    nav ul {
        display: flex;
        align-items: center;
        list-style-type: none;
    }
    nav ul li {
        margin-right: 1rem;
    }
    nav ul li a,
    .nav__right a {
        color: #333;
        text-decoration: none;
    }
    nav ul li a:hover,
    .nav__right a:hover {
        text-decoration: underline;
    }
    .nav__right {
        display: flex;
        align-items: center;
    }
    .logo {
        display: flex;
        align-items: center;
        cursor: pointer;
    }
    .logo img {
        margin-right: 0.5rem;
    }
    .logo span {
        font-size: 1.5rem;
        font-weight: bold;
    }
    @media (prefers-color-scheme: dark) {
        header {
            background-color: #333;
            color: #fafafa;
        }
        .logo {
            color: #fafafa;
        }
        .logo img {
            filter: invert(100%);
        }
        .nav__right a,
        nav ul li a {
            color: #fafafa;
        }
    }
    @media (max-width: 768px) {
        .logo span {
            display: none;
        }
    }
</style>
