<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1">
<title>Vinculación Ciudadana - San Pedro</title>
<script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#fdf6e3] text-zinc-900 font-mono">
<div class="max-w-[420px] mx-auto min-h-screen border-4 border-red-800 bg-white shadow-2xl">

  <div class="bg-red-800 text-white p-4 text-center">
    <h1 class="font-black text-lg uppercase tracking-widest">Mpio de San Pedro</h1>
    <p class="text-xs opacity-80">Vinculación con Atención Ciudadana - Oficina Offline</p>
    <p class="text-[10px] mt-2 bg-white/20 inline-block px-2 py-1 rounded">Sanpedro.html • Cristianos ayudando a Cristianos</p>
  </div>

  <!-- INICIO -->
  <div class="p-4 space-y-4">
    <div class="border-2 border-red-800 rounded-full w-24 text-center py-1 mx-auto font-bold">INICIO</div>

    <div class="border-2 border-red-800 p-3 text-sm">
      <label class="font-bold">1. Datos del Ciudadano:</label>
      <input id="tel" placeholder="Teléfono" class="w-full mt-2 border p-2">
      <input id="dir" placeholder="Dirección - Colonia" class="w-full mt-2 border p-2">
      <input id="correo" placeholder="Correo @" class="w-full mt-2 border p-2">
    </div>

    <div class="border-2 border-red-800 p-3 text-sm">
      <p class="font-bold mb-2">¿En qué te ayudamos?</p>
      <label class="block"><input type="checkbox"> Pago de Serv. { Predial, Luz, Agua, Multas, Parquímetros }</label>
      <label class="block"><input type="checkbox"> Empleo</label>
      <label class="block"><input type="checkbox"> Atención Ciudadana</label>
      <label class="block"><input type="checkbox"> Citas con Alcalde</label>
      <label class="block"><input type="checkbox"> Citas con Regidores</label>
      <label class="block"><input type="checkbox"> Lista de Empresas que ofrecen empleo</label>
      <p class="text-[11px] mt-3 text-zinc-600">Ya tengo la app de Vinculación en Empleo Laguna integrada</p>
    </div>

    <div class="text-center">
      <div class="w-16 h-16 border-2 border-red-800 rotate-45 mx-auto flex items-center justify-center"><span class="-rotate-45 font-bold">SI / NO</span></div>
      <p class="text-xs mt-2">¿Se pudo resolver en ventanilla?</p>
      <div class="flex gap-2 mt-2">
        <button onclick="alert('Dios te bendiga - Pase a Programas Sociales')" class="flex-1 bg-green-700 text-white py-3 font-bold">SI - AYUDADO</button>
        <button onclick="document.getElementById('ayuda').scrollIntoView()" class="flex-1 bg-red-800 text-white py-3 font-bold">NO - CANALIZAR</button>
      </div>
    </div>

    <div id="ayuda" class="border-2 border-red-800 p-3 bg-yellow-50 text-sm">
      <p class="font-black uppercase text-red-800">Ayuda al Ciudadano - On Town México</p>
      <ul class="mt-2 space-y-1 list-disc pl-4">
        <li>Ayuda al Ciudadano</li>
        <li>CANALIZACIÓN A EMPLEO</li>
        <li>Descuentos</li>
        <li>Programas Sociales</li>
        <li>Educación</li>
        <li>Salud</li>
        <li>Bienestar</li>
      </ul>
      <p class="mt-3 text-[11px] font-bold">Un cristiano no puede ver morir de hambre a otro cristiano.</p>
      <button class="w-full mt-3 bg-black text-white py-2">Registrar y Enviar a WhatsApp de Presidencia</button>
    </div>

    <div class="border-2 border-red-800 rounded-full w-16 text-center py-1 mx-auto font-bold">FIN</div>
  </div>
</div>

<script>
// Guarda offline como querías
localStorage.setItem('sanpedro_offline', 'activo');
</script>
</body>
</html>
