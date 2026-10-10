# Placas Avaliação

Primeira versão da vitrine para uma loja de placas premium de avaliação com QR Code e NFC.

## O que já está implementado

- Página responsiva com identidade visual escura e acabamento preto premium.
- Apresentação dos benefícios de QR Code e NFC.
- Personalizador inicial com nome da empresa, upload de logo, link de avaliação, acabamento e estilo de fundo.
- Prévia da placa que atualiza conforme o cliente preenche os campos.
- QR Code gerado no navegador quando a biblioteca externa está disponível.
- Aviso transparente de que o checkout Mercado Pago ainda não está conectado.

## Abrir a página

Abra `index.html` no navegador ou publique o repositório em um serviço de hospedagem estática.

## Próximas etapas para vender de verdade

1. Ajustar a prévia com fotos e medidas reais do produto.
2. Definir preço, frete, prazo de produção e política de troca/privacidade.
3. Criar backend seguro para registrar pedidos e guardar imagens enviadas.
4. Integrar o checkout do Mercado Pago para Pix e cartão, com credenciais apenas no servidor e confirmação de pagamento por webhook.
5. Configurar a gravação/programação do chip NFC e testar o QR Code com links reais.
6. Fazer testes completos em celular e desktop antes de divulgar a loja.

**Importante:** esta versão é um protótipo visual. Ela ainda não registra pedidos, não cobra pagamentos e não programa fisicamente o chip NFC. Nunca coloque access tokens ou outras credenciais secretas do Mercado Pago no código do navegador.
