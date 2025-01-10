Projeto: Controle de Horas em Redes Sociais
Este projeto tem como objetivo fornecer uma ferramenta para ajudar os usuários a controlarem o tempo gasto em redes sociais. Utilizando Kotlin, a aplicação registra e exibe o número de horas gastas em diferentes plataformas de redes sociais, ajudando a promover um uso mais consciente e equilibrado das redes.

Funcionalidades
Registro de Tempo: A aplicação permite que o usuário registre o tempo gasto em diferentes redes sociais.
Histórico de Uso: O histórico de tempo gasto em cada plataforma é armazenado, permitindo ao usuário visualizar quanto tempo foi gasto em cada uma.
Notificações de Limite: O aplicativo pode configurar notificações quando o tempo gasto em uma rede social atingir um limite preestabelecido.
Relatórios de Uso: Gerar relatórios semanais ou mensais sobre o tempo total gasto em redes sociais.
Interface Simples e Intuitiva: A interface foi projetada para ser fácil de usar e de entender, com o objetivo de oferecer uma experiência agradável ao usuário.
Tecnologias Utilizadas
Kotlin: Linguagem de programação principal para o desenvolvimento da aplicação.
Android SDK: Para criação da interface e funcionalidade no Android.
SQLite: Banco de dados local para armazenamento dos registros de tempo.
Notification Manager: Para enviar notificações quando o usuário atingir o limite de tempo configurado.
Requisitos
Android Studio: IDE recomendada para desenvolvimento.
Android 5.0 (Lollipop) ou superior.
Como Usar
Instalação:

Baixe o repositório ou clone o projeto utilizando o Git.
Abra o projeto no Android Studio.
Compile e execute no seu dispositivo Android ou emulador.
Registrando o Tempo:

Ao abrir o app, você será apresentado a uma lista de redes sociais.
Selecione a rede social que deseja registrar o tempo.
Aplique o tempo manualmente ou ative um cronômetro para registrar automaticamente.
Configurando Limites e Notificações:

Vá para as configurações do aplicativo e defina o limite de tempo diário para cada rede social.
Configure notificações para ser avisado quando atingir o limite.
Visualizando Relatórios:

Acesse a seção de relatórios para visualizar gráficos e relatórios do seu uso semanal ou mensal.
Estrutura do Projeto
app/src/main/java/com/exemplo/socialcontrol:

MainActivity.kt: Tela principal com a interface do usuário para interagir com o aplicativo.
DatabaseHelper.kt: Classe responsável pela interação com o banco de dados SQLite.
NotificationService.kt: Gerencia o envio de notificações.
app/src/main/res/layout:

activity_main.xml: Layout da tela principal.
settings_activity.xml: Layout para as configurações do aplicativo.
Contribuições
Sinta-se à vontade para contribuir com o projeto! Se você encontrar um erro ou quiser sugerir melhorias, por favor, abra uma "issue" ou envie um "pull request".

Fork o repositório.
Crie uma branch para sua feature (git checkout -b feature/nova-feature).
Commit suas alterações (git commit -am 'Adiciona nova feature').
Push para a branch (git push origin feature/nova-feature).
Abra um pull request.
Licença
Este projeto é licenciado sob a Licença IFPB.
