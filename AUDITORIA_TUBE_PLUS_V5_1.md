# Auditoria — Tube Plus V5.1

## Problema corrigido

A V5 precisava deixar claro e reforçado que, ao apagar a tela pelo botão físico do celular, o áudio deveria continuar em segundo plano.

## Correções técnicas

- WakeLock parcial no SleepSoundService.
- WakeLock parcial no AudioPlayerService.
- Foreground Service mantido.
- Notificação persistente mantida.
- MainActivity não chama mais `stopSleep()` nem `stopBackgroundAudio()` no `onDestroy()`.

## Resultado esperado

- Som para dormir continua tocando com a tela apagada.
- Vídeo BG continua tocando com a tela apagada quando a fonte for link direto de mídia compatível.
- Parada manual pela notificação ou pelo app.
