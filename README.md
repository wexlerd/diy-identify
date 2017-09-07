# DIY Identify
Create your own online image guessing game without writing any code

> The resources in this repository and the directions in this README allow you to create an interactive image guessing game using your own imagery and data. This template utilizes GitHub as a web hosting platform and Google Sheets as a data server.

An example completed application using the contents of this repository is available here: https://waltgurley.github.io/diy-identify/.

The images for this example are located in the repository directory `./static/images`, and the data is located in [this Google Sheet](https://docs.google.com/spreadsheets/d/1Ew_tsLL-TxHdKuFHkeq807o9gEOekfPvKjFiecznDqc/edit#gid=0)

Prerequisites
===
Before you begin creating your own application you must have access to a [GitHub account](https://github.com/join?source=header-home) and a [Google account](https://accounts.google.com/SignUp?continue=https%3A%2F%2Fmyaccount.google.com/intro).

Directions
===

Fork this repository
---
_You will create a copy of the **DIY Identify** repository in your own GitHub account_

1. On the DIY Identify repository page click the `Fork` button in the upper righthand corner

2. If prompted, select the account to which you would like to fork this repository.

3. You should now have a copy of the DIY Identify repository under your own account. Keep this repository open in a tab in your browser.

Prepare your data in Google Sheets
===
_You will copy an example spreadsheet workbook and format it with your data_

1. Open [this example Google Sheets workbook](https://docs.google.com/spreadsheets/d/1Ew_tsLL-TxHdKuFHkeq807o9gEOekfPvKjFiecznDqc/edit#gid=0) in a new tab in your browser.

2. Select `File > Make a copy...` and add a copy of this workbook to your own Google Drive. You can rename this workbook as you see fit.

3. This workbook contains two sheets: _Image Info_ and _App Info_. Select the `Image Info` tab to begin adding the information for the images that will compose your application. Each row in Image Info contains the necessary information for an image to function in your image guessing game:

  * **Image Name:** The complete name of this image, including the extension (.jpg, .png, etc.). For example, millipede.jpg.

  * **Entity Name:** The name of the entity that is identifiable in this image. *This column of names will be used to randomly generate choices in the game.*

  * **Entity Description:** A short, less than one paragraph, description of the identifiable entity in the image that a user will see if they correctly identify the image.

  Fill out this information for each of your images.

4. Select the `App Info` tab and add the necessary information for your application display:

  * **App Name:** The name of your application. This will appear at the top of the application page.

  * **Group Name:** The name of the person or group creating the application. This will appear at the top of the application page.

  * **Image Entities:** The general type of entity that describes the entities in your images. For example, pictures of insects would by described as Insects.

  * **Site Link:** A link to your/your group's website. This will appear in the information popup accessible via the info button.

  * **App Description** A description of your application. This can be one to several paragraphs providing the user with background on the image series and the person/group behind creating the application. This will appear in the information popup accessible via the info button.

Connect your app to the Google Sheets workbook
===
_You will publish the workbook you just edited and link it to your GitHub repository_

1. In your workbook select `File > Publish to the web...`. Ensure that you are publishing a _Link_ with the _Entire Document_ as a _Web page_. Select `Publish` and confirm by selecting `OK`. Close the _Publish to the web_ popup.

![Publish to the web in Google Sheets](./README-imgs/PublishToWeb.png)

2. Copy the URL from the address bar. It will look something like this: `https://docs.google.com/spreadsheets/d/1fRayIfFSIymfAK_LMTGFJBvMW0Nuk3NQu0gu2xG5oJM/edit#gid=0`

3. Switch to the browser tab in which your GitHub repository is opened.
