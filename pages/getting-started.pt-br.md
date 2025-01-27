# Começando

### O que são Tokens de Design (*Design Tokens*)?
> Os tokens de design são os átomos de design visual do sistema de design - especificamente, eles são entidades nomeadas que armazenam atributos de design visual. Nós os usamos no lugar de valores codificados (como valores hexadecimais para cores ou valores de pixels para espaçamento) a fim de manter um sistema visual escalonável e consistente para o desenvolvimento da UI.
[Salesforce, Lightning Design System](https://www.lightningdesignsystem.com/design-tokens/)

Os tokens de design se originaram na Salesforce, onde [Jina](https://twitter.com/jina) e [Jon](https://twitter.com/jonnyl) cunharam o termo. Uma boa explicação pode ser encontrada no [Youtube da Jina Anne](https://www.youtube.com/watch?v=q5qIowMyVt8).

O [W3C Design Tokens Community Group](https://github.com/design-tokens/community-group) visa estabelecer um padrão no qual as ferramentas podem contar para compartilhar tokens de design. Este plugin tem como objetivo ser compatível com W3C para que você possa pegar seu JSON e passar para outra ferramenta algum dia.

Infelizmente, as ferramentas de design ainda não são avançadas o suficiente para incorporar totalmente os tokens de design. Temos estilos de cor e texto no Figma, mas não há como usar um token de design como raio de borda (*border radii*) ou unidades de espaço de forma reutilizável. Este plugin visa preencher essa lacuna, para ajudá-lo a gerenciar suas cores e estilos de texto e fornecer tokens de design para todas as outras propriedades. Você pode escolher o quão profundo deseja integrar o plugin em seu fluxo de trabalho, uma maneira fácil de começar seria apenas usá-lo para gerenciar suas cores e estilos de texto, o que oferece recursos como referências, matemática para escalas e uma maneira de melhorar criar sistemas de design com vários temas.

### Instalando o plugin

Instale o plugin Figma Tokens clicando no botão `Install` [nesta página](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) (no Figma cliente ou no navegador)

Se você iniciar o plugin pela primeira vez, ainda não terá tokens definidos. Clique em `Get started` para começar.

---

import ReactPlayer from 'react-player'


<ReactPlayer
  muted
  width="100%"
  height="auto"
  loop
  playing
  controls
  url="/getting-started.mp4"
/>

Em seguida, você pode seguir das seguintes maneiras:

- Criar seus próprios tokens pela UI do plugin
- Importar seus tokens já feitos
- Sincronizar seus tokens já existentes usando repositórios remotos (GitHub, GitLab, JSONbin)
- Criar seus tokens através de um editor JSON
