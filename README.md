---

### Project: **MyWallet - Crypto** investment and portfolio manager

#### Objective
Create an Android application that allows users to
1. Track their investments in ETFs and cryptocurrencies.
2. Add, modify and delete transactions.
3. View interactive graphs (e.g. value trends).
4. Configure alerts based on thresholds (price, percentage change, etc.).

#### Features
1. **User authentication** :
   - Integrate Firebase Authentication or similar solution for login and registration.
2. **Investment tracking**:
   - Implement CRUD functionality for ETFs and cryptocurrencies.
   - Display a list of transactions with pagination.
3. **Interactive charts**:
   - Use a library like MPAndroidChart to visualize investment performance.
4. **External API**:
   - Retrieve real-time data via APIs (e.g. CoinGecko for cryptocurrencies or Yahoo Finance for ETFs).
5. **Local and online backup**:
   - Implement Room Database for local persistence.
   - Synchronize data with Firestore or another cloud database.
6. **Modern architecture**:
   - Use Clean Architecture and dependency injection with Hilt.
7. **Modern UI/UX**:
   - Follow Material Design 3 guidelines and integrate simple animations with Jetpack Compose.

#### Steps
1. **Set up the environment** :
   - Prepare Android Studio with the necessary plugins.
2. **Local database**:
   - Create entities and DAOs for ETFs and cryptocurrencies.
3. **UI/UX with Compose**:
   - Develop an intuitive user interface with Jetpack Compose.
4. **API integration**:
   - Configure API calls with Retrofit.
   - Add a Repository layer to manage data.
5. **State management**:
   - Use ViewModel and LiveData to manage states and interactions.
6. **Testing**:
   - Write unit tests for ViewModels and integration tests for APIs.
   - Add UI tests with Espresso.

#### Additional challenge
Integrate an educational section into the application with resources for learning how to invest in ETFs and cryptocurrencies, using an Angular backend to manage the educational content.

---
