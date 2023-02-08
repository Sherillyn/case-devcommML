
# NuvemShop

Nesta documentação você vai encontrar as informações necessárias sobre o plugin do Mercado Pago para se integrar com a Nuvemshop. 

## **Índice**

### 1. [**Primeiros passos**](#primeiros-passos)
> #### i. [**Sobre a NuvemShop**](#sobre-a-nuvemshop)
> #### ii. [**Pré-requisitos**](#pré-requisitos)
> #### iii. [**Ative o Mercado Pago em sua loja**](#ative-o-mercado-pago-em-sua-loja)
### 2. [Instalação do Plugin](#instalação-do-plugin)
### 3. [Configurações](#configurações)
### 4. [Testes](#testes)
### 5. [Personalização](#personalização)
### 6. [Informações adicionais](#testes)
> #### i. [**Alterar conta do Mercado Pago**](#alterar-conta-do-mercado-pago)
> #### ii. [**Credenciais**](#credenciais)
### 8. [Perguntas Frequentes](#perguntas-frequentes)


## Primeiros passos

### Sobre a NuvemShop

[Nuvemshop](https://www.nuvemshop.com.br/loja-virtual?utm_source=google&utm_medium=cpc&utm_campaign=br-web-search-brand-region-4-device_c-id_534414168435&gclid=CjwKCAiArY2fBhB9EiwAWqHK6lm1jhE-m5LA6WbinCkJDWJzwG8ozgDAZ7heZHZOfzkhbm8TPytmLxoCHFAQAvD_BwE) é uma plataforma e-commerce para sua loja virtual, que permite processar pagamentos através do Mercado Pago. Você poderá oferecer aos seus clientes a possibilidade de pagar com cartão de crédito, boleto bancário e Pix no próprio checkout da sua loja ou redirecionado para o site do Mercado Pago.

### Pré-requisitos

Os passos para começar a operar com Mercado Pago, são os seguintes:

1. [Crie uma conta](https://www.mercadopago.com.br/hub/registration/landing) de vendedor no Mercado Pago caso ainda não tenha uma.
2. Ative o **Mercado Pago** como meio de pagamento dentro da sua loja. 
3. Configure as formas de pagamento Mercado Pago.

### Ative o Mercado Pago em sua loja

Para vincular sua conta do Mercado Pago à Nuvemshop, siga os passos abaixo:

1. Acesse as [configurações de meios de pagamentos](https://www.nuvemshop.com.br/login?login_to=https%3A%2F%2Fwwss.lojavirtualnuvem.com.br%2Fadmin%2Fpayments%2F), no painel de administração de sua loja.
2. Localize o **Mercado Pago** na lista de meios de pagamentos.
3. Clique em **Configurar**.
4. E depois em **Ativar**.
5. Você será redirecionado para uma página do Mercado Pago para acessar com seus dados. Clique em **Permitir** para autorizar a conexão.
6. Ao concluir essas etapas, sua conta Mercado Pago já está ativa.

Veja o gif abaixo, para complementar a explicação:

![gif demostrando o passo a passo acima descrito](https://github.com/Sherillyn/case-devcommML/blob/main/assets/gif1.gif)



> Por padrão, a Nuvemshop apresenta algumas informações da conta que está recebendo pagamento, são elas: e-mail, país e a moeda correspondente a sua conta Mercado Pago.


## Instalação do Plugin


## Configurações 


### Configurar as formas de pagamento

Você poderá escolher qual tipo de integração utilizar em sua loja. Pode optar por um dos processos de compra:

- Compra no site do Mercado Pago(Checkout Pro).
- Compra diretamente em seu site(Checkout transparente).

> Só é possível ativar um dos tipos de processos de compra.

Além disso, você pode **configurar parcelas sem juros** e **consultar e configurar as taxas e prazos** de suas vendas online quando quiser.

#### Checkout Pro

O comprador será redirecionado ao site do Mercado Pago e uma vez finalizado o processo, voltará para sua loja, contando com meios de pagamentos como pix, boleto parcelado, débito virtual da Caixa e carteira digital do Mercado Pago.

1. Acesse as configurações de meios de pagamentos, no painel de administração de sua loja, localize o **Mercado Pago** na lista de meios de pagamentos
2. Clique em **Editar**.
3. No item **Tipo de integração** altere para **Processo de compra no site do Mercado Pago**.
4. Selecione quais os tipos de pagamento que deseja oferecer em seu checkout, sendo eles: Cartão de crédito, Boleto bancário e Pix.
5. Clique em **Salvar alterações**.


#### Checkout transparente

É o checkout em que seu cliente finaliza o pagamento no ambiente da sua loja sem ser redirecionado para outro site, onde possibilita processar pagamentos com cartão de crédito, boleto bancário, Pix e Checkout Pro.


> Importante:
Para oferecer a opção de pagamento Pix, você deve ter cadastrada uma chave Pix na conta do vendedor. Este dado é único, serve para identificar sua conta e permitirá que você utilize as funcionalidades do meio de pagamento. [Conheça como criar uma chave Pix](https://www.mercadopago.com.br/stop/pix?url=https%3A%2F%2Fwww.mercadopago.com.br%2Fadmin-pix-keys%2Fmy-keys&authentication_mode=required)

1. Acesse as configurações de meios de pagamentos, no painel de administração de sua loja, localize o **Mercado Pago** na lista de meios de pagamentos
2. Clique em **Editar**.
3. No item **Tipo de integração** altere para **Processo de compra sem sair da loja**.
4. Selecione quais os tipos de pagamento que deseja oferecer em seu checkout, sendo eles: Cartão de crédito, Boleto bancário e Pix.Caso deseje que o pagamento com boleto bancário tenha desconto, informe a porcentagem de desconto no campo **Desconto para pagamentos com boleto**.
5. Clique em **Salvar alterações**.

> Ao instalar o Mercado Pago, todos os meios de pagamento estarão ativos por padrão.

### Configuração de parcelamento

A Nuvemshop utiliza as informações de parcelamento diretamente de sua conta Mercado Pago. As alterações feitas nas configurações de parcelamento em sua conta Mercado Pago **serão refletidas na sua loja online em até 24h**.

- Caso queira sincronizar suas alterações manualmente ou aplicar um valor mínimo da parcela, realize os seguintes passos:

1. Acesse as configurações de meios de pagamentos, no painel de administração de sua loja, localize o **Mercado Pago** na lista de meios de pagamentos
2. Clique em **Editar**.
3. Caso deseje aplicar um valor mínimo de parcela para pagamento transparente, informe o valor no campo **Parcelas**.
4. No item **Parcela** clique em **Ativar agora**.
5. Clique em **Salvar alterações**.

Veja o gif abaixo para complementar o entendimento do fluxo acima, caso necessário.

![gif da tela que representa o fluxo descrito acima](https://github.com/Sherillyn/case-devcommML/blob/main/assets/gif4.gif)

#### Configurando o parcelamento em sua conta Mercado Pago

1. Acesse sua conta Mercado Pago e clique em **Seu negócio**.
2. Clique na opção **Configurações**, navegue até o campo **Oferecer parcelas sem acréscimo**
3. Clique em **Ativar**.
4. Escolha **Quantas parcelas você quer oferecer?** 
5. Llique em **Ativar** para confirmar as alterações.

## Testes


## Personalização 


## Informações adicionais



### Alterar conta do Mercado Pago

Caso precise trocar a conta atual do Mercado Pago por outra, siga os passos abaixo:

1. Desconecte de sua conta Mercado Pago, caso conectada em um navegador.
2. Cliwur no **Menu de opções** e depois em **Sair**.
3. Acesse as configurações de meios de pagamentos, no painel de administração de sua loja, localize o **Mercado Pago** na lista de meios de pagamentos e clique em **Editar**.
4. Clique em **Mudar usuário** para desvincular a conta atual.
5. Refaça o processo para ativar uma nova conta.


> Os serviços do Mercado Envios estão temporariamente indisponíveis, não sendo possível utilizar esse meio de envio na plataforma por tempo indeterminado.

### Credenciais


## Perguntas Frequentes




