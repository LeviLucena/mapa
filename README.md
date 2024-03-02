# Mapa de São Paulo

Este é um projeto que exibe informações sobre casos de arboviroses, nos municípios do estado de São Paulo no formato de um mapa de calor, utilizando bibliotecas para a renderização e interação com os dados geográficos nos municípios representados mediante cores que indicam o nível de incidência dos casos. Para simular casos de doenças transmitidas por vetores, foram gerados dados aleatórios para cada município, mas nada impede que seja utilizado uma conexão via API ou Banco de dados. Além disso, o projeto é responsivo e se adapta a diferentes tamanhos de tela, garantindo uma boa experiência de usuário em dispositivos móveis e desktops.

![image](https://github.com/LeviLucena/mapa/assets/34045910/94238b8b-1740-414a-9f16-cc0cd5bbd25f)

## Demonstração

Uma demonstração em video do mapa pode ser acessada, onde você poderá visualizar os dados e a interação com o mapa.

https://github.com/LeviLucena/mapa/assets/34045910/f7695cb4-6133-4e72-b216-25dc89d77142

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
