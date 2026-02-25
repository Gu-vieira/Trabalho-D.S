gustavo vieira
- **Turma/Turno:** desenvovimento de sistemas/noite
- **Data de entrega:** [24/02/2026]

## 2. Contexto do MVP
Este projeto entrega um sftware de suporte, para registro e acompanhamento de solicitações, conta com um servidor local e um externo

## 3. Link da aplicação em nuvem
https://trabalho-d-s-4.onrender.com
status: offiline

## 4. Requisitos não funcionais adotados (resumo)

### Qualidade
- tudo está funcionando corretamente, porem a aplicação na nuvem não foi possivel
### Integridade
- tudo está funcionando corretamente, porem a aplicação na nuvem não foi possivel
### Usabilidade (técnica)
- o servidor local está funcionando corretamente, porem na nuvem esta dando falha
### Segurança da informação
- tudo está funcionando corretamente, porem a aplicação na nuvem não foi possivel

  ## 5. Tecnologias e justificativas
- **Linguagem/Runtime:** Python
- **Framework:** flask
- **Bibliotecas relevantes:** flask,  request, jsonify, render_template
- **Nuvem/Deploy:** https://trabalho-d-s-4.onrender.com
- **Justificativa vinculada aos RNFs:**
 - eu usei o flask por ser framework de facil utilização
   
   ## 6. Integração via API (o que foi integrado)
o api oferce uma comunicação entre cliente e servidor onde sera possivel fazer uma solicitação

    ## 7. Endpoints do MVP (API)
| POST | /solicitacoes | Cria solicitação | {...} | 201, 400 |
| GET | /solicitacoes | Lista solicitações | filtros | 200 |
| GET | /solicitacoes/{id} | Detalha solicitação | id | 200, 404 |

## 8. Como executar localmente
### Pré-requisitos
runtime

### Variáveis de ambiente
**Não versionar segredos**

### Passos
1. [clicar em "start debugging"]
2. [o sistema processa de codificação]
3. [vai gerar a url]
