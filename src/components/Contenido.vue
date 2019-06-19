<template>
    <div>
        <List col-8>
            <h1>{{tituloPeli}}</h1>
        </List>
        <Abm/>
    </div>
</template>

<script>
import List from './List.vue'
import Abm from './Abm.vue'

export default {
    name: 'Contenido',
    components: {
        List,
        Abm,
    }
}
</script>

