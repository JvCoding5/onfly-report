# Declaração de uso de IA

## Ferramenta e modelo

- **Ferramenta:** Claude Code, da Anthropic, usado dentro do app Claude.
- **Modelo:** Claude Sonnet 5.5.
- **Sessão exportada:** `sessao.md`, nesta mesma pasta.

## Como usei a IA

Usei o Claude principalmente como consultor. Era a minha primeira vez com um projeto desse tipo, então perguntei o que cada coisa era e por que fazer, e levei o que ele explicou para a prática no meu computador. Eu decidia o próximo passo, e o Claude só agia quando eu pedia.

Os defeitos foram corrigidos por mim com o auxílio do Claude. Em cada correção, eu testava o resultado e revisava o que ele tinha feito antes de seguir para a próxima.

## O que consultei na IA

- O que o projeto pedia, ligando cada passo às seções do README.
- Como montar o ambiente (`.venv`, dependências, `pytest`) e como ler a saída dos testes.
- O que cada teste verificava e em qual camada do código procurar o defeito (`repositories/`, `services/`).
- Por que cada trecho estava errado e qual regra do README ele quebrava.
- Como organizar os commits no padrão do meu Notion.
- A redação, em português, dos textos dos commits e do `entrega/README-ENTREGA.md`.
- Uma conferência final do código contra o README, incluindo a amostra de validação.

## O que fiz na prática

- Defini como o trabalho ia andar: um passo por vez, uma correção por commit e nada feito sem eu pedir.
- Criei o ambiente, instalei as dependências e rodei o `pytest` e o CLI no meu computador, colando as saídas para a conferência.
- Li os testes e o código, com as explicações da IA, até entender o que cada regra pedia.
- Corrigi os cinco defeitos com o auxílio da IA, um de cada vez. Nos arquivos, pedi a troca do código à IA, testei e revisei o resultado antes de aceitar.
- Fiz os commits no GitHub Desktop e decidi o que entrava no repositório (por exemplo, o que ficava no `.gitignore`).
- Conferi os resultados finais: `5 passed`, o CSV completo com 300 reservas e a amostra do README.
- Revisei os documentos desta pasta antes de entregar.

## Onde a IA mexeu direto

Em quatro arquivos, a IA fez a troca do código no meu computador, a meu pedido: `currency_converter.py`, `status_policy.py`, `report_builder.py` e `csv_reservation_repository.py`. Depois de cada troca, eu rodei os testes e o CLI e revisei a alteração antes de aceitá-la e commitar.

## Sobre o código entregue

Os testes fornecidos não foram alterados, e os arquivos `data/reservas_hoteis.csv` e `data/taxas_cambio.csv` também não. Não escrevi testes novos.
