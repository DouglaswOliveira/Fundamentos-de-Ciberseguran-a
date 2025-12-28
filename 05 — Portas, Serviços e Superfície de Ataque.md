# 🔓05 — Portas, Serviços e Superfície de Ataque

## 🎯 Objetivo da Aula
Compreender o funcionamento de portas e serviços,
o conceito de superfície de ataque e sua importância
na identificação e redução de riscos em Cyber Security.

---

## 📌 O que são Portas?
Portas são identificadores numéricos utilizados
para direcionar o tráfego de rede aos serviços
corretos dentro de um sistema.

Cada porta está associada a um serviço específico,
permitindo múltiplas comunicações simultâneas.

---

## 🔢 Tipos de Portas
As portas são divididas em faixas:

- **0–1023** → Portas bem conhecidas (well-known ports)
- **1024–49151** → Portas registradas
- **49152–65535** → Portas dinâmicas ou privadas

Exemplos comuns:
- 22 → SSH
- 80 → HTTP
- 443 → HTTPS
- 21 → FTP
- 25 → SMTP

---

## ⚙️ O que são Serviços?
Serviços são aplicações ou processos que ficam
em execução aguardando conexões em portas específicas.

Exemplos:
- Servidor Web
- Servidor SSH
- Servidor de e-mail
- Banco de dados

Serviços mal configurados representam riscos à segurança.

---

## 🎯 Superfície de Ataque
A superfície de ataque corresponde a todos os
pontos de entrada que um atacante pode explorar.

Inclui:
- Portas abertas
- Serviços expostos
- Aplicações web
- Configurações incorretas
- Usuários e credenciais fracas

Quanto maior a superfície de ataque,
maior o risco de incidentes.

---

## 🛡️ Redução da Superfície de Ataque
Boas práticas:
- Fechar portas não utilizadas
- Desativar serviços desnecessários
- Atualizar sistemas regularmente
- Utilizar firewall
- Monitorar logs e acessos

Reduzir a superfície de ataque
é uma das principais estratégias defensivas.

---

## 🧪 Análise de Portas e Serviços
Ferramentas comuns:
- `nmap`
- `netstat`
- `ss`

Essas ferramentas permitem identificar
portas abertas e serviços ativos.

---

## ✅ Conclusão
Portas e serviços são pontos críticos
na segurança de sistemas e redes.

Controlar e monitorar a superfície de ataque
é essencial para prevenir invasões e ataques.
