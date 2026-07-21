# 💸 DeCifra

Aplicativo financeiro colaborativo para casais e famílias, com foco em clareza, projeção e controle.

> 🔐 **Segurança é uma prioridade arquitetural, não um recurso adicional.**

---

## 📱 Sobre o projeto

DeCifra nasceu da percepção de que as ferramentas de gestão financeira existentes são funcionais, mas não geram engajamento. Planilhas e apps tradicionais muitas vezes falham em oferecer 
a clareza visual e a antecipação de problemas que o usuário realmente precisa.

Nosso objetivo é transformar a gestão financeira de uma tarefa árdua em uma experiência intuitiva e empoderadora. DeCifra se posiciona como um produto moderno e profissional, mas com uma 
abordagem humana e visualmente atraente, inspirada na forma como marcas como o Nubank revolucionaram seus mercados. Queremos que o usuário finalmente "decifre" suas finanças, entendendo 
o cenário atual e projetando o futuro com confiança.

DeCifra entrega três coisas que os concorrentes não combinam num só produto: visualização inteligente em camadas do micro ao macro, projeção financeira futura baseada nos padrões do 
usuário, e categorização automática com aprendizado personalizado.

O público-alvo são adultos brasileiros entre 20 e 45 anos que buscam controle financeiro real, incluindo pessoas físicas, casais com finanças compartilhadas ou parcialmente separadas, e 
pequenos empreendedores que misturam finanças pessoais e profissionais.

### Funcionalidades planejadas

*   📊 **Dashboard visual:** Visão consolidada do cenário financeiro com navegação em camadas, permitindo ir do macro (entradas/saídas/projeção do mês) ao micro (lançamento específico)
com facilidade.
*   🔮 **Projeção financeira:** Com base nos lançamentos recorrentes e padrões históricos, o app projeta o saldo futuro e alerta sobre riscos antes que aconteçam.
*   🏷️ **Categorização inteligente:** O sistema sugere categorias automaticamente com base na descrição do lançamento e aprende com as correções do usuário. Suporte a categorias padrão
(Alimentação, Moradia, Transporte, Saúde, Lazer, Investimentos e Recebíveis) e subcategorias personalizadas.
*   💳 **Múltiplas contas e cartões:** Cadastro de bancos, cartões e carteiras separadamente, com visão individual e consolidada.
*   👨‍👩‍👧‍👦 **Perfis compartilhados:** Suporte a finanças de casal ou família com controle de visibilidade por perfil.
*   📝 **Lançamentos e extratos:** Registro manual de transações e futuro suporte a importação, com histórico completo por conta, cartão ou categoria.

### Fora do escopo inicial (para versões futuras)
Conexão automática com bancos via Open Finance, versão web, suporte a múltiplos idiomas e marketplace de serviços financeiros.
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

A segurança não é uma camada adicionada depois – ela é parte do design desde o início.

*   🔐 Autenticação com JWT e refresh tokens
*   🔒 Senhas armazenadas com hashing seguro (bcrypt)
*   🌐 Comunicação exclusivamente via HTTPS
*   ✅ Validação e sanitização de todas as inputs
*   👤 Controle de acesso por perfil de usuário

---

## 📌 Status

🚧 Em desenvolvimento ativo

---

## 👤 Autor

**Luciano Santos**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-luciano--santos-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/luciano-santos-66a1a0416)
[![Email](https://img.shields.io/badge/Email-luciano.santos.sec%40gmail.com-red?style=flat-square&logo=gmail)](mailto:luciano.santos.sec@gmail.com)
