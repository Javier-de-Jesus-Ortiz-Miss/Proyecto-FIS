# Use cases

* [UC01 - Register a profile](#uc01--register-profile)
* [UC02 - Log in to a profile](#uc02--log-in-to-a-profile)
* [UC03 - Customize profile](#uc03--customize-profile)
* [UC04 - Edit profile](#uc04--edit-profile)
* [UC05 - Upload multimedia files](#uc05--upload-media-files)
* [UC06 - Chat between users](#uc06--chat-between-users)
* [UC07 - Visualize other nearby users](#uc07--visualize-other-nearby-users)
* [UC08 - Promote equipment for rent or sale](#uc08--promote-equipment-for-rent-or-sale)
* [UC09 - Select a equipment in need to rent or buy](#uc09--select-a-equipment-in-need-to-rent-or-buy)
* [UC10 - Filter the browser](#uc10--filter-the-browser)
* [UC11 - Add another user](#uc11--add-another-user)
* [UC12 - Eliminate another user](#uc12--eliminate-another-user)

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
| **Normal sequence** | 1. System: presents to user the log in page, asking for phone number/mail and password     |
|| 2. User: The user enters their phone number/mail and password  |
|| 3. System: Validates data and allow user to acces their profile |
| **Postcondition**   |  The user is successfully logged in and gains access to their profile             |
| **Exceptions**      | Account Lockout: if there have been multiple unsuccessful login attempts, the system locks the user's account temporarily for security reasons                  |
| **Comments**        |                  |

## UC03- Customize profile

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |  This function will enable users to choose their preferences|
| **Precondition**    |  User must be connected to Internet and the user is logged into their account|
| **Normal sequence** |  1. User: The application presents the user with options to customize various aspects of their profile, such as profile picture, biografy, interest, --Nivel de formalizacion--, etc |
||2. User: Saves their changes.|
||3. System: Records answers of the user and save it.|
| **Postcondition**   | The user's profile settings and preferences are updated according to their choices    |
| **Exceptions**      |  |
| **Comments**        |                  |

## UC04- Edit profile

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | The user will be able to edit the information registered                 |
| **Precondition**    | The user must be connected to Internet and have acces to a registered account      |
| **Normal sequence** | 1. User: Acces to "Settings" and "Edit profile"                 |
|| 2. System: Opens the edit profile window |
|| 3. User: Modifies the information needed
|| 4. User: Confirm the new information
|| 5. System: Save the new information in the data base
|| 6. System: Close the "Edit profile window"
| **Postcondition**   | The users information is uppdated in the system                 |
| **Exceptions**      |                  |
| **Comments**        |  CHECAR               |

## UC05- Upload media files

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will anable the user to upload files such as videos, photos, music, etc.                 |
| **Precondition**    | The user must be connected to Internet and have acces to a registered account                 |
| **Normal sequence** | 1. User: Acces to profile and select "upload files"                |
|| 2. System: opens the window of the files
|| 3. User: Select the wile wanted and confirm
|| 4. System: Save it in the data base and show it in the profile
| **Postcondition**   | The user file is uploaded in their profile                 |
| **Exceptions**      | The tipe of file is unvalid                 |
| **Comments**        |                  |

## UC06- Chat between users

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     | This function will allow the user to chat between them and store the chat history                 |
| **Precondition**    | Both users must be connected to Internet and have acces to different registed accounts                 |
| **Normal sequence** | 1. User 1: Acces to the "Chat" |
|| 2. System: Show "added users"                 |
|| 3. User 1: Select the destinatary
|| 4. System: Open the chat window
|| 5. User 1: Type message and send it
|| 6. System: Notifies user 2 about the message
| **Postcondition**   | User 1 has send the message and user 2 has recive it                 |
| **Exceptions**      | User 2 has blocked user 1                 |
| **Comments**        |                  |

## UC07- Visualize other nearby users

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC08- Promote equipment for rent or sale

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC09- Select a equipment in need to rent or buy

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC10- Filter the browser

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC11- Add another user

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |

## UC12- Eliminate another user

| <!-- -->            |   <!-- -->       |
|:--------------------|:-----------------|
| **Description**     |                  |
| **Precondition**    |                  |
| **Normal sequence** |                  |
| **Postcondition**   |                  |
| **Exceptions**      |                  |
| **Comments**        |                  |
