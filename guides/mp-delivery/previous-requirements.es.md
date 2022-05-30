# Requisitos previos de integración

Para poder integrar Mercado Pago Delivery con tu PDV/POS, debes cumplir con los siguientes requisitos.

| Requisitos | Descripción |
|---|---|
|Cuenta Mercado Pago| Es necesario que el integrador tenga una cuenta en Mercado Pago para crear una aplicación. Con una aplicación puedes configurar tu Webhook, para recibir notificaciones de nuevos pedidos, y generar tus credenciales. Si no la tienes, [haz clic aquí](https://www.mercadopago[FAKER][URL][DOMAIN]/hub/registration/landing) para crearla.|
|Credenciales| Las [credenciales](/developers/es/guides/additional-content/credentials/credentials) son contraseñas únicas con las que identificamos una integración en tu cuenta, y que sirven para capturar pagos en tiendas virtuales y otras aplicaciones de forma segura.|
|Access Token| Mediante el protocolo de autorización OAuth, cada restaurante debe autorizar a la aplicación creada en la cuenta del integrador para recibir notificaciones de nuevos pedidos. Además, cada restaurante tendrá un Access Token los cuales serán utilizados para realizar operaciones utilizando las APIs de Mercado Pago Delivery. Consulta [OAuth](/developers/es/guides/additional-content/security/oauth/introduction) para entender el flujo de autorización que se debe hacer con los restaurantes.|

> PREV_STEP_CARD_PT
>
> Introducción
>
> Conoce cómo funciona Mercado Pago Delivery.
>
> [Introducción](/developers/es/docs/mp-delivery/landing)

> NEXT_STEP_CARD_ES
>
> Configuración de integración
>
> Aprende a configurar la integración con Mercado Pago Delivery.
>
> [Configuración de integración](/developers/es/docs/mp-delivery/integration-configuration)