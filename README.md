# SINTONIA TV — projeto Android/Google TV

Este projeto empacota o SINTONIA_TV.html em um aplicativo Android TV/Google TV.

## O que já está preparado
- Aplicativo chamado SINTONIA
- Ícone de lançamento compatível com Google TV (Leanback)
- Tela cheia e orientação horizontal
- WebView com JavaScript, armazenamento local e reprodução de mídia
- Permissão de internet
- Navegação por teclado/controle remoto usando as setas e OK, conforme a versão HTML
- O HTML fica dentro do próprio APK, então não é necessário digitar a URL do Netlify para abrir o aplicativo.

## Para gerar o APK
Abra esta pasta no Android Studio e execute:
Build > Build Bundle(s) / APK(s) > Build APK(s)

O APK de debug ficará normalmente em:
app/build/outputs/apk/debug/app-debug.apk

## Observação importante
A lista M3U e os streams continuam sendo os definidos no HTML. O aplicativo não cria canais próprios nem garante que cada stream esteja disponível.
