# FleetWise — Bucket List de Funcionalidades Futuras

Ideias a desenvolver em iterações futuras.

---

## 🔔 Notificações Automáticas por Email
**Contexto:** A plataforma só existe enquanto o browser está aberto, por isso alertas de IPO, seguros e revisões podem passar despercebidos.

**O que fazer:**
- Migrar dados para Supabase (base de dados real)
- Criar Edge Function com cron job diário (ex: todos os dias às 8h)
- Verificar automaticamente: IPOs a vencer ≤ 30 dias, seguros a expirar, revisões pendentes
- Enviar email via Resend (grátis até 3.000/mês) com resumo de alertas
- Funciona completamente em background, sem ninguém abrir a plataforma

**Stack sugerida:** Supabase + Supabase Edge Functions + pg_cron + Resend

---
