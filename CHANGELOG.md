# Changelog

Todas as mudanças notáveis neste projeto serão documentadas neste arquivo.

## [26/04/2025] - Adição do Projeto ECOA

### Adicionado
- Nova seção no index.html para o projeto "ECOA - Evolução Cognitiva"
- Link para a documentação "ECOA-EVOLUÇÃO COGNITIVA Arrays Unidedumultiversais Auto-Informativos.md"
- Separador visual (linha horizontal) entre os projetos FCC e ECOA
- Descrição do projeto: "Framework de Arrays Unidedumultiversais para Sistemas de IA"

### Melhorado
- Corrigido problema de segurança adicionando `rel="noopener"` ao link externo da licença Creative Commons
- Estrutura visual aprimorada com separação clara entre os dois projetos

### Técnico
- Mantidos os mesmos padrões de estilo e formatação do projeto existente
- Links testados e funcionando corretamente
- Responsividade preservada

## [26/04/2025] - Layout Responsivo para Projetos

### Adicionado
- Estrutura em colunas para exibir os projetos ECOA e FCC lado a lado
- Estilos CSS para garantir igualdade de tamanho e alinhamento visual
- Contêiner flexível com margens e espaçamento adequados

### Melhorado
- Ambos os projetos agora ocupam a mesma área visual
- Disposição responsiva para diferentes tamanhos de tela
- Acessibilidade melhorada com contraste e padding ajustados

### Técnico
- Testes realizados em múltiplos dispositivos
- Garantida compatibilidade com padrões HTML5 e CSS3
- Layout mantém coerência com o design original

## [26/04/2025] - Formatação do Documento ECOA

### Reformatado
- Arquivo "ECOA-EVOLUÇÃO COGNITIVA Arrays Unidedumultiversais Auto-Informativos.md" reformatado seguindo o padrão do documento FCC
- Adicionado cabeçalho com informações do autor, data e licença
- Criado sumário/índice com numeração de páginas
- Reorganizado conteúdo em seções numeradas (1-13)
- Adicionado fluxograma do processo de Arrays Unidedumultiversais
- Incluídas referências bibliográficas sugeridas

### Melhorado
- Estrutura de documento mais profissional e acadêmica
- Navegação facilitada através do índice
- Consistência visual com outros documentos do projeto
- Correção de duplicação de seções

### Técnico
- Mantida toda a informação técnica original
- Preservados códigos e exemplos práticos
- Formatação markdown otimizada para leitura

## [26/04/2025] - Conversão do Documento ECOA para TXT e PDF

### Adicionado
- Arquivo "ECOA-EVOLUÇÃO COGNITIVA Arrays Unidedumultiversais Auto-Informativos.txt" - versão em texto puro do documento
- Arquivo "ECOA-EVOLUÇÃO COGNITIVA Arrays Unidedumultiversais Auto-Informativos.pdf" - versão em PDF do documento

### Melhorado
- Disponibilização do conteúdo em múltiplos formatos para diferentes necessidades de uso
- Versão TXT para compatibilidade universal e processamento de texto
- Versão PDF para apresentação profissional e impressão

### Técnico
- Conversão realizada preservando toda a formatação e conteúdo original
- PDF gerado usando biblioteca reportlab do Python
- Encoding UTF-8 mantido para suporte completo a caracteres especiais
- Estrutura de parágrafos e espaçamento otimizada para leitura

## [26/04/2025] - Adição do Brasão ao index.html

### Adicionado
- Imagem "BRASAO_DO_ANDARILHO3.jpg" posicionada no canto superior direito da página
- Estilos CSS para fixar a imagem com posição absoluta no header

### Melhorado
- Design visual com identidade visual reforçada
- Consistência estilística com elementos gráficos existentes

### Técnico
- Código HTML e CSS validados para padrões atuais
- Responsividade mantida em diferentes tamanhos de tela
- Testes visuais realizados para garantia de funcionalidade

## [26/04/2025] - Tradução e Formatação do Documento FCC para Português

### Adicionado
- Arquivo "FracturadeCoerenciaContextual.md" - versão em markdown em português brasileiro do documento FCC
- Tradução completa seguindo o padrão e formatação do documento original em inglês
- Estrutura de índice com navegação por âncoras
- Formatação markdown profissional com seções numeradas (1-12)

### Melhorado
- Disponibilização do conteúdo FCC em português brasileiro
- Consistência visual e estrutural com outros documentos do projeto
- Navegação facilitada através do índice com links internos
- Preservação de toda a informação técnica original

### Técnico
- Tradução baseada no arquivo "FracturadeCoerenciaContextual.txt" existente
- Formatação markdown otimizada para leitura e navegação
- Manutenção de todos os termos técnicos e conceitos originais
- Estrutura de cabeçalho com informações do autor, data e licença

## [26/04/2025] - Atualização do index.html para Documento FCC em Português

### Adicionado
- Link para "FracturadeCoerenciaContextual.md" no projeto FCC
- Botão "Ver Documentação Completa" para acesso ao documento em markdown
- Manutenção do botão "Baixar PDF" para versão em PDF

### Melhorado
- Interface consistente entre os projetos ECOA e FCC
- Disponibilização de múltiplos formatos (MD e PDF) para o projeto FCC
- Experiência do usuário padronizada entre os dois projetos

### Técnico
- Atualização dos links no index.html
- Manutenção da responsividade e design visual
- Preservação da funcionalidade de alternância de idiomas

## [26/04/2025] - Correção de Links e Inversão de Botões no index.html

### Corrigido
- Link do PDF do projeto ECOA que estava apontando incorretamente para arquivo .md
- Inversão da ordem dos botões em ambos os projetos (ECOA e FCC)
- Botão "Baixar PDF" agora aparece primeiro, seguido do "Ver Documentação Completa"

### Melhorado
- Consistência na ordem dos botões entre os dois projetos
- Experiência do usuário mais intuitiva com PDF como primeira opção
- Correção de links quebrados no projeto ECOA

### Técnico
- Verificação e correção de todos os links no index.html
- Manutenção da funcionalidade de alternância de idiomas
- Preservação da responsividade e design visual

## [26/04/2025] - Correção da Função JavaScript de Alternância de Idiomas

### Corrigido
- Erro na função `updateDocumentLinks` que estava sempre redirecionando links ECOA para arquivos .md
- Lógica de detecção de tipo de arquivo (PDF vs MD) corrigida
- Adicionadas referências para 'fcc-md' nos objetos de tradução

### Melhorado
- Funcionamento correto da alternância de idiomas para todos os tipos de arquivo
- Links PDF agora apontam corretamente para arquivos .pdf
- Links MD agora apontam corretamente para arquivos .md

### Técnico
- Reescrita da lógica de detecção de tipo de arquivo baseada no href atual
- Adição de chaves 'fcc-md' nos objetos translations para português e inglês
- Correção da função JavaScript para distinguir entre links PDF e MD

## [26/04/2025] - Adição de Links Sociais e Contato no Rodapé

### Adicionado
- Links para LinkedIn e GitHub no rodapé da página
- Links de email para roger@webstorage.com.br e rlufti@gmail.com
- Ícones SVG personalizados para LinkedIn, GitHub e email
- Estilos CSS para os links sociais e de contato com efeitos hover
- Responsividade para dispositivos móveis

### Melhorado
- Presença digital profissional com links para redes sociais
- Facilidade de contato direto através de emails
- Design visual consistente com o tema da página
- Efeitos de hover com cores específicas para cada plataforma
- Layout responsivo que se adapta a diferentes tamanhos de tela

### Técnico
- Implementação de ícones SVG inline para melhor performance
- Estilos CSS com backdrop-filter para efeito de vidro
- Links sociais configurados com target="_blank" e rel="noopener" para segurança
- Links de email usando protocolo mailto: para abertura automática do cliente de email
- Responsividade implementada para dispositivos móveis
