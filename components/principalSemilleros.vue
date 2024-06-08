<script setup>
const props = defineProps({
    nombre: String,
    programa: String,
    facultad: String,
})
</script>
<template>
    <div>
        <Card class="w-60">
            <template #content>
                <div class="flex flex-col justify-center items-center" >
                    <Avatar image="https://logowik.com/content/uploads/images/universidad-de-cordoba8857.logowik.com.webp" shape="circle" size="xlarge" />
                    <h2>{{ props.nombre }}</h2>
                    <p>{{props.programa}}</p>
                    <p>{{ props.facultad }}</p>
                </div>
            </template>
        </Card>
    </div>
</template>