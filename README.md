# 4TaxScope - Releases & Distribuição Oficial 🚀

Repositório oficial de distribuição e binários homologados do **4TaxScope** — Solução corporativa de alta precisão para Dimensionamento Fiscal, Volumetria e Arquitetura de Soluções Fiscais SAP ECC e S/4HANA, desenvolvida pela **SPS Group & 4Solve**.

---

## 📥 Como Efetuar o Download

### 🌐 1. Portal Web Protegido (Recomendado para Clientes)
Para garantir a segurança dos clientes e parceiros credenciados, o download oficial pode ser realizado através do portal exclusivo com chave de acesso:

* **URL de Download:** [https://taxscope4solve.web.app/download](https://taxscope4solve.web.app/download)
* **Link Direto com Chave Autorizada:** [https://taxscope4solve.web.app/download?k=taxscope4solve](https://taxscope4solve.web.app/download?k=taxscope4solve)
* **Código de Acesso:** `taxscope4solve`

### 📦 2. GitHub Releases
Você também pode baixar os executáveis diretamente pela aba [Releases deste repositório](https://github.com/alissonramos22/4taxscope-Releases/releases).

---

## ⚡ Guia Rápido de Instalação e Execução

O **4TaxScope** foi projetado para ser **100% Portátil**, eliminando entraves de governança corporativa de TI:

1. **Baixar o Executável:** Faça o download do arquivo `TaxScope.exe`.
2. **Sem Instalação:** Não é necessário possuir privilégios de Administrador de TI. Salve o executável em qualquer pasta de trabalho no seu computador (ex: `C:\SPS\TaxScope` ou em sua pasta `Documentos`).
3. **Execução:** Dê um duplo clique em `TaxScope.exe` para iniciar. O sistema carrega o backend local e o painel executivo imediatamente.
4. **Aviso Windows SmartScreen:** Por ser um executável corporativo exclusivo, caso o Windows exiba a tela azul *"O Windows protegeu o seu computador"*:
   - Clique em **"Mais informações"**
   - Em seguida, clique em **"Executar assim mesmo"**
5. **Auto-Atualização Integrada:** O 4TaxScope verifica periodicamente novos hotfixes e atualizações cadastrados no serviço em nuvem Firebase. Quando uma nova versão é detectada, o aplicativo efetua o download e a substituição transparente no boot.

---

## 🛠️ Requisitos de Sistema

| Componente | Requisito Recomendado |
| :--- | :--- |
| **Sistema Operacional** | Windows 10 ou Windows 11 (64-bit) |
| **Memória RAM** | 4 GB ou superior |
| **Espaço em Disco** | 250 MB livres |
| **Conexão** | Acesso à Internet para sincronização de questionários remotos e auto-atualização |
| **Compatibilidade SAP** | SAP Business One (HANA & SQL Server) / SAP ECC / SAP S/4HANA |

---

## 📋 Tabela de Releases & Histórico de Versões

| Versão | Data | Status | Destaques da Release |
| :--- | :---: | :---: | :--- |
| **v1.2.0-hf2** | Set/2026 | 🟢 Homologada (Atual) | Portal de download protegido, auto-update silencioso via Firebase, parâmetros compostos (doc/itens), sistema de abas departamentais, portabilidade de queries da empresa e e-mail SMTP integrado. |
| **v1.2.0-hf1** | Set/2026 | ⚪ Legada | Sincronização de questionários via Firebase Firestore, filtros avançados e revisão por e-mail. |
| **v1.1.0** | Ago/2026 | ⚪ Legada | Exportador executivo em PDF e planilhas dinâmicas Excel (.xlsx). |
| **v1.0.0** | Jul/2026 | ⚪ Legada | Lançamento inicial do motor de dimensionamento fiscal e catálogo SAP. |

---

## 🔒 Segurança, Confiabilidade e Governança

* **Tráfego Criptografado:** Toda comunicação com o serviço em nuvem utiliza protocolo TLS 1.3 / HTTPS.
* **Integridade de Dados:** Exportações de projetos protegidas por chave criptográfica proprietária (`.taxscope`).
* **Privacidade:** Nenhuma senha ou credencial sensível de banco de dados SAP é enviada para a nuvem.

---

## 📞 Suporte e Contato

Em caso de dúvidas técnicas, solicitação de novas chaves de acesso ou suporte a projetos:

* **SPS Group & 4Solve**
* **Repositório Principal:** [https://github.com/alissonramos22/4taxscope](https://github.com/alissonramos22/4taxscope)
* **Portal de Questionários do Cliente:** [https://taxscope4solve.web.app](https://taxscope4solve.web.app)

---
*Copyright © 2026 SPS Group. Todos os direitos reservados.*
