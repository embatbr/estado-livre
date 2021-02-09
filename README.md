# Estado Livre

*Projeto de definição de um **estado livre**, baseado em regras claras e lógicas, de modo a maximizar a liberdade individual e diminuir o poder e a atuação do Estado no tecido social.*


## Considerações iniciais

Este projeto é pensado a partir da cabeça de um engenheiro da computação, não um operador do direito. Logo, ao definir as regras escritas (constituição e outros códigos), a intenção não é abarcar todas as possibilidades comportadas pela linguagem natural (muito abrangente e subjetiva) mas sim da lógica, de modo a atingir seu objetivo de forma clara e eficiente.

### Versionamento

Tomando como exemplo a constituição, por ser fruto de uma mente de programador, não tem por objetivo usar termos como "emendas" e "cláusulas pétreas" (pelo menos não abertamente e ostensivamente), mas sim ser versionado como um software.

Será usado o [versionamento semântico](https://semver.org/) de forma simplificada, sendo a versão composta do seguinte formato: **MAJOR.MINOR.PATCH** (apenas usando números).

- **MAJOR** - versão quando há uma mudança que cause incompatibilidade com a anterior. Por exemplo, na versão **1.y.z**, a liberdade de expressão é total. Caso a liberdade de expressão torne-se restrita, deve-se ir para a versão **2.0.0**;
- **MINOR** - usada quando há adição de elemento com compatibilidade retroativa. Exemplo, na versão **1.10.z**, há a liberdade de expressão. Ao adicionar o elemento de liberdade de culto (professar sua fé) no artigo sobre liberdade de expressão (tornando-o mais abrangente, sem modificar o que já exisita), deve-se ir para a versão **1.11.0**;
- **PATCH** - quando faz-se necessário corrigir algum ponto que tenha ficado contraditório. Por exemplo, na versão **1.10.4**, há o artigo sobre direito à vida a todos os cidadãos. Contudo, no momento em que foi criado o artigo em questão, existia escravidão de negros, não contemplada pelo mesmo. Abolida, deve-se corrigir o artigo, deixando claro que o direito à vida estende-se a todas as pessoas, independente de etnia. Logo, o versionamento deve ir para **1.10.5**, deixando clara a correção (considerando que havia um erro na regra modificada pelo *patch*).
