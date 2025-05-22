# acido_base
Aplicação interativa para estudo do equilíbrio ácido-base com funcionalidades de IA.
Aplicação Interativa para Estudo do Equilíbrio Ácido-Base com IA
Descrição
Esta é uma aplicação web interativa e educacional projetada para ajudar estudantes e profissionais da área da saúde a compreender os complexos mecanismos do equilíbrio ácido-base no corpo humano. A aplicação aborda desde os fundamentos químicos até distúrbios comuns, mecanismos de compensação e ferramentas diagnósticas. Um recurso de destaque é a capacidade de gerar estudos de caso clínicos hipotéticos usando IA (através da API Gemini) para ilustrar os conceitos na prática.

A interface é organizada em seções navegáveis, cobrindo:

Fundamentos: pH, ácidos, bases, equação de Henderson-Hasselbalch e sistemas tampão.

Regulação: Papel dos pulmões e rins na manutenção do pH.

Fontes: Origem dos ácidos e bases no organismo.

Distúrbios: Classificação dos distúrbios primários (acidose/alcalose metabólica e respiratória), mecanismos de compensação e a funcionalidade de geração de estudos de caso por IA.

Diagnóstico: Cálculo e interpretação do Hiato Aniônico (AG) e da Lacuna Delta (ΔGap).

Avançado: Abordagem de Stewart e Acidose Tubular Renal (ATR).

Funcionalidades Principais
Visualizações Interativas:

Gráfico da relação pH vs. [H⁺] com pontos clicáveis.

Gráfico de pizza mostrando a contribuição dos sistemas tampão.

Conteúdo Educacional Detalhado: Explicações claras e concisas organizadas em seções e acordeões expansíveis.

Calculadoras Diagnósticas:

Cálculo do Hiato Aniônico (AG) com correção para albumina.

Cálculo da Lacuna Delta (ΔGap) e da razão Delta-Delta para avaliação de distúrbios metabólicos mistos.

Geração de Estudos de Caso por IA:

Ao selecionar um distúrbio primário, o utilizador pode gerar um estudo de caso clínico relevante, incluindo descrição do paciente, sintomas e valores laboratoriais típicos, fornecido pela API Gemini.

Navegação Intuitiva: Menu fixo e links internos para fácil acesso às diferentes seções.

Design Responsivo: Adaptável a diferentes tamanhos de ecrã para uso em desktops e dispositivos móveis.

Tecnologias Utilizadas
HTML5: Estrutura da página web.

Tailwind CSS: Framework CSS para estilização rápida e responsiva.

JavaScript (ES6+): Lógica da aplicação, interatividade, cálculos e chamadas de API.

Chart.js: Biblioteca para criação dos gráficos interativos.

API Gemini (Google): Para a funcionalidade de geração de estudos de caso clínicos.

Como Usar
Aceder à Aplicação:

Abra o ficheiro index.html (ou o nome que deu ao ficheiro principal) num navegador web moderno.

Ou, se estiver alojado online, aceda através do URL fornecido.

Navegação:

Use o menu de navegação no topo da página para saltar para as diferentes seções de conteúdo.

Em dispositivos móveis, um menu "hambúrguer" estará disponível.

Interagir com os Elementos:

Gráfico pH vs. [H⁺]: Clique nos botões de pH para ver a concentração de H⁺ correspondente e o ponto destacado no gráfico.

Acordeões: Clique nos cabeçalhos das seções (por exemplo, na regulação renal ou ATR) para expandir e ver mais detalhes.

Calculadoras (Hiato Aniônico, Lacuna Delta): Insira os valores laboratoriais nos campos apropriados e clique nos botões "Calcular" para ver os resultados e interpretações.

Gerador de Estudos de Caso:

Na seção "Distúrbios", selecione um distúrbio primário no menu dropdown.

Clique no botão "✨ Gerar Estudo de Caso Clínico".

Aguarde enquanto a IA processa o pedido (um indicador de carregamento será exibido).

O estudo de caso gerado aparecerá abaixo do botão.

Configuração para Desenvolvimento (se aplicável)
Este projeto é um ficheiro HTML único que utiliza CDNs para bibliotecas externas (Tailwind CSS, Chart.js) e faz chamadas do lado do cliente para a API Gemini.

Importante sobre a API Key Gemini:

No código-fonte (index.html), a variável apiKey para a API Gemini está definida como uma string vazia (const apiKey = "";).

Para que a funcionalidade de geração de estudos de caso funcione, uma chave de API válida do Google AI Studio (para a API Gemini) precisa ser fornecida.

Segurança: Nunca incorpore chaves de API diretamente no código HTML/JavaScript do lado do cliente em aplicações públicas. Para produção, a chave deve ser gerida através de um backend ou funções serverless que atuem como intermediário. Se estiver a testar localmente ou num ambiente controlado, pode substituir temporariamente a string vazia pela sua chave, mas esteja ciente dos riscos.

Possíveis Melhorias Futuras
Implementar um backend seguro para gerir a chave da API Gemini.

Adicionar mais estudos de caso ou cenários interativos.

Expandir as seções com mais detalhes ou tópicos avançados.

Permitir que os utilizadores guardem ou exportem os resultados dos cálculos.

Internacionalização para outros idiomas.

Contribuições
Contribuições são bem-vindas! Se tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou um pull request.

