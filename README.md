# Plano-Leve-  
App plano Leve    
     <h1 id="saudacao">Seja bem-vinda!</h1>

<script>
  const urlParams = new URLSearchParams(window.location.search);
  const nomeCliente = urlParams.get('nome');

  if (nomeCliente) {
    document.getElementById('saudacao').innerText = `Olá, ${decodeURIComponent(nomeCliente)}! Seja bem-vinda!`;
  }
</script>
