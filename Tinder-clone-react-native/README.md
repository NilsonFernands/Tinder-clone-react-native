<h1 align="center">
<img
		width="250"
		alt="Tinder Clone - React Native"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/tinder-clone-logo.gif">
</h1>
<h3 align="center">
	Tinder Clone - React Native
</h3>

<p align="center">
	<img alt="Last Commit" src="https://img.shields.io/github/last-commit/stevenpersia/tinder-react-native.svg?style=flat-square">
	<img alt="Licence" src="https://img.shields.io/github/license/stevenpersia/tinder-react-native.svg?style=flat-square">
	<img alt="Star" src="https://img.shields.io/badge/you%20like%20%3F-STAR%20ME-blue.svg?style=flat-square">
</p>

<p align="center">
	<img src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/tinderclone-preview.gif" width="300">
</p>


## Visão geral

⚠️ ** Este repositório não é mais mantido. Fiz outro repositório deste projeto na Expo (e com Typescript): https://github.com/stevenpersia/tinder-expo.**

👏 ** Obrigado por suas estrelas, seus problemas e seus pedidos de pull. Eu realmente amo a comunidade de código aberto. ** ❤️

** Perfeito para iniciar um aplicativo Tinder Clone. ** 4 telas disponíveis: Explorar, Combinar, Mensagens e Perfil. Você encontrará alguns componentes como o componente de cartão para passar adereços e variantes. Nenhum framework UI como Bootstrap ou Material UI é usado.

Mais recursos serão adicionados ao projeto no futuro.

Este projeto foi inspirado por este [incrível trabalho de Kishore no Dribbble] (https://dribbble.com/shots/5631075-Dating-App-Sketch-Freebie-Day-334-365-Project365). Sinta-se à vontade para seguir esse cara porque ele faz ótimas coisas.


## Screenshots

<img
		width="210"
		alt="Capture 1"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-1.png">
<img
		width="210"
		alt="Capture 2"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-2.png">
<img
		width="210"
		alt="Capture 3"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-3.png">
<img
		width="210"
		alt="Capture 4"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-4.png">


## Instalação e uso

Certifique-se de ter instalado todas as dependências e aplicativos para executar o projeto React Native em seu computador: [Getting Started with React Native] (https://facebook.github.io/react-native/docs/getting-started).

Este projeto funciona bem para iOS, mas na versão Android existem sérios problemas de IU porque eu só trabalhei no iOS.


### Executando o projeto

Clone este repositório:

```
git clone https://github.com/NilsonFernands//tinder-react-clone-native.git
cd tinder-react-native
```

Instalar packages :

```
npm install
```

Quando a instalação estiver concluída, execute com a versão de sua escolha :

```bash
react-native run-ios
# or
react-native run-android
```


## Props

### CardItem

| Nome           | Tipo     | Requirido | Descriçao                                               | Exemplo                                             |
| -------------- | -------- | -------- | --------------------------------------------------------- | --------------------------------------------------- |
| `image`        | string   | Yes      | Picture of member.                                        | `image="https://..."`                               |
| `name`         | string   | Yes      | Name of member.                                           | `name="John Doe"`                                   |
| `description`  | string   | Yes      | Description of member.                                    | `description="Full-time Traveller. Globe Trotter."` |
| `matches`      | string   | Yes      | Match percentage.                                         | `matches="95"`                                      |
| `actions`      | boolean  | No       | Display actions buttons (Like, Dislike, ...).             | `actions`                                           |
| `onPressLeft`  | function | No       | Swipe card to left.                                       | `onPressLeft={() => this.swiper.swipeLeft()}`       |
| `onPressRight` | function | No       | Swipe card to right.                                      | `onPressRight={() => this.swiper.swipeRight()}`     |
| `status`       | string   | No       | Display online or offline badge (`Online` and `Offline`). | `status="Online"`                                   |
| `variant`      | boolean  | No       | Display another style of card (used for Matches screen).  | `variant`                                           |

### Mensagem

| Nome          | Tipo   | Requirido | Descriçao             | Exemplo                                                                                    |
| ------------- | ------ | -------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| `image`       | string | Yes      | Picture of member.      | `image="https://..."`                                                                        |
| `name`        | string | Yes      | Name of member.         | `name="John Doe"`                                                                            |
| `lastMessage` | string | Yes      | Last message of member. | `lastMessage="You want order in Gotham. Batman must take off his mask and turn himself in."` |


### ProfileItem

| Name       | Type   | Required | Description                 | Example                                    |
| ---------- | ------ | -------- | --------------------------- | ------------------------------------------ |
| `name`     | string | Yes      | Name of member.             | `name="John Doe"`                          |
| `matches`  | string | Yes      | Match percentage.           | `matches="95"`                             |
| `age`      | string | No       | Age of member.              | `age="25"`                                 |
| `location` | string | No       | Location of member.         | `location="Paris, France"`                 |
| `info1`    | string | No       | More information of member. | `info1="Straight, Single"`                 |
| `info2`    | string | No       | More information of member. | `info2="Tea Totaller & Loves Photography"` |
| `info3`    | string | No       | More information of member. | `info3="Beaches, Mountain & Coffee"`       |
| `info4`    | string | No       | More information of member. | `info4="Last seen: 23h ago"`               |


## Estrela

Sinta-se à vontade para contribuir neste repositório. Se meu trabalho te ajudar, por favor me devolva com uma estrela. Isso significa muito para mim e me faz continuar!
antençao: este conteudo foi adquirdo pelo Live em curso de JavascriptMastery no Youtube, qualquer duvida em aprendizagem pls de uma olhada lá
## Parceiros

<!-- ALL-CONTRIBUTORS-LIST:START - Não remova ou modifique esta seção -->
<!-- prettier-ignore -->


<!-- ALL-CONTRIBUTORS-LIST:END -->
