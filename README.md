<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Offline - New Indian Express E-Paper</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}body{min-height:100vh;font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:linear-gradient(135deg,#f8fafc,#e0e7ff);display:flex;align-items:center;justify-content:center;padding:2rem;text-align:center;color:#0f172a}.container{max-width:28rem}.icon{font-size:5rem;margin-bottom:1.5rem;opacity:.7}.title{font-size:1.75rem;font-weight:700;margin-bottom:.75rem}.message{font-size:1rem;color:#64748b;margin-bottom:2rem;line-height:1.6}.btn{display:inline-block;padding:1rem 2rem;background:linear-gradient(135deg,#3b82f6,#8b5cf6);color:#fff;text-decoration:none;border-radius:1rem;font-weight:600;transition:transform .2s;border:none;cursor:pointer;font-size:1rem}.btn:hover{transform:translateY(-2px)}.btn:active{transform:scale(.98)}@media (prefers-color-scheme:dark){body{background:linear-gradient(135deg,#0a0e1a,#1a1f35);color:#f1f5f9}.message{color:#94a3b8}}
</style>
</head>
<body>
<div class="container">
  <div class="icon">📡</div>
  <h1 class="title">You're Offline</h1>
  <p class="message">
    Looks like you've lost your internet connection. 
    Please check your network and try again.
  </p>
  <button class="btn" onclick="location.reload()">Try Again</button>
</div>
<script>
window.addEventListener('online',()=>{location.reload()});
</script>
</body>
</html>
