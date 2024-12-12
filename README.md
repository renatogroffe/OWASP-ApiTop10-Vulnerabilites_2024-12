# OWASP-ApiTop10-Vulnerabilites_2024-12
Materiais de apresentação sobre OWASP API Security Top 10 realizada no dia 11/12/2024. Inclui ainda informações sobre iniciativas da OWASP para Docker/containers e Inteligência Artificial.

Riscos que fazem parte da **OWASP Top 10 API Security Risks - 2023**:

```mermaid
block-beta
columns 1
  A["API1:2023 - Broken Object Level Authorization"]
  B["API2:2023 - Broken Authentication"]
  C["API3:2023 - Broken Object Property Level Authorization"]
  D["API4:2023 - Unrestricted Resource Consumption"]
  E["API5:2023 - Broken Function Level Authorization"]
  F["API6:2023 - Unrestricted Access to Sensitive Business Flows"]
  G["API7:2023 - Server Side Request Forgery"]
  H["API8:2023 - Security Misconfiguration"]
  I["API9:2023 - Improper Inventory Management"]
  J["API10:2023 - Unsafe Consumption of APIs"]
```

*OBSERVAÇÃO: Para acessar a listagem oficial clique neste [**link**](https://owasp.org/API-Security/editions/2023/en/0x11-t10/).*

---

## Outras iniciativas da OWASP

### OWASP Docker Top 10

Riscos que fazem parte da **OWASP Top 10 API Security Risks - 2023**:

```mermaid
block-beta
columns 1
  A["D01 - Secure User Mapping"]
  B["D02 - Patch Management Strategy"]
  C["D03 - Network Segmentation and Firewalling"]
  D["D04 - Secure Defaults and Hardening"]
  E["D05 - Maintain Security Contexts"]
  F["D06 - Protect Secrets"]
  G["D07 - Resource Protection"]
  H["D08 - Container Image Integrity and Origin"]
  I["D09 - Follow Immutable Paradigm"]
  J["D10 - Logging3"]
```

*ATENÇÃO: Esta lista ainda se encontra em desenvolvimento. Maiores detalhes podem ser encontrados em: https://github.com/OWASP/Docker-Security*

### OWASP Top 10 for LLMs and Gen AI Apps

Riscos que fazem parte da **OWASP Top 10 for LLMs and Gen AI Apps**:

```mermaid
block-beta
columns 1
  A["LLM01: Prompt Injection"]
  B["LLM02: Insecure Output Handling"]
  C["LLM03: Training Data Poisoning"]
  D["LLM04: Model Denial of Service"]
  E["LLM05: Supply Chain Vulnerabilities"]
  F["LLM06: Sensitive Information Disclosure"]
  G["LLM07: Insecure Plugin Design"]
  H["LLM08: Excessive Agency"]
  I["LLM09: Overreliance"]
  J["LLM10: Model Theft"]
```

*ATENÇÃO: Maiores detalhes podem ser encontrados em: https://genai.owasp.org/llm-top-10-2023-24/*

## Certificações Gratuitas da APIsec University

Site da APIsec University: **https://www.apisecuniversity.com/**

Artigos que produzi sobre alguns desses treinamentos/certificações:

[**Certificação Gratuita: OWASP API Security Top 10**](https://renatogroffe.medium.com/certifica%C3%A7%C3%A3o-gratuita-owasp-api-security-top-10-49187dadd141)

[**Certificação Gratuita: API Security Fundamentals**](https://renatogroffe.medium.com/certifica%C3%A7%C3%A3o-gratuita-api-security-fundamentals-40ff8a8f2eb0)

[**Certificação Gratuita: API Gateway Security Best Practices**](https://renatogroffe.medium.com/certifica%C3%A7%C3%A3o-gratuita-api-gateway-security-best-practices-feb18932d4a5)

[**Certificação Gratuita em Inteligência Artificial: Securing LLM & NLP APIs**](https://renatogroffe.medium.com/certifica%C3%A7%C3%A3o-gratuita-em-intelig%C3%AAncia-artificial-securing-llm-nlp-apis-bd8446c38a70)

## Playlists com vídeos do YouTube sobre segurança de APIs

Clique nos links para acessar o YouTube:
- [**Segurança em aplicações .NET: MFA, JWT, frameworks, nuvem... | Canal .NET**](https://www.youtube.com/playlist?list=PLAbYWcQD84aPTzjI_Dxu5QHXq5LGJovOF)
- [**JWT + .NET: implementação de tokens, consumo, boas práticas... | Canal .NET**](https://www.youtube.com/playlist?list=PLAbYWcQD84aNfRYB8WJUAxazsKoNpMO2L)

## OAuth Tools

Ferramenta online para testes com diversos fluxos de autenticação padronizados.

Link: **https://oauth.tools/**

Exemplo de fluxo utilizando autenticação com **Client Credentials** no **Microsoft Entra ID**:

![Client Credentials - Microsoft Entra ID](img/oauth-tools-01.png)

Necessário antes disso configurar também um workspace, com os endpoints empregados num fluxo de autenticação:

![Endpoints - Microsoft Entra ID](img/oauth-tools-00.png)

---

## Extensão REST Client no Visual Studio Code

Exemplo de teste utilizando a extensão **REST Client** e o comando curl gerado com o **OAuth Tools**:

![Testes com a extensão REST Client VS Code](img/rest-client-01.png)

O script pode ser encontrado na pasta **/tests**.

Saiba mais sobre a extensão **REST Client** em: **https://marketplace.visualstudio.com/items?itemName=humao.rest-client**

![Extensão REST Client VS Code](img/rest-client-02.png)