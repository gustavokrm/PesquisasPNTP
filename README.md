# PesquisasPNTP
Cria uma página de pesquisas no Plone que atende aos requisitos do PNTP

Esse page template cria uma busca por pastas no Plone, de forma que se você tiver pastas como transparência, licitações, e precisar apresentá-las com busca, filtros e emissão de relatórios, é possível atender a esses requisitos diretamente no Portal Modelo.

# Como instalar:

Vá na interface de gerência do Zope, /manage
Portal Skins > Custom
Add page template
Coloque um nome e clique em add and edit.
Cole o código e salve. 

Vá agora na pasta em que você quer criar a página de pesquisa e adicione um link, e coloque, no link, o caminho completo para a pasta:
www.cidade.leg.br/transparencia/licitacoes/pesquisaPNTP
Assim o Plone vai buscar arquivos e pastas diretamente naquela pasta onde o link foi colocado.
