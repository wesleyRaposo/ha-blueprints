[![Abra sua instância do Home Assistant e mostre a caixa de diálogo de importação do blueprint com um blueprint específico pré-preenchido.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2wesleyRaposo%2Fha-blueprints%2Fblob%2Fmain%2Fha-blueprint-linked-on-off.yaml)

**Linked On-Off v1.0** 🔛

Este blueprint permite que você crie/mantenha facilmente uma automação que vincula o estado de duas entidades, mantendo-as em estados opostos:
- LIGUE uma entidade vinculada e isso DESLIGARÁ a outra entidade vinculada.
- DESLIGUE uma entidade vinculada e isso LIGARÁ a outra entidade vinculada.

**NOTA**: Você pode selecionar qualquer entidade que tenha os estados LIGADO/DESLIGADO (interruptores, luzes, etc.).

Meu caso de uso foi para entidades assistentes mutuamente exclusivas. Cada uma delas, quando ativa, era o indicador de um estado determinado. A medida que a automação se tornou mais complexa, surgiu a necessidade de nunca permitir que duas entidades distintas ficassem ligadas ao mesmo tempo. 
Por meios normais, isso seria feito com quatro automações diferentes monitorando os eventos de ativação e desativação de cada entidade, mas com esse blueprint apenas uma automação é necessária.

Você poderá encontrar outras utilidades particulares para sua automação.

-----------

This blueprint allows you to easily create/maintain an automation that links the state of two entities, keeping them in opposite states:
- Turning one linked entity ON will turn the other linked entity OFF.
- Turning one linked entity OFF will turn the other linked entity ON.

**NOTE**: You can select any entity that has ON/OFF states (switches, lights, etc.).

My use case was for mutually exclusive assistant entities. Each of these, when active, was an indicator of a particular state. As automation became more complex, it became necessary to never allow two separate entities to be active at the same time.

Normally, this would be done with four separate automations monitoring the on and off events of each entity, but with this blueprint, only one automation is needed.

You may find other particular uses for your automation.

-----------

**REGISTRO DE ALTERAÇÕES / CHANGELOG:**
  - **1.0**: (2024-08-23)
    - Primeiro lançamento oficial
	
**Fonte / Source:**
[![wesleyRaposo - ha-blueprints](https://img.shields.io/static/v1?label=alexdelprete&message=ha-blueprints&color=blue&logo=github)](https://github.com/wesleyRaposo/ha-blueprints/blob/main/ha-blueprint-linked-on-off.yaml "Go to GitHub repo") [![stars - ha-blueprints](https://img.shields.io/github/stars/alexdelprete/ha-blueprints?style=social)](https://github.com/wesleyRaposo/ha-blueprints) [![forks - ha-blueprints](https://img.shields.io/github/forks/alexdelprete/ha-blueprints?style=social)](https://github.com/wesleyRaposo/ha-blueprints)
