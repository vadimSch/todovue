<template>
    <div class="panel-content">
        <TaskList/>
        <TaskAdd/>
    </div>   
</template>

<script>
    
import TaskList from './TaskList.vue';
import TaskAdd from './TaskAdd.vue';    
    
    export default {
        name: 'PanelContent',
        components: {
            TaskList,
            TaskAdd
        }
    }
</script>