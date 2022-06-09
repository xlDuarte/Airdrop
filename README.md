## Smartcontract

<b>Construtor:</b> totalsupply; addressToBalance.
<br>
<b>Propriedades:</b> name; symbol; decimals.
<br>
<b>Funções:</b>
  - totalSupply
  - balanceOf
  - transfer

## AirDrop

<b>Status:</b> ACTIVE, PAUSED, CANCELLED.
<br>
<b>Propriedades:</b> owner; tokenAddress; subscribers; contractState.
<br>
<b>Modificadores:</b> isOwner (Quem tenta enviar não é o dono.).
<br>
<b>Eventos:</b> NewSubscriber.
<br>
<b>Construtor:</b> owner; tokenAddress; contractState.
<br>
<b>Funções:</b>

- Subscribe
- Execute
- State
- Privada (Já subscrito.)
- Kill
