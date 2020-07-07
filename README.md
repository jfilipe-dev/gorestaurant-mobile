# GoRestaurant
#### A mobile application to make orders for a restaurant.

### 📺 Preview
<img src="https://user-images.githubusercontent.com/55659197/86515118-3d34f100-bded-11ea-856f-e9289ccf2927.gif" width="280">


### 👨🏻‍💻 Stack and extensions
- React native with typescript
- Axios
- React navigation
- Styled components
- Json server
- React native vector icons

### 💻 Features
- List dishes
- List dishes by category
- Search for dishes
- Make orders
- Add extras on order
- Increase and decrease the number of dishes
- List orders maked
- Add favorite dishes
- List favorite dishes


### 💾 How to install
1. Clone this repository - 
`git clone https://github.com/jfilipe-dev/gorestaurant-mobile.git`

2. Install the dependencies - 
`yarn`

3. Start Json server - 
` yarn json-server server.json -p 3333`

4. Run aplication (emulator)
- android - 
`adb reverse tcp:3333 tcp:3333`
`yarn android`

- ios - 
`cd ios`
`pod install`
`cd ..`
`yarn ios`
