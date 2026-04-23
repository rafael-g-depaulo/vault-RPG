# Sintaxe e Leitura
{{}}Para desambiguação, aqui um simples guia de como ler e interpretar certas convenções usadas no livro de regras.

## Poderes e outras Habilidades Ativas
A definição de poderes (sejam de classe, gerais, bençãos, etc.) e outras habilidades ativas que um personagem tenha acesso (como habilidades que um item dá) seguem a seguinte sintaxe:

**NOME DA HABILIDADE.** (condição) tipo de ação (custo, se houver): Descrição. *Pré-requisitos: X*.

Vamos passar por cada um dos elementos dessa definição de uma habilidade ativa:

### Nome da Habilidade
Esse é o nome da habilidade que o personagem pode escolher ativar. Esse nome pode ser relevante se for mencionado em outros lugares.

Por exemplo, a classe [[R20/Classes/Class - Champion|Champion]] possui poderes de **Julgamento**, e todos eles tem um nome no formato **Julgamento: XXXX**. Detalhes adicionais sobre como **Julgamentos** funcionam estão escritos no balão separado. De forma semelhante, outros poderes ou habilidades de Champion podem modificar como **Julgamentos** funcionam, ou depender de um **Julgamento** ser usado como condição para sua ativação.

### Condição
Uma parte opcional da definição, que se presente restringe exatamente em quais situações a habilidade pode ser usada, e quais gatilhos permitem que o personagem use ela.

#### "Ao" versus "após"
Uma habilidade pode ser explícita quanto ao *timing* de seu gatilho, usando palavras como após/depois ou ao/enquanto.

Se for uma habilidade que modifica outra habilidade ou ação, como adicionar um efeito a um ataque físico ou habilidade base da classe, a condição vai incluir "ao atacar" ou "ao usar XXX". Em casos como esse, o efeito da habilidade e o efeito da ação gatilho ocorrem simultaneamente.

Se o gatilho for externo ao personagem, como "quando um aliado for atacado", o efeito da habilidade acontece imediatamente antes do efeito do gatilho ocorrer. Considere a situação: 

> Um aliado A com 2 de HP for atacado, o ataque acertar e causar 5 de dano e o personagem B usa uma habilidade com condição "quando um aliado for atacado" e efeito "um aliado recupera 5 HP"

Nessa situação, imediatamente  antes do ataque acertar e seus efeitos (5 de dano) ocorrerem, a habilidade do personagem B toma efeito, e o personagem A sobe de 2 para 7 HP. Depois disso o ataque continua e A toma 5 de dano, terminando com 2 HP. Em nenhum momento nessa situação A chega em ou abaixo de 0 HP, então não fica inconsciente.

Se a habilidade de B tivesse a condição "após um aliado ser atacado", o ataque terminaria com sucesso antes do efeito da habilidade de B ativar, então A iria para -3 HP e ficaria inconsciente, perdendo concentração em qualquer habilidade que tivesse ativa. A então recupera 5 HP e recupera consciência, mas também ganha 1 nível de exaustão.

Se a condição não fala explicitamente quando ela ocorre, é assumido que o efeito da habilidade ocorre imediatamente após sua condição de gatilho terminar.

### Tipo de ação

| Tipo de Ação | Significado                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ação/Padrão  | O uso da habilidade requer o uso da ação padrão do personagem. A habilidade só pode ser executada durante o turno do personagem.                                                                                                                                                                                                                                                                                                                           |
| Movimento    | O uso da habilidade requer o uso da ação de movimento do personagem. A habilidade só pode ser executada durante o turno do personagem. *Enquanto a habilidade ocorre, o personagem pode se mover até metade (arredondado pra baixo) da sua velocidade de movimento.*                                                                                                                                                                                       |
| Reação       | O uso da habilidade requer o uso da ação de reação do personagem. A habilidade só pode ser executada em resposta ao gatilho mencionado na sua condição. *O personagem não possui uma Ação de Reação para poder gastar até o início do seu primeiro turno no combate. O personagem não possui uma Ação de Reação se está surpreso.*                                                                                                                         |
| Livre        | O uso da habilidade não tem nenhum custo de **Ação**. Se a habilidade requer uma condição que ocorreu fora do turno do personagem, ele ainda pode executar a habilidade desde que já tenha tido um turno no combate. *O personagem não pode executar uma **Ação Livre** se ainda não teve um turno no combate, ou se está surpreso*. *O personagem não pode executar habilidades com o mesmo nome como **Ações Livre** múltiplas vezes em um mesmo turno.* |

*OBS:* checar ações e turno de combate para dúvidas sobre definições específicas de **Rodada**, **Turno**, **Ação Padrão**, **Ação de Movimento**, **Ação Livre** e **Ação de Reação**.
### Custo
Se a habilidade tiver algum custo de recursos (tradicionalmente HP, MP ou FP), ele é definido entre parênteses. O custo deve ser gasto toda vez que a habilidade for usada, e a habilidade falha se o personagem não puder arcar com o custo.

{{page-break}}

No caso de habilidades com condição do uso de outra habilidade ou ação, o custo será representado como "+1 MP" em vez de "1 MP" (no caso do custo da habilidade ser 1 MP). Esse custo e a habilidade em si são considerados um **Aprimoramento** (*TODO:* criar uma seção explicando aprimoramentos), e seu custo é adicionado ao custo original da habilidade.

**OBS:** Quando uma habilidade for um aprimoramento, preste atenção para não exceder o limite de custo! (por padrão, um personagem não pode gastar mais MP total em uma habilidade e seus aprimoramentos do que seu nível).

### Efeito
Uma vez que o custo seja pago, a ação gasta e o gatilho ocorrido (se a habilidade tiver uma condição de ativação), o efeito descrito na habilidade ocorre.

### Pré-requisitos
Se a habilidade for um poder de classe ou similar (poder geral, bênção, milagre, etc.), a habilidade não pode ser aprendida ou adquirida se o personagem não preencher seus pré-requisitos. Se o personagem não preencher os pré-requisitos da habilidade, ele não pode ativá-la e ela não tem nenhum efeito.

### Exemplo
Como exemplo, vamos interpretar o poder de **Champion** "**Schadenfreude**":

- **Schadenfreude.** (um inimigo falhou na resistência contra suas **Palavras Afiadas**) livre (1 PM): uma criatura a sua escolha que consegue ver o inimigo ganha PV temporários igual a metade do dano inflingido. Pre-requisites: *Palavras Afiadas*.

Essa habilidade salkdjfsdfjsdlkfjdskl. preguiça de escrever o exemplo.

**PS IMPORTANTE:** se vc vir alguma coisa que não está nessa sintaxe e/ou te deixou confuso ao ler pfv me avisa pra que eu possa corrigir. vlw guys <3