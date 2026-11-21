# GWD Sales OS — Staging Integration & Upstream Attribution

**Organization:** GoWorld.Digital (GWD)  
**Upstream Project:** [DeskcommCRM](https://github.com/melgarafael/DeskcommCRM) (MIT License)  
**Pinned Upstream Commit:** `e1a1b2d6f2b8213254827d6ad830c320b9014450`  
**License:** MIT (Preserved)

---

## 1. Contexto e Soberania Técnica

Este repositório é o fork oficial e público da GoWorld.Digital para o sistema operacional de vendas da **BU03 (Sales & Customer Operations)**.

- **Isolamento Absoluto:** Nenhuma base de dados, credencial, cliente ou configuração de outras entidades (ex: AtlasHub) é importada ou executada neste repositório.
- **Ambiente de Homologação (Staging):** Opera exclusivamente em ambiente local/loopback e liga-se ao **GWD Ops Core** através do adaptador seguro e autenticado [`services/crm-adapter`](https://github.com/GoWorld-Digital/gwd-core/tree/feat/gwd-crm-adapter/services/crm-adapter) em `gwd-core`.
- **Governança Comercial:** Nenhuma proposta, desconto ou compromisso financeiro pode ser enviado a clientes reais sem a aprovação humana obrigatória do Conselho (`A3`). Canais externos de envio de mensagens permanecem desativados no staging.
