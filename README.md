# ASP.NET Core MVC Bootstrap Website

A simple **5-page website built with ASP.NET Core MVC and Bootstrap** for practicing Razor Views, Layout Pages, navigation, responsive design, and Bootstrap components.

## 🚀 Technologies Used

* ASP.NET Core MVC
* C#
* Razor Views
* HTML5
* Bootstrap 5
* CSS
* JavaScript

## 📄 Pages

The project contains five main pages:

1. **Home**

   * Hero section
   * Services section
   * ASP.NET Core
   * Web API
   * Database

2. **About Us**

   * Information about the website/project

3. **Services**

   * Services and technologies

4. **Gallery**

   * Gallery section for images/projects

5. **Contact Us**

   * Contact information
   * Contact form

## 📁 Project Structure

```text
ProjectName/
│
├── Controllers/
│   └── GuestController.cs
│
├── Views/
│   ├── Guest/
│   │   ├── Home.cshtml
│   │   ├── Aboutus.cshtml
│   │   ├── Services.cshtml
│   │   ├── Gallery.cshtml
│   │   └── Contactus.cshtml
│   │
│   └── Shared/
│       └── _LayoutMaster.cshtml
│
├── wwwroot/
│   ├── css/
│   │   └── stylecss.css
│   │
│   ├── js/
│   │
│   └── lib/
│       └── bootstrap/
│
├── Program.cs
├── appsettings.json
└── README.md
```

## 🎨 Bootstrap

Bootstrap is used for:

* Responsive navigation
* Containers
* Grid system
* Cards
* Buttons
* Typography
* Spacing
* Responsive layouts
* Footer layout

Example:

```html
<div class="container">

    <div class="row">

        <div class="col-lg-4">
            Content
        </div>

        <div class="col-lg-4">
            Content
        </div>

        <div class="col-lg-4">
            Content
        </div>

    </div>

</div>
```

## 🧭 Navigation

The website uses the following routes:

```text
/guest/home
/guest/aboutus
/guest/services
/guest/gallery
/guest/contactus
```

## 🏠 Home Page

The Home page contains:

* Welcome section
* Main heading
* Description
* Services button
* Contact button
* Services cards

Services include:

* ASP.NET Core
* Web API
* Database

## 🦶 Footer

The common footer contains:

* Website logo
* Website description
* Quick links
* Contact information
* Copyright information

## 📱 Responsive Design

Bootstrap responsive classes are used to make the website work on:

* Desktop
* Laptop
* Tablet
* Mobile

For example:

```html
<div class="col-lg-4 col-md-6">
```

This allows the layout to automatically adjust according to screen size.

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

Open the project using:

* Visual Studio
* Visual Studio Code

### 3. Restore dependencies

```bash
dotnet restore
```

### 4. Run the application

```bash
dotnet run
```

### 5. Open in browser

Use the URL shown in the terminal, for example:

```text
https://localhost:xxxx
```

## 🎯 Learning Objectives

This project was created to practice:

* ASP.NET Core MVC
* Controllers
* Razor Views
* Layout Pages
* `@RenderBody()`
* `ViewData`
* Routing
* Bootstrap
* Responsive design
* HTML
* CSS
* Basic project structure

## 🔮 Future Improvements

Possible improvements include:

* Add SQL Server database
* Add Entity Framework Core
* Add contact form functionality
* Add authentication and authorization
* Add CRUD operations
* Create Web API
* Connect frontend with API
* Add admin dashboard
* Deploy the application

## 👨‍💻 Author

**Your Name**

Built as an ASP.NET Core MVC and Bootstrap learning project.
