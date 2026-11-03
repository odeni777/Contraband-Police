# Contraband Co-op IL2CPP — v0.2.2

Plugin experimental de presença e movimento para os arquivos de Contraband Police v10.6.4 analisados.

## Download

[Baixar o plugin ZIP](ContrabandCoop-0.2.2-IL2CPP-v10.6.4.zip?raw=true)

- Plataforma: Windows x64, Unity IL2CPP 2022.3.52f1, metadata v31.
- Requer BepInEx 6 Unity.IL2CPP com suporte a metadata v31. Loader não incluído.
- O ZIP contém instruções, configuração de exemplo e somente as três DLLs do plugin/rede.
- Compilação e testes de rede passaram; o funcionamento dentro do jogo ainda não foi validado.
- Este protótipo sincroniza posição/rotação com uma cápsula visual. Não sincroniza missões, NPCs, inventário ou veículos.

SHA-256 do ZIP: `d6ddfa526f6cf1ac6afafd7e3cd3ecfbb8475e527d91796d8ef0e7123154e0f3`

Atualização 0.2.1: polling em segundo plano e diagnóstico com IP/porta. ConnectionFailed ainda exige conferir host, rede e firewall; a atualização não garante corrigir um bloqueio externo.

Atualização 0.2.2: F6/F7 preservam sessões ativas; logs registram polling, tráfego e admissão sem expor a chave. Validada em 14 testes/259 asserções. A causa do timeout entre os PCs ainda depende dos novos logs.
