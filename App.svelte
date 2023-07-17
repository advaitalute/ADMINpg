<script>
	import Button from "./Button.svelte"
	let src = 'https://raw.githubusercontent.com/PureshwarGonekar/Hal-Smart_Township/master/public/logo.ico';

</script>
<div class="container">
<img {src} alt="{name} dances."/>
<h1>Welcome To HAL Township</h1>
<h2>Login/Register</h2>
<Button class="admin">
    ADMIN
</Button>
<Button class="user">
    USER
</Button>
</div>

<style>

	.container{
		
		background-color:white;
		background-image: url("https://images.pexels.com/photos/956981/milky-way-starry-sky-night-sky-star-956981.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260");
	}
	:global(body){
        background-color: white;
        background-image: url("https://images.pexels.com/photos/956981/milky-way-starry-sky-night-sky-star-956981.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260");
    }
h1{
	padding:0,0,0,2;
    color:white;
  
    font-family: 'Montserrat ', sans-serif;
	padding:0;
	margin-block :0;
    font-size: 5.6rem;
	text-align:center;
}
	h2{
				 color:#9BE8D8;
 
		margin:0;
		margin-block :0;
    font-family: 'Montserrat ';
    font-size: 3rem;
		text-align:center;
		
	}
	img{
		-o-object-fit: contain;
  object-fit: contain;
  height: 200px;
		width:100%;
		padding:0,0,0,0;
		margin-block :0;
		
   margin-bottom:-7px;
		
}
</style>
