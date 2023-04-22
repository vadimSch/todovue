<template>
    <div class="main-panel">
        <PanelContent/>
        <PanelInfo/>
    </div>
</template>

<script>

import PanelContent from './PanelContent.vue';
import PanelInfo from './PanelInfo.vue';

    export default {
        name: 'MainPanel',
        components: {
            PanelContent,
            PanelInfo
        }
    }

</script>