# CineStream

Aplicativo de streaming de filmes e séries para Windows e Android TV.

Este repositório publica apenas os instaladores e as atualizações do app. O código-fonte é privado.

## Download

Baixe a versão mais recente na página de [Releases](../../releases). Cada plataforma tem as suas próprias versões:

| Plataforma | Tag da release | Arquivo | Para que serve |
| --- | --- | --- | --- |
| Windows | `v1.x.x` | `CineStream-Setup.exe` | Instalador recomendado. Recebe atualizações automáticas. |
| Windows | `v1.x.x` | `CineStream-Portable.exe` | Versão portátil, sem instalação. Não se atualiza sozinha. |
| Android TV | `tv-v1.x.x` | `CineStream-TV.apk` | App para TV e TV Box. Atualiza pelo próprio app. |

Para Windows, use a release mais recente cuja tag começa com `v`. Para Android TV, use a release mais recente cuja tag começa com `tv-`.

Requisitos:
- **Windows:** Windows 10 ou superior, 64 bits.
- **Android TV:** Android 7.0 ou superior.

## Instalação no Windows

1. Baixe o `CineStream-Setup.exe`.
2. Execute o arquivo e siga o assistente. Você pode escolher a pasta de instalação.
3. Ao terminar, o CineStream abre sozinho.

Se o Windows exibir o aviso "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece porque o instalador ainda não tem assinatura digital.

## Instalação na Android TV

1. Baixe o `CineStream-TV.apk` da release com tag `tv-...` mais recente. Você pode baixar no computador e passar para a TV por pen drive, ou baixar direto na TV com um navegador ou um app de arquivos.
2. Na TV, permita a instalação de apps de fontes desconhecidas para o app que você usou para abrir o arquivo (Configurações > Segurança e restrições).
3. Abra o APK e confirme a instalação.
4. Abra o CineStream, crie uma conta ou entre com a sua.

## O que o app oferece

- Catálogo de filmes e séries, com populares, destaque e navegação por gênero.
- Busca por título.
- Página de detalhes e player de vídeo.
- Conta de usuário com cadastro e login.
- Favoritos.
- Histórico do que você assistiu, com os itens mais recentes na tela inicial.
- Indicação de conteúdo dublado ou legendado.
- Watch Party (Windows): assista em grupo com o player sincronizado e chat.
- Links `cinestream://` (Windows): abrem o app direto em uma página.
- Navegação pelo controle remoto (Android TV).

## Atualizações

**Windows:** com o instalador, o app verifica sozinho ao abrir se existe uma versão nova. Quando houver, aparece um aviso com as opções de baixar e de reiniciar para aplicar. Se você usa a versão portátil, baixe o instalador mais recente desta página e instale por cima.

**Android TV:** o app verifica uma vez por dia, ao abrir. Quando há versão nova, aparece um aviso e um item no sino, no topo direito. Em Configurações > Sobre você também pode verificar na hora. A instalação mostra a confirmação normal do Android. Seus favoritos, histórico e configurações permanecem.

## Problemas e sugestões

Abra uma [issue](../../issues) descrevendo o que aconteceu, a plataforma (Windows ou Android TV) e a versão do app.

## Privacidade

O app guarda sua conta, favoritos e histórico para funcionar. A política completa está na tela "Políticas de privacidade" dentro do app.
