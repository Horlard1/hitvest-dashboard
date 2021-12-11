<template>
    <div class="hero__cards">
        <div class="cards">
            <h3>Deposit Wallet</h3>
            <div class="card__details">
                <h2 class="deposit">$ 600k</h2>
                <span class="success">2.5%</span>
            </div>
            <img src="../assets/deposit.png" alt="deposit">
        </div>
        <div class="cards">
            <h3>Interest Wallet</h3>
            <div class="card__details">
                <h2 class="interest">$ 600k</h2>
                <span class="success-r">2.5%</span>
            </div>
            <img src="../assets/interest.png" alt="interest">
        </div>
        <div class="cards">
            <h3>Total Investment</h3>
            <div class="card__details">
                <h2 class="investment">$ 600k</h2>
                <span class="success-r">2.5%</span>
            </div>
            <img src="../assets/total.png" alt="total">
        </div>
        <div class="cards">
            <h3>Total Deposit</h3>
            <div class="card__details">
                <h2 class="total-d">$ 600k</h2>
                <span class="success">2.5%</span>
            </div>
            <img src="../assets/total-d.png" alt="total">
        </div>
        <div class="cards">
            <h3>Total Withdrawal</h3>
            <div class="card__details">
                <h2 class="withdraw">$ 600k</h2>
                <span class="success-r">2.5%</span>
            </div>
            <img src="../assets/withdraw.png" alt="withdraw">
        </div>
        <div class="cards">
            <h3>Referral Earnings</h3>
            <div class="card__details">
                <h2 class="referal">$ 600k</h2>
                <span class="success">2.5%</span>
            </div>
            <img src="../assets/referal.png" alt="referal">
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
    .hero__cards{
        width: 100%;
        padding: 1em;
        display: grid;
        grid-template-columns: repeat(6, minmax(160px, 1fr));
        grid-gap: 1.5em;
    }
    .cards{
        display: flex;
        flex-direction: column;
        background: white;
        padding: 1em 0 0;
        border-radius: 10px;
    }
    .cards h3{
        padding: 0 .5em;
        font-size: 14px;
        color: #4B4747;
    }
    .cards .card__details{
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: .5em;
    }
    .card__details h2{
        font-size: 18px;
    }
    .card__details h2.deposit{
        color: rgba(242, 162, 24, 1);
    }
    .card__details h2.interest{
        color: rgba(88, 147, 243, 1);
    }
    .card__details h2.investment{
        color: rgba(235, 87, 87, 1);
    }
    .card__details h2.total-d{
        color: rgba(86, 204, 242, 1);
    }
    .card__details h2.withdraw{
        color: rgba(155, 81, 224, 1);
    }
    .card__details h2.referal{
        color: rgba(8, 98, 160, 1);
    }
    .card__details span{
        background: #219654ac;
        color: green;
        padding: 2px;
        padding-left: 20px;
        border-radius: 8px;
        font-size: 13px;
        font-weight: 600;
    }
    .card__details span.success-r{
        background: rgba(235, 87, 87, 0.444);
        color: #F12424;;
    }
</style>