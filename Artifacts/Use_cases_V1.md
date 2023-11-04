# Use cases

* [UC01 - Register a profile](#uc01--register-profile)
* [UC02 - Log in to a profile](#uc02--log-in-to-a-profile)
* [UC03 - Customize profile](#uc03--customize-profile)
* [UC04 - Edit profile](#uc04--edit-profile)
* [UC05 - Upload multimedia files](#uc05--upload-media-files)
* [UC06 - Chat between users](#uc06--chat-between-users)
* [UC07 - Promote equipment for rent or sale](#uc07--promote-equipment-for-rent-or-sale)
* [UC08 - Select a equipment in need to rent or buy](#uc08--select-a-equipment-in-need-to-rent-or-buy)
* [UC09 - Filter the browser](#uc09--filter-the-browser)
* [UC10 - Add another user from Musicder](#uc10--add-another-user-from-musicder)

* cambio paa checar seguridad

## UC01- Register profile

| <!-- -->            |   <!-- -->                                                                                                  |
|:--------------------|:------------------------------------------------------------------------------------------------------------|
| **Description**     | This function will make the registration process                                                            |
| **Precondition**    | User must be connected to Internet and have a phone number or a mail account                                |
| **Normal sequence** | 1. User: Enter to system and select to create a new account                                                 |
|                     | 2. System: Deploy the registration questionnaire                                                            |
|                     | 3. User: Complete the questionnaie with full name, phone number or mail account and accept the terms of use |
|                     | 4. System: Register the new user in the data base and return to log in window                               |
| **Postcondition**   | The system has registered the new user                                                                      |
| **Exceptions**      | The phone or mail has already been registered                                                               |
|                     | 1. System: Inform that that acount has already been registered and return to log in window                  |
| **Comments**        |                                                                                                             |

## UC02- Log in to a profile

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will allow the user to acces their account       |
| **Precondition**    | The user is connected to Internet and the user has acces to a registered account  |
| **Normal sequence** | 1. System: Presents to user the log in page, asking for phone number/mail and password     |
|| 2. User: Enters their phone number/mail and password  |
|| 3. System: Validates data and allow user to acces their profile |
| **Postcondition**   |  The user is successfully logged in and have access to their profile             |
| **Exceptions**      | Account Lockout: if there have been multiple unsuccessful login attempts, the system locks the user's account temporarily for security reasons                  |
| **Comments**        |                  |

## UC03- Customize profile

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |  This function will enable users to choose their preferences |
| **Precondition**    |  User must be connected to Internet and have acces to a registered account|
| **Normal sequence** |  1. User: Selects "Profile" |
|| 2. System: Shows "Profile" window |
|| 3. User: Selecs "Customiza Profile"|
|| 4. System: Shows "Customize Profile" window|
|| 5. User: Selects an option in the parameters shown, shuch as interest, experience, favorite musical genres, etc. |
|| 6. User: Confirm the information |
|| 7. System: Saves the information |
| **Postcondition**   | The user's profile settings and preferences are updated according to their choices    |
| **Exceptions**      |  |
| **Comments**        |  |

## UC04- Edit profile

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | The user will be able to edit the information registered   |
| **Precondition**    | The user must be connected to Internet and have acces to a registered account      |
| **Normal sequence** | 1. User: Acces to "Profile" and "Edit profile"                 |
|| 2. System: Opens the edit profile window |
|| 3. User: Modifies the information needed
|| 4. User: Confirm the new information
|| 5. System: Save the new information in the data base
|| 6. System: Close the "Edit profile" window
| **Postcondition**   | The users information is uppdated in the system                 |
| **Exceptions**      |                  |
| **Comments**        |                |

## UC05- Upload media files

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will anable the user to upload files such as videos, photos, music, etc.                 |
| **Precondition**    | The user must be connected to Internet and have acces to a registered account                 |
| **Normal sequence** | 1. User: Acces to "Profile" and select "Upload files"                |
|| 2. System: Opens files window
|| 3. User: Select the file wanted and confirm |
|| 4. System: Save it in the data base and show it in the profile
| **Postcondition**   | The user file is uploaded in their profile                 |
| **Exceptions**      | The tipe of file is unvalid                 |
| **Comments**        |                  |

## UC06- Chat between users

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will allow the user to chat between them and store the chat history                 |
| **Precondition**    | Both users must be connected to Internet and have acces to registed accounts                 |
| **Normal sequence** | 1. User 1: Acces to the "Chat" |
|| 2. System: Show "added users"                 |
|| 3. User 1: Select the destinatary
|| 4. System: Open the chat window
|| 5. User 1: Type message and send it
|| 6. System: Notifies user 2 about the message
| **Postcondition**   | User 1 has send the message and user 2 has recive it                 |
| **Exceptions**      | User 2 has blocked user 1             |
| **Comments**        |                  |

## UC07- Promote equipment for rent or sale

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will enable the user to upload music equipment for sale and define the price wanted          |
| **Precondition**    | The user must be connected to Internet, have acces to a registered account and have the equipment                  |
| **Normal sequence** | 1. User: Acces the "shop" area                |
|| 2. System: Opens the shop window |
|| 3. User: Select "add" |
|| 4. User: Upload a photo of the equipment and fill the information required |
|| 5. System: Saves the data and post it in the "Shop" area |
| **Postcondition**   | Users equipment is added to the shop page                 |
| **Exceptions**      | User does not fill properly all the information                 |
| **Comments**        |                  |

## UC08- Select a equipment in need to rent or buy

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will enable user to select equipment wanted for rent or to buy                 |
| **Precondition**    | The user must be connected to Internet, have acces to a registered account and other user has submited the equipmed desired        |
| **Normal sequence** | 1. User: Acces the "shop" area                 |
|| 2. System: Shows equioment available nearby |
|| 3. User: Selects the "Search option"
|| 4. System: Shows posibble filters to aply |
|| 5. User: Write the equipment wanted or fill the filters |
|| 6. System: Deploy options according to the users input |
|| 7. User: Select the option wanted |
|| 8. System: Opens chat between user and owner of the equipment |
| **Postcondition**   | User will have selected the equipment andn                 |
| **Exceptions**      | There is not the desired equipment nearby                 |
| **Comments**        |                  |

## UC09- Filter the browser

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will enable users to aply filters when browsing in any area    |
| **Precondition**    | The user must be connected to Internet, have acces to a registered account and be in one of the 3 main area, "Shop", "Chat" or "Tinder"       |
| **Normal sequence** | 1. User: Selects one of 3 areas        |
|| 2. User: Select the search icon |
|| 3. System: Opens search window |
|| 4. System: Shows possible filters to apply deppending on the area |
|| 5. User: Select the options wanted |
|| 6. User: Confirm the information |
|| 7. System: Show information to the user acconrding to the filters and the area |
| **Postcondition**   | User will have recived information wanted more specifically                 |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC10- Add another user from Musicder

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will enable users to add other users                 |
| **Precondition**    | The user must be connected to Internet, user must have acces to a registered account and the added user must be registered              |
| **Normal sequence** | 1. System: Shows a Musicder      |
|| 2. User 1: Select the add icon |
|| 3. System: Notifies User 2 |
|| 4. System: Add user 2 to partners list |
| **Postcondition**   | User 1 has associated with user 2       |
| **Exceptions**      | User 2 rejects User 1         |
| **Comments**        |                  |