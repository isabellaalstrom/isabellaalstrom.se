<Headroom offset={25}>
	<header>
		<nav>
			<ul class="main-nav">
				<li class="name" ><a href="/">Isa</a></li>
				<li>
					<ul class="secondary-nav">
						<li><a href="#intro">Intro</a></li>
						<li><a href="#cv">CV</a></li>
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
        font-size: 2rem;
	}
	nav {
        margin: 2rem 0;
        font-family: 'Montserrat', sans-serif;
        font-weight: 600;
    }
    ul {
        display: flex;
        flex-direction: row;
        list-style: none;
        padding: 0;
        height: 100%;
        align-content: center;
        flex-wrap: wrap;
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
        .name {
            display: none;
        }
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