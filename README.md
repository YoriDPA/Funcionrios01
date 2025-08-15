Sistema de Gestão de Funcionários
📝 Descrição
Este é um sistema web simples, de página única, projetado para auxiliar no gerenciamento de informações e registros de funcionários. A aplicação permite cadastrar novos funcionários, registrar dados como faltas, atestados e abonos, além de calcular o tempo de serviço na empresa.

Todos os dados são salvos em tempo real utilizando o Firebase (Firestore), garantindo que as informações não sejam perdidas ao fechar ou recarregar a página.

✨ Funcionalidades Principais
Adicionar Funcionários: Cadastre novos funcionários com nome, matrícula e data de admissão.

Lista Dinâmica: Visualize todos os funcionários cadastrados em uma lista organizada em ordem alfabética.

Registro de Ocorrências: Anote o número de faltas, atestados e abonos para cada funcionário.

Observações: Adicione notas e observações importantes para cada membro da equipe.

Cálculo de Tempo de Empresa: O sistema calcula e exibe automaticamente há quanto tempo o funcionário está na empresa com base na data de admissão.

Persistência de Dados: As informações são salvas na nuvem, permitindo o acesso de qualquer lugar (dentro do ambiente de execução).

Design Responsivo: A interface se adapta a diferentes tamanhos de tela, funcionando bem em desktops e dispositivos móveis.

🚀 Como Executar o Projeto
Este projeto foi desenvolvido para ser executado em um ambiente específico que fornece as configurações de conexão com o banco de dados (Firebase).

Ambiente de Execução: Para que o salvamento de dados funcione, o arquivo index.html deve ser executado em um servidor ou ambiente que forneça as variáveis de configuração do Firebase (__app_id e __firebase_config).

Uso Local (Visualização): Se você abrir o arquivo index.html diretamente no seu navegador a partir de uma pasta local, a aplicação será exibida, mas não conseguirá se conectar ao banco de dados. As funcionalidades de adicionar, salvar e carregar funcionários não irão funcionar.

🛠️ Tecnologias Utilizadas
HTML5

CSS3 com Tailwind CSS para estilização rápida e responsiva.

JavaScript (ES6 Modules)

Firebase (Firestore) como banco de dados NoSQL em tempo real.AppFuncionarios
