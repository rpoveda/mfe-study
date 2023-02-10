<template>
    <div style="width:890px">
        <h1 style="color:green">{{ key }} - {{ teste }}</h1>
        <iframe width="883" src="https://www.globo.com/" />
    </div>    
</template>

<script>
export default {
    name: 'Header',
    props: ['key', 'teste'],
}
</script>