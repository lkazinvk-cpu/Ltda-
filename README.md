# MHGU Recomp — tentativa de build para iOS

Este repositório reúne o código-fonte original `gu-native-0.1.6.zip` e o workflow do GitHub Actions usado para compilar uma IPA iOS.

## Como gerar a IPA

1. Crie um repositório novo no GitHub.
2. Envie para a raiz do repositório o arquivo `gu-native-0.1.6.zip`.
3. Envie a pasta `.github/workflows/` mantendo exatamente o caminho `.github/workflows/build-ios.yml`.
4. Abra a aba **Actions**.
5. Selecione **Build MHGU Recomp iOS IPA** e toque em **Run workflow**.
6. Quando terminar, abra a execução e baixe o artefato IPA, se o workflow tiver concluído com sucesso.

## Estado atual

- O código-fonte e o workflow foram reunidos para começar em um repositório limpo.
- A IPA gerada anteriormente fechou no LiveContainer; portanto, este projeto ainda não está validado como funcional no iPhone.
- A tela sem dados do jogo é apenas uma etapa de teste. O importador de arquivos iOS ainda não está implementado.
- Não coloque ROMs, dumps do jogo, chaves ou outros arquivos protegidos no repositório.

## Observação

O workflow aplica correções de compatibilidade durante o build. O código-fonte ZIP original é mantido sem alterações para podermos comparar e rastrear os patches.
