<template>
<div class="main__contents">
    <header>
        <form>
            <img src="../assets/search-normal.png" alt="search">
            <input type="text">
            <button type="submit">Search</button>
        </form>
        <div class="icon__holder">
            <img src="../assets/notification.png" alt="notification">      
        </div>
        <div class="icon__holder">
            <img src="../assets/setting-2.png" alt="setting">
        </div>
    </header>
    <Herocards />
    <Table />
</div>
</template>
<script>
import Herocards from './Herocards.vue'
import Table from './Table.vue'
export default {
  components: { Herocards, Table },
    setup() {
        
    },
}
</script>
<style scoped>
    .main__contents{
        width: 100%;
        height: 100%;
        padding: .5em 1em;
        background: rgba(128, 203, 255, 0.1);
    }
    header{
        padding: .5em 1em;
        display: flex;
        width: 100%;
        justify-content: space-between;
        align-items: center;
    }
    header form{
        width: 70%;
        background: white;
        position: relative;
        border-radius: 10px;
        height: 50px;
    }
    .icon__holder{
        background: white;
        width: 50px;
        height: 50px;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
    }
    header form input{
        width: 80%;
        padding: 1em;
        border: none;
        outline: none;
        border-radius: 10px;
        padding-left: 4em;
        height: 100%;
    }
    header form img{
        position: absolute;
        top: 50%;
        left: 10px;
        transform: translateY(-50%);
    }
    header form button{
        width: 20%;
        background: rgba(8, 98, 160, 1);
        color: white;
        transform: translateX(-5px);
        border-radius: 10px;
        border: none;
        outline: none;
        height: 85%;
        font-weight: 600;
        letter-spacing: 1px;
        cursor: pointer;
    }
    .header img{
        width: 45px;
        height: 45px;
    }
</style>