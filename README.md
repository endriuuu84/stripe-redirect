# Stripe Connect Redirect

Pagine di redirect per Stripe Connect Express Onboarding.

Questa semplice pagina HTML gestisce il redirect da Stripe Connect, passando i parametri corretti all'applicazione Peeno.

## Come funziona

1. Stripe Connect completa l'onboarding e reindirizza a questa pagina
2. La pagina analizza i parametri URL e determina il tipo di redirect necessario
3. Reindirizza l'utente all'app Peeno con i parametri appropriati

## Configurazione

Nella dashboard di Stripe Connect, configura l'URL di redirect OAuth come:

```
https://username.github.io/stripe-redirect/
```

Sostituisci "username" con il tuo nome utente GitHub.