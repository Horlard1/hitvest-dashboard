<template>
    <div class="main__nav">
        <img alt="logo" class="logo" src="../assets/logo.png" />
        <p class="menu">Menu</p>
        <ul>
            <li class="active"><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Dashboard</p></li>
            <li><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Investment</p></li>
            <li><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Deposit</p></li>
            <li><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Withdraw</p></li>
            <li><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Transactions</p></li>
            <li><img class="svgs" alt="icons" src="../assets/category.svg"/><p>Referrals</p></li>
        </ul>
        <div class="display__details">
            <img src="../assets/photo.png" alt="user photo">
            <h3>Sandy Oluwatobi</h3>
            <button>View Profile</button>
            <a href="">Copy Referral link</a>
            <span>Log out</span>
        </div>
    </div>
</template>
<script>
export default {
    setup() {
        
    },
}
</script>

<style scoped>
    .main__nav{
        width: 300px;
        display: flex;
        flex-direction: column;
    }
    .main__nav .logo{
        width: 196px;
        align-self: center;
        height: 70px;
        object-fit: cover;
    }
    .main__nav p{
        color: rgba(196, 196, 196, 0.8);
    }
    .main__nav p.menu{
        margin: 1em 0 0 1.5em;
    }
    ul{
        padding: .5em 1em;
    }
    img.svgs{
        color: black;
        margin-right: 1em;
        width: 20px;
        height: 20px;
    }
    ul li{
        display: flex;
        border-radius: 20px;
        align-items: center;
        margin: .2em 0;
        padding: .9em 3em;
        cursor: pointer;
    }
    ul li:hover{
        background: rgba(8, 98, 160, 1);
    }
    /* .main__nav ul li p{
        color: white;
    } */
    .display__details{
        display: flex;
        flex-direction: column;
        height: 300px;
        align-items: center;
        padding: .2em 2em;
        box-shadow: 4px 8px 8px rgba(8, 98, 160, 0.05);
        border-radius: 20px;
    }
    .display__details img{
        width: 60px;
        height: 60px;

    }
    .display__details h3{
        margin: .5em 0;
        color: rgba(87, 83, 83, 1);
    }
    .display__details button{
        padding: 1em 3em;
        background: #0863a05a;
        outline: none;
        align-self: flex-start;
        width: 100%;
        border: none;
        color: rgba(8, 98, 160, 1);
        border-radius: 15px;
        margin: .1em 0;
    }
    .display__details a{
        height: 23px;
        font-weight: 500;
        font-size: 15px;
        line-height: 22px;
        text-decoration-line: underline;
        color: #0C8DE6;
        margin: 1em 0;
    }
</style>