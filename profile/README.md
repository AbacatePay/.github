<div align="center">

# AbacatePay Open Source 🥑

Gateway de pagamentos **simples, inovador e previsível**, com uma comunidade *Open Source* enorme — feito para devs brasileiros.<br>
  Integre PIX facilmente com a taxa fixa de ***R$ 0,80 por transação***, sem surpresas — e com tudo que a AbacatePay tem para oferecer.

<img src="https://res.cloudinary.com/dkok1obj5/image/upload/v1767631413/avo_clhmaf.png" width="100%" alt="AbacatePay Open Source Image"/>

## O que você vai encontrar aqui?

No nosso *Open Source* você encontrará recursos ricos para integrar fácilmente com a AbacatePay, como os nossos *[SDKs](https://docs.abacatepay.com/pages/sdks)*, *[documentação](https://docs.abacatepay.com/)* completa com todos os nossos recursos, *[extensões](https://github.com/abacatepay/vscode-extension)* para o seu editor de código favorito, *[temas](https://github.com/abacatepay/vscode-theme)* e muito mais.

Para uma visão completa do ecossistema, confira nossa *[Awesome List 💯](https://github.com/AbacatePay/awesome-abacatepay)*.

## Integre com a AbacatePay em poucas linhas

</div>

```ts
import { Webhooks } from '@abacatepay/supabase';

export const POST = Webhooks({
    secret: process.env.WEBHOOK_SECRET!,
    async onBillingPaid({ data, event }) { ... },
});
```

<div align="center">

## Junte-se à revolução, use a AbacatePay

Junte-se conosco e venha fazer parte da comunidade da *AbacatePay no [Discord](https://discord.gg/HVNWYE5V)* e nos ajuda a revolucionar o ecossistema de pagamentos no Brasil!

---

Feito com 🥑 pela equipe AbacatePay<br>
Open source, de verdade.

</div>
