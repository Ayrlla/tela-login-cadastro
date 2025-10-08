📘 SISTEMA DE INDICAÇÃO — EDUCAJÁ

Este projeto é uma aplicação web estática voltada para programas de indicação com foco em usabilidade, gamificação e conversão. Ele simula o fluxo completo de um usuário — desde o cadastro até o acompanhamento de suas indicações e recompensas.

🎯 OBJETIVO

Criar uma interface moderna e acessível para incentivar usuários a promoverem produtos ou serviços por meio de links personalizados. O sistema oferece feedback visual, metas de envio e indicadores de desempenho, tudo com uma abordagem leve e responsiva.

🧩 FUNCIONALIDADES

🔐 LOGIN
- Validação de campos obrigatórios
- Redirecionamento para o painel após login
- Opção de mostrar/ocultar senha

🆕 CADASTRO
- Coleta de nome, telefone, e-mail e senha
- Verificação de senha e confirmação
- Feedback visual em caso de erro ou sucesso
- Redirecionamento automático para login

📊 DASHBOARD
- Exibição de link de indicação com botão de copiar
- Indicadores de desempenho: indicações, vendas e cashback
- Metas e recompensas visuais
- Barra de progresso com porcentagem
- Simulador de atividade para testes de interface

🎨 DESIGN E ESTILO

- Interface responsiva com layout centralizado
- Cards com efeito blur e transparência
- Tipografia moderna e legível
- Cores baseadas em verde (tema de crescimento e confiança)
- Ícones e imagens ilustrativas para reforçar a identidade visual

🖼️ IMAGENS DE FUNDO

- `back1.jpg`: aplicado nas páginas de login e cadastro
- `back2.jpg`: aplicado na página de dashboard

As imagens são aplicadas via CSS nas classes `.auth-page` e `.dashboard-page`, garantindo que fiquem atrás dos cards e ocupem toda a tela.

📁 ESTRUTURA DE PASTAS

- `/img`: imagens do projeto (logo, ícones, fundos)
- `/css`: arquivo `styles.css` com todas as regras visuais
- `/`: arquivos HTML (login.html, cadastro.html, dashboard.html)

🛠️ TECNOLOGIAS UTILIZADAS

- HTML5 sem dependências externas
- CSS3 com variáveis, media queries e efeitos visuais

🚀 COMO USAR

1. Clone o repositório:
   git clone https://github.com/seu-usuario/sistema-indicacao.git

2. Abra `login.html` em seu navegador

3. Navegue pelo fluxo:
   - Login → Dashboard
   - Cadastro → Login → Dashboard

📌 OBSERVAÇÕES

- Este projeto é estático e pode ser facilmente integrado a um backend (Node.js, PHP, Firebase, etc.)
- Ideal para prototipagem, testes de usabilidade ou como base para sistemas de afiliados e marketing de referência

📝 LICENÇA

Este projeto está sob a licença dos participantes, qualquer alteração deve ser comentada e autorizadas pelos dev do projeto.
