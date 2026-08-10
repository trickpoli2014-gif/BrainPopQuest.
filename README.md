# BrainPop Quest 3.0 — Android Cloud Build

Este pacote contém a versão 3.0 do BrainPop Quest convertida para Android.

## O que já vem pronto
- Jogo BrainPop Quest 3.0 completo dentro do app
- Funciona offline
- Tela cheia
- Progresso salvo no aparelho
- Nome do app: BrainPop Quest
- Pacote: com.brainpop.quest
- Versão: 3.0
- Android mínimo: 6.0 (API 23)
- Workflow do GitHub Actions para gerar o APK na nuvem

## Como gerar o APK só pelo celular
1. Crie uma conta no GitHub (caso ainda não tenha).
2. Crie um novo repositório.
3. Envie TODOS os arquivos e pastas deste pacote para o repositório, mantendo a pasta .github.
4. Abra a aba Actions do repositório.
5. Abra “Build BrainPop Quest APK”.
6. Use “Run workflow”.
7. Quando terminar, abra a execução e baixe o artefato “BrainPop-Quest-3.0-APK”.
8. Dentro do ZIP baixado estará o arquivo app-debug.apk.
9. No Android, permita instalação de apps desconhecidos para o navegador/Meus Arquivos e instale o APK.

Observação: o APK gerado pelo workflow é uma versão de teste/debug. Para publicar na Play Store, depois é necessário gerar uma versão release assinada.
