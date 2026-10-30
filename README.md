# Academia Vital

Site de uma academia fictícia, criado como projeto de portfólio por **Thyego**. O visitante conhece a proposta da academia, compara os planos em versão mensal ou anual e vê na hora se ela está aberta.

**Acesse:** [thyego17.github.io/Academia-Vital](https://thyego17.github.io/Academia-Vital/)

## Funcionalidades

- **Planos mensais e anuais:** um seletor alterna entre as duas opções, e os valores são recalculados na hora, com o total do ano e o equivalente por mês.
- **Benefícios:** seis diferenciais da academia apresentados em uma grade numerada.
- **Status em tempo real:** uma etiqueta no topo informa se a academia está aberta ou fechada agora.
- **Horários do dia:** a tabela de funcionamento destaca automaticamente o dia de hoje e inclui o horário de feriados.
- **Contato rápido:** botões de telefone, e-mail e mapa.

## Planos

| Plano | Descrição | Mensal |
| --- | --- | --- |
| Básico | Musculação livre | R$ 79,90 |
| Plus | Musculação + cardio | R$ 109,90 |
| Premium | Acesso total + aulas especiais | R$ 149,90 |

No plano anual, o cálculo de exemplo é pagar 10 meses e usar 12.

## Horário de funcionamento

| Dia | Horário |
| --- | --- |
| Segunda a sexta | 6h às 22h |
| Sábado | 8h às 18h |
| Domingo | 8h às 12h |
| Feriados | 8h às 14h |

## Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS e animações)
- JavaScript puro, sem bibliotecas
- Fontes [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) e [Jost](https://fonts.google.com/specimen/Jost), via Google Fonts

## Design

- Visual elegante e moderno, com fundo cinza-azulado escuro e acento em azul-gelo.
- Título em tamanho grande, tipografia serifada e rótulos em caixa-alta espaçada.
- Layout responsivo, pensado primeiro para o celular.
- Foco visível, HTML semântico e respeito à preferência de movimento reduzido.

## Estrutura

```
Academia-Vital/
├── index.html
└── README.md
```

O site inteiro está em um único arquivo, com CSS e JavaScript incorporados.

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/thyego17/Academia-Vital.git
   ```
2. Abra o `index.html` no navegador.

Não é necessário instalar nada.

## Como personalizar

Tudo fica no `index.html`:

- **Planos:** altere a lista `PLANS` no início do script. Cada plano é `["Nome", "Descrição", preço mensal, destacado]`, e o `true` na última posição dá o contorno de destaque ao plano.
- **Desconto anual:** o total anual é calculado como `preço × 10`. Para mudar a regra, altere essa conta na função `plans` e o texto da variável `nota`.
- **Horários:** edite a lista `HOURS`. Cada linha é `["Dia", abre, fecha]`, e o domingo sempre vem primeiro. A linha de feriados é escrita direto na tabela, logo abaixo da lista.
- **Contato:** troque o telefone no link `tel:`, o e-mail no link `mailto:` e o endereço na seção de contato. No botão de mapa, ajuste o endereço dentro do link do Google Maps.
- **Cores:** edite as variáveis em `:root`, no início do `<style>`.

## Observações

Este é um projeto de demonstração. Nome, endereço, telefone, e-mail, preços e a condição do plano anual são fictícios.

## Autor

**Thyego**

- Portfólio: [thyego17.github.io/Portif-lio](https://thyego17.github.io/Portif-lio/)
- GitHub: [@thyego17](https://github.com/thyego17)
