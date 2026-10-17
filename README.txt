BOMBA PATCH MOBILE 2026/27 — ANDROID CLOUD BUILD
Protótipo inicial leve: menu clássico e mini-jogo 2D visto de cima, com controles touch.
Este ainda não é o jogo 3D completo nem inclui elencos licenciados.

COMO GERAR O APK USANDO SÓ O CELULAR:
1. Extraia o ZIP (ou envie o ZIP para o GitHub sem extrair, se o GitHub permitir; o mais fácil é extrair com o gerenciador de arquivos).
2. No navegador, entre em github.com e crie uma conta ou entre.
3. Crie um repositório novo chamado BombaPatchMobile. Marque Public se quiser usar Actions grátis com menos complicações.
4. Faça upload dos arquivos e pastas que estão dentro desta pasta do projeto. Importante: envie também a pasta oculta .github/workflows/build-apk.yml. Se o app do GitHub esconder pastas, use o navegador em modo desktop.
5. Depois de enviar, abra a aba Actions do repositório.
6. Se aparecer a mensagem para habilitar Actions, habilite.
7. Abra “Build Bomba Patch APK” e toque “Run workflow”.
8. Quando terminar com marca verde, abra a execução e baixe o artefato “BombaPatchMobile-debug-apk”.
9. Extraia o ZIP do artefato; dentro estará app-debug.apk. Toque nele para instalar. Talvez seja necessário permitir instalação desta fonte.

TAMANHO:
- O projeto-fonte é pequeno; o APK final pode ter alguns MB.
- O APK é compilado na nuvem, então não precisa instalar Godot/Android Studio no celular.
- Requer internet para enviar o projeto e baixar o APK.
- Se der erro no build, copie a mensagem do GitHub Actions para que possamos corrigir.

PRÓXIMAS ETAPAS:
1. Melhorar gameplay, IA e física.
2. Evoluir para 3D leve.
3. Adicionar times, uniformes, ligas e campeonatos.
