# DOCUMENTAÇÃO DE PROMPTS – PROJETO FRONT-END

**Projeto:** Nome do projeto   
**Disciplina:** Desenvolvimento Front-End   
**Data:** DD/MM/AAAA

---

## 1. Objetivo do projeto

Desenvolver uma página web utilizando HTML, CSS e JavaScript, tendo como referência visual um protótipo previamente desenvolvido no Figma.

As ferramentas de Inteligência Artificial foram utilizadas como apoio durante o desenvolvimento, auxiliando na construção, correção e otimização do código.

## 2. Ferramentas utilizadas
- **Gemini**
- **ChatGPT:** Auxílio na estruturação, explicação e correção de códigos.
- **VS Code:** Editor de código utilizado no desenvolvimento.
- **GitHub:** Controle de versão e armazenamento do projeto.
- **Figma:** Referência visual para a implementação da página.

## 3. Histórico de prompts utilizados

### 3.1. Análise do protótipo do Figma

**Ferramenta:** ChatGPT

**Objetivo:** Analisar o protótipo e identificar os elementos necessários para desenvolver a página.

**Prompt utilizado:**

"https://www.figma.com/proto/u8KmxOxg3xV0pCMvkzO73Z/Sem-t%C3%ADtulo?node-id=4-417&t=OAXiyvRBykNZsRnl-1

analise o prototipo criado no figma e apos a analise me de as tags necessarias para a estruturacao da pagina"

**Resultado obtido:**

Após o prompt, a IA me deu as tags inicias que eu iria precisar para começar a estruturar minha pagina com o HTML, além de ja analisar todo o prototipo e me ajudar com o passo a passo daqui em diante
---

### 3.2. Desenvolvimento da estrutura HTML
**Ferramenta:** ChatGPT

**Objetivo:** Criar a estrutura inicial da página.

**Prompts utilizado:**

Chat, agora que temos a estrutura HTML completa e organizada, vou te enviar o código final para que você faça uma revisão completa.



Quero que você:

1. **Analise e revise o código:** verifique toda a estrutura HTML e procure possíveis erros de sintaxe, organização, hierarquia, posicionamento e estrutura das tags.
2. **Corrija os erros encontrados:** depois da análise, envie o código completo, corrigido e organizado, mantendo a estrutura e a proposta original do projeto.
3. **Explique os erros:** apresente uma lista com todos os problemas encontrados, explicando o que estava errado, por que era um erro e como foi corrigido.
4. **Explique o código completo:** após a revisão, crie uma lista explicando cada parte do documento HTML, incluindo todas as tags utilizadas, suas funções e a importância de cada uma na estruturação da página.

Quero entender não apenas o que foi corrigido, mas também como funciona cada elemento do código, para que eu possa aprender e melhorar minhas habilidades em HTML.



Por favor, faça uma análise detalhada e didática, explicando tudo de forma clara e organizada.

**Resultado obtido:**

Fiz meu primeiro código com a ajuda do ChatGPT. Durante o desenvolvimento, eu mesmo escrevia o código e recorria à IA sempre que tinha alguma dúvida ou não sabia como fazer determinada coisa.

Depois de finalizar, criei um prompt e pedi para a IA organizar melhor minhas instruções, deixando tudo mais claro e fácil de entender.

Nesse prompt, pedi que ela revisasse e corrigisse meu código, apontasse os erros encontrados e explicasse o que foi corrigido e o motivo de cada alteração. Também solicitei uma explicação de todas as tags HTML utilizadas, para entender melhor a função de cada uma e como elas contribuem para a estrutura da página.

---

### 3.3. Desenvolvimento da estilização CSS

**Ferramenta:** ChatGPT

**Objetivo:** Implementar o visual do protótipo do Figma.

**Prompt utilizado:**

# Estilização CSS baseada no protótipo do Figma

Com base no protótipo desenvolvido no Figma, realize a estilização completa da página utilizando CSS, buscando reproduzir o mais fielmente possível o design apresentado.

## 1. Fidelidade ao protótipo

- Analise cuidadosamente o protótipo do Figma antes de começar a implementação.
- Reproduza com a maior fidelidade possível o layout, as cores, as fontes, os tamanhos, os espaçamentos, os alinhamentos, as imagens, os botões e os demais elementos visuais.
- Respeite a identidade visual e a organização dos elementos apresentados no Figma.
- Não invente elementos ou altere o design original sem necessidade.
- Caso algum detalhe do protótipo não esteja claro, explique a dúvida antes de tomar decisões que possam comprometer a fidelidade visual.

## 2. Responsividade

O site deverá ser totalmente responsivo e apresentar uma boa experiência de navegação nos seguintes dispositivos:

- **Desktop:** computadores e notebooks.
- **Android:** smartphones e tablets.
- **iOS:** iPhones e iPads.

Utilize boas práticas de CSS responsivo, como:
- Media Queries (`@media`).
- Flexbox e CSS Grid, quando apropriado.
- Unidades flexíveis (`%`, `rem`, `vw`, `vh`).
- Imagens adaptáveis.
- Ajustes de espaçamento, tamanho de fontes e organização dos elementos conforme a tela.

A página não deve apresentar elementos cortados, sobrepostos, desalinhados ou barras de rolagem horizontais indesejadas.

## 3. Organização e qualidade do código

- Mantenha o código limpo, organizado e fácil de entender.
- Utilize nomes de classes claros e padronizados.
- Organize o CSS por seções, seguindo a estrutura dos elementos da página.
- Evite repetições desnecessárias e regras conflitantes.
- Utilize comentários para identificar as principais seções e explicar regras importantes.
- Preserve a estrutura HTML existente sempre que possível, realizando alterações somente quando forem realmente necessárias para alcançar o resultado do Figma.
- Não remova elementos ou funcionalidades já existentes sem justificar a necessidade.

## 4. Comentários e identificação das alterações

Toda alteração realizada deverá ser identificada e explicada por meio de comentários.

- Comente as novas regras e os principais blocos de CSS.
- Explique a finalidade das alterações feitas no HTML, caso sejam necessárias.
- Identifique claramente as novas implementações e os ajustes realizados.
- Informe quais partes do código foram modificadas e por quê.
- Mantenha os comentários objetivos, evitando comentários excessivos que dificultem a leitura.

O objetivo é permitir que outra pessoa consiga entender o código, localizar as alterações e realizar futuras modificações com facilidade.

## 5. Testes e validação

Após finalizar a implementação:

- Verifique se a página está visualmente próxima do protótipo do Figma.
- Teste o funcionamento em diferentes tamanhos de tela.
- Verifique a responsividade em dispositivos desktop, Android e iOS.
- Corrija problemas de alinhamento, espaçamento, dimensionamento e posicionamento.
- Confira se imagens, fontes, botões, links e demais elementos continuam funcionando.
- Não considere o trabalho concluído antes de verificar os principais pontos da página.

## 6. Documentação final

Ao concluir o desenvolvimento, gere um documento explicativo em formato Word (`.docx`) contendo:

1. **Visão geral:** o que foi desenvolvido e qual era o objetivo da estilização.
2. **Estrutura da página:** explicação dos principais elementos HTML.
3. **Estilização CSS:** explicação das propriedades, seletores e técnicas utilizadas.
4. **Responsividade:** explicação de como o site se adapta a desktop, Android e iOS.
5. **Alterações realizadas:** descrição do que foi modificado, adicionado ou ajustado.
6. **Organização dos arquivos:** explicação da função de cada arquivo do projeto.
7. **Como fazer alterações futuras:** orientação de onde modificar cores, fontes, imagens, espaçamentos, tamanhos e outros elementos.

Explique cada parte com linguagem clara e didática, considerando que o material também será utilizado para estudo.

## 7. Entrega final

Ao terminar, disponibilize:

- Os arquivos do projeto atualizados.
- O CSS completo, organizado e comentado.
- O HTML atualizado, caso tenha sido necessário modificá-lo.
- O documento Word (`.docx`) explicando o desenvolvimento e as alterações realizadas.

**Importante:** não substitua todo o código existente sem necessidade. Trabalhe a partir da estrutura atual do projeto, preserve o que já funciona e faça alterações incrementais. Priorize a fidelidade ao Figma, a responsividade, a organização e a facilidade de manutenção do código.

**Resultado obtido:**

Após esse prompt a IA me deu a estilização completa, trazendo uma estilização semelhante ao prototipo do Figma, além de fazer toda a parte responsiva do site, garantindo que ele funcione corretamente em dispositivos diferentes mantendo o UX e UI

---

### 3.4. Implementação de funcionalidades JavaScript

**Ferramenta:** ChatGPT

**Objetivo:** Implementar as interações da página.

**Prompt utilizado:**

> [Cole aqui o prompt utilizado.]

**Resultado obtido:**

[Explique o resultado.]

---

### 3.5. Correções e melhorias

**Ferramenta:** ChatGPT

**Objetivo:** Identificar e corrigir erros e melhorar o código.

**Prompt utilizado:**

> [Cole aqui o prompt utilizado.]

**Resultado obtido:**

[Explique o que foi corrigido.]

---

## 4. Considerações finais

A Inteligência Artificial foi utilizada como ferramenta de apoio ao desenvolvimento, sendo necessário analisar, testar e compreender os códigos gerados antes de sua implementação no projeto.

O desenvolvimento e as decisões finais foram acompanhados pelo aluno, que deverá ser capaz de explicar a estrutura, o funcionamento e as funcionalidades implementadas.