# 🛡️ Desafio de Segurança: Análise Prática de Ataques de Autenticação e Validação Manual

Repositório dedicado à documentação do laboratório prático de testes de autenticação em ambiente controlado. O projeto aborda a execução de ataques de dicionário, a teoria de pulverização de credenciais (*password spraying*), a identificação crítica de falsos positivos em ferramentas automáticas e o papel indispensável da validação humana para equipes de SOC / Blue Team.

---

## 🛠️ Ambiente do Laboratório

- **Hypervisor:** Oracle VM VirtualBox
- **Configuração de Rede:** Host-Only (rede estritamente isolada e sem exposição à internet)
- **Máquina Atacante / Auditoria:** Kali Linux
- **Máquina Alvo:** Metasploitable 2
- **Ferramental Utilizado:** `medusa` (auditoria de autenticação), cliente `ftp`, navegador web (Firefox) e editor de código (VS Code).

---

## 📁 Estrutura de Arquivos

```text
├── images/
│   ├── 01-wordlists-criada.png.png
│   ├── 02-medusa_ftp-success.png.png
│   ├── 03-validacao-login-ftp.png.png
│   ├── 04-medusa-dvwa-teste.png
│   └── 05-validacao-login-dvwa.png
├── pass.txt
├── README.md
└── user.txt