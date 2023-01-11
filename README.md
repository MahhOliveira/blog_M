# blog_M
Hyde
Hyde é um Zola descarado de duas colunas baseado no tema Jekyll de mesmo nome que combina uma barra lateral proeminente com conteúdo descomplicado.

Hyde screenshot (em inglês)

Conteúdo
Instalação
Opções
Menu da barra lateral
Conteúdo da barra lateral pegajosa
Temas
Layout reverso
Instalação
Primeiro baixe este tema para o seu diretório:themes

cd themes
git clone https://github.com/getzola/hyde.git
e, em seguida, habilite-o em seu :config.toml

theme = "hyde"
Opções
Menu da barra lateral
Defina um campo com uma chave de:extrahyde_links

[extra]
hyde_links = [
    {url = "https://google.com", name = "Google.com"},
    {url = "https://google.fr", name = "Google.fr"},
]
Each link needs to have a and a .urlname

Sticky sidebar content
By default Hyde ships with a sidebar that affixes it's content to the bottom of the sidebar. You can optionally disable this by setting to false in your .hyde_stickyconfig.toml

Themes
Hyde ships with eight optional themes based on the base16 color scheme. Apply a theme to change the color scheme (mostly applies to sidebar and links).

Hyde in red

There are eight themes available at this time.

Hyde theme classes

To use a theme, set the field in to any of the themes name:hyde_themeconfig.toml

[extra]
hyde_theme = "theme-base-08"
To create your own theme, look to the Themes section of included CSS file. Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.

Reverse layout
Hyde com layout reverso

A orientação da página do Hyde pode ser invertida definindo como no .hyde_reversetrueconfig.toml
