<template>
    <div>
        <h2> This is the description of the pessoa: {{ nome }} </h2>
        <info /> 
    </div>
</template>

<script>

import info from './info'

export default {
    name: 'People',
    components: {
        info
    },

    data() {
        return {
            nome: 'Daniel Lagares'
        }
    }
}
</script>