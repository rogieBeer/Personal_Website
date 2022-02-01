// CSS for the main title in the navbar

<template>
    <div class="title">
        <h1 style="cursor: pointer" @click="$router.push('/')">@rogieBeer</h1>
    </div>
</template>

<script>
export default {
    name: 'Title',
    data: () => ({

    }), 
  }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Montserrat');

.title {
	font-family: "Montserrat";
	text-align: center;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	letter-spacing: 1px;
	
}

h1 {
	font-size: 15px;
	line-height: .75;
	margin: 10px 0;
	color: #EFEBE9;
}
</style>