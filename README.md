# 📚 Desafio 3 – Perfil de Usuário com Banco de Dados

## Objetivo
Criar um sistema de login em PHP que verifica o usuário e a senha cadastrados no banco de dados `exercicio`, permitindo escolher a cor de fundo da página de perfil.

## Arquivos do projeto
- **15d_login.php:** formulário de login com usuário, senha e escolha da cor de fundo.
- **15d_perfil.php:** página que exibe uma mensagem de boas-vindas e aplica a cor escolhida.
- **15d_logout.php:** encerra a sessão e retorna à página de login.

## Funcionamento
O sistema consulta a tabela `usuarios` para verificar os dados informados. Se estiverem corretos, inicia uma sessão e redireciona para o perfil. Caso contrário, exibe uma mensagem de erro. O usuário também pode sair do sistema pelo link de logout.

## Tecnologias utilizadas
- PHP
- HTML
- CSS
- MySQL

## Banco de dados
**Banco:** `exercicio`

**Tabela:** `usuarios`

## Conclusão
A atividade permite praticar a conexão entre PHP e MySQL, a validação de login, o uso de sessões e a personalização de páginas com CSS.
