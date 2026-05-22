# COMAP Campo · App de Fiscalização

App PWA mobile para fiscais em campo. Sincroniza automaticamente com o [Sistema Principal COMAP](https://comaptjmg.github.io/comap-tjmg/).

## Funcionalidades
- 📋 **Diário de Fiscalização** — registro diário de atividades
- 🚨 **OSE** — visualização das ordens emergenciais da sua região
- 🔄 **Periódicas** — manutenções programadas
- 🔄 **Sincronização automática** — dados enviados ao sistema principal

## Acesso
**URL**: https://comaptjmg.github.io/comap-campo/

## Comunicação entre sistemas
- App de campo lê dados do `comap-tjmg/data/`
- App de campo escreve em `comap-campo/data/registros.json`
- Registros do diário são sincronizados em `comap-tjmg/data/diario.json`
