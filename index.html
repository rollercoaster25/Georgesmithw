<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Secure Wallet</title>

<style>
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
  display:flex;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  color:#fff;
}

.container{
  width:90%;
  max-width:420px;
  background:#111;
  padding:20px;
  border-radius:14px;
  box-shadow:0 10px 40px rgba(0,0,0,.6);
}

.hidden{display:none}

.card{
  background:#1e1e1e;
  padding:14px;
  border-radius:10px;
  margin-bottom:14px;
}

.row{
  display:flex;
  justify-content:space-between;
}

.green{color:#2ecc71;font-weight:bold}
.red{color:#e74c3c;font-weight:bold}
.small{font-size:12px;color:#aaa}

input,button{
  width:100%;
  padding:12px;
  margin-top:8px;
  border:none;
  border-radius:8px;
}

input{
  background:#222;
  color:#fff;
}

button{
  background:#1abc9c;
  font-weight:bold;
  cursor:pointer;
}

.spinner{
  width:36px;
  height:36px;
  border:4px solid #333;
  border-top:4px solid #1abc9c;
  border-radius:50%;
  margin:20px auto;
  animation:spin 1s linear infinite;
}

@keyframes spin{to{transform:rotate(360deg)}}

.tx{
  padding:10px 0;
  border-bottom:1px solid #333;
}
</style>
</head>

<body>

<!-- LOGIN -->
<div class="container" id="login">
  <h2>Trust Investment Wallet</h2>
  <input placeholder="Email">
  <input type="password" placeholder="Password">
  <button onclick="go('dashboard')">Login</button>
</div>

<!-- DASHBOARD -->
<div class="container hidden" id="dashboard">
  <h2>GEORGE SMITH</h2>

  <div class="card">
    <div class="row">
      <span>Main Balance</span>
      <span id="mainBal" class="green">$130,000 USD</span>
    </div>
    <div class="row">
      <span>Gas Balance</span>
      <span id="gasBal" class="green">933</span>
    </div>
  </div>

  <button onclick="go('withdraw')">Withdraw</button>

  <div class="card">
    <strong>Recent Transactions</strong>
    <div id="txList">
      <div class="tx"><span class="green">$363 CREDIT</span></div>
      <div class="tx"><span class="red">-$85 DEBIT</span></div>
    </div>
  </div>
</div>

<!-- WITHDRAW FORM -->
<div class="container hidden" id="withdraw">
  <h2>Withdraw Funds</h2>

  <input id="wName" placeholder="Account Name">
  <input id="wNumber" placeholder="Account Number">
  <input id="wBank" placeholder="Bank Name">
  <input id="wAmount" placeholder="Amount">

  <button onclick="submitWithdraw()">Send</button>
  <button onclick="go('dashboard')">Cancel</button>
</div>

<!-- PROCESSING -->
<div class="container hidden" id="processing">
  <h2>Processing</h2>
  <div class="spinner"></div>
  <p class="small" style="text-align:center">Confirming withdrawal…</p>
</div>

<!-- SUCCESS -->
<div class="container hidden" id="success">
  <h2>Withdrawal Successful money arrives in the next 18hours 34mins.</h2>

  <div class="card">
    <p><strong>Account Name:</strong> <span id="sName"></span></p>
    <p><strong>Account Number:</strong> <span id="sNumber"></span></p>
    <p><strong>Bank:</strong> <span id="sBank"></span></p>
    <p><strong>Amount:</strong> <span id="sAmount"></span></p>
    <p class="small">Gas fee applied</p>
  </div>

  <button onclick="finishWithdraw()">Done</button>
</div>

<script>
let withdrawData={};

function go(id){
  document.querySelectorAll('.container')
    .forEach(c=>c.classList.add('hidden'));
  document.getElementById(id).classList.remove('hidden');
}

function submitWithdraw(){
  withdrawData={
    name:wName.value,
    number:wNumber.value,
    bank:wBank.value,
    amount:wAmount.value
  };

  if(!withdrawData.name||!withdrawData.number||!withdrawData.bank||!withdrawData.amount){
    alert("Fill all fields");
    return;
  }

  go('processing');

  setTimeout(()=>{
    sName.innerText=withdrawData.name;
    sNumber.innerText=withdrawData.number;
    sBank.innerText=withdrawData.bank;
    sAmount.innerText='$'+withdrawData.amount;

    go('success');
  },3000);
}

function finishWithdraw(){
  mainBal.innerText='$0.00';
  gasBal.innerText='0.03';

  const tx=document.createElement('div');
  tx.className='tx';
  tx.innerHTML='<span class="red">-$'+withdrawData.amount+' Withdrawal</span>';
  document.getElementById('txList').appendChild(tx);

  go('dashboard');
}
</script>

</body>
</html>
