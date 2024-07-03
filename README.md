MyStorageApp
MyStorageApp is a simple eCommerce application built with React Native and Expo. The app lets users browse a list of products, add them to a cart, and view or remove items from the cart. It also saves the cart items locally using AsyncStorage, so your cart is preserved even if you close the app.

We used @react-navigation/native and @react-navigation/bottom-tabs to set up easy navigation between the Home screen and the Cart screen. On the Home screen, users can see all available products and add them to their cart with a single tap. The Cart screen shows the selected items and allows users to remove them if needed.

For local storage, we implemented a utility using @react-native-async-storage/async-storage. This handles saving and loading the cart items seamlessly. The Home screen displays products with an "Add to Cart" button for each, while the Cart screen lists cart items with a "Remove from Cart" button.

To get started with MyStorageApp, clone the repository from GitHub, install the dependencies with npm install, and start the Expo development server with npm run start. Screenshots of the app are available in the screenshots directory, showing the Home screen and the Cart screen in action.

MyStorageApp is open-source and licensed under the MIT License. We welcome contributions, so feel free to fork the repository and submit pull requests.

screenshorts

<img width="174" alt="sshot 1" src="https://github.com/Aforve-Peter/rn-asssginment6-11134106/assets/151939336/0fed09b9-0a91-40e5-afee-21da13daf784">
<img width="176" alt="sshot 2" src="https://github.com/Aforve-Peter/rn-asssginment6-11134106/assets/151939336/2c581985-6378-48d0-98c9-2cc3fbb8b359">
<img width="173" alt="sshot 3" src="https://github.com/Aforve-Peter/rn-asssginment6-11134106/assets/151939336/9a42db1a-5465-4703-9ec4-c61cf392438f">
<img width="173" alt="sshot 4" src="https://github.com/Aforve-Peter/rn-asssginment6-11134106/assets/151939336/4916079b-d23f-452b-af2e-c887d328f802">








