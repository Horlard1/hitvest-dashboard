<template>
    <div class="display_table">
        <div class="table__ctrl">
            <div class="payment__ctrl">
                <button class="active">Deposit</button>
                <button>Withdrawal</button>
                <button>Interest</button>
            </div>
            <div class="data__ctrl">
                <span class="d-active"><img src="../assets/calendar.png" alt="calendar"></span>
                <span class="d-active">D</span>
                <span>W</span>
                <span>M</span>
                <span>Y</span>
            </div>
        </div>
        <table>
            <thead>
                <tr>
                    <th>S/N</th>
                    <th>Date</th>
                    <th>Transaction ID</th>
                    <th>Amount</th>
                    <th>Wallet Balance</th>
                    <th>Details</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
                <tr>
                    <td>5</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>12/12/2021</td>
                    <td>#565542554</td>
                    <td>$ 60,000</td>
                    <td>$ 60,000</td>
                    <td>You have got a sign up bonus</td>
                </tr>
            </tbody>
        </table>
        <button class="views__btn">View All <img src="../assets/arrow.png" alt="arrow"></button>
    </div>
</template>
<script>
export default {
    setup() {
        
    },
}
</script>

<style scoped>
    .display_table{
        background: white;
        padding: .5em 1em;
        width: 97%;
        margin: 1em auto;
        border-radius: 40px;
        display: flex;
        flex-direction: column;
    }
    .table__ctrl{
        display: flex;
        justify-content: space-between;
        margin: .5em 0 1em;
    }
    .payment__ctrl button{
        border: none;
        outline: none;
        padding: 1em 1.5em;
        margin-right: 1em;
        cursor: pointer;
        font-weight: 600;
        border-radius: 10px;
        background: transparent;
        color: rgba(140, 136, 136, 1);
    }
    .payment__ctrl button.active{
        background: #0863a047;
        color: rgba(8, 98, 160, 1);
    }
    .data__ctrl{
        display: flex;
    }
    .data__ctrl span{
        width: 40px;
        height: 40px;
        background: rgba(196, 196, 196, 1);
        margin-right: 1em;
        display: flex;
        justify-content: center;
        align-items: center;
        font-weight: 600;
        border-radius: 8px;
        cursor: pointer;
        color: rgba(87, 83, 83, 1);
    }
    .data__ctrl span.d-active{
        color: rgba(8, 98, 160, 1);
        background: #0863a047;
    }
    table{
        width: 100%;
    }
    th{
        text-align: left;
        padding-left: 2em;
        color: rgba(140, 136, 136, 1);
        padding-bottom: .5em;
    }
    td{
        text-align: left;
        padding: .7em 0 .5em 2em;
        color: rgba(140, 136, 136, 1);
    }
    .views__btn{
        padding: .7em 2em;
        background: #0863a047;
        outline: none;
        border: none;
        font-size: 15px;
        font-weight: 600;
        border-radius: 10px;
        color: rgba(8, 98, 160, 1);
        width: 15%;
        align-self: flex-end;
        margin: .5em 0 0;
        transform: translateX(-50%);
        display: flex;
        align-items: center;
    }
    .views__btn img{
        margin-left: .5em;
    }
</style>