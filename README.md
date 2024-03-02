# Mapa de São Paulo

Este é um projeto que exibe informações sobre casos de arboviroses, nos municípios do estado de São Paulo no formato de um mapa de calor, utilizando bibliotecas para a renderização e interação com os dados geográficos nos municípios representados mediante cores que indicam o nível de incidência dos casos. Para simular casos de doenças transmitidas por vetores, foram gerados dados aleatórios para cada município, mas nada impede que seja utilizado uma conexão via API ou Banco de dados. Além disso, o projeto é responsivo e se adapta a diferentes tamanhos de tela, garantindo uma boa experiência de usuário em dispositivos móveis e desktops.

![image](https://github.com/LeviLucena/mapa/assets/34045910/94238b8b-1740-414a-9f16-cc0cd5bbd25f)

## Demonstração

Uma demonstração do mapa pode ser acessada https://vimeo.com/manage/videos/918534823 , onde você poderá visualizar os dados e a interação com o mapa.
<div style="padding:46.88% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/918534823?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Mapa-de-São-Paulo"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Funcionalidades

- **Contadores de Casos:** Exibe contadores dos casos de arbovirores.
- **Legenda de Cores:** Fornece uma legenda explicando o significado das cores utilizadas no mapa.
- **Pop-ups de Informações:** Ao passar o mouse sobre um município, um pop-up é exibido com informações detalhadas sobre os casos de cada doença naquela região.

## Como Utilizar

1. Clone o repositório para sua máquina local.
2. Abra o arquivo `mapa.html` em um navegador web.
3. Aguarde o carregamento completo do mapa e dos dados.
4. Explore o mapa movendo-se pela região de São Paulo e interagindo com os dados.

## Bibliotecas Utilizadas

- **Leaflet.js:** Biblioteca JavaScript de código aberto para mapas interativos.

## Arquivo JSON

Os limites dos municípios de São Paulo são carregados a partir do arquivo `SP_Municipios_2022.json`.

## Critérios para as Cores

As cores dos municípios são determinadas com base nos seguintes critérios:

- **Vermelho:** Casos acima de 2000.
- **Laranja:** Casos entre 1000 e 1999.
- **Amarelo:** Casos entre 100 e 999.
- **Verde:** Casos abaixo de 99.

## Contribuindo

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga estas etapas:

## Autor

Este projeto foi desenvolvido por [Seu Nome], e é mantido pela comunidade.

## Licença

Este projeto está licenciado sob a Licença MIT.
