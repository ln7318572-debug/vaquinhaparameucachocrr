
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ajude Meu Cachorro ❤️</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
    font-family:Arial,Helvetica,sans-serif;
    background:linear-gradient(135deg,#eef7f1,#d7f5e2);
    color:#333;
    padding:30px;
}
.container{
    max-width:820px;
    margin:auto;
    background:#fff;
    border-radius:18px;
    overflow:hidden;
    box-shadow:0 12px 30px rgba(0,0,0,.15);
}
header{
    background:#28a745;
    color:#fff;
    text-align:center;
    padding:24px;
}
img{
    width:100%;
    display:block;
}
.content{padding:24px}
.meta{display:flex;justify-content:space-between;font-weight:bold;margin:18px 0}
.barra{
    background:#e5e5e5;
    border-radius:999px;
    overflow:hidden;
    height:28px;
}
.progresso{
    width:20%;
    height:100%;
    background:#28a745;
    color:#fff;
    text-align:center;
    line-height:28px;
    font-weight:bold;
}
.pix{
    margin-top:24px;
    background:#f8f9fa;
    border:2px dashed #28a745;
    padding:18px;
    border-radius:12px;
}
.pixcode{
    background:#fff;
    border:1px solid #ccc;
    border-radius:8px;
    padding:12px;
    margin:12px 0;
    word-break:break-all;
}
button{
    background:#28a745;
    color:#fff;
    border:none;
    padding:12px 18px;
    border-radius:8px;
    cursor:pointer;
    font-size:16px;
}
button:hover{background:#218838}
#msg{margin-top:10px;color:#28a745;font-weight:bold}
</style>
</head>
<body>
<div class="container">
<header>
<h1>🐶 Ajude Meu Cachorro</h1>
<p>Toda contribuição faz diferença ❤️</p>
</header>

<img src="52cc6c7aa309a72c168a2e13c1f7357f.jpg" alt="Foto do cachorro">

<div class="content">
<p>Meu cachorro está lutando contra o câncer e precisa de tratamento urgente. Qualquer ajuda é muito bem-vinda.</p>

<div class="meta">
<span>Meta: R$ 2.500,00</span>
<span>Arrecadado: R$ 500,00</span>
</div>

<div class="barra">
<div class="progresso">20%</div>
</div>

<div class="pix">
<h3>💚 Chave PIX</h3>
<div id="pix" class="pixcode">71675244170</div>
<button onclick="copiarPix()">Copiar chave PIX</button>
<div id="msg"></div>
</div>
</div>
</div>

<script>
function copiarPix(){
    const chave=document.getElementById("pix").innerText;
    navigator.clipboard.writeText(chave).then(()=>{
        document.getElementById("msg").innerText="✅ Chave PIX copiada!";
    }).catch(()=>{
        document.getElementById("msg").innerText="Não foi possível copiar.";
    });
}
</script>
</body>
</html>
