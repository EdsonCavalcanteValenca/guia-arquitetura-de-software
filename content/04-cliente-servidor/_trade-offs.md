| Atributo | Efeito | Por quê |
|---|---|---|
| Gerenciamento centralizado | Favorecido | Regras de negócio e dados residem no servidor, facilitando atualizações sem reimplantação nos clientes. |
| Segurança | Favorecida | Ponto centralizado para autenticação, autorização e validação de regras de acesso a recursos sensíveis. |
| Reusabilidade | Favorecida | A mesma API/servidor atende múltiplos tipos de clientes (Web, Mobile, Desktop). |
| Disponibilidade | Comprometida | O servidor central representa um ponto único de falha (*Single Point of Failure*); se cair, o sistema fica inoperante. |
| Desempenho e Latência | Comprometido | Todas as solicitações trafegam via rede, adicionando latência em comparação com execução estritamente local. |
| Simplicidade operacional | Comprometida | Exige gestão de infraestrutura de rede, balanceamento de carga e monitoramento contínuo do servidor. |