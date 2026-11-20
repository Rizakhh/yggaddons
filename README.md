# RizakH Addons

Um conjunto de recursos para personalizar e acompanhar suas sessões no [YggIdle](https://jogo.yggidle.com.br/). O addon funciona como um script de usuário instalado no navegador e oferece recursos de caça, informações de progresso e métricas de combate.

Entre os recursos estão opções de caça e alcance, Kite, contadores de abates, acompanhamento de EXP e Chaos, DPS e dano sofrido. Alguns recursos dependem das informações disponíveis durante a sessão; as estimativas não garantem resultados. As opções de Kite protegidas exigem a senha fornecida pelo autor.

## Instalação

1. Instale a extensão **Tampermonkey** pelo [site oficial](https://www.tampermonkey.net/) ou pela [Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
2. No Chrome, abra `chrome://extensions/`; no Brave, abra `brave://extensions/`. Encontre o Tampermonkey e clique em **Detalhes**.
3. Ative **Permitir scripts de usuário**. Se essa opção não aparecer na sua versão do navegador, ative o **Modo do desenvolvedor** na página de extensões. Os nomes e a disponibilidade podem variar conforme o navegador e a versão; consulte as [instruções oficiais do Tampermonkey](https://www.tampermonkey.net/faq.php?locale=pt_BR&q=Q209).
4. Clique em **[Instalar RizakH Addons](https://raw.githubusercontent.com/Rizakhh/yggaddons/main/RizakH-Addons.user.js)**. Na página aberta pelo Tampermonkey, confirme em **Instalar**. Se o código aparecer como texto, confira se a extensão está ativa e se a permissão do passo anterior foi habilitada.
5. Abra ou atualize o [YggIdle](https://jogo.yggidle.com.br/) e acesse o painel do addon. Use **Alt + F5** para abrir ou restaurar a interface.

Se você já usava uma cópia anterior sem atualização pelo GitHub, instale novamente pelo link acima para associá-la ao endereço de atualização. Confirme a substituição no Tampermonkey, se solicitado.

## Atualizações

O Tampermonkey pode verificar e instalar atualizações conforme as configurações da extensão. Além disso, o addon consulta a release pública mais recente do GitHub e, quando detecta uma versão superior à instalada, exibe um aviso com acesso à página de releases. A consulta ocorre ao abrir o jogo e depois periodicamente enquanto a página permanecer aberta. Falhas de conexão ou limites da API podem impedir temporariamente o aviso; o funcionamento do addon continua e o Tampermonkey mantém sua própria verificação.

As versões disponíveis e seus arquivos estão na [página de releases](https://github.com/Rizakhh/yggaddons/releases).

## Uso

Abra o painel no jogo e habilite somente os recursos que deseja utilizar. Os painéis de progresso e métricas ajudam a acompanhar a sessão, enquanto as opções de caça alteram o comportamento do personagem. Consulte as dicas ao passar o mouse sobre os controles para conhecer cada opção.

O addon é um projeto independente e não é uma ferramenta oficial do YggIdle. A versão distribuída é ofuscada; a ofuscação dificulta a leitura, mas não impede a recuperação ou análise do código.

## Histórico de alterações

Consulte o [changelog](CHANGELOG.md) para acompanhar as mudanças de cada versão publicada.

## Problemas

Para relatar um erro ou sugerir melhorias, abra uma [issue](https://github.com/Rizakhh/yggaddons/issues) informando a versão do addon, navegador, situação e, se possível, uma captura de tela.
