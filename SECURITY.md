# 🛡️ Política de Segurança — Bio+Tech EduDesign

<div align="center">
<img src="https://github.com/Bio-Tech-Edu/.github/raw/main/profile/biotech_edudesign.png" alt="Bio+Tech EduDesign" height="60">
</div>

---

## 🔒 Nosso compromisso com a segurança

A comunidade **Bio+Tech EduDesign** leva a sério a segurança de seus recursos educacionais, código-fonte e — especialmente — dos **dados de estudantes, educadores(as) e contribuidores(as)** que interagem com nossos projetos.

Este documento descreve como **reportar vulnerabilidades**, quais **versões são suportadas** e como respondemos a incidentes.

---

## ✅ Versões suportadas

| Versão | Status de suporte de segurança |
|:---:|:---:|
| `main` (última estável) | ✅ Suportada |
| `develop` (em desenvolvimento) | ⚠️ Parcial |
| Versões anteriores | ❌ Não suportadas |

Recomendamos sempre usar a versão mais recente publicada na branch `main` dos repositórios.

---

## 🐛 Como reportar uma vulnerabilidade

**Por favor, NÃO abra uma issue pública para relatar vulnerabilidades de segurança.**

Em vez disso, siga este processo confidencial:

### 📧 Canal preferencial
Use o recurso [**Report a vulnerability**](../../security/advisories/new) do GitHub Security Advisories neste repositório. Isso cria um canal privado entre você e a equipe mantenedora.

### 📨 Canal alternativo
Envie mensagem direta via GitHub para a mantenedora principal:
- 👤 [@pamellabiotec](https://github.com/pamellabiotec)

### 📋 Informações a incluir no relatório

Para acelerar a análise, inclua:

1. **Descrição clara** da vulnerabilidade.
2. **Repositório e versão** afetados.
3. **Passos para reproduzir** (PoC quando possível).
4. **Impacto potencial** (quem/o quê pode ser afetado).
5. **Sugestão de correção**, se tiver.
6. Se você deseja **crédito público** após a correção.

---

## ⏱️ Tempo de resposta

| Etapa | Prazo estimado |
|:---|:---:|
| Confirmação de recebimento | 48 horas úteis |
| Análise inicial e triagem | 7 dias úteis |
| Correção e publicação | Até 30 dias (conforme severidade) |
| Divulgação pública coordenada | Após patch disponível |

---

## 🚨 Escopo de segurança

### ✅ Dentro do escopo
- Vulnerabilidades em código dos repositórios da organização `Bio-Tech-Edu`.
- Exposição acidental de dados sensíveis (credenciais, dados de estudantes).
- Falhas de autenticação/autorização em sistemas educacionais publicados.
- Injeção de conteúdo malicioso em recursos educacionais abertos (REA).
- Dependências vulneráveis (CVE conhecidas) usadas no projeto.

### ❌ Fora do escopo
- Vulnerabilidades em serviços de terceiros (GitHub, Canva, Notion, Vercel, etc.) — reporte diretamente aos provedores.
- Ataques de engenharia social contra pessoas contribuidoras.
- Uso indevido de conteúdo por terceiros fora dos repositórios oficiais.

---

## 🤖 Segurança em contribuições assistidas por IA

Se você contribui com apoio de ferramentas de IA, redobre a atenção com:

- 🔑 **Credenciais e segredos:** nunca inclua tokens, chaves de API ou senhas — mesmo em exemplos.
- 📦 **Dependências:** valide pacotes sugeridos por IA (podem existir pacotes maliciosos com nomes similares — *typosquatting*).
- 🧪 **Código gerado:** execute análise estática (ex.: `bandit`, `npm audit`, `pip-audit`) antes de submeter PRs.

Consulte também nosso [Código de Conduta](CODE_OF_CONDUCT.md) na seção sobre uso responsável de IA.

---

## 🔐 Boas práticas para contribuidores(as)

- Ative **2FA** (autenticação de dois fatores) na sua conta GitHub.
- Assine seus commits com **GPG** ou **SSH** quando possível.
- Revise seus PRs em busca de dados sensíveis antes de enviar.
- Mantenha suas dependências locais atualizadas.
- Use ferramentas como [gitleaks](https://github.com/gitleaks/gitleaks) para escanear segredos antes do commit.

---

## 🏅 Reconhecimento (Hall of Thanks)

Pessoas que reportarem vulnerabilidades de forma responsável poderão ser reconhecidas publicamente (com autorização prévia) em um arquivo `SECURITY_ACKNOWLEDGMENTS.md`.

---

## 📚 Referências

- [GitHub Security Advisories](https://docs.github.com/pt/code-security/security-advisories)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Coordinated Vulnerability Disclosure (CVD)](https://www.cisa.gov/coordinated-vulnerability-disclosure-process)

---

<div align="center">

**🛡️ Segurança é um esforço coletivo. Obrigada por ajudar a proteger nossa comunidade. 💚**

</div>
