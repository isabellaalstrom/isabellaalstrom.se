<Headroom offset={25}>
	<header>
		<nav>
			<ul class="main-nav">
				<li><a class="name" href="/">Isa</a></li>
				<li>
					<ul class="secondary-nav">
						<li><a href="#work">Work</a></li>
						<li><a href="#hobby">Hobbies</a></li>
						<li><a href="#contact">Contact</a></li>
					</ul>
				</li>
		
			</ul>
		</nav>
	</header>
</Headroom>
<style>
	.name {
        font-family: 'Montserrat Subrayada', sans-serif;
	}
	nav {
        margin: 2rem;
        font-family: 'Montserrat', sans-serif;
        font-weight: 600;
    }
    ul {
        display: flex;
        flex-direction: row;
        list-style: none;
        padding: 0;
    }
    .main-nav {
        gap: 10rem;
    }
    .secondary-nav {
        justify-content: space-evenly;
        gap: 3rem;
    }
        /* Small screens */
    @media screen and (max-width: 600px) {
        .secondary-nav {
            margin-right: 3rem;
        }
    }
    a {
        color:#fff;
        text-decoration: none;
    }
    a:hover {
        cursor: pointer;
    }
</style>
<script>
  import Headroom from "svelte-headroom";
</script>