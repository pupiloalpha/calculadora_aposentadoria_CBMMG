# Simulador de Aposentadoria CBMMG

Aplicação web para estimar cenários de aposentadoria e de direito ao abono de permanência de militares do Corpo de Bombeiros Militar de Minas Gerais (CBMMG). O simulador reúne os dados básicos do militar, apresenta um diagnóstico inicial e permite comparar cenários com acréscimos de tempo informados pelo usuário.

**Acesse a aplicação:** [pupiloalpha.github.io/calculadora_aposentadoria_CBMMG](https://pupiloalpha.github.io/calculadora_aposentadoria_CBMMG/)

## Funcionalidades

- Cálculo do tempo de serviço efetivo a partir da data de inclusão.
- Estimativa da data de aposentadoria compulsória, considerando idade ou tempo de serviço conforme os parâmetros implementados na aplicação.
- Estimativa da data de direito ao abono de permanência.
- Detalhamento dos quinquênios e do pedágio, quando aplicável.
- Simulação e comparação de cinco cenários: compulsória por tempo, compulsória por idade, voluntária antecipada, voluntária com garantia do 6º quinquênio e abono de permanência.
- Inclusão de tempo averbado, férias anuais não gozadas e férias-prêmio não gozadas nos cenários de simulação.
- Área de ajuda com explicações sobre os resultados, as regras consideradas e a legislação de referência.

## Como usar

1. Abra a aplicação pelo link acima (ou abra `index.html` em um navegador).
2. Na aba **Dados do Militar e Resultados**, informe data de nascimento, data de inclusão no CBMMG e sexo. Se aplicável, selecione a opção de Oficial de Saúde/Capelão.
3. Clique em **Calcular Informações Iniciais** para ver o diagnóstico.
4. Na aba **Simulação de Cenários**, informe tempo averbado e dias de férias não gozadas, se houver, e clique em **Simular Cenários**.
5. Consulte os resultados detalhados e a tabela comparativa. A aba **Informações e Ajuda** descreve os cenários e conceitos usados.

## Tecnologias

- HTML5, CSS e JavaScript, em uma página única (`index.html`).
- [Bootstrap 5.3.3](https://getbootstrap.com/) para componentes e layout responsivo, carregado por CDN.
- Fonte [Inter](https://fonts.google.com/specimen/Inter), carregada do Google Fonts.
- Hospedagem pelo GitHub Pages.

Não há etapa de compilação ou instalação de dependências. Para executar localmente, basta abrir `index.html` em um navegador com acesso à internet para carregar os recursos externos.

## Regras e limitações

Os parâmetros e regras de cálculo estão implementados diretamente no JavaScript de `index.html`. A aplicação apresenta como referências, entre outras, a Lei nº 13.954/2019, a EC nº 103/2019, a EC nº 41/2003 e legislação estadual mineira. Consulte a aba **Informações e Ajuda** e a legislação oficial para conhecer as premissas aplicadas.

Os resultados são **estimativas informativas**, baseadas nos dados fornecidos pelo usuário e nas regras codificadas no simulador. Não constituem parecer jurídico, decisão administrativa ou garantia de concessão de benefício. As regras podem variar conforme a situação funcional e a legislação vigente; confirme os requisitos e os períodos reconhecidos com os setores competentes do CBMMG e/ou um profissional qualificado antes de tomar decisões.

## Desenvolvimento

Como o projeto é uma página estática, alterações podem ser feitas diretamente em `index.html`. Depois de publicar as mudanças na branch configurada para o GitHub Pages, a versão hospedada será atualizada pelo próprio serviço.

## Licença

Nenhuma licença de uso está indicada no repositório neste momento. Consulte o proprietário antes de reutilizar ou redistribuir o conteúdo.
