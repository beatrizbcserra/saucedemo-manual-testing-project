# **ID do Bug**: BUG-001

**Título**: Link "Wish list" na barra lateral não executa nenhuma ação ao ser clicado

**Severidade**: Média (Funcionalidade visível, mas inoperante)

**Prioridade**: Alta (Impacto na experiência de retenção do usuário)

**Ambiente**: Linux, Mozilla Fire Fox 146.0 (64-bits)

**URL**: https://sauce-demo.myshopify.com/

**Descrição**: Ao navegar pela página inicial e tentar acessar a lista de desejos através do menu lateral, 
o sistema não apresenta nenhuma reação, permanecendo na mesma página sem exibir mensagens de erro ou redirecionar o usuário.

**Pré-condições**: Estar na página inicial do site.

**Passos para Reproduzir**: 1. Clicar na opção "Wish list" presente na "Home page".

**Resultado Esperado**: O usuário deve ser redirecionado para a página de lista de desejos 
ou visualizar um pop-up confirmando que o item foi adicionado/exibindo a lista.

**Resultado Atual**: Nada acontece após o clique. O link parece estar quebrado ou não mapeado para uma função ativa.

**Evidência**: https://drive.google.com/file/d/15OHKkKR7n62ETRk9s54-UuFfzfgVtK71/view?usp=sharing

---

# **ID do Bug**: BUG-002

**Título**: Link "Refer a friend" no menu lateral está inativo (sem resposta ao clique)

**Severidade**: Média (Funcionalidade de negócio indisponível)

**Prioridade**: Média/Alta (Afeta a estratégia de indicação e crescimento da base de usuários)

**Ambiente**: Linux, Mozilla Fire Fox 146.0 (64-bits)

**URL**: https://sauce-demo.myshopify.com/

**Descrição**: Ao clicar na opção "Refer a friend" localizada no menu de navegação lateral, o sistema não executa nenhuma ação. Não há redirecionamento para um formulário de indicação, nem abertura de pop-up ou mensagens de erro.

**Pré-condições**: Estar na página inicial ou em qualquer página que exiba o menu lateral.

**Passos para Reproduzir**: 1. Clicar no link "Refer a friend" presente na "Home Page".

**Resultado Esperado**: O sistema deve exibir uma interface (página ou modal) onde o usuário possa inserir o contato de um amigo para realizar a indicação.

**Resultado Atual**: O link permanece estático. O cursor do mouse muda para o símbolo de seleção, mas o clique não dispara nenhum evento no sistema.

**Evidência**: https://drive.google.com/file/d/1J3BgoMmOmsZjTn7wgYmOlC59vBU_ljNb/view?usp=sharing

---

# **ID do Bug**: BUG-003

**Título**: O usuário não consegue acessar o "My Cart" pela página do item adicionado ao carrinho".

**Severidade**: Alta (Funcionalidade de negócio indisponível)

**Prioridade**: Média/Alta (Impacto na experiência do usuário na compra do produto)

**Ambiente**: Windows, OperaGX 126.0.5750.56 (64-bits)

**URL**: https://sauce-demo.myshopify.com/

**Descrição**: Ao clicar no botão [ADD TO CART] e posteriormente no link "My Cart" pela página do produto, o sistema não conclui o carregamento. Não há redirecionamento para uma página, nem a abertura de pop-up ou mensagens de erro.

**Pré-condições**: Usuário cadastrado.

**Passos para Reproduzir**:

1. Clicar em um dos itens presentes na "Home Page".
2. Clicar no botão [ADD TO CART]
3. Clicar no link "MY Cart"

**Resultado Esperado**: O usuário deve deve conseguir acessar o "My Cart" pela página do item adicionado ao carrinho".

**Resultado Atual**: O usuário não consegue acessar o "My Cart" pela pagina do item adicionado ao carrinho".

**Evidência**: https://drive.google.com/file/d/15c0HgnNG4Zk3aFAa1KycTjjlH9rAAD18/view?usp=sharing
