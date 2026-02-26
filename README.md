# roksik<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUBG & MINECRAFT | LINKS</title>
    <style>
        body { font-family: -apple-system, system-ui, sans-serif; background-color: #0d0d0d; color: white; display: flex; flex-direction: column; align-items: center; min-height: 100vh; margin: 0; padding: 20px; }
        .container { width: 100%; max-width: 400px; text-align: center; margin-top: 10px; }
        h1 { font-size: 20px; margin-bottom: 25px; color: #fff; text-transform: uppercase; letter-spacing: 1px; }
        h2 { font-size: 18px; color: #ffcc00; margin-bottom: 15px; }
        
        .link-btn { display: flex; align-items: center; justify-content: center; background: #1a1a1a; color: white; text-decoration: none; padding: 16px; margin-bottom: 12px; border-radius: 14px; border: 1px solid #333; font-weight: bold; transition: 0.3s; cursor: pointer; width: 100%; box-sizing: border-box; }
        .link-btn:hover { background: #252525; transform: scale(1.02); border-color: #555; }
        
        /* Стили кнопок */
        .main-btn { border-left: 6px solid #0088cc; }
        .uc-btn { border-left: 6px solid #ffcc00; }
        .metro-btn { border-left: 6px solid #ff4444; }
        .mc-btn { border-left: 6px solid #4caf50; background: #1b2e1c; }
        .settings-btn { border-left: 6px solid #00ff88; background: #1e2a24; }

        .emoji { margin-right: 12px; font-size: 20px; }

        /* Окна с кодами */
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.9); z-index: 100; justify-content: center; align-items: center; padding: 20px; box-sizing: border-box; }
        .modal-content { background: #1a1a1a; padding: 25px; border-radius: 20px; border: 1px solid #444; width: 100%; max-width: 350px; position: relative; }
        .close-btn { position: absolute; top: 10px; right: 15px; font-size: 24px; cursor: pointer; color: #888; }
        
        .code-block { background: #000; padding: 12px; border-radius: 8px; margin: 10px 0; border: 1px dashed #555; font-family: monospace; font-size: 14px; color: #00ff88; word-break: break-all; text-align: left; }
        .label { font-size: 11px; color: #aaa; text-transform: uppercase; margin-top: 10px; text-align: left; }
    </style>
</head>
<body>

    <div class="container">
        <h1>Мои ресурсы</h1>
        
        <a href="https://t.me/pubgmobile76ua" class="link-btn main-btn" target="_blank"><span class="emoji">📱</span> Основной канал</a>
        <a href="https://t.me/roksus" class="link-btn uc-btn" target="_blank"><span class="emoji">💎</span> UC Шоп</a>
        <a href="https://t.me/roksmetro" class="link-btn metro-btn" target="_blank"><span class="emoji">🛒</span> Метро Шоп</a>
        <a href="https://t.me/rocksminecraft" class="link-btn mc-btn" target="_blank"><span class="emoji">🧱</span> Minecraft Канал</a>

        <hr style="border: 0; border-top: 1px solid #333; margin: 25px 0;">

        <div class="link-btn settings-btn" onclick="openModal('tdmModal')"><span class="emoji">🎯</span> Сенса и Раскладка TDM</div>
        <div class="link-btn settings-btn" onclick="openModal('metroModal')"><span class="emoji">🚇</span> Сенса и Раскладка METRO</div>
    </div>

    <div id="tdmModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('tdmModal')">&times;</span>
            <h2>НАСТРОЙКИ TDM</h2>
            <div class="label">ID Аккаунтов:</div>
            <div class="code-block">51826771261<br>51576068499</div>
            <div class="label">Код Сенсы:</div>
            <div class="code-block">1-7592-0962-9266-1637-679</div>
            <div class="label">Код Раскладки:</div>
            <div class="code-block">1-7592-0962-9266-1637-678</div>
        </div>
    </div>

    <div id="metroModal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeModal('metroModal')">&times;</span>
            <h2>НАСТРОЙКИ METRO</h2>
            <div class="label">Код Сенсы:</div>
            <div class="code-block">1-7599-9580-2673-5850-734</div>
            <div class="label">Код Раскладки:</div>
            <div class="code-block">1-7599-9580-2673-5850-733</div>
        </div>
    </div>

    <script>
        function openModal(id) { document.getElementById(id).style.display = 'flex'; }
        function closeModal(id) { document.getElementById(id).style.display = 'none'; }
        window.onclick = function(event) {
            if (event.target.className === 'modal') { event.target.style.display = 'none'; }
        }
    </script>

</body>
</html>
