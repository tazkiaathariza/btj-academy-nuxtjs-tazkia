<template>
    <div>
        <p class="item my-2 p-2" @click="toIntro">Introduction</p>
            <hr/>
        <p class="item my-2 p-2" @click="toEdu">Education</p>
            <hr/>
        <p class="item my-2 p-2" @click="toWork">Work</p>
            <hr/>
        <p class="item my-2 p-2" @click="toPorto">Portfolio</p>
            <hr/>
        <p class="item my-2 p-2" @click="toOrg">Organization</p>
            <hr/>
        <p class="item my-2 p-2" @click="toContact">Contact</p>
    </div>
</template>

<script>
export default {
    methods: {
        toIntro(){
            alert("Redirect to intro")
            navigateTo('/admin/intro')
        },
           toEdu(){
            alert("Redirect to edu")
            navigateTo('/admin/edu')
        },
           toWork(){
            alert("Redirect to work")
            navigateTo('/admin/work')
        },
           toPorto(){
            alert("Redirect to portfolio")
            navigateTo('/admin/portfolio')
        },
           toOrg(){
            alert("Redirect to organization")
            navigateTo('/admin/organization')
        },
           toContact(){
            alert("Redirect to contact")
            navigateTo('/admin/contact')
        },
    }
}
</script>

<style>
#btj {
color: white;
}

.row {
    display: flex;
}

.sidebar {
   align-items: center;
    text-align: center;
    background-color: white;
    border-color:#AB3C41;
}

.item {
    color: #AB3C41;
}

.item:hover{
    cursor: pointer;
    color: white;
    background-color: #AB3C41;

    border-radius: 5px;
}
hr {
    color: #AB3C41;
}
</style>