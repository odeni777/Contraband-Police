# Contraband Co-op IL2CPP — v0.2.1

Plugin experimental de presença e movimento para os arquivos de Contraband Police v10.6.4 analisados.

## Download

[Baixar o plugin ZIP](ContrabandCoop-0.2.1-IL2CPP-v10.6.4.zip?raw=true)

- Plataforma: Windows x64, Unity IL2CPP 2022.3.52f1, metadata v31.
- Requer BepInEx 6 Unity.IL2CPP com suporte a metadata v31. Loader não incluído.
- O ZIP contém instruções, configuração de exemplo e somente as três DLLs do plugin/rede.
- Compilação e testes de rede passaram; o funcionamento dentro do jogo ainda não foi validado.
- Este protótipo sincroniza posição/rotação com uma cápsula visual. Não sincroniza missões, NPCs, inventário ou veículos.

SHA-256 do ZIP: `25fd844a6e719ed09288cf447ef220180743bbe8baa9774c048597faa077d60c`

Atualização 0.2.1: polling em segundo plano e diagnóstico com IP/porta. ConnectionFailed ainda exige conferir host, rede e firewall; a atualização não garante corrigir um bloqueio externo.
