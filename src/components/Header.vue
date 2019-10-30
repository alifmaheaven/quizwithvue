<template>
    <div>
        <b-nav tabs>
            <b-nav-item disabled> <b>Active Fancy Quize App</b> </b-nav-item>
            <b-nav-item disabled>Counter : {{numCorrect}}/{{numTotal}}</b-nav-item>
            <!-- <b-nav-item>Another Link</b-nav-item>
            <b-nav-item disabled>Disabled</b-nav-item> -->
        </b-nav>
    </div>
</template>

<script>
export default {
    props:[
        'numCorrect',
        'numTotal'
    ]
}
</script>
