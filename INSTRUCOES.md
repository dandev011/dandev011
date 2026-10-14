# Perfil de Danilo — pronto para publicar

Esta pasta contém a apresentação de Danilo e da Real Mídia Center para o perfil do GitHub. Não exige instalação, dependências, servidor ou build.

## Arquivos

- `README.md`: apresentação que será exibida no perfil.
- `assets/terminal.svg`: painel de apresentação, sem scripts ou recursos externos.
- `assets/profile.jpeg`: retrato de 384 × 384 pixels.
- `INSTRUCOES.md`: este guia de publicação e manutenção.
- `perfil-github-danilo.zip`: pacote desses quatro arquivos, com a estrutura de pastas preservada.

## Publicar pelo navegador

1. Entre na sua conta do GitHub e crie um repositório **público**, pertencente à sua conta pessoal, com o nome exatamente igual ao seu nome de usuário.
2. Extraia `perfil-github-danilo.zip` em uma pasta separada.
3. Na página do repositório, use a opção de enviar arquivos. Envie `README.md`, `INSTRUCOES.md` e a pasta `assets`, mantendo seus dois arquivos dentro dela. Não envie o ZIP.
4. Confirme o commit na branch padrão. Se já existir um README, substitua seu conteúdo pelo arquivo deste pacote.
5. Abra seu perfil e confira a apresentação e as imagens.

O `README.md` precisa ficar na raiz do repositório. A pasta local não é atualmente um repositório Git válido; a publicação pelo navegador dispensa configurar Git neste diretório.

Documentação oficial: https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme

## Contatos usados

- Site: https://realmidiacenter.com
- Desenvolvimento: https://dev.realmidiacenter.com
- E-mail: contato@realmidiacenter.com

Os contatos são os mesmos no README e no SVG. Antes de publicar, confirme que são os endereços que deseja divulgar. A validação local verifica consistência; não confirma funcionamento dos sites ou entrega de e-mail.

## Estatísticas opcionais

A apresentação principal está pronta sem estatísticas. O bloco no fim do README está configurado para o usuário `dandev011`.

Os cards dependem de serviços externos e podem ficar indisponíveis.

## Atualizar depois

Edite `README.md` para alterar a apresentação. Ao mudar contatos, atualize também `assets/terminal.svg`. Para trocar o retrato, substitua `assets/profile.jpeg` mantendo o nome ou ajuste o caminho no README.

O ZIP é uma cópia dos arquivos no momento da preparação. Alterações posteriores precisam ser incluídas em um novo pacote ou enviadas diretamente ao repositório.

## Verificações realizadas

- As duas imagens referenciadas pelo README existem.
- O SVG é XML válido e não contém scripts nem elementos foreignObject.
- O retrato tem assinatura de arquivo JPEG válida.
- Os contatos do README e do SVG são consistentes.
- As estatísticas usam o usuário `dandev011`.

A exibição final deve ser conferida no GitHub após a publicação.
