# 💸 Finanças Flex

Aplicativo financeiro colaborativo para casais e famílias. Controle de gastos, parcelamentos, alertas e compartilhamento entre usuários.

> 🔐 **Segurança é uma prioridade arquitetural, não um recurso adicional.**

---

## 📱 Sobre o projeto

O Finanças Flex nasceu de uma dor real: a dificuldade de controlar finanças compartilhadas de forma simples, transparente e segura. O app permite que casais e famílias acompanhem juntos seus gastos, parcelamentos e transferências — sem distorcer os dados de quem pagou o quê.

### Funcionalidades planejadas

- 📊 Controle de gastos por categoria
- 💳 Rastreamento de parcelamentos
- 🔔 Alertas de vencimento e limite
- 👥 Compartilhamento entre usuários (casal/família)
- 💸 Registro de transferências sem distorcer o saldo
- 👤 Rastreamento de valores devidos por terceiros

---

## 🏗️ Arquitetura

```
financas-flex/
├── backend/        # API REST com Python + FastAPI
├── web/            # Interface web com React
├── mobile/         # App mobile com React Native
└── docs/           # Documentação do projeto
```

---

## 🛠️ Stack

| Camada | Tecnologia |
|--------|-----------|
| Backend | Python + FastAPI |
| Banco de dados | PostgreSQL via Supabase |
| Web | React |
| Mobile | React Native |

---

## 🔐 Segurança

A segurança não é uma camada adicionada depois — ela é parte do design desde o início:

- Autenticação com JWT e refresh tokens
- Senhas armazenadas com hashing seguro (bcrypt)
- Comunicação exclusivamente via HTTPS
- Validação e sanitização de todos os inputs
- Controle de acesso por perfil de usuário

---

## 📌 Status

🚧 Em desenvolvimento ativo

---

## 👤 Autor

**Luciano Santos**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-luciano--santos-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/luciano-santos-66a1a0416)
[![Email](https://img.shields.io/badge/Email-luciano.santos.sec%40gmail.com-red?style=flat-square&logo=gmail)](mailto:luciano.santos.sec@gmail.com)
```

---

Cola, faz o commit e me manda o print!
