<script>
    let buttonProps = {
    class:[$$restProps.class]
    }
</script>
    <button on:click 
        {...buttonProps}>
            <slot/>
    </button>
<style>
    .admin{
			height:40px;
			width:80px;
			background:#6528F7;
			 margin-top: 0;
		
  text-transform: inherit !important;
  background-color: black !important;
  color: white;
			margin-left:45%;
    }
    .user {
			
			height:40px;
			width:80px;
	
			 margin-top: 0px;
  text-transform: inherit !important;
  background-color: black !important;
  color: white;
		}
</style>
