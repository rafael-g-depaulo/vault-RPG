## Problemas
### Problema: Combo PCA
Organicamente se desenvolveu o que eu chamo de combo PCA (*P*lanta *C*onduente *A*rcana sendo a peça central). Esse é um padrão poderoso, seguro e mais linear e homogêneo do que ideal. Para executar a estratégia o seguinte padrão é seguido todo (ou quase todo) turno:
- Invocar o máximo de mudas que conseguir
	- depois de uma primeira muda criada as seguintes são criadas a partir da primeira, criando uma corrente que dá ao caster alcance incrivelmente longo
- Usar *Tunel Pelo Solo* para relocar as plantas longe do combate para perto da ação
- Usar *Plantas Conduentes Arcanas* para focar vários casts de um truque num mesmo alvo
	- Isso toma proveito da economia de turnos e multiplica o dano e oportunidades de acerto.
	- Adiciona um drawback de limitar as magias ofensivas utilizadas para truques

Essa estratégia é efetiva e engaja com algumas das mecânicas centrais da classe de forma interessante, mas traz os seguintes problemas:

1. **Alcance extremo:** a possibilidade de chaining de mudas faz com que frequentemente o alcance do plantomancer seja 9sqr(distância do caster para muda1)+9sqr(distância do caster para muda2)+alcance da magia.
2. **Cobertura:** o caster pode começar a estratégia e agir só a partir das suas mudas, se removendo do perigo do combate. Isso reduz a interatividade.
3. **Dano Excessivo:** mesmo com a restrição de magias para truques, a possibilidade de afetar 1 alvo com várias magias contorna o drawback do dano reduzido de **PCA**, e aparenta ser uma das melhores formas de um Plantomancer dar dano. Junto com as outras vantagens da estratégia, isso quebra o *"meta"*.
4. **Restrição de escolhas de magia:** apesar de ser para balanceamento, o fato de só poder usar truques com **PCA** significa que qualquer personagem que acabe usando a estratégia se vê com menos incentivo para explorar e usar magias de círculos maiores.

### Problema: Baixo incentivo de exploração de diferentes plantas
Sendo consideravelmente mais poderoso do que as alternativas, o PC tem fica desincentivado a explorar as outras habilidades da classe. Isso reduz possibilidades e leva a um gameplay menos interessante

## Soluções
### Solução¹: Rework de Muda Mágica
Mudar efeito da Muda Mágica para impedir a possibilidade de chaining de mudas (uma muda cria outra que cria outra, cada vez mais longe do caster). Adicionar de volta essa possibilidade com um poder (adiciona custo de investimento, e potencialmente pré-requisito de nível) retorna a possibilidade do combo, mas com custo considerável para rebalancear ele.

Implementando essa solução, o efeito da habilidade de classe **Muda Mágica** vai de "Você consegue usar seus sentidos através da Muda Mágica, e pode usar magias e habilidades de Plantomancer através dela." para "Você consegue usar seus sentidos através da Muda Mágica, e pode usar magias através dela.", com um poder novo sendo adicionado à classe. esse poder é o seguinte:

**Polinização Cruzada.** Você pode usar habilidades de Plantomancer (incluindo **Herbomancia**) a partir de uma **Muda Mágica**. Pré-requisito: nível 7 de Plantomancer.

### Solução²: Nerf do combo PCA e rework de PCA
Escolher alguns dos pontos fortes de **PCA** e nerfar eles, fazendo a habilidade ficar mais especializada. Busca assim criar um nicho mais confortável para a habilidade e o combo, sem que ele dê overshadow sobre as outras opções.

O ponto positivo menos interessante é o **3. Dano Excessivo** (single target). Existem várias formas de buscar um dano alto single target, mas a ideia central de PCA como poder busca muito mais utilidade, alcance e controle do que dano.

Se removermos a possibildade de usar PCA como opção de dano single target, se abre um espaço de design para expandir seus outros pontos positivos. Assim, o efeito de PCA muda de "Quando você usa um truque (feitiço nível 0), você pode escolher um número das suas Plantas Mágicas ativas, limitado pelo seu nível. Gaste essa quantidade de PM, e o truque é executado por você e pelas plantas selecionadas ao mesmo tempo (você escolhe os alvos)." para:

**Plantas Conduentes Arcanas.** (ao lançar uma magia) (+**X**PM): Você escolhe **X** **Mudas Mágicas**, e elas lançam a magia ao mesmo tempo em alvos a sua escolha. Uma criatura ou objeto só pode ser afetado por uma instância da magia. Pré-requisito: nível 5 de Plantomancer.

## Conclusão
