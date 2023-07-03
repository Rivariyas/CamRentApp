# CamRentApp
Here's a step-by-step breakdown of the algorithm in the code:

1. The Main3 class contains the `main` method, which serves as the entry point of the program.
2. In the main method, an instance of the CamRentApp class is created, and the  displayWelcomeScreen and login methods are called.
3. The CamRentApp class represents the camera rental application and contains methods for displaying the welcome screen, handling login, showing the main menu, renting a camera, managing the wallet, and listing cameras.
4. The login  method prompts the user to enter their username and password. If the entered credentials match the predefined username and password, the user is logged in and the showMainMenu method is called. Otherwise, an error message is displayed, and the application exits.
5. The showMainMenu method presents a menu of options to the user and handles their choices using a switch statement.
6. If the user chooses option 1, the handleMyCamerasMenu method of the CamerasMenus class is called, which allows the user to add, remove, or view their cameras.
7. If the user chooses option 2, the rentCamera method is called. It displays the available cameras and prompts the user to enter the camera ID they want to rent. If the camera is available and the user has enough balance in their wallet, the camera is rented, and the wallet balance is updated accordingly.
8. If the user chooses option 3, the listCameras method is called, which lists all available cameras and their details.
9. If the user chooses option 4, the handleWalletMenu method is called. It displays the current wallet balance and allows the user to deposit more money if desired.
10. If the user chooses option 5, a farewell message is displayed, and the program exits.
11. The CameraApp class represents a camera object with properties such as ID, brand, model, rental amount, and rental status. It provides getter and setter methods for these properties.
12. The CamerasMenus class provides methods to handle the menu options related to managing the user's cameras. It allows the user to add a camera, remove a camera, and view their cameras.
