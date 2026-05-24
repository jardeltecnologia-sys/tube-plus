# Tube Plus V5.1 — Tela Apagada

Aplicativo Android de vídeo, áudio em segundo plano e sons para dormir.

## Repositório

```text
https://github.com/jardeltecnologia-sys/tube-plus.git
```

## Principal correção da V5.1

A V5.1 reforça a execução em segundo plano para o caso em que o usuário aperta o botão físico do celular para apagar a tela.

Agora o Sono Premium e o Vídeo BG usam:

```text
Foreground Service
WakeLock parcial
Notificação persistente
Botão Parar
```

## Como deve funcionar

1. Escolha um som na aba Sono.
2. Aperte o botão físico para apagar a tela.
3. O som continua tocando.
4. Para parar, use a notificação ou o botão dentro do app.

## Observação

Em celulares com economia de bateria agressiva, pode ser necessário permitir execução em segundo plano nas configurações do Android.

## Artifact

```text
Tube-Plus-V5-1-debug-apk
```
