# Azure AD B2C App in .NET for User Sign Up and Sign In
This repository contains sample code for implementing an Azure AD B2C App in .NET responsible for user sign up and sign in. The app requires users to provide some mandatory default attributes such as display name, surname, phone number, and custom attributes like movie and color.

# Demo
<b> Access the app at <a href="https://uniccapp1.azurewebsites.net">App 1</a> </b>
1. You will be directed to the sign up or sign in page.
2. You will need to create a new account and fill out the form with the required attributes, including display name, surname, phone number, and custom attributes like movie and color. 
3. Submit the form to create or sign in to a user account.
4. You will be signed in to the app
5. You have an option to sign out at the top right of the page
6. You will be able to sign back in using the account you created on step 1


## Getting Started
### Prerequisites
To use this app, you will need the following:

- An Azure account
- An Azure AD B2C tenant
- Visual Studio or another .NET development environment

### Installation 
1. Clone the repository to your local machine.
2. Open the project in Visual Studio or another .NET development environment.
3. Build the project.

### Serve app with different Azure account
In the appsettings.json file, replace the placeholders with your Azure AD B2C tenant information.

### Usage
To use the app, follow these steps:

1. Run the project.
2. Navigate to the sign up or sign in page.
3. Fill out the form with the required attributes, including display name, surname, phone number, and custom attributes like movie and color.
Submit the form to create or sign in to a user account.

### Resources
<a href="https://docs.microsoft.com/en-us/azure/active-directory-b2c/">Azure AD B2C Documentation </a> <br/>
<a href="https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-6.0&tabs=visual-studio">ASP.NET Core Identity Documentation </a>
