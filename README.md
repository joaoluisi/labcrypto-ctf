# 🔐 LabCrypto CTF — Cryptography & Security Lab

Ambiente prático de **Criptografia Aplicada e Segurança Cibernética** com foco em exploração de vulnerabilidades reais.

---

## 🎯 Objetivo

Explorar uma aplicação vulnerável e encontrar **4 flags** relacionadas a falhas de:

- Autenticação  
- Criptografia mal implementada  
- Tokens inseguros  
- Exposição de dados sensíveis  

---

## 🚀 Setup do Ambiente

### 📦 Pré-requisitos

- Docker  
- Docker Compose  
- Git  

---

### 📥 Clonar o repositório

```bash
git clone https://github.com/joaoluisi/labcrypto-ctf.git
cd labcrypto-ctf
```

---

### 🔧 Subir o ambiente

```bash
docker compose up --build
```

---

### 🌐 Acessar a aplicação

Abra no navegador:

👉 http://localhost:3000

---

## 🧩 O Desafio

A aplicação contém vulnerabilidades que simulam cenários reais de segurança.

Seu objetivo é identificar e explorar essas falhas.

---

## 🏁 Flags

Você deve encontrar **4 flags** no formato:

```
flag{...}
```

---

## 🎯 Objetivos

| Flag | Descrição | Pontos |
|------|----------|--------|
| 🟢 Flag 1 | Vulnerabilidade básica | 2 |
| 🟡 Flag 2 | Exposição de dados sensíveis | 3 |
| 🔴 Flag 3 | Problema de autenticação/token | 3 |
| 💣 Flag 4 | Falha crítica de segurança | 2 |

**Total: 10 pontos**

---

## 📦 Entregável

Você deve entregar um **relatório técnico** contendo:

### 1. Introdução
- Objetivo da atividade  
- Descrição do ambiente  

### 2. Metodologia
- Ferramentas utilizadas  
- Estratégia adotada  

### 3. Vulnerabilidades

Para cada flag:

- Descrição da vulnerabilidade  
- Como foi explorada  
- Evidências (prints)  
- Impacto  

### 4. Conclusão
- Aprendizados  
- Possíveis mitigações  

---

## 📸 Evidências obrigatórias

O relatório deve conter:

- Prints das requisições/respostas  
- Prints da aplicação  
- Print das flags  

⚠️ Flags sem evidência não serão consideradas  

---

## 🧰 Ferramentas recomendadas

- DevTools (F12)  
- Burp Suite  
- CyberChef  
- curl  

---

## ⚠️ Regras

- Não realizar brute force desnecessário  
- Não atacar sistemas externos  
- Não compartilhar respostas  
- Focar na análise técnica  

---

## 🧠 Dicas

- Nem tudo que parece criptografia… é criptografia  
- Encoding ≠ Encryption  
- Observe headers, requests e responses  
- Tokens podem ser manipulados  

---

## 🏫 Uso educacional

Este projeto foi desenvolvido para fins educacionais em:

- Segurança Cibernética  
- Criptografia Aplicada  
- Pentest em aplicações web  

---

## 👨‍💻 Autor

João Luisi
